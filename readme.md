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


Ignore everything below:

1. (Optional) Set your MULE_HOME env variable: `export MULE_HOME={locationOfMuleInstall}`

1. Package and deploy: `mvn install`