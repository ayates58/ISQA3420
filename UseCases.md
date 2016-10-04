#Use Case #1
----
##**Title:** 
Determine License and Vulnerability Information

##**Primary Actor:** 
Manager

##**Goal in Context:** 
The manager is able to see all of the software packages, licenses, and vulnerabilities from the Open Source Database. 

##**Stakeholders:** 

Manager - To receive clear and relevant project information

Developer - To provide the correct software package

##**Preconditions:** 
Correct package/file information in the OSS Components Database and correct information is provided to the manager. 

##**Main Success Scenario:** 
The Manager receives an accurate report on all of the software packages, licenses, and vulnerabilities for the requested project packages.

##**Failed End Conditions:** 
Manager receives an inaccurate report on the requested project packages.

##Trigger: 
Request for Packages and Licenses Report sent

----


#Use Case #2
----
##**Title:** 
Managing the Open Source Policy Database


##**Primary Actor:** 
Manager


##**Goal in Context:** 
The manager will be able to submit any policy document and modify the documents when needed. 
 

##**Stakeholders:** 

Developer - The manager is able to update and modify the policies whenever needed.



##**Preconditions:** 
Manager uploads the correct policy documents and updates the new policies. 

##**Main Success Scenario:** 
The manager is able to submit new policies to the database so projects can be compared, and the manager can also modify the policies when needed. 


##**Failed End Conditions:** 
Manager uploads the wrong document or cannot upload/modify any policies.

##Trigger: 
The manager submits any new policies and makes the correct adjustments when necessary. 

----



#Use Case #3
----
##**Title:** 
Software Package for License Scanning


##**Primary Actor:** 
Developer

##**Goal in Context:** 
The developer send a software package that is scanned for licenses, and vulnerabilities with the results being sent back to the developer, but also go to the OSS components database. 

##**Stakeholders:** 
Developer - To submit the software package and receive the results.
Manager - Be able to view the scan results in the OSS components database.



##**Preconditions:** 
The developer has the software package and submits the package to the correct scanner. 

##**Main Success Scenario:** 
The software package is scanned for licenses and vulnerabilities with the results going back to the developer, and to the OSS components database so the manager can view the results as well. 


##**Failed End Conditions:** 
The developer sends the wrong software package, the package is not successfully scanned, the results aren't sent to the developer or the database. 

##Trigger: 
Developer has software package that needs to be scanned for licenses/vulnerabilities. 

----
