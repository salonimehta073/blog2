---
layout: post
author: Saloni
title: My perfect To-Do list maker - productivity app for the future
categories: Product
image:
  path: /assets/link_preview.PNG
  height: 100
  width: 100
---

*After a thoroughly unproductive day of daydreaming*

Alright, I’m already overselling it. But hey, so are most of the productivity apps out there. Also, there are too many of them? Sure, some of them seem very promising – especially Notion and Roam Research (haven’t used this one but I’m relying on Twitter tech bros fanboying over it); however, most products in the productivity category have fairly similar offerings. I do think this is an important problem to solve – there is way too much information and complexity in our lives. Anything that tries to organize our chaos is great and I want to share my vision of the perfect task management app through this post (will also try to include relevant, rational references so as to not sound like I’m 420ing). 

I use [Todoist](https://todoist.com/) on days when I want to feel inspired by the general concept of productivity. On other days, I scribble everywhere – Google Keep on my phone, OneNote on my work laptop, a piece of paper, etc. The challenge with creating ‘tasks’ and organizing your life is.. well, there are quite a few:

1.	Inertia. Not knowing how and where to start

2.	Prioritizing tasks – Understanding HOW to prioritize

3.	Estimating time to complete or as productivity gurus call it, time management

4.	Losing focus/other distractions

How do most to-do apps solve this (these?) problem?

They allow you to ‘add’ all your tasks to a slick-looking app (add sub tasks if you are really in the mood), waste some time in colour coding them, set up reminders and alerts, show you a shaming chart with completion % (or as they call it, visualizing productivity), allow your friends to comment on your impending workload and they also offer integrations to other time-wasting apps. What ends up happening is perfectly summarized in this tweet:

![Funny tweet about to-do apps](/assets/todo.png)

I think the biggest issue with commitment to tasks is the first two challenges I mentioned – inertia and prioritization. They are also deeply connected, and Mark Twain agrees. 
 
>“The secret of getting ahead is getting started. The secret of getting started is breaking your complex overwhelming tasks into small, manageable tasks, and then starting on the first one.”
– Mark Twain quoted in Getting Things Done

Essentially, priority, in the context of dealing with tasks can be better understood with scheduling and optimization concepts… What’s that? My loyal readers (0 at this point but I’m hopeful) remember me reviewing one of the coolest books ever – [Algorithms to live by]({% post_url /_posts/2020-05-24-4-Books-You-Should-Read-This-Quarantine %})? 

Yes, the book touches on this subject and this is when I envisioned a cool to-do app that would use concepts of scheduling from the algorithm world and apply it to our chaos. Simply, the app would do the following:

1.	Allow the user to add tasks and the total amount of time he/she intends to dedicate to these tasks in a day

2.	For standard tasks (say, filling out a form or buying groceries, or walking your dog), the product will have built-in time estimates (time to complete the task). The user can change the estimate for his/her use at this stage

3.	For tasks that the system can’t recognize, the user will be invited to add it manually

4.	The user will also be asked to flag any ‘passive’ task – something that can be accomplished while doing other active tasks – for example, getting some batter sitting and ready for dinner. Along with this, the user can also mark if a task is ‘dependent’ on any other task(s) in that list

5.	The user will be asked for the parameter he is optimizing for – maximizing number of tasks completed, minimizing the overall ‘lateness’ of tasks, maximize the number of “urgent” tasks completed, maximizing the number of “important” tasks completed, etc. Any of these selections will ask the system to use the respective algorithm that optimizes for this parameter.  For criteria such as ‘maximizing the number of important tasks completed’ – an importance score (relative, of course) can be assigned by the user

With these inputs, the system will ‘Plan the Day’ for the user and give him a detailed task list with:

a.	Ordered/Sorted tasks – Which one should I start with to fulfil my goal?

b.	An alert when it’s time to move to the next task

c.	An alert when I can start another task while I continue with the current (parallel)

d.	Overview of which tasks I will have to reschedule/let go 

The user can obviously go through the data and change his/her ‘key metric’ and get an updated list of *sorted* tasks. Wouldn’t that just be awesome? You simply look at the clock and a piece of software introduces you to your task for the next 1 hour without the burden of looking at a daunting task list and not knowing how to get through it. 

Do I really think it’s possible to build something like this? Yes. These algorithms already exist: for example, say you want to order your tasks by task length and consider the importance too. You can divide the time required for a task by the relative importance and get a ‘weighted’ task length. If you want to minimize the number of tasks that are late, you can use Moore’s algorithm: sort tasks by earliest due date; however as soon as you realize that something is going to be late, you toss out the biggest task (or the one that takes the most amount of time). The coolest bit in the book about tasks was the simple scheduling concept of ‘task switching cost’:  There is a cost of switching to another task and that cost shouldn’t be higher than either of the task ‘costs’ themselves. 

If you have any feedback on this idea or simply want to tell me ‘this already exists, stupid’, feel free to reach out to me. 

