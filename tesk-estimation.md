### Introduction

Task estimation in scrum agile projects in a crucial part of the developement process, that assign to every task previously created her estimated difficulty, which gives an indication on how much time the task required to be done and who should do the task. Task estimation is usually done with the whole development team as it requires everyone to agree on the estimation.

### Techniques estimating tasks

There are several techniques that teams can use to estimate the difficulty of the tasks. The most popular one is the planning poker. The planning poker is a meeting where all the
members of the team are reunited to estimate togtether the tasks. Each task is passed on the table and everyone must say a number that correspond to how much he thinks the task
is complicated. The team has to come to an agreement based on what everyone answered and on the discussion they had about it.
A common practice when estimating tasks is to not use days as an unit but story points, which is a representation of how complicated the task is. Story points are usually following a fibonacci sequence (1, 2, 3, 5, 8, 13, 21 ..). Story points allows the team to have a more general vision of the task, also using days as an unit is most of the time
inaccurate since it depends on who does the task and there is often unpredicted things that happen to be done to complete the task.
To be more accurate on the estimations and having more vision over the sprint, the teams can estimate the tasks twice, in days/hours and in story points. That allows to ensure that every aspect of every task has been taken into consideration. However, estimating twice has disavantages. For example if the team is accurate enough with story points, estimating in hours may only be a waste of time since it won't bring anything more. Also working in hours is often not appreciated by developers since it push them to to their task in the estimated time. That is a source of pressure and it can be unfair in the case that the task has been underestimated. 

### How to estimate efficiently

Whatever the used technique to estimate, to be the most accurate possible, the members should ask themselves a few questions that are going to help them understand the task more 
deeply :
* Design: What is the prior and mandatory knowledge that we should have before starting to work on it ?
* Coding: How much coding is required for implementing this user story. Have we come across any similar user story previously ?
* Unit Testing: Are any mock objects required for doing unit testing for this user story ?
* Integration Testing: Does this story impact the other functionalities of the same module and other modules also ?
* Acceptance Testing: What are the points to be taken care to deliver the desired product as desired by the Customers ?
* Expertise: Does any of the participants have done similar story before and is an expert in it ?

### Useful tools

There is several tools that facilitate task estimation and make it faster. For example, for planning poker, a lot of services can be found online by searching on google for "planning poker tools". To regroup all the tasks, write them before estimate them, and store them with all necessary informations after the estimation, the team can use a scrum project manager such as jira or trello. These tools allow to create the tasks, assign them to the right person, assign them story points, priority levels, and allow developers to move the task in areas corresponding to their level of advancement. The levels of advancement usually are :

* backlog - the tasks are stored here before having being estimated
* todo - the tasks has been estimated and need to be assigned to someone
* ongoing - the task has been assigned to someone and he is working ont it
* to review - the task is completed and needs to be validated in a code review
* to test - the task has been validated in the review and the final test have to be done
* done - the task is fully tested and completed
* to fix - the task has been considered finished but some changes have been found to be done


### Ressources :
* https://medium.com/serious-scrum/best-way-to-estimate-effort-using-story-point-in-sprint-planning-f43ad2d6fa91
* https://www.softwaretestinghelp.com/agile-estimation-techniques/
* https://hubstaff.com/tasks/agile-estimation-techniques
* https://www.projectmanagement.com/blog/blogPostingView.cfm?blogPostingID=46054&thisPageURL=/blog-post/46054/Task-Estimation-with-Scrum#_=_
* https://maartendalmijn.com/why-estimate-twice-in-scrum-fd0d68744501
