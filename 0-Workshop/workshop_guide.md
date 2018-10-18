# GitHub Training - Hands-on Workshop
Matt Casari<br>
NOAA/PMEL/EDD<br>
matthew.casari@noaa.gov

## Overview
This training is split up into the following subsections:

1. GitHub Website and Navigation
2. Working in an existing repository
3. Project Management tool
4. Issue tracking
5. Creating a wiki
6. Creating a repository
7. Other tools
8. Resources


<br><br><br>

--------------
<div class="pagebreak"></div>

## 1. GitHub Website and Navigation

The GitHub website more than just the cloud storage site for a project repository.  GitHub has many powerful tools that provide the user the ability to update, modify and view documenation and code.  Additionally, the issue tracking and project management tools make it an effective site to perform project management tasks on a (relatively, with training) easy to use website.

You can access GitHub by going to:<br>
www.github.com

As NOAA and CI employees, you *must* have a GitHub account which is tied to your @noaa.gov email address.  Your GitHub account can then be tied to the **NOAA-PMEL** account, giving you access to all of PMELs repositories and the ability to create Private repos.

1. **User Site vs. NOAA-PMEL**
    <br> All work being accomplished under a funded NOAA project **MUST** be commited to a repository on the **NOAA-PMEL** page.    

    Work performed for personal use, tutorials, example code, etc. may be saved in repositories on your personal GitHub page.

    To change from your personal page to the NOAA-PMEL page, click on the switch dashboard content dropdown, seen here:

    ![alt text](images/github_mainpage_userpage.png "Switch Dashboard Content Dropdown")<br><br>



1. **Your Profile**
    <br> ![alt text](images/github_mainpage_profile.png "Your Profile")<br><br>

    To access your profile page, select the dropdown menu in the upper right-hand corner of your webpage
    with your icon.  From this page you will see your public profile which includes which repositories you work in, and any information about yourself you may provide.

    ![alt text](images/github_profile_main.png "Your Profile Page")<br><br>

    
1. **Settings**
    <br> ![alt text](images/github_mainpage_settings.png "Settings")<br><br>

    Your settings page controls your access to GitHub, security and other configurations.

    NOAA requires Two-Factor Authentication (TFA) on the GitHub website.  To set this up, select "Security" from the "Personal Settings" list:

    ![alt text](images/github_settings_tfa.png "Two-Factor Authentication")<br><br>


<br><br><br>

--------------
<div class="pagebreak"></div>

##  2. Working in an existing repository
In this exercise, you will create a file within an existing repository, located here:

Training Repository:<br>
https://github.com/NOAA-PMEL/PMEL-training

<br><br>

1. Click "Create new File"<br>
    ![alt text](images/github_edit_createnew.png "Projects Tab")<br><br>

2. Create a new folder and filename with format "YourName/README.md"<br>
    To create a new folder, type "Foldername/" in the path form.  Finish the line with "README.md"<br>
    ![alt text](images/github_edit_createnew_form_filename.png "Fill in filename")<br><br>

3. Add two lines of text into the edit new file form.  Intentionally make a mistake in one word.<br>
    ![alt text](images/github_edit_createnew_form_text.png "Fill in filename")<br><br>

4. Scroll down and fill in the "Commit Changes" forms.
    It is important to be descriptive in the commit changes message (and later when commiting in Git) since this 
    message can be used to help you roll back your code to earlier states.<br>
    Press "Commit new file" when complete.<br>
    ![alt text](images/github_edit_createnew_commit.png "Fill in filename")<br><br>

At this point you have committed your first file to a repository.  If you followed the instructions, you will 
remember that there was a type in README.md.  Lets go fix it.

5. Go into the folder you created (your name)<br>
    ![alt text](images/github_edit_newfolder.png "Click Edit")<br><br>

6. Click on the README.md file.  <br>
    ![alt text](images/github_edit_newfile.png "Click Edit")<br><br>

7. Click on "Edit" icon <br>
    ![alt text](images/github_edit_clickedit.png "Click Edit")<br><br>

8. Fix the typo<br>
    ![alt text](images/github_edit_createnew_editing.png "Click Edit")<br><br>

9. Scroll down and fill in "Commit changes block"<br>
    ![alt text](images/github_edit_createnew_editing_commit.png "Click Edit")<br><br>

10. Press "Commit changes" and you will be returned to the folder view.<br>
    ![alt text](images/github_edit_createnew_editing_commit_saved.png "Click Edit")<br><br>

Now you have finished editing and committing the new changes.  GitHub has a tool to help you visualize what you have changed.  Lets explore this:

11. Navigate to the file you just changed (if you're not there already).  Click on "History"<br>
    ![alt text](images/github_edit_createnew_editedfile.png "Click Edit")<br><br>

12.  This will bring up the commit history for that file.  On the right hand side, you will see a seven 
digit alphanumeric code.  This is referred to as the "commit hash" and it is a truncated version of the 40-digit
SHA-1 hash code generated during the commit process.  Click on the most recent hash to open.<br>
    ![alt text](images/github_edit_createnew_history_hash.png "Click Edit")<br><br>

13. The resulting screen is a "Diff"(or difference) of the most recent commit and the previous commit.  Green fields with "+" represent added text, while red fields with "-" represent removed text.<br>
    ![alt text](images/github_edit_createnew_diff.png "Click Edit")<br><br>

The "Diff" tool is extremely useful in determining what has changed from commit to commit.  In this GUI form, it
is good for seeing changes in documentation.  When used with the Git client it is a powerful tool for determining accidental code changes and quickly determining where to roll back the code to.

At this point, you have created and modified a file within a repository in GitHub. 

<br><br><br>

--------------
<div class="pagebreak"></div>

## 3. Project Management tool

The Project Management tools within Github allow project managers and project maintainers to have a visual tool for keeping track of tasks within a project.  The format used in GitHub is a Kanban board.  In essence, a Kanban board is a columnar progress chart.  For the most basic Kanban board there would be three columns; "To Do", "In Progress" and "Done".  

For this exercise, you will be creating a task in an existing project.  You will then move the task from "To Do" to "In Progress".

1. Locate the "Projects" tab and click on it<br>
   ![alt text](images/github_projects_tab.png "Projects Tab")<br><br>

2. Select the "GitHub Training Test Board"<br>
   ![alt text](images/github_projects_window.png "Select Project")<br><br>

3. Create a task within the "GitHub Training Test Board" project<br>
    ![alt text](images/github_projects_addtask.png "Add the task")<br><br>
    ![alt text](images/github_projects_addtask2.png "Add the task")<br><br>

    Click "Add" when you're done filling in the issue

4. Drag that task to "In progress"<br>
    ![alt text](images/github_projects_dragtask.png "Drag Task to In Progress")<br><br>

5. Complete!<br>
    ![alt text](images/github_projects_complete.png "Complete Project Task Creation")<br><br>


<br><br><br>

--------------
<div class="pagebreak"></div>

## 4. Issue tracking
The GitHub issue tracker is a fantastic way to track software bugs, enhancements your project needs, places you
need help in the project, and questions about the project that need answers.  

In this exercise, you will create an issue, assign it to someone (Eugene, perhaps), label the issue and add it to a project from the project management tool.

1. Go to the Issues tab<br>
   ![alt text](images/github_issue_tab.png "Find the issue tab")<br><br>

2. Create a new issue<br>
   ![alt text](images/github_issue_new.png "Create a new issue")<br><br>

3. Complete the issue form.  Be descriptive!<br>
    ![alt text](images/github_issue_form.png "Complete issue form")<br><br>

4. When you're done with the form, press "Submit new issue".  Your issue is now submitted.<br>
    ![alt text](images/github_issue_created.png "Issue is now created")<br><br>

5. Assign someone to the issue using the "Assignees" edit tab<br>
   ![alt text](images/github_issue_assign.png "Assign the issue")<br><br>

6. Apply a label to the issue using the "Label" edit tab<br>
    ![alt text](images/github_issue_label.png "Add a label")<br><br>
    
7. Add the issue to a project using the "Project" edit tab<br>
    ![alt text](images/github_issue_projects.png "Add to a project")<br><br>

1. You have completed creating an issue!<br>
    ![alt text](images/github_issue_complete.png "Issue is created and published")<br><br>


<br><br><br>


--------------
<div class="pagebreak"></div>


## 5. Creating a wiki
A Wiki is a great place to keep information about a project for easy reference on the website.  In this exercise, you will create a new Wiki and work with the Markdown language to generate a simple but nicely formatted web page.

1. Navigate to the Wiki<br>
    ![alt text](images/github_wiki_tab.png "Wiki location")<br><br>
    
2. Create a new page<br>
   ![alt text](images/github_wiki_homepage.png "Create a new Wiki Page")<br><br>

3. Use Markdown to create formatted text<br>
    ![alt text](images/github_wiki_create.png "Fill in the Wiki Page")<br><br>

4. Press "Save page" and admire the results<br>
    ![alt text](images/github_wiki_complete.png "Wiki Complete")<br><br>


<br><br><br>

--------------
<div class="pagebreak"></div>

## 6. Creating a repository
Eventually, you will want to create your own repository.  This step is fairly simple, but you must remember that all funded NOAA work must be created within the **NOAA-PMEL** page.  

The task of creating a repository is fairly straightfoward.  In this execise, you will create a new repository within our personal account to minimize how many training repositories end up in **NOAA-PMEL**

1. From your dashboard, select "+" > "New Repository"<br>
  ![alt text](images/github_mainpage_newrepo.png "Two-Factor Authentication")<br><br>

2. Fill out the fields based on what you want your repository to reflect<br>
   
    ![alt text](images/github_createrepo_form.png "Two-Factor Authentication")<br><br>
    1. Adding a description is useful for external users to understand what the project or code does
    2. Public vs. Private: Private repos cost PMEL $, so use Public as much as you can.
    3. Initializing with a README is good practice.
    4. Add a license:  For code that you are willing to share openly, the Unlicense is a good choice.
    5. Add .gitignore: This sets up your repository to ignore files generated by compilers, tools, etc. that are not required in the repository.
3. Press "Create repository".  You have now created a new repo!<br>
    ![alt text](images/github_createrepo_complete.png "Two-Factor Authentication")<br><br>
4. To Clone a repo (use it from Git tool) click on the "Clone or download" button.<br>
   
    ![alt text](images/github_clone_repo.png "Clone the Repo")<br><br>

    1. Copy the link and use with your Git tool on your desktop or server to interact with this GitHub repository. <br>
   
    ![alt text](images/github_clone_repo_copylink.png "Copy the link")<br><br>


<br><br><br>

--------------
<div class="pagebreak"></div>

## 7. Other tools - Explore on your own
1. Git Gist
2. Marketplace
3. Search tool -> Explore thousands of repos for free!


<br><br><br>

--------------
<div class="pagebreak"></div>

## 8. Resources 
### GitHub Tutorials
* Introduction to GitHub<br>
  https://services.github.com/on-demand/intro-to-github/

* GitHub Hello World<br>
  https://guides.github.com/activities/hello-world/

### Git & GitHub Tutorials
* How to Use Git and GitHub - Version Control for Code<br>
  https://www.udacity.com/course/how-to-use-git-and-github--ud775

* Git & GitHub Crash Course for Beginners<br>
  https://www.youtube.com/watch?v=SWYqp7iY_Tc

### Markdown
* GitHub Mastering Markdown<br>
https://guides.github.com/features/mastering-markdown/

* Markdown Cheatsheet<br> 
https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#images