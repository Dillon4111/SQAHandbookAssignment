# **Coding Standards**
When working as a team, it is very important to set rules and guidelines of what your code should look like. This can be from simple naming conventions to refactoring, so everything works and operates effeciently. Without a standardised way of coding it can be very difficult for new and existing team members to understand the codebase which can increase the development life cycle of a program.
In a lot of real-world situations, teams are working on older, already existing software that were previously developed by a different team. Having good-quality coding standards will make it easier for everyone.


<p align="center">
  <img src="https://miro.medium.com/max/933/1*D1LUjhNa6_9gW519n6V9iQ.jpeg"
        alt="Markdown Monster icon" width="350"/>
</p>

## Benefits of having good coding standards:
- Easy for different team members to read and maintain.
- Reduces code complexity which in turn reduces the number of bugs and errors in the code.
- Makes code more secure, the quality of code is better and it's less likely to be hacked.
- Improves efficiency of programmers as it takes them less time to understand another programmers code and it's easier to test.

## Naming Conventions: 
It's very important to give meaningful names to variables, functions, packages etc. so they are easily undertandable. It's up to the developer what to use but in general...
- CamelCase should be used for local variables e.g firstName. So the first lettter of each word is a capital apart from the first.
- Constants should have all capital letters e.g CONSDATA
- Global variables should start with a capital letter e.g GlobalVariable.
- Avoid using digits in variable names.
- Functions should be written in CamelCase and should describe what it is doing.
- File names should use CamelCase.

## Indentation:
- Must be a space after a coma between two function arguments
- Nested blocks should be properly indented and spaced
- All braces should start from new line
- Appropriate indentation should be at the end of each block.

## Comments: 
- Adding comments helps other developers to understand your code
- When writing a complex function add a short comment at the beginning to briefly explain it
- At the top of each file or class specify its role and contents
- Avoid unnecessary comments that explain lines of code that are obvious
- Keep comments clear and tidy

## Error Handling & Testing:
- When throwing an exception make sure to properly handle the error and give an informative message
- All functions that are encountering an error condition should either return a 0 or 1 for simplifying the debugging
- Unit tests need to be written for all functions so any changes down that road can be done with peace of mind
- Unit testing saves time and also reduces code complexity

# **Task Estimation in Scrum**
When using scrum, one of the main problems encountered is how to estimate the size and measure the velocity for a project or task. Task estimation is a process that helps solve this problem by creating an estimation using techniques based on the effort needed to complete the work and the duration it will take to be completed. Task estimation can provide us with:
- More control over sprints.
- Prevent over and under committing to tasks.
- Provides transparency on how much work there is left to do.
- Measure the overall projects success.

There is many different methods to help us accurately create an estimation as outlined below, each having their on advantages depending on the project and team. However when implementing them we must be careful and only use the most relevant data to ensure our estimations are accurate, otherwise we may face future problems such as:
- missed deadlines
- bottlenecks
- roadblocks
- scope creep

## **Estimation Techniques**


## Story Points
- Story points are a unit for measuring an estimation on the overall effort required to implement a feature.
- For each story point created we assign a value to it.  The values must be relative to other story points so for example a story that has been assigned a value of 2 must be twice as much work as a story assigned a value of 1.
- The amount of story points completed per iteration will define the teams velocity.
- To create a story point estimation, there are 3 main considerations for the task being estimated:
  - The risk involved with the project
  - The complexity of developing a feature
  - Repetiton of certain tasks within development
- If something changes such as requiremnts for the feature then the task should be re-estimated.
- If a story has a high estimation, there will be a high degree of uncertainty with it. Therefore it is better to break these featues down into smaller stories where possible. 
-  Very small stories should be grouped. If a story is less than a 1 but being assigned a 1 it can give the team a false sense of success as it appears more work is being done.
- It is important that estimation is done with the whole team, meaning that those who will be carrying out the work will be involved in the estimation.

## Planning Poker
- Planning poker is where each member of a team are given a set of cards. 
- Normally the cards will have numbers on them that are based on the Fibonacci sequence. 
- The product owner goes through each story point with the group with everyone holding up a card for each one to give their estimate of how much effort it takes to complete each story. 
- Team members with uncommon numbers will give their opinion on why they chose their number. 
- After these discussions the team re-estimates the story point until they agree and the result is recorded.
- Being restricted to 9 numbers speeds up the estimation process a lot. 
- This technique focuses on smaller features, higher estimates are usually not well understood and get re-estimated another time. 
- It gets every team member involved in the decision making process and this leads to more accurate results.
- A lack of appropriate acceptance criteria can make this technique difficult.

## T-Shirt Sizes
- This is a simple technique thats quick and easy to get started. 
- It involves grouping together tasks of similar sizes. 
- Tasks are labelled using t-shirt sizes Extra Small(XS), Small(S), Medium(M), Large(L) and Extra Large(XL). 
- It cannot be assosiated with a specific time which makes it very effective because when an estimate is asociated with time, people feel pressured into being as accurate as possible.

## The Bucket System
- This technique is usually used when a larger number of people are involved in the estimation process or there is a large number of items to b estimated.
- Tasks are placed in appropriate buckets based on the estimates of the diffreent team members. 
- This makes estimation in big groups faster.

## Large Uncertain Small
- This is where the team groups the items into different categories.
- Starting off with the extreme ones first, the items are put into Large, Uncertain or Small.
- This technique is better used in smaller teams with similar items.

## Dot Voting
- When dealing with only a handful of items (usualy less than 10) and you want to keep things simple use this technique.
- Team members use stickers to vote on each of the different items.
- This is very efficient for estimating a small number of tasks without using more complicated techniques.



# **Code Reviews**
A code review is when one member of the team checks another members code to examine it for areas which could improve such as finding bugs or errors and improving code quality.  Code reviews should be integrated into the teams existing process, for example if the team are using task branching workflows then the code review should be conducted before the code is merged. Reviewing a codebase makes sure that every software or new feature developed is of high quality. It is a crucial part of software quality assurance that provides many benefits to the development lifecycle. 

## **Benefits of Code Reviews**

-	Helps to identify bugs early which saves time and resources in the long term.
-	Developers share knowledge with each other allowing them to improve and write better code. This also helps young developers improve their skills and coding ability. 
-	Improves the quality of code making it easier for others to collaborate. 
-	Optimises the code for better performance.
-	Helps maintain a level of consistency in software design and implementation.
-	Improves Team cohesion as code reviews help generate discussions around the project and get team members working together.


<p align="center">
  <img src="https://www.dotnetcurry.com/images/software-gardening/code-reviews/code-review-benefits.jpg"
        alt="Markdown Monster icon" width="350"/>
</p>


# **Code Review Techniques**

## **Line and Time Management**
* Review fewer than 400 lines of code at a time. 

A couple of years prior Cisco did a huge Case Study on lightweight code review measures. 
As indicated by Cisco, to get ideal adequacy, developers should survey less than 200-400 lines of code (LOC) at a time. It additionally influences the capacity to discover flaws inside the actual code. 
In practise, an hour is a decent amount of time as anything more  could yield a 70-90% defect finding. The mind can adequately handle a limited amount of data at a time; beyond 400 LOC, the capacity to discover deficiency decreases. 
Additionally, following an hour the reviewer can become burnt out and will not be as productive in discovering mistakes and imperfections. 

<p align="center">
  <img src="http://blog.overops.com/wp-content/uploads/2017/01/density.png?_ga=2.90773850.1357615081.1617277416-1155500591.1617277416"
        alt="Markdown Monster icon" width="350"/>
</p>

Furthermore, Cisco brings up that the ideal examination rate is under 300-500 LOC/hour. This ratio permits developers to take as much time as necessary with the code review, examine it and discover the issues that may be in it.
While evaluating at a quicker pace of 400-500 LOC/hour, there’s an extreme drop-off in effectiveness, and when the rate goes more than 1000 LOC/hour, you can be almost certain the reviewer is simply looking through the code without really checking it.

<p align="center">
  <img src="http://blog.overops.com/wp-content/uploads/2017/01/defect.png?_ga=2.22682363.1357615081.1617277416-1155500591.1617277416"
        alt="Markdown Monster icon" width="350"/>
</p>

## **Set Objectives and Principles**
Prior to executing a code review, it is critical to choose significant measurements and to characterize specific objectives. The Objectives include acceptable coding standards in the organisation. Having set norms ensures that every product item created and reviewed in the organization satisfies the companies standards.


When reviewing code considering certain questions can help to focus on the right things. For example, they may assess the code to answer:

1.    Do I understand what the code does? 

2.    Does the code work as I anticipate that it should? 

3.    Does this code satisfy administrative prerequisites?


## **Capture metrics**
Before implementing a process, the team should determine how they will measure the effectiveness of the code review.

* **Time in review** - Determining how long every developer spends on code reviews is a measure of how engaged every developer in the team is.

* **Defect count**- How many defects were recorded of the code review session that can count towards the performance of the review. 

* **Percent of code reviewed** - Every developer in the team needs to review each other's code. The percent of code reviewed per developer assists with responsibility in the review process.

## **Establish Reviewee Responsibilities**
 
 * **Make smaller pull requests** - Making more modest pull requests is the most ideal approach to accelerate the code review time. Keeping pull requests small allows reviewers to iterate swiftly and efficiently.

 * **Avoid changes during the code review** - Major changes in the code review fundamentally resets the whole review process. In the event that the reviewee needs to make significant changes, the reviewee may allow the initial code submission to be completed and then follow-up with the additional changes. 

## **Use agendas**
 Agendas are the best method to take out regularly made mistakes and to battle the difficulties of defect findings. Code review agendas additionally furnish team members with clear assumptions for each review and can be useful to track and report for improvement purposes.

 ## **Encourage a Positive Culture**
 Cultivating a positive culture around code reviews is significant, as they assume an essential part in item quality. Code reviews can create tension in interpersonal team relationships. By cultivating a positive culture, it will assist the team with appreciating (as opposed to fear) feedback from code reviews.

 <p align="left">
  <img src="https://www.yourerc.com/hubfs/Imported_Blog_Media/Workplace-Culture-What-it-Is-Why-it-Matters-How-to-Define-It-3.jpg"
        alt="Markdown Monster icon" width="350"/>
</p>


## **Resources**

### Coding Standards

- https://medium.com/@psengayire/the-importance-of-coding-standards-and-conventions-in-the-software-development-team-how-they-can-5d252556a05#:~:text=Coding%20standards%20are%20collections%20of,methods%20for%20a%20programming%20language.&text=Without%20the%20coding%20conventions%2C%20every,code%20in%20the%20near%20future.

- https://levelup.gitconnected.com/write-better-code-with-coding-standards-546faf3fd4d1

- https://www.geeksforgeeks.org/coding-standards-and-guidelines/
  
- https://rhamedy.medium.com/a-short-summary-of-java-coding-best-practices-31283d0167d3

- https://www.multidots.com/importance-of-code-quality-and-coding-standard-in-software-development/


### Task Estimation
- https://www.projectmanagement.com/blog/blogPostingView.cfm?

- https://www.knowledgehut.com/blog/agile/top-5-scrum-estimation-techniques-find-your-best-fit

- https://endjin.com/blog/2019/02/a-beginners-guide-to-agile-estimation-and-planning

- https://www.pmi.org/learning/library/agile-project-estimation-techniques-6110

- https://www.lucidchart.com/blog/how-to-estimate-agile-story-points

### Code reviews
- https://www.atlassian.com/agile/software-development/code-reviews

- https://www.perforce.com/blog/qac/9-best-practices-for-code-review

- https://www.brightspot.com/products/developer-life-5-reasons-why-the-code-review-process-is-critical-for-developers

- https://smartbear.com/learn/code-review/best-practices-for-peer-code-review/

- https://www.freecodecamp.org/news/code-review-the-ultimate-guide-aa45c358bbf5/
