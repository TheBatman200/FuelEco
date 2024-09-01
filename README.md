# FuelEco
Table of Contents:
Understanding Data Attributes
Ask Questions
Evaluating Data
Clean Column Labels
Filter, Remove Nulls, Deduplicate
Examine Data Types
Correcting Data Types
Exploring with Visualizations
Merging Datasets
Analyzing Merged Data
What is Fuel Economy?
According to Wikipedia, fuel economy in automobiles refers to the efficiency relationship between the distance a vehicle travels and the amount of fuel it consumes. This can be measured as the volume of fuel used per distance traveled or the distance covered per unit of fuel consumed.

Dataset:
Fuel Economy Data This data is provided by the U.S. Environmental Protection Agency, Office of Mobile Sources, National Vehicle and Fuel Emissions Laboratory. The datasets we’ll be using are slightly simplified versions compared to those available through the following links:

EPA Fuel Economy Testing
DOE Fuel Economy Data For a deeper understanding of the dataset, refer to the Green Vehicle Guide Documentation and data description.
Attribute Descriptions:
Model: Vehicle make and model
Displ: Engine displacement - the engine's size in liters
Cyl: The number of cylinders in the engine
Trans: Transmission type and number of gears
Drive: Drive axle type (2WD = 2-wheel drive, 4WD = 4-wheel/all-wheel drive)
Fuel: Fuel type
Cert Region*: Certification region code
Sales Area**: Sales region code
Stnd: Vehicle emissions standard code (View Emissions Standards)
Stnd Description*: Emissions standard description
Underhood ID: A 12-digit ID found on the vehicle’s underhood emission label, required by the EPA to designate its "test group" or "engine family." Learn more here.
Veh Class: EPA vehicle class
Air Pollution Score: Air pollution score (smog rating)
City MPG: Estimated city miles per gallon (MPG)
Hwy MPG: Estimated highway MPG
Cmb MPG: Estimated combined MPG
Greenhouse Gas Score: Greenhouse gas rating
SmartWay: Yes, No, or Elite
Comb CO2*: Combined city/highway CO2 emissions in grams per mile
"*" means not included in the 2008 dataset. "**" means not included in the 2018 dataset.
