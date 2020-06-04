
# InterviewQuestions

Collection of Questions I like

## Introduction

What are we looking for when we interview anybody?  

The main thing we are trying to assess is: Can this person successfully do the day to day work for the role that they are applying to?

The answer to this question has to be approached from many angles, such as behaviors, specific skills, generic skills, etc. 

When we look at technical skills, whether at screening time or final interview, it's very important to keep that northstar in mind: "Can this person do what we need of this role?".  "Do they have the right technical skills?"  becomes a matter of letting them solve a problem, in a way that helps us answer our question.


The purpose of this question bank is to give you inspiration for *useful* interview questions.  You can modify / adapt them as needed. As long as you follow some basic guidelines you will be able to get *useful* information from a candidate will help you determine if they have a high probability of being successful in the role.



## Anatomy of a bad question:


> "Traverse a Binary Tree in a specific algorithmic way (eg: Left to right, skipping odd numbered nodes, etc)."


What's wrong with this question? 

A few things: This is not a task we typically have to do on a day to day basis. If a candidate answers this question correctly, does that tell you that they are good at writing an API spec? Can they troubleshoot why your service is not logging correctly to CAL?  Can they write reusable code that won't add to tech debt?

The only thing that a question like this can answer is whether the candidate read "Cracking the Coding Inteview".

Algorithmic questions, no matter how novel you try to make them, can usually be solved in two ways: The One True O(Log(n)) way, or some horrible nested loop contraption. 

There is some signal you can extract from these questions, such as variable naming, approach to a problem, but these tend to be low value.


## Anatomy of a better question

Caveat: There are no good questions that you can ask in a 45 minute interview that will give you complete certainty of anyone's abilities. The best we can hope for are glimpses of how a candidate will work under various situations.

### A good question should not be overly specific. 
You want to leave room for creativity and multiple approaches. A candidate should feel compelled to ask clarifying questions on how the question should be answered.  This will give you an opportunity to observe how they approach vague requirements (Which never happens around here, right?), how they start building a mental model around the problem space, and how comfortable they are in making design decisions. 

### A good question should be open ended.
Given the time constraints of an interview, you want the candidate to approximate a working solution. However, the problem space should be such that they could continue to improve on it if given more time (eg: The 45 minute question could easily expand to a take-home assignment).

### A good interview question will let you observe multiple areas. 
Your questions should expand beyond a single-function-call answer. Let the candidate explore various aspects (Work with third party libraries, Include Unit/functional tests, interoperability, etc.)  By doing this, you will usually be able to gauge proficientcy not just with a programing language, but with its ecosystem. 

### A good interview question can scale according to the candidate's level.
Junior candidates should be able to provide simple solutions that are correct.  Advanced candidates can consider an elaborate on more complex uses cases, using it as an opportunity to showcase their knowledge	





## Examples of Good Engineering Questions:


### Front End:

>"Image Carousels are very common components on websites. They allow a user to see a series of images, starting with large central image accompanied by thumbnails of other available images.  We would like to implement one."


#### Why is this a good question? 
- Open ended. There is no single "right" approach to implementing such a component
- Not specific. The candidate should be asking many questions on functionals / non-functional requirements for the app
- Multiple areas: A question like this will involve HTML / JS / CSS.  It it framework agnostic, so it can be adapted to React / Angular / Vanilla JS, etc as the role demands. 
- It can scale according to candidate level. 

#### What do you look for in an answer?  (Some of these might scale by level)
- Did they first and foremost build something workable?
- Did the candidate clarify what / how it should be built, or did they immediately jump into solving it?
- Does the candidate show proficiency working with various aspects of a modern web application? (The measurement of this will vary a bit according to candidate level). eg: Correct use of semanting HTML, Specificity/structure of CSS	
-  What edge cases were considered?
- How did the candidate test his own work (You may have to specifically ask for this. Always interesting to observe)
- Are they familiar with libraries that could make their life easier?
- Do they think about accessibility? 
- Are they building it in a reusable way?



### Back End:


>"We want to build a news feed service. Collect and store the headlines from the top 5 news websites, twice a day"	


#### Why is this a good question? 
- Open ended. There is no single "right" approach to implementing such a component
- Not specific. The candidate should be asking many questions on functionals / non-functional requirements for the app
- Multiple areas: Scheduling services, working with permanent storage / SQL / NoSQL, connecting to third parties, configuring a service, etc


#### What do you look for in an answer?
- Did they first and foremost build something workable?
- Do they clarify Functional / Non-Functional requirements
- Are they leveraging frameworks / OS capabilities to create this application (Are they proficient at them)
- Are they creating a good structure for their application? (Functions / Classes / Modules/ etc)
- Corner cases considered?
- Testing?








