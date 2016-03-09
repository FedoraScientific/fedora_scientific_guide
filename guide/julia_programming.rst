Julia programming
-----------------

Fedora Scientific includes the `Julia language
<http://julialang.org>`__. The `official documentation
<http://docs.julialang.org/en/release-0.4/>`__ is a good place to
start looking into Julia. There are a number of other resources listed
on the `learning page <http://julialang.org/learning/>`__.

The `community <http://julialang.org/community/>`__ page lists the
various mailing lists.


Julia development in Jupyter
============================

Using `IJulia.jl <https://github.com/JuliaLang/IJulia.jl>`__, you can
program in Julia in `Jupyter notebooks <http://jupyter.org/>`__. Here
is how you can install IJulia:

.. code::
   $ julia
   > Pkg.add("IJulia")

Once that completes, run the following:

.. code::

   $ julia
   > using IJulia
   > notebook()


In addition, if you are curious, you can look into using `Juno
<http://junolab.org/>`__ for Julia programming.
