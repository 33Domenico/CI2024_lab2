## TSP Problem

I have developed two versions of an evolutionary algorithm to address the TSP problem. Both use an adaptive mutation strategy: the mutation rate increases when there is no improvement and decreases when there is progress, balancing exploration and exploitation. Furthermore, in both algorithms, if the mutation rate exceeds a predetermined threshold, a restart phase is triggered via Simulated Annealing to avoid convergence to local minima.

The second version adds a population diversity check, inserting new random solutions when the population becomes too homogeneous. However, tests showed that this variant did not lead to significant improvements over the first.

In the end, I chose the first version as it proved to be faster and just as effective, providing greater overall efficiency.
