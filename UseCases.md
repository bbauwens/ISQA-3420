There will be 3 USE CASES files embedded into this file

##Title: Manage Software and Package Info for License Scanning and Vulnerabilities

##Primary Actor: Manager

##Goal in Context: The Manager is able to determine Software and Package Info for License Scanning and Vulnerabilities.

##Stakeholders:

####-Manager: To receive clear and relevant project information
####-Developer: To provide the relevant file/package level information
####-Project Owner: To clearly understand manager decisions to green/red light a project

##Preconditions:
####-Relevant file/package information is in the NIST Vulnerability database
####-Proper software package and vulnerabilities information has been provided

##Main Success Scenario: Manager receives accurate software package for license scanning and vulnerability information for the requested project package of license scanning and vulnerabilities from NIST Vulnerability database. 

##Failed End Conditions: Manager receives inaccurate or invalid license and vulnerability information for the requested project package of license scanning and vulnerabilities from NIST Vulnerability DB.

##Trigger: Manager requests project information to which accurate license and vulnerability information is provided from NIST Vulnerability DB
#---------------------------------------------------------------

##Title: Request for Software Project License and Vulnerability Information

##Primary Actor: Manager or Developer

##Goal in Context: The Manager or Developer is able to request Software Project License and Vulnerability Information.

##Stakeholders:

####-Manager: To receive clear and relevant project license and vulnerability information
####-Developer: To receive clear and relevant project license and vulnerability information

##Preconditions:
####-Relevant file/package information is in the OSS Pacakage Database
####-Proper software package and vulnerabilities information has been provided

##Main Success Scenario: Manager or Developer receives accurate software package for license scanning and vulnerability information for the requested software project license and vulnerability information. 

##Failed End Conditions: Manager receives inaccurate or invalid license and vulnerability information for the requested software project license and vulnerability information. 

##Trigger: Manager or Developer requests software project license and vulnerability information 
#---------------------------------------------------------------
##Title: Create/Modify Policy Documents

##Primary Actor: Manager

##Goal in Context: The Manager is able to Create/Modify Policy Documents to the OSS Package Policy DB.

##Stakeholders:

####-Manager: To be able to Create/Modify Policy Documents accurately.
####-Developer: To be able to view the update from the Manager
####-Project Owner: To trust the update done by the manager doesn't destroy the project

##Preconditions:
####-Relevant Software Package Policy information is provided in OSS Package Policy DB.
####-Proper Software Package Policy information has been provided.


##Main Success Scenario: Manager provides accurate Software Package Policy to the OSS Package Policy DB for Developer to request.

##Failed End Conditions: Manager provides inaccurate Software Package Policy update to the OSS Package Policy DB that is retrieved by the developer.

##Trigger: Manager provides accurate Software Package Policy update to OSS Package Policy DB and the Developer receieves accurate info.
#---------------------------------------------------------------
## Policies
-InternalOSSUse.txt
-OSSComProds.txt
