# Marginal improvements
Authors: Neev Mittal, Christian Kovacs

## Motivation 
A study was conducted on Novak Djokovic's progress from being ranked 680 in 2004 to rank 3 in 2007 and to rank 1 in 2011. 
The way he was able to acheive that success was by winning more matches and he did that by winning more points.
Every point in tennis requires about 1-3 decisions. So, when he was ranked 680 he was winning 49% of his points. 
When he was ranked 3, he was winning 52% of his points and as number 1 he was winning 55% of his points. 
This goes to show that it only requires marginal improvements to make considerable progress towards your goal, any goal. 

Typically, self-improvement apps seem like a lot of commitment and they manage to scare off the users because improvement feels like a lot of work. 

## Customer Pain Point
When people see a huge amount of work, they tend to shy away from it. 
This is preventing a lot of people from achieving their goals and their full potential.
For example - someone is trying to finish reading a book, but cannot find the motivation to do it. 
If you tell them that they have to read a "400 page book" or "an entire book," it tends to throw people off from finishing the book. 
But if you say something like "You jut need to read 10 pages today and you have time slot A and time slot B to do it," it seems more achievable. 

There are a lot of scheduling apps and motivation apps that are not being effective, as they are trying to be inspirational and not action oriented. 
The ones that can help out are paid counsellors that take time to understand what you're trying to achieve and what your life looks like. 
It is really hard to find an action-oriented app that is able to take into account a personal schedule and preferences to help achieve specific goals, also to help make goals. 

## Audience
This will be an application exclusively for students who are looking to achieve any goals (complete an assignment, read a book, finish knitting a scarf). 
These goals should be something that can be divided up into smaller tasks (which really covers most goals). 
This student should also use a calendar for organizing their time (or any other way the application can know when they are busy).


## Feature List: (This is a rough outline, can be updated as we progress)
1. The user will create a goal and go through a process to determine the scope of each achievement.
2. Then the program asks how to break it down in to small, incremental tasks and assign a unit of time for each micro task and macro task. ( Example: User states: I want to read a 400 page book in the next month, this averages to around 13 and a third pages a day.  This example is simple but we can explore more uses)
3. Import calendar from Apple or Google and add preferences (Example: I prefer to go to the gym in the morning and do my reading in the night time or afternoon.)
4. The program then creates a progress bar, potentially point system or percent system to track small goals and overall goals.  
4a. We need to figure out a way to gamify it, some sort of rewarding system for completing daily tasks.
5. If goal is failed, ask the user to adjust goals. 
6. Using map api to track gym use, library use, class etc. and award points for entering facilities, since usually entering the gym is the hard part, not working once you are there.  Could be used to track chores ( laundromat, grocery store, etc) as well as personal growth buildings (library, gym, classroom, bookshop, healthy restaurant)

## Scope:
An important aspect of the success of retaining users of this app will be if they feel rewarded using it.  A good UX/UI must be designed or else nobody would want to use the web app or mobile app, and the both the desktop and mobile applications must be equally usable, not biased towards just one.  This poses a challenge as we are not design students so we are going to have to learn as we go how to create not just a user interface, but one that encourages users to frequently return.

Also, we will need to implement a complex point or progress system, and experiment with what works and does not.  We want the user to feel that they are working towards a larger goal, while still being motivated to work on the small goals.  This will require research on what makes a gamification system work, and how to implement it.

Finally, to use the Google or Apple maps api might prove challenging and we are going to need to find a way to implement it.  We are also going to need to work with Apple and Google Calendar to be able to fit tasks around timeslots in the users day, such as classes or work, along with a way to figure out availabilities and preferences.  

Finally we are going to need to build a database to host all of the users progress with not only their one goal, but also all of their goals, so that their progress is saved and can be referenced later on once completed.
