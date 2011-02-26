Evaluates the [Tree Width](http://en.wikipedia.org/wiki/Tree_decomposition#Treewidth) on molecular graphs. This code
uses the [libtw](http://www.treewidth.com/) library to evaluate the tree decomposition and the tree width for
arbitrary graphs. This repository provides an adapter class to convert a CDK IAtomContainer object to the graph
data structure supported by [libtw](http://www.treewidth.com/) and a simple driver to read a SMILES file
and report the timings and tree width values. The driver currently uses a single algorithm to get the upper
bound on the tree width.

To compile and run, you should have the comprehensive CDK jar file and the libtw jar file in your CLASSPATH.
