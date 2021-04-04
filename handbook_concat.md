# Software quality insurance handbook

## Introduction

This handbook has been written so the team can have clear guidelines and practices to follow in the futures development projects.
The handbook will be divided in 3 main parts. The first one will be about the advantages of code review and the best practices to follow in this exercice.
The second part will be about coding standards. It will explain how to manage the challenge of implementing coding standards to the development process of a team.
The last part will be about task estimation in scrum. It will explain what you should do and avoid in the task estimation process and how to improve the accuracy of
your predictions.

## Code review

The main objective of the code review process is to evaluate all new code for bugs, errors and quality standards set by the organization. Every team can benefit from code reviews regardless of the development methodology. Agile teams, however, can realize huge benefits because the work is decentralized within the team. No one person is the only one who knows a specific part of the code base. Simply put, code reviews facilitate knowledge sharing within the code base and within the team. But the code review process should not be limited to one-way feedback. Therefore, an intangible benefit of the code review process is the collective improvement of the team's skills by exposing each other to a different approach to the topic at hand and thus being able to mentor new engineers by sharing our knowledge. This in turn reduces development costs through knowledge sharing and improves code performance because due to lack of experience, some young developers may not know the optimization techniques that could be applied to their code. The code review process allows these developers to gain skills and improve the performance of their code. In addition, it gives these young developers a chance to hone their skills and become experts in their field. The code reviews help create a certain cohesion within the team and bring a better communication on the project.
 
 ![image](https://user-images.githubusercontent.com/39206476/113065208-646bf380-91b0-11eb-8512-f578c68cf3d6.png)

 ![image](https://user-images.githubusercontent.com/39206476/113065222-68981100-91b0-11eb-9218-fa0da8b229ba.png)
 
To summarize, here are the positive points of a code review
- Reduce costs
- Expose everyone to different approaches
- Minimize errors and their impact
- Better code quality
- Conform to style guidelines
- Have better estimates
- Mentor new engineers and share knowledge
- Ensure project quality
- Have a consistent implementation
- Improve code performance
- Create cohesion in the team

Let's talk about the bad uses of code reviews and the things to avoid during them.
One of the most important things in a team is cohesion and trust, it's important to know how to question each other and accept the objections of other developers. When we criticize something, we tend to highlight only the bad points and never the good. While a good code review is about pointing out imperfections in the code, your feedback should not be limited to finding errors. When you do reviews, you can also use comments to praise someone's good work. Do this especially if you learned something from the code or noticed a solution that you would not have found yourself. On the other hand, it is important not to hesitate to participate in code reviews, as some people are afraid to say what they think for fear of offending. In the way of saying things it is better for everyone to make suggestions rather than give orders such as, it allows others to come and ask themselves the question "what can it bring" rather than just execute the order. For example, if someone says "You should use getter and setter. This code is wrong. "This will discredit the developer's code and it may hurt the person's feelings, so it's better to offer a suggestion: In this case, "I would recommend using getter and setter, because..." This will allow the developer to research the topic and realize their mistake for themselves.

### Resources:
* https://hackernoon.com/code-review-for-real-people-261e3d9124ba
* https://tsh.io/blog/code-review-best-practices/
* https://www.atlassian.com/agile/software-development/code-reviews
* https://www.brightspot.com/products/developer-life-5-reasons-why-the-code-review-process-is-critical-for-developers
* https://phauer.com/2018/code-review-guidelines/

## Coding standards

Coding standards is a very important problematic in today software development teams and companies. It is mandatory in large organizations to have an unified way of coding
and ensure everyone can understand and work on code written by others. This page will cover the advantages of having coding standards in a team, how to put coding standards
in place, and how coding standards can affect and improve the work and the efficiency of the developers.


### Why introduce coding standards

Introducing coding guidelines and standards has become mandatory in todays large organizations. The two main reasons are that it ensures the security and the performance of the code.
Having a whole team of developers coding their own way without taking into consideration the specifics of the project or the system that it's going to work on can cause
critical security issues that are going to be hard and fastidious to fix.
Coding standards allow the code to be less complex, easier to understand rapidly by those who didn't wrote it.
It also allows the solution to be updated much faster since it reduces the compatibility issues between one piece of code and another. The developers will know the structure of the
code they are working on and they will save time on finding how to adapt themselves.
Another great advantage of having coding standards is the easy bug fixing. A desorganized and wild code will cause a lot of useless research and work to fix the smallest bug.
Having a well organized code will allow developers to identify the source of the problem fastly, and to fix it without having to redevelop the whole part.

Coding standards are today a very common practice in organizations, but it can take time to be fully accepted by developers. One of the main problems introducing
coding standards is the disagreements about the rules and the guidelines that are getting adopted.
There is a lot of viable ways of doing things in every coding language, and each developer may have his vision on how to do them, that leads to reticence to adopt new guidelines. 
Making them do things as the organization decided is a real challenge, and requires efforts by the developer to adapt his standards. That can be supported by automated tools.

### Automated code formatting

Implementing coding standards has become that important for companies that some of them developed automatisation tools that ensure of the respect of the guidelines. Usually coding
standards are mostly related to formatting and typography matters, like the amount of spaces or indentations at the begining of the lines, or the position of the brackets.
Each coding language has a lot of code formaters that can help a developer format his code, or check if it respects the standards that have been input. The best practice
is to have an automated tool that checks automatically the new code at every commit in the repository, and that send a report to the team on how well the code is formatted and 
how well it respects the guidelines. For example if the technology used is .NET, Team Foundation Server allow the organization to setup a checker that automatically checks the code,
highlighting to potential errors that have been made in term of coding standard, but also regarding the quality of the code, potential security breachs, and it gives recommendations
on how to fix it.


### Resources :
* https://www.freecodecamp.org/news/the-100-correct-coding-style-guide-5b594a1655f0/
* https://dzone.com/articles/tips-for-implementing-code-standards
* https://www.multidots.com/importance-of-code-quality-and-coding-standard-in-software-development/
* https://dev.to/georgehanson/why-are-coding-standards-important-49dp
* https://www.linkedin.com/pulse/motivation-importance-coding-standards-himalya-bansal/

## Task estimation in scrum

Task estimation in scrum agile projects in a crucial part of the development process, that assign to every task previously created her estimated difficulty, which gives an indication on how much time the task required to be done and who should do the task. Task estimation is usually done with the whole development team as it requires everyone to agree on the estimation.

### Techniques estimating tasks

There are several techniques that teams can use to estimate the difficulty of the tasks. The most popular one is the planning poker. The planning poker is a meeting where all the
members of the team are reunited to estimate together the tasks. Each task is passed on the table and everyone must say a number that correspond to how much he thinks the task
is complicated. The team has to come to an agreement based on what everyone answered and on the discussion they had about it.
A common practice when estimating tasks is to not use days as an unit but story points, which is a representation of how complicated the task is. Story points are usually following a fibonacci sequence (1, 2, 3, 5, 8, 13, 21 ..). Story points allows the team to have a more general vision of the task, also using days as an unit is most of the time
inaccurate since it depends on who does the task and there is often unpredicted things that happen to be done to complete the task.
To be more accurate on the estimations and having more vision over the sprint, the teams can estimate the tasks twice, in days/hours and in story points. That allows to ensure that every aspect of every task has been taken into consideration. However, estimating twice has disadvantages. For example if the team is accurate enough with story points, estimating in hours may only be a waste of time since it won't bring anything more. Also working in hours is often not appreciated by developers since it push them to to their task in the estimated time. That is a source of pressure and it can be unfair in the case that the task has been underestimated. 

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
* ongoing - the task has been assigned to someone and he is working on it
* to review - the task is completed and needs to be validated in a code review
* to test - the task has been validated in the review and the final test have to be done
* done - the task is fully tested and completed
* to fix - the task has been considered finished but some changes have been found to be done


### Resources :
* https://medium.com/serious-scrum/best-way-to-estimate-effort-using-story-point-in-sprint-planning-f43ad2d6fa91
* https://www.softwaretestinghelp.com/agile-estimation-techniques/
* https://hubstaff.com/tasks/agile-estimation-techniques
* https://www.projectmanagement.com/blog/blogPostingView.cfm?blogPostingID=46054&thisPageURL=/blog-post/46054/Task-Estimation-with-Scrum#_=_
* https://maartendalmijn.com/why-estimate-twice-in-scrum-fd0d68744501
