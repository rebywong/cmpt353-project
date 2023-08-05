# Vancouver Transit Exploration Task
## CMPT 353 Final Project
### Jason Cai, Rebekah Wong (Group: "Mute Jammers")

Welcome! We hope you'll enjoy exploring trends in Vancouver's public transit system with us. First, let's outline some steps for you to be able to run our project.

## Which libraries are required?
Please ensure that the following libraries have been installed prior to running any code:
* `geopandas`
* `matplotlib`
* `numpy`
* `pandas`
* `scipy`
* `seaborn`
* `shapely`

## How do we run the project?
The file `vancouver_transit.ipynb` should have all the contents of running our project saved. Feel free to click on the `Kernel` and `Restart & Run All` as needed to rerun the code and reproduce the results. Since this is the only file, there is no order of execution.

We used a Jupyter notebook due to our heavy use of visuals in the project to map out transit data across regions of Vancouver, and being able to view all of the graphs in one notebook was convenient.

## Which input files are expected?
Ensure that everything from the `data` folder has been downloaded, keeping the exact naming of the `data` directory. These input data files include:
* `CensusLocalAreaProfiles2016.csv` - 2016 census information pertaining to different Vancouver neighbourhoods ([source](https://opendata.vancouver.ca/explore/dataset/census-local-area-profiles-2016/information/))
* `local-area-boundary.zip` - identifies boundaries in geometry of where the different Vancouver neighbourhoods are located ([source](https://opendata.vancouver.ca/explore/dataset/local-area-boundary/information/))
* `transit.zip` - Vancouver transit quality data ([source](https://doi.org/10.25314/5e94d820-678e-4d3a-9a97-51fb730d5cf5))
* `translink-annual-journeys.csv` - Translink data for transit journeys taken per year (i.e. transferring buses multiple times to reach a destination would still be one journey) ([source](https://www.translink.ca/plans-and-projects/data-and-information/accountability-centre/ridership))
* `translink-historic-ridership-trend.csv` - Translink data for ridership stats (in which each tap into public transit counts as a ride, as opposed to the 'journey' measurement above) ([source](https://www.translink.ca/plans-and-projects/data-and-information/accountability-centre/ridership))

## What files are produced?
Ensure that a folder named `output` exists prior to running the code. Within this folder, running the Jupyter Notebook (or pulling this repository) will produce an output file `neighbourhood_transit_quality.csv` containing the aggregated results of processing transit quality scores for each neighbourhood, along with each corresponding neighbourhood's population.

And that's all! Thanks for looking at our project, and have fun!
