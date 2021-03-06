.. co2_project_methods documentation master file, created by
   sphinx-quickstart on Thu Feb 18 21:33:45 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Documentation for co2_project_methods
===============================================

.. image:: images/co2_exp_setup.png
    :align: center
    :width: 600px
    :alt: alternate text

Welcome to use co2_project_methods. This package contain modules that help you analyze data for electrochemical pH swing CO2 capture/release experiemnts.

1 E-Chem module: help you analyze electrochemical data, such as voltage, current and pH data recorded by a Gamry Potentiostat.

2 Gas Flow Methods: help you analyze gas flow data, such as pCO2, gas flow rate and mass flow controller input recorded by an Arduino.

3 Theoretical DIC Calculation Methods: helps you analyze dissolved inorganic carbon concentration given a state.

4 Utility Methods: Utility functions that facilitate data processing.

5 Plotting Methods: Provide easy presentation of the analyzed data.


**Use Package**: Clone https://github.com/martin94jjj/co2_project_methods.git 

.. Note::

   Please cite Jin *et al.*, *Energy Environ. Sci.*, 2020,13, 3706-3722 if you use this package to analyze your data.

.. toctree::
   :maxdepth: 3
   :caption: Contents:

   modules 
   ./tutorial_local/tutorial.ipynb
   License
   Help

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
