# Step-By-Step Guide on How to Start a New Group Project on GitHub

## 1. Make a new GitHub repository
You want a central place where all group members can contribute, so one member (Team Leader) should make a new repo. Follow the instructions below:

* Open [GitHub](https://github.com/) and log in to your account
* Create a new repository in your account.
* Write a *Repository name*. You may leave the *Description* blank.
* Keep your repository **Public** so I can view your work for grading.
* Check both **Add a README file** and **Add .gitignore**. In the **.gitignore template** dropdown menu, select C++.
    * **README.md** is a file for an introduction to your project 
    * **.gitignore** file will prevent unneeded files from being uploaded to GitHub and taking up space
* If you need more help, here is a [tutorial](https://docs.github.com/en/github/getting-started-with-github/create-a-repo) from GitHub.

## 2. Add other members
The person who set up the new repo can then give the other members push access by adding them as collaborators. To do this:
* Go to *Settings* tab of your repository
* Go to *Manage Access* tab from the side table
* Click button to *Invite a collaborator*
    * Supply GitHub username or email
    * Also invite the instructor (username: `gabrieledcjr`)

Each member will get an email invitation that they then need to accept.

## 3. Clone the repo
Every other member of your group should then clone the repository to their local machine.
* At this point, everyone should have a copy of the basic folder structure on their machine. 
* Every member's commit will be accounted for in the GitHub tracker. This is also a way for the instructor to see each member's contribution to the code.

> **IMPORTANT NOTE:** that you **will not** have a repository on your GitHub account, but you can fork it when the project is finished in order to share links to it.
    
## 4. Create a branch protection rule
You don't want to push code that hasn't been reviewed to the **main/master** branch, so the admin should create a branch protection rule. To do this:
* Go to the *Settings* tab of your repository
* Click on the *Branches* tab from the side table
* Click "Add Rule"
* Type "main" in branch name pattern and select:
    * "Require pull request reviews before merging"
    * "Include administrators" - ***With this setting, the owner of the repo also has to get approval before merging with master***
* Click the "Create" button

With these settings, at least one person MUST review code before it can be merged into the `main` branch.

## 5. Create a new branch for each new feature
From this point, each member of the group will 

> Source: Adapted from https://www.digitalcrafts.com/blog/learn-how-start-new-group-project-github
