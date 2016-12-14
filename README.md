<div align="center">
    <h1>The Longflow Manifesto</h1>
    <em>Version 1</em>
</div>

## About this manifesto

The longflow model is an engineering-centric workflow for serious software developers, tired of the "Agile"/"Scrum" bullshit.

## The question of Time

### Time and Work

In the software industry, like in every industry, a business owner does not sell time. A business owner sells a product.
However, a software developer does sell his time.

Somewhere, time must be transformed into improvements to the product.
The action of applying this transformation to time is called work.

However, the relation between time spent and work done is absolutely *not* linear.
Premature optimization, for example, is a good candidate for a log-like relation, where more and more time is being invested for less and less benefits.
On the other hand, good refactoring can use a moderate amount of time for exponential returns over a long period of time.

This is the key principle of the longflow methodology : **everything has to be done with long-term goals in mind**.

That does not mean no prototyping.  
That does not mean premature optimization.  
That does mean quality has a price : time.

### Estimates

Estimates are to be avoided at all cost.
They create needless pressure, competition, and participate in a toxic witch-hunt of who is the less productive.

In the software development world, it is impossible to produce meaningful estimates, let alone precise ones, for anything but nano-tasks.

It is often impossible to split a task into meaningful smaller ones, even more so *before* starting the original task.
Just like it may be impossible to split a function into meaningful smaller ones, when such function is already coherent and provides a self-contained service.

Have the workflow match the project, not the other way around.  
This draws a nice parallel with data-oriented design, where the data is the core and the logic have to match it.  

### Time based events

Frequent, time-based interactions between executives and engineers are one of the best way to crash a company.  
Having a meeting once in a week/month or other indicator based soley on time is meaningless. It conveys the idea that all the tasks are the same, that all progress must be at a steady pace.
It's also an excellent way to focus more on immediate results than on the long term goals.

Interactions between executives and engineers must be limited in terms of number and frequency.  
It's also best to be as unintrusive as possible : a mail may be better than a meeting in a lot of cases.

Micro-management should be avoided at all costs, because it creates interferences between executives and engineers, and reduces creativity.

*Rushes, sprints, crunch-time, etc. are toxic and dangerous.*

Quality is infinitely superior to quantity. Software engineers aim to produce working, beautiful, readable code.  
By forcing deadline upon them, they are encouraged to produce "the least dysfunctional" code instead of "the best possible" code.
The longflow methodology advocates having medium to large sized meaningful tasks, self-assigned whenever possible, where developers can leverage both technical and problem-solving skills.
Have developers write no code at first, but simply think about how they can solve the problem. Or, better yet, asking themselves questions like:

 * Is there a problem to solve?
 * Can I improve this part of the code?
 * Are there tasks I wish I had done differently?

Curiosity and creativity are very important skills for software developers, but these skills can't develop if there is pressure to release code as fast as possible.
It is very detrimental to have long, let alone permanent, deadlines.

Developers should be allowed, and even encouraged, to spend some time learning and toying with new things and concepts.
Being able to apply a large variety of solutions and concepts on a problem is crucial for a good software developer.
Denying their right to learn will hinder the ability of developers to improve and produce quality code.

## The longflow methodology in simple steps

### Management

 * Keep thinking about long term goals.
 * Let engineers self-assign tasks.
 * Value quality over deadlines.
 * Let the engineers do engineering.
 * Don't micro-manage.
 * Don't interfere with engineers more than strictly required.
 * Never rush, always think and plan ahead.
 * Don't fear to fail.
 * Avoid cargo-cults like the plague.

### Technical

 * Keep thinking about long term goals.
 * Pick up your own tasks.
 * Try to fix bugs before introducing new features, to an extent.
 * Try to clean the codebase before introducing new features, to an extent.
 * Try to write the best possible code.
 * Don't fear trying something different.
 * Think more, write less.
 * Always try to learn things, be curious.
 * Don't fear running late.
 * Don't fear to fail.
 * Avoid cargo-cults like the plague.

## A typical implementation

A typical implementation of the longflow manifesto, from the point of view of an engineer, is something like this:

 1. I pick or create a task.  
 2. I spent a few minutes/hours/days thinking about the task. Do we need it? Have I done something similar before? What does the task achieves?  
 3. If the task turns out to be unneeded, go back to 1.  
 4. If I need to learn something to do the task, I go learn it.  
 5. If I *want* to learn something new, I go learn it too.  
 6. I think about the task again. I may go back to 4 or 1 if the things I learned changed my mind about the task.  
 7. I work on the task. I may go back to 2 at any point.  
 8. I finish the task.  
 9. I think about the task again. I may want to go back at 2.  
 10. The task is now considered done, but I (or someone else) can decide to work on it at any time, going back to 2.  

It may seems messy at first, but a workflow like this is both extremely flexible and extremely good in terms of quality of the code produced, because everyone can improve any part of the codebase whenever they want.

## Author

This manifesto was written by [Nax](https://github.com/Nax).  
Feel free to modify it.
