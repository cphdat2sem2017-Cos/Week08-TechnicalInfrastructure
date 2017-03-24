# Week 8: Technical infrastructure

## What will happen:
This week is a preparation for starting on the semester project. In this week we will focus on establishing the technical infrastructure for the project, in particular how to use git and github for collaboration.

## Studymaterial:
The book: Pro GIT [Mainly chapter 2-4](https://git-scm.com/book/en/v2) 
 
Good explanation of [the 3 workflows](https://www.atlassian.com/git/tutorials/comparing-workflows).

This is a small interactive tutorial on branching [here](http://learngitbranching.js.org/)  


## Plan for the week

### Monday
We will do a peer-feedback on the cupcake exercise which is now a few weeks old. We will learn several things from this:

- Return to code which is even just a few weeks old will train your self in reflecting on which kind of things should have had a comment, and which things are easy to understand
- We will use github **issues** to give each other feed back
- We will use github issues to respond to comments.

In order to stucture your feedback to the other group, you will pay attention to the following feedback issues:

1. Layout of the code - is it consistent, are the names of variables and classes meaningful to you (you might have done it different, but can you understand what the other group did)
2. Three layer architecture. In particular
	- No JSP or Servlet contain any JDBC
	- No SQLExceptions leave the storage layer
3. Seperation between JSP and Servlets, in particular	- No Servlet produce html
	- No JSP tries to send updates to the database (but use forms)
4. JSP and Servlet collaboration
	- When you read a JSP page with a form, is it clear which servlet will handle the form
	- Is there a consistency in which jsp pages post to which servlets
	- Is session used only for data which lives for the whole session, or is it used also for simple communication between servlet and a jsp page (where you should use request attributes)

The plan for the day is:

- Short presentation of the tasks for the day, including git issue.
	- We will use this sheet to coordinate who reviews which groups
- You will get 30 minutes to do self critique (raise issues to your own code on github)
- You will have one hour to read and critique the other groups project
- You will have 15 minutes to read the critique given by the other group
- You will have 2*30 minutes to discuss the critiques based on the issue.
	- If new issues comes up in the discussion, remember to put them on git.


### Tuesday and Wednesday: [2 days on GIT](presentation.md):
These 2 days covers what you need to know to work efficiently as a team using git and github for code collaboration, version control and backup.  
- Learning collaboration with git 
  - What and why
  - Installing git 
  - Creating repository on github  
  - Add collaborators (team members)  
  - Cloning repository  
  - git commands like: add, commit, push, fetch, merge  
  - Create branches  
  - Merge branches with rebase  
  - Forking a project
  - Making a pull request  
  - Using git issues   
  - Labels and notifications  
  - 3 typical work flows  
    - Centralized workflow (most simple and easy to use - small projects)  
    - Feature Branch workflow (good for team collaboration on each feature - larger projects)  
    - Forking workflow (good for opensource projects with untrusted third parties)

### Thursday
The studypoint exercise for this week is to get some preliminary code for your project up on git, and have all of members of the group do at least a couple of commits each.

#### Semester mid-term evaluation
No - not an exam, but we need to do the semesterly quality assurance with feedback on all aspects of 2 second semester. Delphi (3 good things and three problems, passing around in class) and a questionaire followed by in class discussions.


### Friday
Studypoint exercise day, presence not taken. Deadline for Sunday 23:59.


This SP exercise is intended to check that each project group has a GitHub repository, which should contain:

1. All members of the group should be be visible in the "Contributors" tab (just above the green button on the front page).
1. The source code from the Thursday exercise should be there, with branches as specified.
1. All members must have at least two commits with reasonable commit messages
1. All members must have tried to do one branch, and one merge.

#### Handin 
The link to this SP exercise should be send to XXX by Sunday 16<sup>th</sup> October, 23:59. 

The email should also contain a **list which clarifies who is behind each GitHub name**.


