# NYC_Livability_Index_2
Updates to Original

Project Title: 
    New York City Livability Index 
Project Description: 
    This project looks at 5 factors and uses user preference to calculate a livability score for New York City. 
    Those five factors are crime, restaurants, housing, health, and transit.
    ### ADD MORE HERE 

VISUALIZATION INITIALIZATION
	EXECUTION
		1. In folder that the README is located, in the address bar type "cmd" to open the command prompt terminal
		2. In the command prompt terminal, type in "python -m http.server 8000"
		3. In a web browser, type in  "localhost:8000"
		4. On the webpage click on "Code/"
		5. On the page click on "NYC_Livablity_Index.html"


TRAITS CALCULATION AND INDEX CREATION
	INSTALLATION:
    		In order to install, please follow these steps: 
        		1. open final_notebook.ipynb in a python IDE 
        		2. Install all required packages
				- Numpy
				- Pandas
				- scikit-learn
				- decimal
				- census_geocoder
				- time
	EXECUTION:	
		1. open final_notebook.ipynb in a python IDE 	
		2. Set path variables
			- path: should lead to Data folder inside the project folder     
			- test_files: should lead to Code/Test_files located inside the proejct folder
		3a. to do a fresh run, set RAW_RUN to True and run all. This will take raw data located in the path folder and does a clean run.  This will output a CSV file inside the test_file + Final folder. 
		3b. to do a run based on already pre-processed data, set RAW_RUN to False and run all. This will pull in preprocessed data located inside the test_file path. This will output a CSV file inside the test_file + Final folder.
		NOTE: it is recommended to run using pre-processed data to save on run time.
		4. Take final_index.csv located inside Test_files/Final ADD PATH HERE WHEN DONE### ### ADD NEXT STEPS HERE####  
CREDIT: Zoë Bakker, Mariana Fuentes, Jared Kaplan, Ethiraj Purushothaman, Alex Reiners, Salina Sok 
