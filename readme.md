# Fuzzy Framework for Speed Estimation

This is a framework that employs fuzzy control to estimate average speed based on the parameters road class, road slope, road surface and link length. The exact methodology is described in the paper "Multi-Parameter Estimation of Average Speed in Road Networks using Fuzzy Control" which is published in the ISPRS International Journal of Geo-Information. You can find the paper in the main folder under "Fuzzy_Guth_etal_2020.pdf".

### Prerequisites

- Anaconda
- Pgsql database with postGIS and pgRouting extension

However the code can be altered to read in and give out csv files, so a Pgsql database is not absolutely necessary. 

### Project organisation

The main file is "Fuzzy-FSE.ipynb" which is in the main folder.

In the folder "Example_applications" there are the two examples mentioned in the paper. One for the BioBio and Maule Region in Chile and one for the region in the north of New South Wales in Australia.
Examplary membership functions for both regions can be found there.

In the folder "OSM_data" you can find the OSM data for both study regions with all required parameters in a csv format.

## License

This project is licensed under the BSD 3-Clause License - see the LISCENSE file for details.

## Authors

* **Johanna Guth**
