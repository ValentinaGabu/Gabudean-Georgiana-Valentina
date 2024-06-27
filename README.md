Testing Project for Orange HRM Demo
The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application.

Application under test: https://opensource-demo.orangehrmlive.com/web/index.php/auth/login

Use the fallowing info to log in:

  - user: Admin
  - password: admin123
  
 Tools used: Jira, Zephyr Squad.

Functional specifications:
The below story was created in Jira and describes the functional specifications of the My info module, for which the final project is performed upon.

![story nou 1](https://github.com/ValentinaGabu/Gabudean-Georgiana-Valentina/assets/157517316/158dc8b5-c5c3-4e13-9cc3-401ac877ca96)

![story nou 2](https://github.com/ValentinaGabu/Gabudean-Georgiana-Valentina/assets/157517316/643dac6d-894c-496e-a6ec-56649d2daaed)

Here you can find the release that was created for this project:


![realease](https://github.com/ValentinaGabu/Gabudean-Georgiana-Valentina/assets/157517316/507dfa0c-4cd4-448a-a183-2b372e21b5ed)
![release 1](https://github.com/ValentinaGabu/Gabudean-Georgiana-Valentina/assets/157517316/87e47840-7571-44b8-974b-7bfef284fb9d)

Testing process

The test process was performed based on the standard test process as described below.



1.1 Test planning


The Test Plan is designed to describe all details of testing for all the modules from the Orange HRM Demo application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. 

The test plan that was created for this project can be found here [test_plan .docx](https://github.com/user-attachments/files/15876476/test_plan.docx)


1.1.1. Roles asigned to the project and persons allocated


Project manager: Maya Robins

Product owner: John Kant

Software developer: Karina Shan

QA Engineer: Gabudean Valentina


1.1.2 Entry criteria defined


Documentation Review

Environment Setup

Features Completeness

Content Readliness

User Permission

Accessibility and Compatibility

Testing Tools and Data


1.1.3 Exit criteria defined


Functional coverage

Performance and Scalability

Security

Usability and User Experience

Cross-Browser and Cross-Device

Compatibility

Regression Testing

Documentation and Reporting


1.1.4 Test scope


Tests in scope:

1. Functional Testing:
   
   - Log in in the app
   - My info module
   - Complete personal information
   - Save personal information
  
2. Compatbility Testing:
   
   - Testing on various browsers: Chrome, Firefox, Safari
   - Testing on diferent devices: Desktop, Laptop, Smartphone (iOS, Android)

3. Security Testing:
   
   - Vulnerability assessment (penetration testing) to identify potential security risks

4. Usability Testing:
   
   - User interface testing to evaluate design consistancy and user experinece



Tests not in scope:


1. Legacy Browser Compatibility:
   
   -Testing on outdated browsers that are no longer supported by the website

2. Advanced Network Security Testing:
   
   - Deep analysing of network security protocols beyond the website scope


1.1.5 Risks detected


Project risks:

Budgent overrun

Lack of resources

Change in requirement

Delivery delays

Product risks:

Improper Functionality

Complicated navigation


1.1.6 Evaluating entry criteria


The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.


1.2 Test Monitoring and Control


The monitoring and control stage in testing is crucial for tracking the oricess of testing, identifying deviations from the initial plan, and ensuring that objectives and acceptance criteria are efficiently met. This stage allows the testing team to adapt strategies and activities in real-time based on the results and findings from the testing process.

How the monitoring and control stage was conducted:

We implemented the monitoring and control stage using Zephyr for Jira to manage and report testing progress effectively.

We used Zephyr to generate regular status reports, including test status report and testing matrics such as the nnumber of planned tests, executed tests and their autcomes.

![raport de executie](https://github.com/ValentinaGabu/Gabudean-Georgiana-Valentina/assets/157517316/4bf9f73b-c728-41fe-bb29-35e3fbf6439c)


1.3 Test Analysis


The testing process will be executed based on the application requirements. 

The following test conditions were found:

![conditii de testare](https://github.com/ValentinaGabu/Gabudean-Georgiana-Valentina/assets/157517316/5855b7e4-5446-4923-adf8-1bb9e9d7a5ff)


1.4 Test Design


Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here:

[Test case-uri.pdf](https://github.com/user-attachments/files/15883703/Test.case-uri.pdf)


1.5 Test Implementation


The following elements are needed to be ready before the test execution phase begins:

Testing Environment

Testing Tools

Test Data


1.6. Test Execution


Test cases are executed on the created test Cycle summary: 

https://itfclasses.atlassian.net/projects/GGV?selectedItem=com.thed.zephyr.je__cycle-summary

Bugs have been created based on the failed tests. The complete bug reports can be found here: 

[Bug reports.pdf](https://github.com/user-attachments/files/15883953/Bug.reports.pdf)

The following is a summary of the bugs that have been found:

Can not chose license expiry date - medium priority, medium severity

Can not chose marital status - medium prority, medium severity

Can not select date of birth - medium prority, medium severity

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.


1.7 Test Completion As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team


The traceability matrix was generated and can be found here: 

![matricea de trasabilitate](https://github.com/ValentinaGabu/Gabudean-Georgiana-Valentina/assets/157517316/b7b62081-278f-4268-a044-5c87bc9ab063)

Test execution chart was generated and can be found below.

![raport de executie](https://github.com/ValentinaGabu/Gabudean-Georgiana-Valentina/assets/157517316/a7fc8638-7427-49a7-8770-85653fe67321)

The final report shows that a number 3 tests have failed of a total of 11.

A number of 11 total bugs were found, from which the priority is: all of them is medium priority.

The total number of stories is 2, 1 executed, and 1 unexecuted. The total number of written and executed tests is 11, The number of identified bugs is 3, all of them with medium severity level. There bugs affect the initiation and completion of My info module. They can frustrate users.
