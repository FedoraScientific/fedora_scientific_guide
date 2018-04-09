R programming
-------------

Fedora Scientific includes `R
<http://www.r-project.org/index.html>`__ - a software environment for
statistical computing. The `R manuals
<http://www.r-project.org/index.html>`__ are a good place to get
started as well as extensive documentaion on R. The `R-help
<https://stat.ethz.ch/mailman/listinfo/r-help>`__ is a mailing list
which can be used to seek help on R.

`rkward <http://sourceforge.net/apps/mediawiki/rkward/>`__ - a GUI for
R is also installed.

.. note::

   rkward is not included in Fedora 28, you can however install it
   using: ``dnf -y install rkward``.



R development in Jupyter
========================

Using `IRkernel <http://irkernel.github.io/>`__, you can run your R code in `Jupyter notebooks <http://jupyter.org/>`__. First, you will have to install the ``czmq-devel`` package using ``dnf -y install czmq-devel`` from the terminal. 

Then start the ``R`` interactive shell from the terminal (``$R``) and as per the `install instructions <http://irkernel.github.io/installation/>`__, do:

.. code::
  
   > install.packages(c('rzmq','repr','IRkernel','IRdisplay'),
                 repos = c('http://irkernel.github.io/', getOption('repos')),
                 type = 'source')
                 
Once that completes, run the following:

.. code::
   
  > IRkernel::installspec()
  
Now, start the Jupyter notebook server using ``ipython3 notebook`` and you will be able to select the ``R`` kernel.
