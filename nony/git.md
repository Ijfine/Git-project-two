# Git project

## Git description

Git is an open source distributed version control system that is available for free. The Git source code is hosted on GitHub, from where it can be downloaded or installed. 

Git is used primarily by developers to manage their source code. With Git, each user can maintain the primary copy or clone of the repository, including its entire history which as a result, each clone serves as a backup.

# Git Commands

## Initializing Git

The **git init** command creates a new Git repository. It is the first command you'll run in a new project.

*git init*

create a working folder (*mkdir DevOps*)

move into the folder (*cd DevOps*)

then run the Git command (*git init*)

![initializing Git repository](https://github.com/Ijfine/Git-project-two/assets/140953321/cc9ba28b-7242-4a34-b0ef-8706e506f9bf)

## Making commit

**git commit** command captures the snapshot of your entire repository at a specific time. When a commit is created, it makes a record of exactly how all the files and directories looked at the moment of creation. 

create a file inside your working folder (*touch index.txt*)

write a sentence inside the file (*echo "made a good choice" > index.txt*)

add the changes to git staging (*git add .*)

now commit your changes to git (*git commit -m "initial commit"*)

![making commit](https://github.com/Ijfine/Git-project-two/assets/140953321/514d8f17-4a41-46f4-8ecc-967cc5587d45)

## Working with branches

A branch in Git is a new or seperate version of the main repository. It allows you to copy code, rename files, or update your design on your main branch.

To create and change into new branch (*git checkout -b UpdateText*)

![first Git branch](https://github.com/Ijfine/Git-project-two/assets/140953321/436ec454-5403-4469-bb15-789b61a4b8c1)

## Listing all git branches

To see all your local branches, run this command (*git branch*)

![listing git branches](https://github.com/Ijfine/Git-project-two/assets/140953321/b1e87465-b0d4-47bd-b0a3-e74346ddf5b8)

## Change into an old branch

To change into an old branch, run this command (*git checkout main*)

![change into old branch](https://github.com/Ijfine/Git-project-two/assets/140953321/8f9a7aee-0e0f-49bc-9f50-46424fd792f0)

## Merge a branch into another branch

Use this command (*git merge main*)

![merge branches](https://github.com/Ijfine/Git-project-two/assets/140953321/034c1289-4fed-4d50-9137-5186806fa0d2)

## Deleting a Git branch

Run this command (*git branch -d UpdateText*)

![delete git branch](https://github.com/Ijfine/Git-project-two/assets/140953321/03f9d1ee-47ac-48a4-8493-19c8430f8fdc)

## Creating a repository

Inorder to create a repository for your project, you need to set up a GitHub account. Afterwards, you can create your repository.

![create repository](https://github.com/Ijfine/Git-project-two/assets/140953321/a01963a4-d65c-4da1-9411-aedbb1878f90)

Having created a GitHub account and repository, the next step is to send a copy of your work to your repository in github

Copy git remote add origin <link to your github repo>

git remote add origin https://github.com/Ijfine/Git-project.git

![push repository](https://github.com/Ijfine/Git-project-two/assets/140953321/424895dd-ed63-4066-88ab-ad776f1dbc81)

Push the content to your remote repo

*git push -u origin main*

![push origin](https://github.com/Ijfine/Git-project-two/assets/140953321/16c03dec-373f-43e6-be4d-6f67b8d28c82)

## Cloning your repository

**git clone* command helps you to make a copy of your remote repository.

use this command *git clone, <link to your remote repository> 

(*git clone https://github.com/Ijfine/Git-project.git*)

![clone repository](https://github.com/Ijfine/Git-project-two/assets/140953321/f1307fe9-8267-40e9-9278-66b82689724d)
