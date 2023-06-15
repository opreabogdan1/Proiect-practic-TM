 <h1 align="center">OrangeHRM Project<h1>
 <h2 align="center">-Test plan-<h2>

## Revision history
| Date | Version | Authors | Comments |
| :-----: | :---: | :---: |:---: |
| 11.03.2023 | v1.1| Oprea Bogdan Ștefan | Draft plan|
| 18.03.2023 | v1.1| Ioana Popescu | Test results for functional testing |
| 25.03.2023 | v1.2| Maria Popescu | More details added for Test Implementation  |

1. Introduction

    1.1 Project objective

    1.2 Functionalities in scope

    1.3 Functionalities and tests out of scope

2. Test process

    2.1 Test planning

    2.2 Test analysis

    2.3 Test design

    2.4 Test implementation

    2.5 Test execution

    2.6 Test closure

    2.7 Test monitoring and control

3. Test deliverables

    3.1 Test plan

    3.2 Test conditions

    3.3 Test cases

    3.4 Daily test summary reports

    3.5 Traceability matrix

    3.6 Test case results

    3.7 Bugs report

    3.8 Test completion report
    
   ## 1. Introduction
  
  This test plan describes the strategies, process, workflows and methodologies used to plan, organize, execute and manage testing process for **OrangeHRM** browser application. 
  
### 1.1 Project objective
  
  The scope of the final project for ITF Manual Testing Course is to use all gained knowledge through the course and apply them in practice using a live application. 
  
  Application under test: https://opensource-demo.orangehrmlive.com/web/index.php/pim/viewEmployeeList 
  
  Application documentation: https://www.orangehrm.com/assets/Files/Complete-Administrative-User-Guide.pdf?url=/Files/Complete-Administrative-User-Guide.pdf
  
  Tools: ***Jira***, ***Postman***, ***MySql***.
  
### 1.2 Functionalities in scope
  
  - All features of the ”Job Titles” and ”Pay Grades” modules which were defined in software requirement specs need to be: functional testing, GUI testing, API testing.
  
### 1.3 Functionalities and tests out of scope
  - All OrangeHRM features except the ”Job Titles” and ”Pay Grades” modules ;
  - Non-functional testing like stress, performance is beyond scope of this project;
  - No QA support for mobile application developed. Only web application will be tested;
  - Automation testing is beyond scope.
  
    ## 2. Test process
    
### 2.1 Test planning
  
#### Roles and responsabilities
  

| Software Developer | Tănase Ionuţ|
  | :-----: | :---: |
| Product Owner | Ioana Miruna Stroe| 
| Product Manager |Marian Apostol| 
| QA Engineer |Bogdan Ştefan Oprea| 
| Senior QA Engineer| Andreea Năstase|
  
#### Entry criteria:

- Functional specifications defined; 
- Roles needed for the project are allocated; 
- Initial project risks were detected and mitigated;
  
#### Exit criteria:
  
- All test cases have been executed; 
- The number of unresolved bugs is insignificant or have low priority; 
- All resolved bugs have been re-tested and closed by QA team; 
- Deadline was reached; 
- No detected major risks remained un-mitigated. 
  
#### Risks:
  
Project risks: 
  
- Lack of experience of the QA team; 
- Only one QA in the QA team; 
- Unavailability of the test environment; 
- Short deadline of Zephyr Squad and Jira tools.
  
Product risks:
  
- Validation constraints on the fields might be too restrictive to the end user. 

### 2.2 Test analysis

- Analyze business requirements to make sure that we have all the details for creating the test conditions; 
- Write test conditions that will be tested in out test process.
  
### 2.3 Test design
  
- Functional test cases will be created in Zephyr Squad; 
- GUI test cases will be created in Zephyr Squad;
- API test cases will be created in Postman; 
- The test design techniques used for generating test cases are: equivalence partitioning, boundary value analysis. 
  
### 2.4 Test implementation
  
Verify that the following elements are ready before the test execution phase:
  - Test environment is up and running: https://opensource-demo.orangehrmlive.com/web/index.php/auth/login; 
  - Access to the test environment is given: ***username*** = Admin, ***password*** = admin123;
  - Cycle summary was created and the test cases were added to the cycle summary; 
  - Postman collections were created. 
  
### 2.5 Test execution
 
 - Test cases are executed on the create Cycle summary;
 - Bugs are created based on the failed test cases;
 - API test cases were executed;
 - Full regression pack are executed.

### 2.6 Test closure
  
 -  As the exit criteria were met and satisfied as mentioned in the 2.1 section, this feature is suggested to go live by the QA team. 
  
### 2.7 Test monitoring and control
  
 -  Generate periodic reports to check the project status: status for the test cases executed, status for the converge of the business requirements, etc.
  
    ## 3. Test deliverables
  
### 3.1 Test plan
  
### 3.2 Test conditions
*screenshots cu test conditions din Jira
  
### 3.3 Test cases
*screenshots cu test cases din Jira
  
### 3.4 Daily test summary report 
*screenshots cu raportul generat zilnic din Jira 
  
### 3.5 Traceability matrix
*screenshots cu matricea generate in Jira
  
### 3.6 Test case results
*screenshots/pdf  cu rezultatele test case-urilor exportate din Jira
  
### 3.7 Bugs report
*screenshots/pdf cu defectele exportate din Jira
  
### 3.8 Test completion report
  
### 3.9 Schedule
 
Run functional test cases for Admin Job submenu     13.03.2023   Andreea Năstase  
Run GUI testing for Admin Organization submenu      14.03.2023   Bogdan Ştefan Oprea
  
  
  
  ![Screen user story](https://github.com/opreabogdan1/Proiect-practic-TM/blob/main/Captur%C4%83%20de%20ecran%202023-04-08%20100925.png)
  
  
  
  
  
  
  
  
  Link catre fisier sau altceva [Test cases for user story x](https://github.com/opreabogdan1/Proiect-practic-TM/blob/main/OR-11.pdf)




  



