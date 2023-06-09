# STRIDEvsSTRIDE- Replication package
This repository contains the data used to execute a replication of a control experiement to measure and compare the performance indicators (productivity and precision) of two STRIDE variants (per-element and per-interaction).

### General overview
To prepare for this experiement, several steps were taken in to consideration. 
First we prepared all textual materials. This included choosing relevant but comparable scenarios. To this end, we presented a kubernetes and a GitHub scenario for the first and confirming experiments. To further make the student's background knowledge comparable , for the subjects relevant to this study (security and the domains of the selected scenarios), we developed training videos.
From the scenarios, we compiled 10 threats, each containing a unique thretad ID, threat description, assumption, affected components, and an associated STRIDE threat type. 5 of the threats were real and 5 were fabricated.
Additional reading materials, selcted book chapters on STRIDE were also made availabe.

To measure the role of the data flow diagram in validating threats, we proposed comparing it to a process diagram, a sequence diagram. To this end, we defined two treatment group. Intervention received both the DFD and sequence diagram while control group received only a sequence diagram.

### The Task
When provided with the relevant training and reading materials, the participants were asked to complete two tasks:
1. From the case description, create a data fow diagram (DFD)
2. Identify security threats (by following the prescribed technique depending on the treatment), and document the identified threats using the provided template


### Available material for replication
To aide in the replication, we have made available the following materials;
1. Case description- homesys
2. Snmple DFD from each treatment group (per-element and per-interaction)
3. Sample CSV templete
4. Python notebook

## How to cite us
To be updated


### Getting started
To execute the python file:
1. First dowload the "sample participants report and exit questionnaire" file. The format of the csv file is the same as the one used during this data analysis.
2. Add the csv file to your Google drive
3. Open the .ipynb file and follow the specified steps. 
4. Change the drive directory and the file name of the downloaded csv sheet 
5. All relevant python packages have already been pre-defined where necessary



## Repository Structure
This is the root directory of the repository. The directory is structured as follows:

    template-replication-package
     .
     |--- Data/                            Contains the case study description, the template csv used by participants to report their identified threats, and sample DFD from each treatment groups.
     |
     |--- src/                             Contains the python notebook with a step-by-step analysis of the data obtained from participants. We did not provide the actual data used in analysis, however, the data format follows the same columns contained in the excel files uploaded in the "Data folder" in this repository. 
    
    
     
                         
  




## Preferred repository license
As general indication, we suggest to use:
* [MIT license](https://opensource.org/licenses/MIT) for code-based repositories, and 
* [Creative Commons Attribution 4.0	(CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) for text-based repository (papers, docts, etc.).

