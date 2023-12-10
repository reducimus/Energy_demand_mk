DJP Data Analytics with Python Assignment #2

Group members:

Miroslav Kapuscinski, Fionna Loughlin, Shahnawaz Parvin

Emails:
mkxoz2006@gmail.com (miroslav.kapuscinski@gmail.com)

fionna.loughlin@gmail.com

sp.boby1@outlook.com


Overall description of Code:

This notebook of code takes developes a model of Energy Demand based on Weather data. 

Files requires:
input: weather.csv, price_demand.csv

Code: Run all fields in jupyter notebook to replicate numbers and figures in Assignment2_group5 Report

Sections: 
1. Data Cleaning and Visualization

2. Model Buiding
	2A- a Calculation of Pearsons correlation coefficients
	2A- b Defining optimal temperature range for persons coefficients

	   --------------Report Table 3 -------------
	   Code 2A must be run with each variable in the following list to generate Report Table 3
	   'max_temp'
	   '3_temp'
	   '9_temp'
	   '3_humi'
	   'min_temp'
	   '9_humi'
	   'rain'
	   '9_press'
	   '3_press'
	   'Speed of maxumum wind gust'
	   '3_wspeed'
	   3_wspeed'
	   '9_wspeed'

	2B- a Linear regression model on full 3pm temperature range
	2B- b Kfold cross validation 

	2B- a Linear regression model on Restricted 3pm temperature range
	2B- b Kfold cross validation

			-- Feature Selction optimization --
	2C- a Linear regression model with Multi-features
	2C- b Kfold cross validation

	Code-2C must be run with the variable combinations below to replicate Report Table 3

			'3_temp',
			'3_temp', ‘rain’
			'3_temp',
			‘3_humi’
			'3_temp', '3_humi',
			'3_temp', '3_wspeed',
			'3_temp', '3_north_south'
			'3_temp', '3_press
			'3_temp', '3_humi', 3_press’,'3_north_south'
			'3_temp', '3_humi', '3_wspeed', '3_north_south'
			'3_humi', 3_press’,'3_north_south'

4. Appendix - Building a simple descision tree
		Optimal accuracy score achived with:
		Features: 3_temp','3_humi', '3_press', 'min_temp 

		Classlabel: with variable bins 
		DailyMaxDemand6
		DailyMaxDemand5
		DailyMaxDemand4
		DailyMaxDemand3


Output files:

Cleaned and pre-processed data:Group5_data_final.csv

Visualizations, graphs and validation parameters in notebook
