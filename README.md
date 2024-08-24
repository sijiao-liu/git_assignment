# Git Assignment - sijiao-liu  

## a. What is an **_issue_**?
GitHub Issues are items you can create in repository to plan, discuss and track work. 
- Issues are simple to create and flexible to suit a variaty of scenarios. 
- You can use issues to track work, give or receive feedback, collaborate on ideas or tasks, and efficiently communicate with others.
(Ref: [About issues - GitHub Docs] (https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues "GitHub Doc/GitHub Issues/Issues")

Issues are used to track todos, bugs, feature requests, and more. 
- As issues are created, they'll appear here in a searchable and filterable list. 
(Ref: description given by the issues tab in the GitHub repository created)


## b. What is a **_pull request_**?
A pull request is a proposal to merge a set of changes from one branch into another.
- In a pull request, collaborators can review and discuss the proposed set of changes before they integrate the changes into the main codebase.
- Pull requests display the differences, or diffs, between the content in the source branch and the content in the target branch.
(Ref: [About pull request - GitHub Docs] (https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests "GitHub Doc/Pull requests/Collaborate with pull requests/Propose changes")

Pull requests help you collaborate on code with other people.
- As pull requests are created, they will appear in a searable and filterable list.
(Ref: description given by the Pull requests tab in the GitHub repository created)


## c. Describe the steps to **_open a pull request_**?
Note that I will be using the Git Assignment as an example
1. In your main repository  
    (i.e. git_assignment: https://github.com/sijiao-liu/git_assignment)
#### Method 1
2. Switch to the branch you created locally using the dropdown menu  
    (i.e assignment: https://github.com/sijiao-liu/git_assignment/tree/assignment)
3. If you see your recent push on top of your branch repository (i.e. assignment), then click on the button **_Compare & pull request_**.
4. Make sure you choose the right base (i.e. main) and compare (i.e. assignment)
5. Add a title: TITLE: UofT-DSI | <Module Name> - Assignment <assignment number>  
    (i.e. **_UofT-DSI | git - homework 1_**)
6. Add a description: explain your thought process. For example,
    * What changes are you trying to make? (e.g. Adding or removing code, refactoring existing code, adding reports)
    * What did you learn from the changes you have made?
    * Was there another approach you were thinking about making? If so, what approach(es) were you thinking of?
    * Were there any challenges? If so, what issue(s) did you face? How did you overcome it?
    * How were these changes tested?
    * A reference to a related issue in your repository (if applicable)
    * Checklist: - [ ] I can confirm that my changes are working as intended
7. Click on the button **_Create pull request_**

#### Method 2
8. Click on **_Pull requests_** tab
9. Under the **_Comparing changes_** section, make sure you choose the right base (i.e. main) and compare (i.e. assignment), then the button **_Create pull request_** will become green and clickable.
10. Click on the **_Create pull request_** button.
11. Apply step **_5-7 from Method 1_**.


## d. Describe the steps to add a collaborator to a repository (share write permissions)
1. Click on the the repository your want to add collaborator and share write permissions from your profile.
2. In the top-right click on Settings, if you cannot see Settings, you can find it from the drop down menu (...).
3. Click on _Collaborators_ tab which you can find under _Access_ section
4. Click the **_Add People_** button under **_Manage Access_** section, you can search people by username/full name/email.
5. After select the existing account, the _Add <git username> to this repository_ button will turn green and clickable. 
6. Click on the green button, in this way GitHub will send a notification email to the desired collaborator and the invitation will also shown in the message box of the desired collaborator. 
7. I suppose after the desired collaborator accept the invitation, you can select the type of access under **_Manage Access_** section mentioned in step **_4_**. However, I have tried this personally with one of the Learning Supports, unfortunatly I don't see the option of provide the access. I supposed that **_share the access type_** option is not avaliable for the GitHub free version.


## e. What is the difference between **_git_** and **_GitHub_**?
### Git vs. GitHub
|Git|GitHub|
|----------|
|a software installed locally|a service hosted in the cloud|
|----------|
|focused on version control and code sharing|focused on centralized source code hosting|
|----------|
|primarily a command-line tool|a graphical interface administered through the web|
|----------|
|no user management features|built-in user management|
|----------|
|open source licensed|included both free and pay-for-use tiers|


## f. What does **_git diff_** do?
The _git diff_ command help you see, compare, and understand changes in your project by comparing what is in your working directory to what is in your staging area.  
For example, if you've made changes to your files without running _git add_, you'll see the comparison. Otherwise, nothing will be shown if there are no differences.  


## g. What is the **_main_** branch?
The _main_ branch is the official working version of any git-versioned GitHub project.  
N.B. Don't mess up with the _main_ branch. If you ever want to make some changes to _main_, do it on anther branch and have it review first before merging the changes to _main_.


## h. Besides our initial commit if it is a new repository, should we push our changes directly into the **_main_** branch?
No, we shouldn't push our changes into the _main_ branch directly.

