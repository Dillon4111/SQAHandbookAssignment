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

## **Estimation Techniques**

## Story Points

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


## Resources:

- https://medium.com/@psengayire/the-importance-of-coding-standards-and-conventions-in-the-software-development-team-how-they-can-5d252556a05#:~:text=Coding%20standards%20are%20collections%20of,methods%20for%20a%20programming%20language.&text=Without%20the%20coding%20conventions%2C%20every,code%20in%20the%20near%20future.

- https://levelup.gitconnected.com/write-better-code-with-coding-standards-546faf3fd4d1

- https://www.geeksforgeeks.org/coding-standards-and-guidelines/
  
- https://rhamedy.medium.com/a-short-summary-of-java-coding-best-practices-31283d0167d3

- https://www.multidots.com/importance-of-code-quality-and-coding-standard-in-software-development/