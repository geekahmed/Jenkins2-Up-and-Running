# Jenkins 2 Up and Running, Evolve Your Deployment Pipeline for Next Generation Automation
This is my summary of the Jenkins 2 Up and Running, Evolve Your Deployment Pipeline for Next Generation Automation by Brent Laster. Contributions: Issues, comments and pull requests are super welcome.  


If you want to download the book, please use this link: 
https://www.oreilly.com/library/view/jenkins-2-up/9781491979587/ 

<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->  
# Table of Contents  
- [Chapter 1. Introducing Jenkins 2](#chapter-1-introducing-jenkins-2)  
- [Chapter 2. The Foundations](#chapter-2-the-foundations)  
<!-- /TOC -->  

# Chapter 1. Introducing Jenkins 2
- This chapter has offered a short overview of what distinguishes Jenkins 2 from standard Jenkins. There is fundamental support for pipelines as jobs and as Jenkinsfiles, which are distinct from Jenkins. When developing pipeline code, you may use either the old, more flexible Scripted Pipeline syntax or the more structured Declarative Pipeline syntax.
- Jenkins 2 also includes a number of new project categories. 
	- The Folder type allows you to combine projects together under a common namespace and environment. 
	- The Multibranch Pipeline type enables simple automatic task generation per branch as well as continuous integration, both of which are triggered by Jenkinsfiles located in the branches.
	- The organisation project type provides the multibranch capabilities to all projects under a GitHub or Bitbucket organisation structure.
# Chapter 2. The Foundations