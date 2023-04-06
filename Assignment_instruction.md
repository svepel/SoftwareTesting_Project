# Assignment guidelines

Last modified: 10.11.2022

> Note: This assignment guideline can stay in your submission. Kindly do not modify the guideline.

# Table of content
[ToC]

# Download Template
- **Step1:** Download the Project_Template.zip file.
- **Step2:** Unzip the Project_Template.zip file on your computer.
- **Step3:** Open the Test files one by one from the PageObject folder.
- **Step4:** Edit the Test file as per the Assignment instruction described below in the **Assignment Task** section 
- **Step5:** Write a bug report 
- **Step6:** Edit the Learning Reflection file as per the Assignment instruction described below in the Assignment Task section 

# Assignment Deliverables

- [ ] Create Test cases for all pages which are already there in project's **PageObject** folder
  - [ ] 03_RegisterPage
  - [ ] 04_ProjectPage
  - [ ] 05_IssuePage
- [ ] Perform all TODO: tasks describe in each above pages
- [ ] Create bug report for one test case which are already there in project's BugReport folder
  - [ ] 02_ProjectPageReport
- [ ] Write Learning Reflection page and upload in project's LearningReflection folder 
   - [ ] 01_LearningReflection.md
  
# Assignment Overview

### Functionality overview

The example application GitLab is a complete DevOps platform that enables professionals to perform all the tasks in a project—from project planning and source code management to monitoring and security. Furthermore, it allows teams to collaborate and build better software.

URL: https://gitlab.com


## Home page

- URL: https://gitlab.com/ 
- Precondition: login
- List of projects
- Pagination for list of projects

## Sign-in page

- URL: https://gitlab.com/users/sign_in

## Sign up page

- URL: https://gitlab.com/users/sign_up

## Profile page

- URL: https://gitlab.com/-/profile

## Project page

- to create a project
- URL: https://gitlab.com/projects/new
- Create a new blank project: https://gitlab.com/projects/new#blank_project
- Create a new project from the template: https://gitlab.com/projects/new#create_from_template

## Issue page

- Precondition: project
- URL: https://gitlab.com/group-slug-here/project-slug-here /-/issues/new
- Delete issue (click on pencil-icon for Edit or Delete issue)


## How to write Test Case

- Open PageObject/01_TestSuit_template.txt, guide you through the sections where you need to write details about the test case and test suit.
- Learn from Canvas Workspace page 7.2 | How to write a Test case and each detail

## Sample Test Cases for Login page

- Open web application URL: https://gitlab.com/users/sign_in
- Open PageObject/02_LoginPage.txt
- Notice the sections in the above file, Settings, Variables, Test Cases, and their fields Description, Tags, Precondition, Postcondition, Data, Test Case title, Test Case steps, section, and understand each step when you log in to the web application
- Check out each scenario's steps as described in the 02_LoginPage test suite.

## Assignment Tasks

1. Open Application (GitLab) for Test
2. Review Sample Test Cases for Login page section and File PageObject/02_LoginPage.txt
3. [ ] Create Test cases for all below pages which are already there in the project's **PageObject** folder
  - [ ] 03_RegisterPage
  - [ ] 04_ProjectPage
  - [ ] 05_IssuePage
- [ ] Perform all `TODO:` tasks describe on each above pages 
4. Start Testing the application as described in `TODO:` tasks by writing manual test cases for a given app (GitLab)
5. Review the Assignment Evaluation section before writing and editing Test cases for all pages
6. Write Test Suite predefined fields
   - Settings
   - Variables
   - Description
   - Tags
   - Precondition
   - Postcondition
   - Data
   - Test Cases and process steps
7. Write the Test Case title
8. Write each step for the test case and used test data besides that or write the variables' name
9. Repeat for the rest of the pages which are already there in the project's **PageObject** folder
10. Open Assignment_bug_instruction from the project's **BugReport** folder.
   - Start writing the bug report for the page Project creation as described in the Assignment instruction
   - Open the file 02_ProjectPageReport.md
   - Start writing the bug report 
   - Follow the instructions in the 01_Template_BugReport.md file
11. Open Assignment_LearningReflection_instruction from the project's **LearningReflection** folder.
   - Start writing the Learning reflection as described in the Assignment instruction
   - use template file 01_LearningReflection.md
12. zip all folders and text files
13. Upload to the Canvas platform as an Assignment return
14. Remember to write down the name of the folder as defined on the assignment page.
15. “Firstname_Lastname_Testing_Project.zip” 
16. Or Upload your project file on Github and share your repository link or give collaboration access to the teacher
17. When you submit your assignment on the Canvas learning platform then kindly share your git repository into the text box or comment field.
18. Good luck!

   

