# Git Bash Commands

Cd - Changes Directory

Ls - Check directory

Mkdr - make directory

Nano - to save Control X - Y for yes N for no

Code - check in visual studio

Cat - Prints what’s inside file

RM - deletes files

Rmdir - Delete directory

git --version - Git Version

py --version - Python version

--version - Universal version

git status - current status

git init - creates new local repository.

git commit -m "Commit message" commit changes to head but not to remote repository.

git commit -a - Commit any files you've added with git add and commit any files you've changed since.

git revert - lets you go back to previous version.

git log - check status of commits

git merge - simple changes merging to main file or choosing which conflicting file to keep.

Git reset —hard

Git clean - fxd -

git remote -v - list all currently configured remote repositories.

git remote add origin - connect to remote repository.

Branch
git branch -m main

git checkout -b - Create a new branch and switch to it

git checkout switch from one branch to another.

git branch - list all the branches in your repository and what branch you're in.

git branch -d - delete the branch

git push -u origin - send changes to specified branch of remote repository.

git push --all origin - push all branches to your remote repository.

git push origin :<branchname> - delete a branch on your remote repository

Update from the remote repository
git pull - fetch and merge changes on the remote server to your working directory

git merge to merge a different branch into your archive branch

git diff - view all the merge conflicts

git diff --base - view all merge conflicts against base file

git diff - preview changes before merging

git tag 1.0.0 - mark significant change such as a release

git log - Create CommitID using this

git push --tags origin - push all tags to remote repository.

Undo local changes
git checkout -- - replace the changes in your working tree with the last content in head. Changes already added to the index and new files will be kept.

git fetch origin - fetch the latest history from the server git reset -- hard origin/main - point your local main branch at it.

https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html

cp [name of file] [name of output file] - copy paste into another file

git config --global user.name - tell Git who you are

git clone - create a copy of a local repository.

git clone username@host:/path/to/repository - for remote repository

git push -f origin main - overrides conflicts

# Agile

Agile is an iterative approach to project management and software development that helps teams deliver value to their customers faster and with fewer headaches. Instead of betting everything on a "big bang" launch, an agile team delivers work in small, but consumable, increments.

The four values of the Agile Manifesto
* Individuals and interactions over processes and tools.
* Working software over comprehensive documentation.
* Customer collaboration over contract negotiation.
* Responding to change over following a plan.

Agile Methods, Practices, Frameworks and Techniques
- Scrum
- Kanban
- Extreme Programming (XP)
- Lean Development
- Crystal
- Feature-Driven Development FDD
- Dynamic Systems Development Method (DSDM)
- Scaled Agile Framework (SAFe)
- Scrum@Scale
- Scrum of Scrums (SoS)
- Large Scale Scrum (LeSS)
- Nexus
- Disciplined Agile (DA)

Agile Manifesto

Individuals & Interactions over process and tools

Working software over comprehensive documentation

Customer collaboration over contract negotiation

Responding to change over following plan

Information radiator
Three pillars of Scrum
1. Transparency
2. Inspection
3. Adaptation

Scrum Roles
- Product Owner
- Scrum Master
- Development Team

How can we effectively gather requirements?
1. Establish Wants vs needs - Qualifying requirements

User Stories 
As a… I want… So that…

Independent 
Negotiable 
Valuable
Estimable
Small
Testable

The Three C’s
Card
Conversation
Confirmation

Gherkin Scenario
Given 
         AND
When 
         AND
Then 
        AND


Retrospective
- Make sure you have 3 points for next time
- What went well
- What could be improved
- Actions

