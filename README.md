Cuhre.jl
=========

Provides a subset of the functionality of the Cuhre routine from the [Cuba package](http://www.feynarts.de/cuba/) of integration routines.

Installation
---------------

Install by running, under the Julia prompt,

    Pkg.clone("https://github.com/tflovorn/Cuhre.jl.git")
    Pkg.build()

Implementation details
--------------------

The simplifications made to the cuhre call are:

Always set key = 0.

The name of the statefile is randomly generated for each invocation.
