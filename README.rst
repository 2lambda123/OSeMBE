OSeMBE
======

.. image:: https://readthedocs.org/projects/osembe/badge/?version=latest
    :target: https://osembe.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation Status

This repository cotains:

The Open Source energy Model Base for the European Union (OSeMBE)
-----------------------------------------------------------------

An Energy model base for the European Union developed using the **OSeMOSYS** Modelling Framework.
The model provides country-detailed representation of the 28 European Union (EU) Member States + Switzerland and Norway. The model aims at being used as a multi-regional stakeholders engagement model at the European level.
The development was funded by the European Union’s Horizon 2020 research and innovation programme under grant agreement No 691739.

Setup and Installation
----------------------

To run this analysis you need to install GLPK and a solver such as CBC, gurobi or CPLEX.

It is recommended to run the dataset in combination with the fast code of  OSeMOSYS v1.0.1. https://github.com/OSeMOSYS/OSeMOSYS_GNU_MathProg/releases/download/v1.0.1/osemosys_gnu_mathprog_v1.0.1.zip 

For the visualisation scripts you should have an environment with the following dependencies:
- `python` >= 3.6 
- `pandas`
- `plotly`

Folder structure
----------------

- Input data are stored as `datapackages` in the `input_data` folder
- A modified OSeMOSYS model file is stored in the `model` folder

Documentation
-------------

A more detailed documentation of OSeMBE can be found here: https://osembe.readthedocs.io/en/latest/

Licensing
---------
- Data is released under the terms of a CC-BY-4.0 International License Agreement.
- A modified copy of OSeMOSYS is redistribruted in this repository under Apache 2.0 license agreement, a copy of which can be found in the `model` folder

Citation
--------

If you wish to use, extend or otherwise build upon the work contained within this repository, you are
welcome to do so, provided you abide by the terms of the licenses detailed above.

Please cite this work in the following manner:
    `Henke, H., 2019, The Open Source energy Modelling Base for Europe (OSeMBE)`