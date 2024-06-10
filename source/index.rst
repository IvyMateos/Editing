.. ReadTheDocs_Tutorial documentation master file, created by
   sphinx-quickstart on Mon Jun 10 11:19:00 2024.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome MerCat2!
================================================
|paper| |preprint| |install with| |Anaconda.org| 

..  |paper| image:: https://camo.githubusercontent.com/4e62fbf1240e11569ff5a5a55cfd46dd12aa4dfa41c1edd821f4f887d8e05c61/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f70617065722d42696f696e666f726d6174696373416476616e6365732d7465616c2e7376673f7374796c653d666c61742d737175617265266d61784167653d33363030
   :target: https://doi.org/10.1093/bioadv/vbae061 

..  |preprint| image:: https://camo.githubusercontent.com/4b1ce666560094f833328c23d008ff7aa59e483db5f38e2aa2c6fd9e58f133e7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f7072657072696e742d42696f527869762d7265642e7376673f7374796c653d666c61742d737175617265266d61784167653d33363030
   :target: https://doi.org/10.1101/2022.11.22.517562

..  |install with| image:: https://camo.githubusercontent.com/2b3da1f4ac43c9ff4aa3151c2ea27dd4d00f147e01dfb55225b08b1cbc284774/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f696e7374616c6c253230776974682d62696f636f6e64612d627269676874677265656e2e7376673f7374796c653d666c6174
   :target: http://bioconda.github.io/recipes/mercat2/README.html

..  |Anaconda.org| image:: https://camo.githubusercontent.com/8c1a83f3189c641f0f819a71dae7cabf3f7a002314f13621efba4d450a06d8a4/68747470733a2f2f616e61636f6e64612e6f72672f62696f636f6e64612f6d6572636174322f6261646765732f76657273696f6e2e737667
   :target: https://anaconda.org/bioconda/mercat2 
Getting Started
==================
.. note::
There are two different ways of installing mercat2: Bioconda Installer and Source Installer

* Installing Conda should be done first before running any of these options on the terminal, download Conda to install the latest verison to your system

Option 1: Bioconda Installer
~~~~~~~~~~~~~~~~~~~~~~~~~~
1. Install mamba using conda 

::

   mamba create -n mercat2 -c conda-forge -c bioconda mercat2
   conda activate mercat2v

::

.. note::
   Make sure you install mamba in your base conda environment. We have found that mamba is faster than conda for installing packages and creating environments. Using conda might fail to resolve dependencies. 