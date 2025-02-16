# Git-Flows

## Tasks

0. Setting up gitflow

Objective: Understand and initialize a GitFlow workflow

Instructions:

Install git-flow if not already installed. Steps here

Create an empty repository ALXprodev-advanced_git

Clone your repository to have it available locally.

Initialize Git Flow within the repository using default settings i.e git-flow init [-d]

Create an empty README.md file

Repo:

GitHub repository: ALXprodev-advanced_git
File: REDME.md
 
1. Creating a feature branch
mandatory
Score: 16.67% (Checks completed: 33.33%)
Objective: Learn how to work with feature branches in GitFlow.

Instructions:

Create a new feature branch feature/implement-login from the develop branch

In the feature/implement-login create a new directory called login-page, inside it create a README.md file with the message: “Login Feature Coming soon

Commit your changes and push to github

Repo:

GitHub repository: ALXprodev-advanced_git
Directory: Login-page
File: `Login-page/README.md`
  
2. Creating a Release Branch
mandatory
Score: 0.00% (Checks completed: 0.00%)
Objective: Understand the release process in GitFlow.

Instructions:

Create a new feature branch feature/implement-signup from the develop branch and create a directory called signup-page with a README.md file with the message feature coming soon

Commit the changes and push to github

Merge the 2 branches to the develop branch. Fix conflicts if any

Create a new release branch release/1.0.0

Make changes to signup/READMDE.md file by adding the following text:” data requirements: email, firstName, lastName, profilePic]” inside the release branch

Commit and push changes to github then merge the release branch to the main branch and the develop branch

Tag the release with v1.0.0 and push the tags to the remote repository

Repo:

GitHub repository: ALXprodev-advanced_git
Directory: Login-page, Signup-page
File: `Login-page/README.md, Signup-page/README.md`
  
3. Git Hooks and Automation
mandatory
Score: 50.00% (Checks completed: 100.00%)
Objective: Implement Git hooks to automate parts of the GitFlow process.

Instructions:

Implement a pre-commit hook in the file .git/hooks/pre-commit that checks if each directory in a Git repository has a README file

Implement a post-merge hook that logs the merge after completing a merge into the main branch.

Hint: Read more here

Repo:

GitHub repository: ALXprodev-advanced_git
  
4. Manual Review
mandatory
Score: 0.0% (Checks completed: 0.0%)
Repo:

GitHub repository: ALXprodev-advanced_git