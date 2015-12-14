##Comparing Numba and Cython

This is a longer exercise to practice skills in profiling code and utilising numba and cython to get performance improvements.

You are given an example code `julia.py` that generates a plot of the [Julia set](https://en.wikipedia.org/wiki/Julia_set). It is a CPU-bound program.

Using **profiling**, attempt to determine where the code spends most of its time.

* Choose one or more functions and use both numba and Cython to create optimised versions of the code.
* Time (or profile) the impact your improvements create.
* Comment on the advantages and disadvantages of each method

