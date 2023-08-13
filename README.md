## Main script 

+ There are two parts used in this thesis,``AIS_BBM`` focus on model training mode optimisation
+ The ``AIS_WBM`` script focus on FOC prediction by using power estimation method by [HoltropMennen84](https://repository.tudelft.nl/islandora/object/uuid%3Aca12a502-fc85-45e4-a078-db7284127e3c)

## Datasets

+ The main dataset will be the ``AIS_weather_H_ok2_copy.csv``, this includes the fused information between AIS data and weather data by ECMWF and CMEMS. The sole purpose of ``AIS_weather_h_rename_copy.csv`` is for information on current and wind speeds as well as directions 

## Dependencies

To set up your development environment and install the required packages, follow these steps:

+ Clone the repository:
 >https://github.com/hiwafi/thesis-ais.git
+ Create and activate the virtual environment (if not already created), and change the `your_virtual_environment_name`` to your own preference:

> `conda create --name your_virtual_environment_name`<br>
> `conda activate your_virtual_environment_name`
+ Install the required packages from the `geron1.txt` file:
> `conda install --file geron1.txt`
+ This will ensure you have the same packages and versions as used during development.

The Python version used for this virtual environment is `Python 3.9.15`


