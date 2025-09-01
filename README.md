
# Software Testing Overview

## What is Software Testing?
Software testing is the process of verifying that the developed software/application fulfills all the client-required functionalities.

There are two main approaches:

1. **Manual Testing** – Verifying an application without using any automated tool/software.
2. **Automation Testing** – Verifying an application/software with the help of automated tools/software.

---

## SDLC (Software Development Life Cycle)

Key roles:
- **BA (Business Analyst)** – Service based
- **PO (Product Owner)** – Product based

### SDLC Phases
1. Requirement Gathering
2. Designing Phase
3. Implementation/Development Phase
4. Testing Phase
5. Delivery/Deployment Phase
6. Maintenance Phase

---

## STLC (Software Testing Life Cycle)

### STLC Phases
1. Requirement Gathering
2. Test Planning & Test Case Creation
3. Test Environment Setup
4. Test Case Execution Phase
5. Defect Logging
6. Test Cycle Closure

### Deferred :-
When any issue which is not impacting the major functionalities  of application so in that case 
developer said we will fixed that into the next version.

### Duplicate :-
When any bug is already raised  incorporate  with another  issue so that  is called duplicate condition..


## Bug/Defect Life Cycle 
 1. **New**
 2. **Assign to Dev**
 3. **open** <br>
 &nbsp;  &nbsp; ***Deferred*** <br>
 &nbsp;  &nbsp; ***Duplicate*** <br>
 &nbsp;  &nbsp;  ***Rejected*** <br>
<br>

4.**Fixed** <br>
5.**Retesting** <br>
6.**Verified**  <br>
7.**Closed**   <br>




---

## Test Plan Document Structure
1. Introduction
2. Objective
3. Testing Approach
4. Test Strategies
5. Test Deliverables
6. Entry & Exit Criteria
7. Estimations
8. Risk & Mitigation Plan
9. Conclusion

---

## Test Case Examples
- To verify by entering valid credentials
- To verify by entering invalid credentials
- To verify by entering a valid user and invalid password

---


---
## Lecture 3

### Bug
- All the issues which is found during testing enviroment known as bug..

### Defect
- All the issues which is found over production enviroment known as defect.

### Error
- All the compile time issues are known as errors.



## Bug Report

- Project name -->XYZ
- Summary --> user is not able to logged in.
- Interface-->Login
- Module --> Login
- Enviroment -->Testing
- Description -->
   (A) Problem Statement:-User is not able to logged in with valid credentials.
   (B)Steps to reduce-->Open the url > click on login button > Enter valid credentials > click on submit.

- Labels/Watcher -->XYZ
- Assignee-->Dev XYZ
- Priority-->Highest/Low/Medium
- BA-->XYZ
- Click on Create Btn.
## Test Case Documentation 

![Test Case Documentation](<Screenshot 2025-09-01 164654.png>)

## Jira
Jira is a versatile project management and issue-tracking software developed by Atlassian that helps teams plan, track, and manage their work throughout the software development lifecycle. It supports various agile methodologies, such as Scrum and Kanban, offering features like customizable boards, roadmaps, and reports. While widely used by software development and IT teams for bug tracking and planning, Jira's flexibility allows other departments like marketing, design, and operations to use it for project management and workflow customization. 

### Key Features and Uses
1. **Agile Project Management:**
- Jira provides the tools for agile frameworks, including Scrum and Kanban boards, to visualize and manage workflows. 
2. **Bug and Issue Tracking:**
- It offers robust features to track bugs, manage tasks, and resolve issues efficiently, serving as a centralized system for tracking project-related problems. 
3. **Customizable Workflows:**
- Teams can create custom workflows to align with their specific project needs and processes. 
4. **Planning and Roadmaps:**
- Jira allows teams to create roadmaps, set goals, track dependencies, and break down large projects into smaller, achievable steps. 
5. **Reporting and Dashboards:**
- It provides various reports and dashboards to give teams visibility into their work and enable data-driven decision-making. 
6. **Integrations and Extensibility:**
- Jira integrates with numerous other development and business tools, enhancing its functionality through a wide ecosystem of apps and add-ons. 

### Who Uses Jira?
- Software Development Teams: For planning, tracking, and releasing software. 
- IT Teams: For managing IT projects and service requests through products like Jira Service Management. 
Product Management Teams: To create product roadmaps and manage the product lifecycle. 
- Marketing Teams: For planning and tracking campaigns. 
- Other Business Functions: Including finance, human resources, design, and operations, leveraging Jira for general project and task management. 

### BA--> Task (Epic) Need to Develop then e-commerce
<!-- Epic and user story  is the jira's vocab  -->

#### subtask (User Story)
 - develop the login functionality
 - develop the category pages
 - develop the order flow 
 - develop the payment methods
