Python libraries and related software
-------------------------------------

Fedora Scientific includes the widely used Python libraries and
tools for scientific and numerical computing. Specifically, most of
the core components of the `SciPy stack
<http://www.scipy.org/about.html>`__  (Numpy and Scipy libraries,
Matplotlib, Sympy and IPython are included). With the exception of
SymPy, you will find that the Python 3 equivalents are also installed.

SciPy
=====

The official documentation for the SciPy and Numpy libraries are `here
<http://docs.scipy.org/doc/>`__. The `Python Scientific Lecture notes
<http://scipy-lectures.github.io/>`__ may be useful too. 

You can seek help from the mailing lists for both SciPy and Numpy
`here <http://www.scipy.org/scipylib/mailing-lists.html>`__. 

SymPy
=====

SymPy is a library for symbolic math. The official documentation for
SymPy is `here <http://docs.sympy.org>`__. 

The user mailing list is `here
<https://groups.google.com/forum/#!forum/sympy>`__. 

IPython
=======

IPython is an enhanced interactive shell with various features to
support rapid interactive computing. The IPython Notebook is a browser
based environment which allows you to create rich JSON based documents
embedding rich text, numerical calculations and inline graphs. See the
IPython `homepage <http://ipython.org/>`__ to learn more. 

The official documentation is `here
<http://ipython.org/documentation.html>`__. There are also a number of
`talks and presentations <http://ipython.org/presentation.html>`__ and
`videos and screencasts <http://ipython.org/videos.html#videos>`__. 

The IPython mailing list is `here
<http://mail.scipy.org/pipermail/ipython-dev/>`__.

Pandas
======

pandas is a Python library mostly useful for data analysis.

The `cookbook
<http://pandas.pydata.org/pandas-docs/stable/tutorials.html#pandas-cookbook>`__
is a good place to start and the `Lessons for New pandas Users
<http://pandas.pydata.org/pandas-docs/stable/tutorials.html#lessons-for-new-pandas-users>`__
look useful too.

You can ask questions on `stackoverflow
<http://stackoverflow.com/questions/tagged/pandas>`__.

Plotting
========

Matplotlib is the most feature-rich Python library for creating
publication ready graphs and figures.

The official documentation is `here
<http://matplotlib.org/contents.html>`__ and the `example gallery
<http://matplotlib.org/examples/index.html>`__ has a large number of
examples of creating plots of all kinds using matplotlib.

Parallel and Distributed Computing
==================================

The Python standard library's multiprocessing module is useful for
parallel programming. Fedora Scientific includes these additional
libraries.

The `MPI for Python <http://mpi4py.scipy.org/>`__ project provides
Python bindings to the Message passing interface (MPI). The official
documentation is `here
<http://mpi4py.scipy.org/docs/usrman/index.html>`__ with the mailing
list available `here <http://groups.google.com/group/mpi4py>`__. 

`Parallel Python <http://www.parallelpython.com/>`__ is another
alternative made available. The official documentation is linked from
the homepage. The `examples
<http://www.parallelpython.com/content/view/17/31/>`__ should help you
get an idea of what the programs look like and the kind of things you
may be able to do. The forum for seeking help is `here
<http://www.parallelpython.com/component/option,com_smf/Itemid,29/>`__. 

You can also use IPython for parallel computing, including using MPI with
IPython. See the official documentation `here
<http://ipython.org/ipython-doc/rel-1.1.0/parallel/index.html>`__.


Other libraries
===============

The `NetworkX library <http://networkx.github.io/>`__ allows you to play
with complex networks. Simple use cases include learning and teaching graphs.
The official documentation is `here <http://networkx.github.io/documentation.html>`__
and the project's mailing list is `here <http://groups.google.com/group/networkx-discuss/>`__.

.. note::

   networkx is not included in Fedora 28, you can however install it
   using: ``dnf -y install python*-networkx``.


Sage
====

.. note::

   sagemath is not included in Fedora 28, you can however install it
   using: ``dnf -y install sagemath``.


Sage provides an unified interface to "`100 open source packages <http://www.sagemath.org/tour.html>`__".
The videos `here <http://www.sagemath.org/help-video.html>`__ may help you get an overview of what
sage is and what it can do for you. The official documentation is `here <http://www.sagemath.org/help.html>`__
and ways to get help are listed `here <http://www.sagemath.org/development.html#mailingList>`__. 
