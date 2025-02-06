The Redwood Creek PRMS Model was calibrated to provide unimpaired modeled flow estimates at a subbasin scale and has a model run time from October 1, 1981 to February 23, 2023. Files generally needed for a PRMS model to run include a control file, data file, parameter file, model executable, and batch file. Executing the model per the directions outlined in this read me will produce daily flows for the entire time period, although flows for this model run have been primarily optimized from May 1 to September 30. 

The control file is called 'redwood_control_optimization1.control' 
The data file is called 'redwood_data.data'
The parameter file is called: 'redwood_optimization1_May_to_Sep.params'
			 
The model executable is in the bin folder of the GitHub repository.
The batch file is called 'run.bat'

Directions on how to run the model:

Optimization 1 - Spring Recession and Dry Season Optimization
Download and extract the GitHub repository, preferably directly to your C drive. Navigate to the PRMS_Optimization_May_to_Sep subfolder. Run the model by double clicking on 'run.bat.' A prompt will show up and the model will take some time to execute. Once the model is finished executing, it will produce two csvs, redwood_optimization1_May_to_Sep_sub_cfs.csv and redwood_optimization1_May_to_Sep_sub_inq.csv. In each csv, the column headers include Date followed by Subbasin IDs. Unimpaired modeled flow estimates for each subbasin are reported in daily average cubic feet per second (cfs).

redwood_optimization1_May_to_Sep_sub_cfs.csv is the cumulative subbasin flow at the outlet of each subbasin. 
redwood_optimization2_May_to_Sep_sub_inq.csv is the individual subbasin flow contribution for each subbasin. 


PRMS is open-sourced, publicly available, and  maintained by the United States Geological Survey (USGS). PRMS is well documented by Markstrom, Regan, and others (2008) from the USGS. The model documentation, manual, software releases, and updated notes and tables from new releases can be found at the following URL:
https://www.usgs.gov/software/precipitation-runoff-modeling-system-prms
