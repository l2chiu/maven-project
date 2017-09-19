# maven-project

This is my Maven project from MuleSoft's advanced development class

## How to run the project

1. Add the remote repository: `git remote add origin https://github.com/{yourGithubUser}/maven-project.git`

1. Enter the repo: `cd maven-project`

1. git status (lots of system folders/files)

1. create .gitignore to ignore most of the system files, look at example.

1. git status

1. git add .

1. git add -f .gitignore

1. git status

1. git commit -am "Initial commit"

1. git push origin master


## How to update project files

1. Make changes

1. git add .

1. git commit -am "Added Changes"

1. git push origin master

For above, combine 2 commands:
1. git add . && git commit -am "Format change"

Ignore everything below:

1. (Optional) Set your MULE_HOME env variable: `export MULE_HOME={locationOfMuleInstall}`

1. Package and deploy: `mvn install`


## Internal

1. Create Repo in Github

1. Go to folder of Project

1. git init

1. Copy .gitignore file

1. Verify files with git status

1. git Add .

1. git commit -am "Initial Commit"

1. git remote add origin https://github.com/{yourGithubUser}/maven-project.git`

1. git pull origin master --allow-unrelated-histories (if Readme.MD created)

1. git push origin master
