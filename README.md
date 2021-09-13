# xAct-Mathematica-template-notebooks-for-physics
Mathematica notebooks using the tensor algebra package xAct for computations in theories of gravity

In modern gravitational physics, computations can get laborious quickly, making it infeasible to do them by hand. This stems from the presence of differential geometry and non-linear partial differential equations in Einstein's theory of General Relativity (and its various extensions/modifications). Fortunately, many computations today can be done efficiently and more intuitively on a computer.

xAct is a suite of packages written in the Wolfram language, used for tensor algebra manipulations occurring in various theories of gravity (http://xact.es/index.html). It is perhaps the most extensive package of its kind currently available.

This repository contains a few template files using the xAct package that I used to perform computations in some of my own physics papers (https://inspirehep.net/authors/1721040).

xAct template.nb - is the main template file for initializing variables and some conventions. It can be used to perform perturbations and (covariant) scalar-vector-tensor decomposition of these aforementioned perturbations in any theory of gravity.

xPand template for 3+1 split.nb - is the template file for performing 1+3 decomposition of perturbations into their scalar, vector and tensor components, in any theory of gravity. 3+1 perturbation theory is used especially in cosmology to compute observables which can then be used to constrain/rule out competing theories from actual observational data.

GR propagator in flat space.nb - is a sample file which computes the graviton propagator around flat space in General Relativity in the covariant scalar-vector-tensor decomposition format. The file can be easily modified to consider more general, non-flat spacetimes, dimensions other than 4, and gravitational theories other than General Relativity.
