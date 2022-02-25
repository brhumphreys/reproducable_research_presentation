ECON 709: Reproducible Research Projects
========================================================
author: Brad R. Humphreys
date: Spring 2022
autosize: true

What is Reproducible Research?
========================================================

* “Reproducibility is just collaboration with people you don’t know, including yourself next week” quote from Philip Stark, University of California Berkeley Statistics Department
* Designing a research project so that an independent outside observer can reproduce all results in the final paper without any instructions from you using your code and data
* Building blocks of reproducible research: 

1. file, folder, and variable naming 
2. folder structure 
3. metadata 
4. raw data integrity 
5. scripting



Why Undertake Reproducible Research?
========================================================

- Journals are increasingly requiring submission of code and data along with papers, also employing data editors to check replication
- Facilitates collaborative research
- Helps your future self. This approach will save you hundreds, perhaps thousands of hours spent "reinventing the wheel" over your career 



Naming Conventions
========================================================

* All names should provide information about the contents
* Names should be "human readable"
* Never, never, never include spaces in any folder or file name
* No "garbage" characters!  @#$~&*+= and the like
* Use "-" and "_" for readability
* Take advantage of standard OS ordering: 0-9, a-z (and left pad initial numbers) 
* Bad: datafile 1.csv
* Good: raw_price_data_from_bls.csv 

Folder Structure
========================================================

* Folder names convey information about folder contents
* Needs to be adaptable to your project
* I often use something along these lines

📁 project_name  
|── README.md  
|── requirements.txt  
|── code/  
|── data/  
|── literature/  
|── documents/  
|── workflow/  

Metadata
========================================================

* Data on data.  The who, what, when, where, why, how of your research.
* Every folder should have a file with metadata for that folder
* Many formats 

* More information: 
* https://data.research.cornell.edu/content/readme
* https://data.research.cornell.edu/content/writing-metadata

========================================================
📁 project  
|── README.md  
|── requirements.txt  
|── raw_data/  
|   ├── bls_raw_price_data.csv  
|   └── README.md    
|── code/  
|   ├── 01_utilities.R  
|   ├── 02_data_cleaning.R  
|   ├── 03_analysis.R  
|   └── 04_generate_plots_and_tables.R    
|   └── README.md  
|── results/  
|   ├── cleaned_data.csv  
|   └── derived_data.csv  
|   └── README.md  
***

|── outputs/  
|   └── latex/  
|       ├── README.md  
|       ├── paper.tex  
|       └── slides.tex  
|    ── floats/  
|       ├── README.md  
|       ├── table.tex  
|       └── time_series_plot.pdf  

========================================================

