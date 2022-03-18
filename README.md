# META-DATA
GENERAL INFORMATION

1. Title of Dataset: **Academic behaviors that could affect online courses academic achievement** 

2. Author Information
	A.Principal Investigator Contact Information\
		[Name]: Ruoqi Wang\
		[Institution]: Teachers College, Columbia University\
		[Address]: New York\
		[Email]:(markwangruoqi@gmail.com)

	B. Associate or Co-investigator Contact Information\
		[Name]:
		<br />
		[Institution]: 
		<br />
		[Address]: 
		<br />
		[Email]:
		<br />

	C. Alternate Contact Information <br />
	<br />
		[Name]: 
		<br />
		[Institution]:
		<br />
		[Address]: 
		<br />
		[Email]:
		<br />

3. Date of data collection: 
		<br />
		Approximate Date: 
		<br />
		2022-April-30 : the data extracted from Zoom throughout the whole term.
		<br />
		2022-April-30 : the data extracted from canvas throughout the whole term.
		<br />
		2022-May-10 (After students' final exam): Surveys (whether this is the mandatory or elective courses) (Detect Confounding Variables)
	
	

4. Geographic location of data collection <latitude, longiute, or city/region, State, Country, as appropriate>:
		<br />
		Location: An online class in a highschool. 
		<br />
		State: New York 
		<br />
		Country: The United State
		<br />	
		
5. Information about funding sources that supported the collection of the data:
		<br />
		No funding in this study currently.  
		<br />
SHARING/ACCESS INFORMATION

1. Licenses/restrictions placed on the data: 
	<br />
	The raw data would be kept by school, the potential users could ask for accessing the raw data from the school.
	There would be no sensitive data, the data would be public with the agreement from schools. Further changes would be noticed as soon as possible. 
	<br />
2. Links to publications that cite or use the data:
 	<br />
	The research is undergoing, the links will be published once the study is finished. 
	<br />
3. Links to other publicly accessible locations of the data: 
	<br />
	The research is undergoing, the links and the related information will be published once the study is finished. 
	<br />
4. Links/relationships to ancillary data sets: 
	<br />
	The research is undergoing, the links will include the ancillary data sets.  
	<br />
5. Was data derived from another source?
	<br />
	No
	<br />
6. Recommended citation for this dataset:
	<br />
	The research is undergoing, the citation will be publichsde once the study is finished 
	<br />

DATA & FILE OVERVIEW

1. File List: **(refers to TIER folders)**  
<list all files (or folders, as appropriate for dataset organization) contained in the dataset, with a brief description>
	- Original Data folder: (contains files about raw data)
		- raw data extracted from Zoom
			- File name: raw_zoom.csv (More information will be updated once the raw data is obtained)  
		- raw data extracted from Canvas 
			- File name: raw_canvas.csv (More information will be updated once the raw data is obtained)
		- raw data collected from survies
			- File name: raw_survies.csv (Generated from Google forms)
	- MetaData Guide folder:
		- information about each data files
			- File name: 
				- raw_data_description.doc : describes the rows and columns of each raw data files.
				- clean_data_description.doc : describe the rows and columns of each clean data files and transformation from raw data to clean data) 
				- Coding_description.doc : A code book that describes the study conceptual framework and every variables and abbreviation in detials) 
				- timeline_record.doc : Record the major changes in each phases in the study.  		
	- Data Appendix: (contains information about variables) 
		- information about variables 
		 	- codebook files
				- File name: codebook.pdf
		- core data **(refer readings from week 8)**  
			File name: core_data.csv (keep one record of the core data that can replicate the study outcome) 
					- rows 
						- student psudo ids
					- attribute 
						- the study is undergoing, the attributes will be the same with the newest analysis_code version.  
	- Analysis Data: (contains clean (importable) data and data used to analysis) 
		- cleaned data from Zoom 
			- File name: clean_zoom.csv
				- rows
					- students' psudo ids 
				- attributes 
					- the number of "hand-rasing" clicks 
					- the number of absent days 
		- cleaned data from Canvas 
			- File name: clean_canvas.csv 
				- rows
					- students' psudo ids 
				- attributes 
					- the number of discussion post
					- the total number of canvas resources visited 
					- the rate of assignment completion 
					- average essay score 
					- average test score 
		- transformed data from survies
			- File name: clean_survies.csv 
				- rows 
					- students' psudo ids
				- attributes 
					- mandatory? (categorical data: whether the course is mandatory or not) 
					- office hour attendence? (categorical data: whether a student has attended office hour) 
					- the estimated totoal number of study hours outside of the class
	- Command files: (Keeping track of the whole research process) 
		- Research Records in each phases 
			File name: Research_record.pdf 
		- analysis files
			- Code that generate results
				- File name: cleaning_code.html (demonstrate the code for cleaning data) 
				- File name: analysis_ready_data_v1.html (the clean data file that combined all the separate clean csv files)
					- rows
						- student psudo ids
					- attributes 
						- the number of "hand-rasing" clicks 
						- the number of absent days 
						- the number of discussion post
						- the total number of canvas resources visited 
						- the rate of assignment completion 
						- average essay score 
						- average test score 
						- mandatory? (categorical data: whether the course is mandatory or not) 
						- office hour attendence? (categorical data: whether a student has attended office hour) 
						- the estimated totoal number of study hours outside of the class
				- File name: analysis_code_v1.html (the fist code version for analyzing)
					- cluster analysis 
					- Principle Component analysis 
					- logistic regression model
				- File name: analysis_ready_data_v2.html (the clean data file when some attributes need to be filtered out from analysis_ready_data_v1.html) 
					- rows 
						- student psudo ids 
					- attributes
						- the study is undergoing, the adjusted attributes will be updated here
				- File name: analysis_code_v2.html (the second code version for analyzing) 
					- cluster analysis 
					- Principle Component analysis 
					- logistic regression model 
					(the study is undergoing, the adjusted analysis method will be updated here) 
				- File name: core_data.csv (the data that generate the outcome of study, this will be stored in appendix section too) 
					- rows 
						- student psudo ids
					- attribute 
						- the study is undergoing, the attributes will be the same with the newest analysis_code version.  
		

2. Relationship between files, if important: 
	The files a
3. Additional related data collected that was not included in the current data package: 
	No additional related data. 
4. Are there multiple versions of the dataset? yes/no
	A. If yes, name of file(s) that was updated: 
		i. Why was the file updated? 
		ii. When was the file updated? 


METHODOLOGICAL INFORMATION

1. Description of methods used for collection/generation of data: 
<Include links or references to publications or other documentation containing experimental design or protocols used in data collection>

2. Methods for processing the data: 
<describe how the submitted data were generated from the raw or collected data>


3. Instrument- or software-specific information needed to interpret the data: 
<include full name and version of software, and any necessary packages or libraries needed to run scripts>

4. Standards and calibration information, if appropriate: 

5. Environmental/experimental conditions: 

6. Describe any quality-assurance procedures performed on the data: 

7. People involved with sample collection, processing, analysis and/or submission: 


DATA-SPECIFIC INFORMATION FOR: [FILENAME]
<repeat this section for each dataset, folder or file, as appropriate>

1. Number of variables: 

2. Number of cases/rows: 

3. Variable List: 
<list variable name(s), description(s), unit(s)and value labels as appropriate for each>

4. Missing data codes: 
<list code/symbol and definition>n

5. Specialized formats or other abbreviations used: 
