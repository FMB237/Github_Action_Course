# This is a brand new course i'm starting today on my Udemy is course been design for me to improve my Devops skills in 2026

# This is Github_Action_For_CI/CD_Devops_Pipelines

This is mainly Fully new course where i gonna learn mainly new concepts 


# Lesson 1 :Introduction
**What is github ?** 
Today github has become a reference plateform for hosting,developpement and deployment of applications.

Github action is mainly a function  that permit to write our applications ad workflow that will acts like CI/CD
In this course we will learn how to create workflows for differcent types of applications whether the are **.NET apps** or even **Nodejs apps** ,**Java apps** so we gonna use these tools together with terraform for continous testing and deployemt. Then we gonna used some other tools that will permit us the secure and scan our applications.

**Note: This course mainly focuses on cloud and devops so let start**
Me teacher for this course is an indien guy know as **Houssem Dellai**

---
# Lesson 2 : Create my First Github Action workflow
For this we need to have a github account if already sign in and create a new github repo  or initialse the repo from vscode  then go to the **actions** on our github repo  the mainly have mainly functions more than simple CI/CD

Let move on to the action buttons and explore the options there.
1. Let view the options and let create a new workflow.
2. Let click  on start a **simple workflow**
3. This will create a folder with name **.github/workflows/blank.yml** which is automatically creted when we start a simple workflow but when  going further we will have more control on our workflows creations.
4. The Worflow have a default name which is CI(**Continuous Integration**)
5. We also have Trigger which points to my Git branches and repo.
6. We have jobs we can define one or multiple jobs. like build where we choose the environment where to build our app like ubuntu-lastest or even windows and others
7. On the steps we can find the actions like **actions/checkout@v4** which is mainly an open-source projects for acting on out workflows which means each actions applied has their own repo with source code that can be modified and customise.
8. Then we run the script generally we run the command **Hello world**
9. Then we run **Run a multi-line script**
10. Then commit your file 
11. Then move back the action menu  and observer the analyse change and run the workflow
---

# Lesson 3 :Create Workflow with inputs 
