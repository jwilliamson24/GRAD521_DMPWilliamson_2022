# Data description

## Research Question
My research proposal is split into two chapters. The primary goal of my research is to determine how habitat changes due to timber harvest and wildfire impact salamander populations in western Oregon, and this portion of the project is referred to later as Chapter 1. I will be conducting a resurvey which builds on a project my academic advisor completed from 2013-2019. This original project was focused on the impacts of timber harvest on salamander populations, and in 2020 many of those study sites burned. My goal is to resurvey those plots and quantify the effects of both disturbances (harvest plus wildfire) on salamander occupancy and abundance, as well as compare results over time before and after the disturbances. The secondary goal of my research, referred to later as Chapter 2, is focused on determining the difference in detection probabilities of daytime and nighttime salamander survey methods. For this project I will be actively searching for salamanders (flipping logs, searching the forest floor) during the daytime and nighttime, in both spring and fall.

## Data creation

This project will utilize five categories of data:
1.	Historic pre-fire data
2.	Field data
3.	Site-level information. 
4.	Logger Data
5.	Model data

### Category 1 
Includes data was taken by my advisor. We have open access. These are compiled into excel datasheets.  

### Category 2 
Includes all the data we will be collecting for chapters 1 and 2 in the field. Including:  
  a.	Salamander data (diversity, occupancy, and abundance)   
  b.	Habitat data (downed wood abundance, size, decay class, % charcoal, duff depth, and canopy cover)  
  c.	Microclimate data (soil moisture, ambient temperature, and relative humidity)  

These observational data will be taken in the field on paper datasheets and transferred to excel files. During field seasons, crews will visit a site and establish seven random sublots. Subplots will be searched by turning over all cover objects to estimate individual detection probabilities from each species of salamander. Crews will record habitat information at the point of detection for all salamanders, including size, decay class, and pyrogenic carbon class of any associated downed wood. At each subplot, crews will also record soil moisture at multiple depths using handheld volumetric soil moisture probes under and adjacent to downed wood structures, sub-plot canopy cover using densiometers, temperature and relative humidity using Kestrel fire weather meters, substrate type, and sampling time and date. Additionally, transects will be established and used to quantify and characterize the amount of downed wood in the subplot.

### Category 3 
Compiled from preexisting data for each site. This includes maps for fire severity, pre-fire stand age, basin temperature, precipitation, and vapor pressure deficit data. We will not collect these in the field.

### Category 4 
Data from electronic data loggers. These will take temperature measurements over time under pieces of downed wood in some of our plots. 

### Category 5 
Includes the coding and modeling that we create in RStudio after data collection. We will be using occupancy models (Mackenzie and Royle models) to analyze the salamander occupancy data in the context of the habitat covariates.

## Amount of data created  

|Category|Amount|Description|
|-------:|-----:|:----------|
|1|	~400 KB	|Excel files for 7 years of salamander data and habitat data, R code files|
|2|	>300 KB	|Excel files for 2 years of salamander data and habitat data|
|3|	2-3 MB	|Fire severity maps and climate data csv files|
|4|	Unsure	|Unsure – waiting on advisor response|
|5|	>100 KB	|Plain text files with R code|
|Total| 	>3-4 MB	| |


# Roles and responsibilities

Most of the data management roles that must be accomplished for this project will be my responsibility, with help from my academic advisor.  

**Data Generation and Collection:** I will be creating data sheets that are based on metrics determined by my advisor for the previous field seasons. I will lead field crews and take data along with other crew members. I will be responsible for quality-control by checking data sheets in the field to ensure that data taken by all crewmembers is legible and complete.  

**Data Management and Organization:** I will create an excel sheet to organize data for both Chapter 1 and Chapter 2 field work. I will be the primary person responsible for compiling datasheets, entering data from field work, and organizing the excel sheets. Each excel document will include a readme tab describing the metadata for the document. I will include information on column headings, units of measurement, and version-change documentation.  

**Data Analysis:** I will be responsible for data analysis for both chapters. It is likely that I will do this with support from Weyerhaeuser collaborators who my advisor has worked with in the past.  

**Archiving and preservation:** My advisor and I will share responsibilities for ensuring proper archiving and preservation of all data collected throughout the project.  

**DMP implementation:** My advisor and I will share responsibility for ensuring that the data management plan is executed.  

If anyone responsible for these roles leaves during the project, all responsibilities will fall to the remaining individual. It will be up to that person to find a replacement for help completing the project.


# Data standards and metadata  

I will produce several types of data throughout this project, including paper datasheets, excel files, csv files, and plain text files. The types of data that will be produced from each data category are as follows:  

1.	Historic pre-fire data: This data is already organized into excel files. I will acquire these files and keep them organized in a subfolder on my personal computer (and shared and external drives) and will not be editing them or creating new versions. The metadata for this data includes a readme tab in the excel document.
2.	Field data: This data will be taken on data sheets and compiled into excel documents.
3.	Site-level information: This data will be taken on data sheets and compiled into excel documents.
4.	Logger Data: This data will be in a csv file.
5.	Model data: This code will be created in R and saved in a plain text format.  

*Paper datasheets:* These data will be transferred to excel documents. The sheets will then be scanned and uploaded into a shared drive.  

*Excel documents:* These files will include a readme tab that will outline the details of the file, including brief but informative data descriptions and collection information. This information will be stored within each excel file, and will include information on column headers, units, and a description of how the data was collected if necessary. This will be done upon initial creation of the excel document early in the research process, before data collection begins.  

My field work for Chapter 2 will take place in HJ Andrews LTER, and they use a version of Ecological Metadata Language (EML) for published data that is produced in the LTER. I will be using these excel templates to organize the metadata for all data.  

*Plain text files:* I will keep metadata directly in the text file. I will include a header with information about what the script does, as well as information that explains the purpose and output of each line or chunk of code, and how to use it.  

*All digital files:* I will name files using the following format: filename_date. The file name will be descriptive and written in all lowercase letters with an underscore between words and dates. The date will be written as YYYYMMDD and will be updated each time I change the document. The readme document in each folder will include a table that outlines the file name and description of each file in the folder. When I make significant alterations on a draft of a document, such as after receiving feedback from a collaborator on a project proposal, I will create a copy of the document to serve as a new draft, with the same file name and the new date. This will allow me to keep track of multiple versions of a document in case older drafts are needed later.

# Storage and security  

Throughout the project, we will keep both paper copies of the data and digital copies in the form of excel sheets. The data from the paper data sheets will be transposed to the excel sheets weekly, subsequently scanned to a shared drive, and physical copies will be kept in a folder in my office on the OSU campus.  

The digital excel files will be stored in three locations: a local copy will be kept on my personal computer, a shared copy will be stored in a shared drive, and a third copy will be saved to a personal external hard drive. The drive will be shared with my advisor and another graduate student, so that the data access will not be lost when I leave the university. The local and shared copies will be updated automatically through connections to OneDrive.  

Additionally, I will be responsible for checking the files once per term for the duration of my degree to ensure that there are no issues with the backup process. After my graduation, that duty will fall to my advisor and will be done once per year.
None of my data is sensitive, and therefore does not need to be protected.  


## Sensitivity statement
None of my data is sensitive, and therefore does not need to be protected.  

# Access and data sharing  

All data taken for this project will be shared publicly. However, because my data for Chapter 1 will be taken on land owned by a private company, any publication materials must be approved by the landowner prior to submission. This data will be published in the Dryad data repository using a CC0 license before my degree completion in Summer 2024.  

There are no factors that could limit the publishing of the data taken in Chapter 2. It is taken on HJ Andrews LTER property, and they encourage open data publishing. This data will be published in the Andrews Forest data catalog by the time I graduate, in Summer 2024. This data will be entirely in csv format using a CC0 license.

# Archiving and preservation

Data will be archived physically in the digital formats described in Section 4. These copies will be kept on personal hard drives and shared drives indefinitely. The data will be publicly preserved as detailed in Section 5. Chapter 1 data will be preserved in the Dryad data repository, which states that they aim to store data for the long term. This long-term policy is “informed by the Open Archival Information System (OAIS) reference model … which defines "long term" to be a period of time long enough for there to be concern about the impacts of changing technologies, including support for new media and data formats, and of a changing user community”. The data produced from Chapter 2 will be preserved and archived within the Andrews Forest data catalog, where they have been storing data for more than 60 years.  
