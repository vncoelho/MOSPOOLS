# Multi-Objective Smart Pool Search Matheuristic

This project describes the Multi-Objective Smart Pool Search Matheuristic (MOSPOOL) Matheuristic, a set of tools for connection Mathematical Black-Box solver for the generation of sets of non-dominated solutions.


## Scientific papers

* [Bi‐criteria formulation for green scheduling with unrelated parallel machines with sequence‐dependent setup times](https://onlinelibrary.wiley.com/doi/abs/10.1111/itor.12566)
* [A multi-objective green UAV routing problem](https://www.sciencedirect.com/science/article/pii/S0305054817301028)

## Useful commands

### Generating Pareto fronts graphs

TODO

### GLPK

Solve with glpk:
`glpsol -m model.mod -d data.dat -o output.txt`

Convert to LP:

* `glpsol --model arq.mod --data arq.dat --wcpxlp arq.lp --check`
* `glpsol -m model.mod -d data.dat -wcpxlp model.lp -nointopt -nomip -tmlim 0`.

### Developing on Eclipse

Include libraries paths `/opt/ibm/ILOG/CPLEX_Studio$Version/concert/include` and
`/opt/ibm/ILOG/CPLEX_Studio$Version/cplex/include` to `C/C++ General -> Paths and Symbols -> GNU C++ (Includes)`

### Hypervolume calculus

The code provided by [http://lopez-ibanez.eu/hypervolume](http://lopez-ibanez.eu/hypervolume).

In this sense, we would like to thanks:

* Carlos M. Fonseca, Luís Paquete, and Manuel López-Ibáñez. An improved dimension - sweep algorithm for the hypervolume indicator. In Proceedings of the 2006 Congress on Evolutionary Computation (CEC'06), pages 1157–1163. IEEE Press, Piscataway, NJ, July 2006.

## Current maintainers

[Vitor Nazário Coelho](https://github.com/vncoelho) and [LucianoCota](https://github.com/lucianocota)
