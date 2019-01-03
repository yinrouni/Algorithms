# Spring 19 Algorithms Monorepo

* *Your name here* **(TODO: Change this heading to your name)**
* *[Phonetic spelling](https://dictionary.cambridge.org/us/help/phonetics.html) of your name here* **(TODO: Change this)**

## Partners Spreadsheet
(Lookup your weekly lab partner(s) here) 
https://docs.google.com/spreadsheets/d/1ORbEDLNAFzAMT4FbUeMy1wUdxxUpqs7wNUR8s4OUByY/edit?usp=sharing

*Note: It may be helpful to review this spreadsheet before each class, but I will typically put up the partners spreadsheet before lab starts. If you know you will be sick or otherwise miss class, e-mailing me beforehand helps me rearrange teams.*

## Obtaining a Khoury account

Note that all assignments are run on the Khoury web servers: `ssh your_user_name@login.khoury.neu.edu`

[Creating a Khoury account if you need one](https://www.khoury.northeastern.edu/systems/getting-started/) 

## The Monorepo

Welcome! This repository will be how to retrieve homework assignments and in-class lab assignments for this course,

Okay, let's get started!

### Learning git
If you are not familiar with git, you can quickly learn the basics of how it works in about 15 minutes.

* An interactive tutorial: 
  * https://www.codecademy.com/learn/learn-git

### Github and this course

This course utilizes github because:

- It is good real world skill to have.
- Github is the website which provides a service to store our files, and 'git' is the version control system.
- It is easy for me to monitor your progress and receive your assignments for grading.
  - (You will also never e-mail me code snippets, I can just look!)
- In order to receive your assignments, you simply do 'git pull' after I have released them.
  - This will make sense after trying the tutorial if you are new to git.

That being said, I can only grade what you have **pushed** to your repo. Make sure to push your latest changes to your repo. The timestamp tells me when your file was submitted as well.

## FAQ

- Q: May I upload the github to a public repository for prospective employers to see?
  - A: **No**. You may not upload any assignments. This is for your protection in case assignments or parts of assignments are reused. You *may* list the project on your resume/CV if you like, and provide the code upon request to the employer. You could additionally provide a webpage describing the project, showing screenshots, and discussing high-level ideas of how you solved the project.
- (Applicable only to my courses with final projects)
- Q: May I upload my final project to a public repository after the semester is over?
  - A: **Yes under the following conditions**
    - The course actually has a final project, which is a unique idea (i.e. not assignment or series of assignments) that you or a team developed from scratch.
    - You acknowledge your team members for their contributions.
    - You remove the README.md provided with the assignment (delete it entirely from your github history), as you'll want your own readme anyway.

## Logistics
For all assignments, you must login into the servers through `your_khoury_name@login.khoury.neu.edu` to complete the assignments. The reason is because the examples I will provide below are compiled strictly for our machines architecture, and this is where your submission will be graded. While it is true you can probably do much of the assignments locally (if you have a Mac, Windows Terminal, or Linux machine), you **must** make sure your submissions work on the Khoury servers.

## Monorepo

A monorepo is known as a 'monolithic' repository. Companies like Google for instance have nearly all of their code from every single employee in one single repository. Some companies choose to have many separate repositories. Which strategy would you think is better? Take a moment to think about it, and you can read more on the 'why' (at least for Google) and other companies below: 

* https://cacm.acm.org/magazines/2016/7/204032-why-google-stores-billions-of-lines-of-code-in-a-single-repository/fulltext
* https://danluu.com/monorepo/
