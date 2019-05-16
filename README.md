# locsan-parent-pom
A parent pom project, to manage the versions of the  libraries for locsan application.

## Prerequisites
* To run the application you need to have git, mvn and JDK8 installed.

## Download
* Open command line and move to your workspace.
* Download project using your username: 
<br>`> git clone https://github.com/kmponis-nhs/locsan-parent-pom.git`
* Go to project: 
<br>`> cd /locsan-parent-pom`

## Run 
* Use terminal and move to your workspace
* Run in command line:
  <br>`> mvn clean install`

## Use
* Add to maven dependencies:
  <br>`<dependency>
    <groupId>com.locsan</groupId>
    <artifactId>locsan-parent-pom</artifactId>
    <version>1.0.0</version>
  </dependency>
  `

# General Info

## GIT Strategy
* Open command line and move to your workspace.
* Download project using your username: 
<br>`> git clone https://github.com/kmponis-nhs/locsan-parent-pom.git`
* Go to develop branch
<br>`> git checkout develop`
* Create a slave branch - using the story number (ex. sml-9)
<br>`> git branch <newBranchName>`
* Select slave branch 
<br>`> git checkout <newBranchName>`
* Add slave branch to repository 
<br>`> git push --set-upstream origin <newBranchName>`
* When story is finished push and request a merge
* Pull changes from develop
<br>`> git checkout <newBranchName>`
<br>`> git fetch origin`
<br>`> git merge origin/develop`
<br>`> git push`