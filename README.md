Cuhre.jl
=========

Provides a subset of the functionality of the Cuhre routine from the [Cuba package](http://www.feynarts.de/cuba/) of integration routines.

Current status
---------------

Not functional. Data is passed into Cuhre correctly, but results are not correctly retrieved.

Installation
---------------

Install by running, under the Julia prompt,

    Pkg.clone("https://github.com/tflovorn/Cuhre.jl")
    Pkg.build()

Implementation details
--------------------

The simplifications made to the cuhre call are:

Always set nvec = 1, key = 0, spin = -1.

The name of the statefile is randomly generated for each invocation.
