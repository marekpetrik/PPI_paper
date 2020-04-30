# PPI_paper

This repository includes files that desribe the robust Markov decision processes used in the numerical evaluation of the paper "Partial Policy Iteration For S-Rectangular Robust Markov Decision Processes" (see <http://cs/unh.edu/~mpetrik>).

The specification of each Markov decision processes is saved in a CSV file. Each state of the MDP is identified with a 0-based integer. Each action is also identified using a 0-based integer. The columns columns of the CSV are `idstatefrom`, `idaction`, `idstateto`, `probability`, `reward`. Each row represents a single transition that describes that if the process starts from the state `idstatefrom` and the action `idaction` is taken, then it transitions to the state `idstatefrom` with probability `probability`. The reward accrued in this transition is `reward`.

The folder `inventory` includes the specification of the inventory problems, and the folder `cart-pole` includes the specification of the cart-pole problem, as described in the paper.
