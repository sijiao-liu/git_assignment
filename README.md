# Git Assignment - sijiao-liu  

## a. What is an **_issue_**?
GitHub Issues are items you can create in repository to plan, discuss and track work. 
- Issues are simple to create and flexible to suit a variaty of scenarios. 
- You can use issues to track work, give or receive feedback, collaborate on ideas or tasks, and efficiently communicate with others.  

Issues are used to track todos, bugs, feature requests, and more. 
- As issues are created, they'll appear here in a searchable and filterable list. 


## b. What is a **_pull request_**?
A pull request is a proposal to merge a set of changes from one branch into another.  
- In a pull request, collaborators can review and discuss the proposed set of changes before they integrate the changes into the main codebase.
- Pull requests display the differences, or diffs, between the content in the source branch and the content in the target branch.  

Pull requests help you collaborate on code with other people.
- As pull requests are created, they will appear in a searable and filterable list.


## c. Describe the steps to **_open a pull request_**?
I will be using the Git Assignment as an example in the following:
1. In your `main` repository.
#### Method 1
2. Switch to the branch `assignment` you created locally using the drop down menu.
3. If you see your recent push on top of your branch, then click on `Compare & pull request` button.
4. Make sure you choose the right base `main` and compare `assignment`.
5. Add a title: highlight the main point of this request.  
    (i.e. **_UofT-DSI | git - assignment 1_**)
6. Add a description: explain your thought process. For example,
    * What changes are you trying to make? (e.g. Adding or removing code, refactoring existing code, adding reports)
    * What did you learn from the changes you have made?
    * Was there another approach you were thinking about making? If so, what approach(es) were you thinking of?
    * Were there any challenges? If so, what issue(s) did you face? How did you overcome it?
    * How were these changes tested?
    * A reference to a related issue in your repository. (if applicable)
    * Checklist: [ ] I can confirm that my changes are working as intended.
7. Click on `Create pull request` button.

#### Method 2
8. Click on `Pull requests` tab.
9. Under the `Comparing changes` section, make sure you choose the right base `main` and compare `assignment`, then the button `Create pull request` will become green and clickable.
10. Click on `Create pull request` button.
11. Apply **_step 5-7 from Method 1_**.


## d. Describe the steps to add a collaborator to a repository (share write permissions)
1. In your profile, click on the the repository/project your want to add collaborator and share write permissions.
2. In the top-right of each repository/project click on `Settings`. If you cannot see it, you can find it from the drop down menu (`...`).
3. Click on `Collaborators` tab which you can find under `Access` section from the left panel.
4. Click the `Add People` button under `Manage Access` section, you can search people by their username/full name/email.
5. After select the existing account, the `Add <git username> to this repository` button will turn green and become clickable. 
6. Click on the green button, in this way GitHub will send a notification email to the desired collaborator along with an invitation shown in the their `notification` centre. 
7. I suppose after the desired collaborator accept the invitation, you can select the type of access under `Manage Access` section mentioned in **_step 4_**.  
However, I have tried this personally with one of the Learning Supports, unfortunatly I don't see the option of provide the access. I supposed that **_share the access type_** option is not avaliable for the GitHub free version.


## e. What is the difference between **_git_** and **_GitHub_**?
### Git vs. GitHub
Below is a table shown the differences between Git and GitHub.  
|Git|GitHub|
|---|------|
|a software installed locally|a service hosted in the cloud|
|focused on version control and code sharing|focused on centralized source code hosting|
|primarily a command-line tool|a graphical interface administered through the web|
|no user management features|built-in user management|
|open source licensed|included both free and pay-for-use tiers|


## f. What does **_git diff_** do?
The `git diff` command help you see, compare, and understand changes in your project by comparing what is in your working directory to what is in your staging area.  
_For example,_ if you've made changes to your files without running `git add`, you'll see the comparison. Otherwise, nothing will be shown if there are no differences.  


## g. What is the **_main_** branch?
The `main` branch is the official working version of any git-versioned GitHub project.  
_N.B._ Don't mess with the `main` branch. If you ever want to make some changes to `main`, do it on anther branch and have it reviewed and/or discussed first before merging the changes to `main`.


## h. Besides our initial commit if it is a new repository, should we push our changes directly into the **_main_** branch?
No, we shouldn't push our changes into the `main` branch directly.

