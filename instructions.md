# Project Proposal
Write a proposal for a software product you would like to pursue for the majority of the semester.   Make it obvious, interesting, and make the need for it sound convincing.

## Collaboration
You are welcome to write a proposal with up to 5 other students, if desired.  If you do work with others on the proposal, you **must** clearly indicate the names of all the team members in your proposal.

## What to include
Your proposal must focus on the product's value proposition, including answers to the questions below.  Keep it thorough but concise.  If you are not clear on whether your writing is any good, consult with a friend.

### Project title
Give your project a nice title.
Event Planning System

### What and why?
What software system would you like to build this semester, and why?  Include a description of what problem the system would solve and why this is important.

In recent times, event planning can get convoluted and people can get confused as to when is what or what they have to bring. There's been several times when I have tried to plan events with friends, where some may be lost as to what the exact precise details are and there can endless times of tagging people in the group chat. So, this project will incorporate not just messaging but other accessory features as well such as creating the event right then and there in the group chat and the event would be create on Google Calendar. Another feature can be dedicating tasks to certain group mates, so no one has room to mess up.

### For whom?
Who will this software be for?  These people are your end-users or customers.

Do not make software for imaginary users who do not exist - you must have real people as your initial end-users.  Tell us who they are.  For example, is it for a particular type of business, mass consumer, a campus office, a professor, or friends or family, or ... people just like you.

Understanding who your end-users are, and ideally speaking with some along the way, will help you refine your designs to be suitable for your audience, and understand whether you have succeeded at the end or not.

This software can be used by anyone who wants to plan an event of any kind, such as parties, sporting events, etc. It is basically for friend circles.

### How?
A description of what the system will do from an end-user's perspective.  Be as complete as necessary to fully explain the system, but do not worry about technical implementation - this will be developed in subsequent work.

Users will sign up for an account. After logging in, the user can add friends, create group chats, and then start messaging. In addition, there will be options for users to create a google calendar event. The rest in the group chat can either accept or decline the event. If accepted, an event would be added to their Google Calendar through the use of Google Calendar's API. After accepting, our own site will also keep track of the specific user's events in a different page. In the page, each event can have info such as what they have to bring to the event if anything is required to be brought, time, location, etc. 

### Scope
A brief justification that the proposal is neither too easy nor too ambitions for a group of approximately 4 - 6 programmers to undertake in one semester.

I think it is not too easy because there a lot of relationships to consider when it comes to the managing the database. One component of the project - live updates - is what can be tricky. We need to use Socket.io for messaging, potentially sending/receiving/accepting friend requests, but that can be decided later whether we want the user to just reload the page or if we want to make it live.  I think it is not too ambitious because we are not creating our own calendar system, but we are relying on Google Calendar.

## Submission
Complete the assignment as a Markdown document in the file named `README.md` in this repository. The message should be nicely formatted and outlined with a clear heading and sub-headings for each section.

Use the `git` features of **Visual Studio Code** to commit your work and `push` them to the GitHub repository.

Share the link to your document in your private Slack assignments channel AND in the public #project-ideas channel.  In both cases, include the title of your project for all to see in the message.

## What happens next

We will select a subset of the proposals that we think will be the most interesting and appropriate for this course. These will be published to the class. Your next assignment will be to rank your favorites. We will then make team assignments based on this information and the answers you have provided to the previous introductory questionnaire. 

If your proposal is selected, you are 99% guaranteed to be part of that team.
