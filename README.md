# META-DATA
GENERAL INFORMATION

1. Title of Dataset: **Behavioral factors may affect undergraduate students' test scores in the American history course in one semester for the synchronous online settings such as Zoom & Canvas** 

2. Author Information
	A.Principal Investigator Contact Information\
		[Name]: Ruoqi Wang\
		[Institution]: Teachers College, Columbia University\
		[Address]: New York\
		[Email]:(markwangruoqi@gmail.com)

	B. Associate or Co-investigator Contact Information\
		[Name]: Wendy Wen\
		[Institution]: Teachers College, Columbia University\
		[Address]: China
		<br />

	C. Alternate Contact Information <br />
		[Name]: Rebecca\
		[Institution]:Teachers College, Columbia University\
		[Address]: China 
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
	We expect the raw data would be kept by school, the potential users could ask for accessing the raw data from the school.
	There would be no sensitive data, the data would be public with the agreement from schools. Further changes would be noticed as soon as possible. 
	However, since the project is undergoing and the data has not been collected, further changes will be updated here. 
	<br />
2. Links to publications that cite or use the data:
 	<br />
	The research is undergoing, the related information will be posted once the study is finished. 
	<br />
3. Links to other publicly accessible locations of the data: 
	<br />
	The research is undergoing, the related information will be posted once the study is finished. 
	<br />
4. Links/relationships to ancillary data sets: 
	<br />
	The research is undergoing, the related information will be posted once the study is finished.  
	<br />
5. Was data derived from another source?
	<br />
	No
	<br />
6. Recommended citation for this dataset:
	<br />
	The research is undergoing, the citation or related information will be posted once the study is finished 
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
	None.
3. Additional related data collected that was not included in the current data package: 
	None.
4. Are there multiple versions of the dataset? yes/no
	No.


METHODOLOGICAL INFORMATION

1. Description of methods used for collection/generation of data:
  We expect that the data will be collected with the permission from school, Zoom, and Canvas. 

2. Methods for processing the data: 
  Data Cleaning Process: 
	* Combine two tables into one, with rows being represented as observations and columns being represented as variables. 
	* Continuous variable with a wide range, we standardize them to improve model performance, such as ‘average essay scores’ and ‘average previous tests’. 
	* variables that are likely to have many zeros, we make it into categorical variables to prevent the skewing of data (left-skewed). 
	* variables that contain outliers and null values will be substituted with median, mean, or mode depending on the distribution of data.


3. Instrument- or software-specific information needed to interpret the data: 
	Jupyter Notebook version 6.4.5 will be used to interpret the data
4. Standards and calibration information, if appropriate: 
	None
5. Environmental/experimental conditions: 
	Not specified
6. Describe any quality-assurance procedures performed on the data: 
	None 
7. People involved with sample collection, processing, analysis and/or submission: 
	Ruoqi Wang will involve with sample processing and analysis, other project members will be responsible for sample collection, and submission. 

DATA-SPECIFIC INFORMATION FOR: core_data.csv

1. Number of variables: 
	10 (further changes will be updated) 
2. Number of cases/rows: 
	200 (further changes will be updated)
3. Variable List: 
	- numhandraise: the number of "hand-rasing" clicks - variable is assessed by how many times the student clicks on the “raise hand” button on Zoom throughout the whole semester. 
	- abentdays: the number of absent days - This is assessed by the number of times the student did not enter the zoom meeting at all while there is a class scheduled throughout the whole semester. 
	- discussposts: the number of discussion post -This is assessed by how many posts the students posted on the voluntary discussion board of the course.
	- resourvisit: the total number of canvas resources visited - This is assessed by how many times the student visits the course Canvas page throughout the entire semester. 
	- assigncomplete: the rate of assignment completion - This data is assessed by the number of assignments completed throughout the semester divided by the total number of assignments assigned by the instructors throughout the whole semester. 
	- avges: average essay score - This is assessed by the total number of essay scores of the entire semester divided by the total number of essays assigned throughout the semester. 
	- avgts: average test score - This variable is assessed by the total number of points gained in all tests throughout the semester divided by the total number of tests given by the instructors throughout the semester.
	- mandatory? : categorical data: whether the course is mandatory or not 
	- office hour attendence? : categorical data: whether a student has attended office hour
	- estlearntime: the estimated totoal number of study hours outside of the class
4. Missing data codes: 
	No

5. Specialized formats or other abbreviations used:  
	No
