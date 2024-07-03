# Regional_Models
This repo has all modules to produce the regional models. Each module needs to be run from beginning to end. 
NOTE: currently module 1.1. has two different process and need to be split in two. 

0.Data prep
	0.0. StudyAraePrep: Module to prepare the study area shapefile using the BCRs from BAM national models v5
1. Data Extraction: As data comes from two different sources there are two different modules.  
	1.1. WildTraxDataExtraction: Module to extract data from Wildtrax
	1.2. ebirdDataExtraction: Module to extract data from ebird 
2. Calculate offsets: This module calculates offsets using QPAD
3. 