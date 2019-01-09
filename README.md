#  Lecture on Mixed Integer Conic Optimization using Julia and JuMP for the Grid Science Winter School 2019


This site contains materials for my lecture at the [Los Alamos National Laboratory Grid Science Winter School, January 7-11, 2019](http://www.cvent.com/events/2019-grid-science-winter-school-conference/event-summary-58d3065a0e2947bb8750464ffab634ce.aspx). 

## Installation Instructions for Julia v1.0

You should use the latest version of Julia v1.0. Binaries of Julia for all platforms are available [here](http://julialang.org/downloads/).
You will also need to get an academic license for [Mosek](https://www.mosek.com) using this [form](https://license.mosek.com/academic/) and get an academic version of [CPLEX](https://www.ibm.com/analytics/data-science/prescriptive-analytics/cplex-optimizer).


You can install all the required packages by running:
```julia
ENV["JUPYTER"]=""
Pkg.add("IJulia")
Pkg.add("Plots")
Pkg.add("JuMP")
Pkg.add("PolyJuMP")
Pkg.add("MultivariatePolynomials")
Pkg.add("DynamicPolynomials")
Pkg.add("SumOfSquares")
Pkg.add("Pajarito")
Pkg.add("Mosek")
Pkg.add("CPLEX")
Pkg.add("SCS")
Pkg.add("Convex")
```


