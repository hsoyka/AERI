# AERI
This repo contains conference programs and files from AERI (Archival Education and Research Institute), as well as datasets compiled by Heather Soyka and Eliot Wilczek that were derived from the programs and websites of the AERI institutes held from 2009 through 2018. 

## Data Authors and Compilation
* Heather Soyka, Assistant Professor, Kent State University
* Eliot Wilczek, Corporate Records and Archives Manager, The MITRE Corporation
* Mallory McCorkhill, Graduate Research Assistant, Kent State University

## Date
These notes on the AERI datasets are current as of January 26, 2019.
This data is also available for download via Figshare: https://figshare.com/articles/Archival_Education_Research_Institute_AERI_Programs_and_Reconciled_Data_2009-2018/7635983

## Background and Methods

The Building the Future of Archival Education and Research Initiative (AERI) represents a collaborative effort that was initiated amongst nine core U.S. academic institutions to stimulate the growth of a new generation of academics in archival education. The AERI project was initially developed with significant federal funding support from the Institute of Museum and Library Services under the Laura Bush- 21st Century Librarian Program, and is coordinated through the Center for Information as Evidence at the University of California, Los Angeles. 

Each summer, AERI hosts annual institutes (Archival Education and Research Institutes) at higher education institutions. Given the nature of funding and support for the annual institute, each host/partner institution and organizing committee has used their own systems, organizational schemes, and methods for staging and providing access to program materials. This has presented some incompatibilities, technical issues, and unfortunately, data loss. Whenever possible, we have used the site and information that was created and provided by the host committee as the primary source of information for this set of files. Those URLS are listed below, by year. If the original website created by the host institution/committee no longer exists, the UCLA AERI URL for that year has been used. Wikis and websites for the 2010 and 2011 AERIs are no longer publicly accessible or functional as of 2017. For the years of 2011 and 2012, information was requested and received directly from program participants whenever possible. 

## Sources
Notes are also provided within the datasets on the source of content, with particular notation to content from sources other than an institute program. 

### Websites

* 2009: University of California, Los Angeles: https://aeri.gseis.ucla.edu/2009.htm
* 2010: University of Michigan: https://aeri.gseis.ucla.edu/2010.htm [original wiki no longer accessible]
* 2011: Simmons College: https://aeri.gseis.ucla.edu/2011.html [original wiki no longer accessible]
* 2012: University of California, Los Angeles: https://aeri2012.wordpress.com/
* 2013: University of Texas at Austin: https://www.ischool.utexas.edu/aeri2013/index.html
* 2014: University of Pittsburgh: http://www.ischool.pitt.edu/aeri2014/
* 2015: University of Maryland: http://aeri2015.umd.edu/
* 2016: Kent State University: https://www.kent.edu/iSchool/archival-education-and-research-institute-aeri-2016
* 2017: University of Toronto: http://aeri2017.org/
* 2018: University of Alabama: https://aeri2018.ua.edu/


In cases where the website has been removed or links are broken, we looked for information from the main AERI websites, hosted by UCLA. Those links are: 1) https://aeri.gseis.ucla.edu/index.htm  and 2) http://aeri.website/

In situations where information could still not be found, we reached out directly to the lead faculty/committee chair for the host institution for those years. For the years 2011 and 2012, we contacted participants directly to fill in gaps in the data. Data received directly from respondents is located in the datasets for their respective years. 


### Programs
Programs collected from the institute websites and the host institutions may be found in this repo. Note: no separate program was available for 2010 or 2017; we have created PDFs that contain/replicate the websites as they exist in 2019 for future use. 

## Data 

There are two types of data in this repo. The first set are the programs of the AERI Institutes, created by the host organizations. The second set of data are structured content of AERI Institute programs, compiled by and created by the authors. 

#### AERI Institute Programs
Programs created by the host committee for each institute are stored in this repository by date and location. See note above regarding programs for each year.

#### AERI Institute Programs Structured Content

##### Overview
This repo contains structured content for AERI institutes from 2009 through 2018. These datasets were compiled by and authored by Heather Soyka and Eliot Wilczek. The structured content is stored in .xlsv (Microsoft Excel) files, one file per year. These are designed to be easily reused and may be converted to CSV files. 

The baseline unit of measure for these content files is the individual presentation, poster, workshop, or plenary talk. A paper session, for example, that has four presentations, will manifest itself in the structured content file as four entries--one for each presentation. In some cases, particularly for sessions like panel discussions, the authors had to make subtle judgements between representing that panel discussion as one entry, or breaking session into multiple entries--one for each panelist. When reasonable, the authors of this dataset chose to break sessions into multiple entries in an effort to highlight individual presentations and work. Individual presentations are still connected to their larger panel using the shared session title in the Session Title field.

Multi-authored papers,  posters, and workshops, where those presentations cannot be subdivided, are contained within a single entry. Entries with multiple authors will have more than one name in the Presenter field and more than one institution in the Presenter Institution field. For multi-authored work, the organization of this structured content privileges presentations over individual identification. Other researchers wishing to use this data set for analysis on individual or groups of authors will likely need to do some additional preparation before conducting their research.

Some data contained inconsistencies when the program was compared with the host website and/or other sources. Not all institutes had a separate program, and in some cases the website or wiki no longer exists, or portions are unavailable as of 2017 (2010, 2011, 2012). No separate program was created by the host committee for the 2017 AERI, but we have captured the website portions that exist in 2018/2019. In order to resolve these challenges, we have been as inclusive as reasonably possible. When a paper or poster appears on the website, but not in the program, we have made the choice to include it in the data. In situations where an event on the program may not have happened due to cancellation or other reasons, we have kept it as part of the data in order to reflect the original intent and record of the host committee and participants.

##### Fields
###### ID Number
Unique identifier for each entry in this data set across all AERI Institutes. Four-digit year string followed by three-digit number: [YYYYNNN].

###### Presenter
Name of presenter. Name in natural order (first name last name). Many presenters have made presentations at multiple AERI Institutes. The authors here have not normalized names across institute years in this dataset. Names in the dataset are as they appear in the Institute programs, with the exception of updating typos and irregularities when they were easily observable.  Multiple names are delimited by semicolon.

###### Presenter Institution
Name of institution associated with a presenter as noted in institute programs. Many institutions are represented at multiple AERI Institutes. Institution names are normalized across institute years in this dataset. In the case of presentations with multiple authors, multiple institutions are in this field in the same corresponding order as the authors are listed. Multiple institutions are delimited by semicolon. In some cases, when it made sense to reasonably do so, we have corrected or added an institutional affiliation for clarity. 

Institutions have been normalized in the data according to the following convention: for state universities where the presenter is from the flagship campus, only the title of the institution is listed. For non-flagship campuses, the location is also listed, but no punctuation. 
* Example 1: The University of Texas at Austin is the flagship, therefore the affiliation would read: University of Texas
* Example 2: UCLA is not the flagship campus, therefore the affiliation would read: University of California Los Angeles


###### Session Title
The name of the session a paper, workshop, poster belongs to, as represented by the institute programs. 

###### Presentation Title
The name of the paper, poster, workshop, or other event title, as represented by the institute programs.  

###### Abstract
The text of the abstract as it appeared in institute programs or other sources.    

###### Presentation Type
The type of presentation. This field contains the following controlled values: Paper, Poster, Plenary, Workshop, Other.

###### Concurrence 
This field indicates if a presentation was given concurrently with other presentations at the same time or if it was given to the entire institute with no other concurrent presentations. This field contains the following controlled values: Plenary, Concurrent.

###### Source and Notes
This field documents the source from which the dataset authors gathered the information on a particular presentation. Most of the data in this dataset comes from institute programs. In some cases, the authors of this dataset reached out to the presentation authors for information on their presentations, especially their abstracts. Many presentation authors generously sent their abstracts to the dataset authors. See the Sources section of this notes document for additional details.  


