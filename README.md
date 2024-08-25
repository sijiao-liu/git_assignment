# Git Assignment - sijiao-liu  

## a. What is an **_issue_**?
An `issue` in GitHub is a tool used to plan, discuss, and track work within a repository.  
- It helps manage tasks, track bugs, request features, and facilitate communication and collaboration.  
- Issues are easy to create, flexible, and can be organized in a searchable and filterable list.  


## b. What is a **_pull request_**?
A `pull request` in GitHub is a proposal to merge changes from one branch into another.  
- It allows collaborators to review, discuss, and approve changes before they are integrated into the main codebase. 
- Pull requests also show the differences between the source and target branches and are listed in a searchable and filterable format once created.


## c. Describe the steps to **_open a pull request_**?
To open a pull request in GitHub, follow these steps:  

1. Switch to the branch you want to merge (e.g., assignment) using the drop-down menu in your repository.  

### Method 1
2. Click the `Compare & pull request` button if you see your recent push on top of your branch.
3. Ensure the _base_ branch is `main` and the _compare_ branch is `assignment`.
4. Add a title and description for your pull request.
5. Click `Create pull request`.

### Method 2
6. Go to the `Pull requests` tab.
7. In the `Comparing changes` section, select `main` as the _base_ branch and `assignment` as the _compare_ branch.
8. Click `Create pull request` once it becomes clickable.
9. Add a title and description for your pull request.
10. Click `Create pull request`.


## d. Describe the steps to add a collaborator to a repository (share write permissions)
To add a collaborator with written permissions to a repository, follow these steps:  

1. Go to the repository you want to modify from your profile.
2. Click `Settings` in the top-right corner of the repository. If not visible, find it under the `...` menu.
3. Select the `Collaborators` tab under the `Access` section in the left panel.
4. Click `Add People` under the `Manage Access` section and search for the person by username, full name, or email.
5. After selecting the user, click the green `Add <username> to this repository` button.
6. GitHub will send an email invitation to the collaborator.
7. Once the collaborator accepts the invitation, you can set their access level under Manage Access.  _Note:_ Access levels might not be available on free GitHub plans.


## e. What is the difference between **_git_** and **_GitHub_**?
Below is a table shown the differences between Git and GitHub:  

|Git|GitHub|
|---|------|
|a version control software installed locally|a cloud-based service that hosts repositories|
|no user management features|built-in user management|
|focused on managing code versions and changes|focused on centralized source and collaborative code hosting|
|a command-line** tool|a web-based interface|
|open source licensed|included both free and pay-for-use tiers|


## f. What does **_git diff_** do?
The `git diff` command shows the differences between your working directory and the staging area.  
- It helps you compare and understand changes that have been made to files before they are staged. 
- If no changes are present, it will show no differences.


## g. What is the **_main_** branch?  
The `main` branch is the primary branch of a GitHub project, representing the official working version. 
- Changes to `main` should be made in separate branches, reviewed, and discussed before merging.


## h. Besides our initial commit if it is a new repository, should we push our changes directly into the **_main_** branch?
No, you should avoid pushing changes directly into the `main` branch besides the initial commit of a new repository. Instead, use separate branches for making changes, and merge them into `main` after review and testing.

