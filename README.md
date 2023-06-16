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
  
- Functional test cases will be created in Zephyr Squad (for more details see chapter 3.3); 
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
 
 - Test cases are executed on the create Cycle summary (for more details see chapter 3.3 and 3.6);
 - Bugs are created based on the failed test cases (for more details see chapter 3.7);
 - API test cases were executed;
 - Full regression pack are executed.

### 2.6 Test closure
  
 -  As the exit criteria were met and satisfied as mentioned in the 2.1 section, this feature is suggested to go live by the QA team. 
  
### 2.7 Test monitoring and control
  
 -  Generate periodic reports to check the project status: status for the test cases executed, status for the converge of the business requirements, etc.
 -  The following status report was generated after 40% of the test cases were executed, on 30 April 2023:
  
  ![Test execution by Test Cycle](https://github.com/opreabogdan1/Proiect-practic-TM/assets/128214529/668c1e63-00f4-4581-9bd9-7eccf7b1f53d)
  
  
    
   ## 3. Test deliverables
### 3.1 Test plan
  
### 3.2 Test conditions
- The test conditions created for the ”Job Titles” and ”Pay Grades” modules can be viewed here: [Test conditions](https://github.com/opreabogdan1/Proiect-practic-TM/blob/main/test%20conditions.xlsx)
  
### 3.3 Test cases
- The test cases were created in Zephy Squad, based on the analysis of the specifications. The test design techniques used for generating test cases are boundary value analysis, equivalence partitioning and use case testing. 
- The test cases with steps can be accesed at this link: [Test cases](https://github.com/opreabogdan1/Proiect-practic-TM/blob/main/Test%20cases%20Job%20Title%20%2B%20Pay%20Grade.pdf)
  
### 3.4 Daily test summary report 
- On April 30, 2023, the testing process began and 6 tests were performed, of which 4 were pass and 2 were fail. On May 2, 2023, 3 tests were run, of which 1 failed and 2 passed. On June 11, 6 tests were run, all of which were passed. The daily test summary report cand be seen below:
 ![Screenshot_2](https://github.com/opreabogdan1/Proiect-practic-TM/assets/128214529/0355cdb0-f864-41d4-a94c-0d6cd589a7b7)
  

  
### 3.5 Traceability matrix
- The traceability matrix was generated and can be found here: [Traceability Matrix](https://github.com/opreabogdan1/Proiect-practic-TM/blob/main/Traceability_Matrix.xlsx)
  
### 3.6 Test case results
- Test cases are executed on the created test Cycle summary and the results can be seen here: [Test case results](https://github.com/opreabogdan1/Proiect-practic-TM/blob/main/Test%20case%20execution.pdf)
  
### 3.7 Bugs report
- Bugs have been created based on the failed tests. The complete bug reports can be seen here: [Bugs report](https://github.com/opreabogdan1/Proiect-practic-TM/blob/main/Bugs%20report.pdf)
  
### 3.8 Test completion report
- Final test execution chart was generated ([click here](https://github.com/opreabogdan1/Proiect-practic-TM/blob/main/Test%20execution%20report%20FINAL.pdf)), the final report shows that 8 tests have failed from a total of 26.
- A number of 26 test cases were planned for execution and all of them were executed.
- In total 8 bugs were found, from which the priority is: 2 is high and 6 are medium.
  
### 3.9 Schedule
 
Run functional test cases for ”Job Titles” and ”Pay Grades” modules 30.04.2023 Bogdan Ştefan Oprea
  



  



