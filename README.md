EASE-Project_v1.0
====================

Electricity Analysis Suggestion Ensemble, or short for EASE, is a Proejct guided by the eScience Insititue and Chemical Engineering Department at the University of Washington. 

EASE is classification model that predicts best electricity generation source from weather, cost, carbon dioxide emission/taxation, and energy source distribution data at a specific user input location within the states. The output of the model is an optimized suggestion with most economical, best weather suitable, clean, and most efficient. EASE project  utilized Machine Learning (RamdomForest) algorithem from scikit-learn to do classificiation.

Please give credits for the contributors if you use this code.

**EASE_RF_v1.0**

Jiarong I. Cui**(1)**, Tai-Yu D. Pan**(1)**, Jiayuan Guo**(1)**, Yongquan Xie**(2)**

**(1)** University of Washington, Department of Chemical Engineering, Seattle, WA </p>
**(2)** University of Washington, Department of Material Science and Engineering, Seattle, WA


---------
License
---------
No License has been created just yet, it will be added shortly.

-------------------
Database Sources
-------------------
**All the database are either self-constructed, or obtained from open sources.**

* USA Electricity Souce Database [https://www.eia.gov/electricity/data/state/](https://www.eia.gov/electricity/data/state/)
* USA Weather-info Database [https://www.ncdc.noaa.gov/qclcd/QCLCD?prior=N](https://www.ncdc.noaa.gov/qclcd/QCLCD?prior=N)
* Carbon Dioxide Emssion/Taxation Database [http://www.eia.gov/environment/data.cfm](http://www.eia.gov/environment/data.cfm)
* Cost Dataset(Self-composed)
    * [https://www.eia.gov/electricity/data/state/](https://www.eia.gov/electricity/data/state/)

-----------------------
Software Depedencies
-----------------------
**Package is written in Python 3.x version**</p>
**All the required software is open source.**

Numpy  [http://www.numpy.org/](http://www.numpy.org/)</p>
Pandas  [http://pandas.pydata.org/](http://pandas.pydata.org/)

Scikit-Learn  [http://scikit-learn.org/stable/](http://scikit-learn.org/stable/)

**Operating system information**

Both Mac OS X and Windows operating system should be able to execute the package in default Python environment.

---------
Folders
---------
**Project_Goal** - The folder contains the project scope, example of use case of the package, user interactive diagram, as well as all other brainstorming thoughts and dataset descriptions relative to the project from the very beginning.

**Original_Data** - The folder contains the orginal datasets downloaded from all the open sources stated above, these raw dataset contains information that are not useful for the package development.

**Arrange_Data** - The folder contains the iPython scripts that import and clean different original raw dataset from the **Original_Data** folder. 

**Model** - The code for the model, EASE_v1.0, and all other scripts for the model development.

-------------------
Acknowledgements
-------------------
David A. Beck and Jim Pfaendtner, eScience Institue, Chemical Engineering Department, as well as Directors for the DIRECT program at University of Washington, served as mentors for the development of this package.
