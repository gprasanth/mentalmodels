---
theme: default
class: text-center text-black
highlighter: shiki
background: https://jrnl.in/content/images/size/w2000/2019/10/ugo-mendes-donelli-e4FbcDByhjI-unsplash.jpg
title: Mental Models for Developers
---

## Mental Models for Developers

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/gprasanth92/mentalmodels.dev" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--

Hello, everyone,

Thank you so much for joining us today.

I'll quickly introduce myself and then give you an overview of how the talk is going to be like before we get started.

Alright,

-->

---
layout: cover
background: https://i.imgur.com/hwU1KMY.png
class: 'text-white text-center'
---


## Prasanth Gangaraju
### Co-founder, EmptyCup


<!--

So, I am Prasanth, I am problem solver and a frontend developer. I've been doing web development for more than 12 years.

I am also one of the co-founders of EmptyCup, a platform for interior design.

At EmptyCup we believe that a well-designed house, slowly shapes the life of the family living in it, in a hundred little ways over a decade.

We are on a mission to make good interior design accessible.

If that sounds like a problem you'd like to help solve, do reach out to us on LinkedIn or over email.

Now, coming back to this talk,
-->


---
layout: cover
class: text-center text-black
background: https://jrnl.in/content/images/size/w2000/2019/10/ugo-mendes-donelli-e4FbcDByhjI-unsplash.jpg
title: Mental Models for Developers
---

## Mental Models for Developers


<!--

Over the next 40 minutes,

We'll be going over a few mental models, understand why they are important, and how they help us write better code or solve problems effectively

I'm hoping this will be an interactive session, so feel free to share your comments or your own experiences on some of the topics we are going to discuss, and if you have any questions, you can put them in the chat, and we'll be taking them up at the end of the session.

Let's get started,

-->

---
layout: fact
---

## Okay, so, what's a mental model?

<v-click>
<p>How things work.</p>
</v-click>

<!--
To simply put,                ->

it's an understanding of how things work.

There are a lot of mental models in various domain of life, and right from our childhood we learn many of these directly or indirectly through our day to day experiences.

This talk is specifically about mental models that you help you with software development.

So, we'll go over the models, briefly talk about then and then discuss of a few of these in detail.

-->


---
layout: fact
---

## Mental Models

<v-clicks>

Communicating Clearly

Debugging Effectively

Managing Complexity

Being Productive

Seeking Feedback

</v-clicks>

<!--

Communication -- 7 minutes

Debugging -- 15 minutes

Managing Complexity -- 5 minutes

Being Productive -- 10 minutes

Seeking Feedback -- 5 minutes

These are only a few of the models that I've learnt personally over a decade of building things and solving problems.

-->

---
layout: fact
---

## Communicating Clearly

<v-click>

With the machine

With ourselves

With peers

With stakeholders and customers

</v-click>

<!--
As developers we need to communicate a lot. With the machine, ourselves, peers, stakeholders, and customers.

- With the machine
  - Being able to do that effectively in case of a computer means you need to have great deal familiarity with the programming language
  - And, having the ability to learn different languages quickly if required
  - Personally I believe that "jack of many, master of one" is a great approach when it comes to learning programming languages

  - Usually, it's helpful when you're porting a function or a library from a different language
  - Also, depending on your situation you might need to pick a different programming language that might be better suited
  
  - Being a javascript developer, when I was working on React Native I was able to work on a native plugin whose code base was in Swift and Java would not have been possible if I hadn't spent a lot of time fiddling with c# and java previously

- With ourselves
  - Self talk is definitely an important skill to have
  - Being able to articluate ideas effectively helps a lot with improving our own clarity
  - And clarity most of the times determines how well ideas get implemented
  - RubberDuckDebugging is a concept I find very helpful to maintain project context

- With peers
  - A friend once shared with me that your world is limited by your vocabulary.
  - Learning different concepts and abstractions helps you share context with others, which makes the discussions flow smoothly


- And with other stakeholders in the project and even customers that may not have a technical background
  - It's easier for you to understand their domain than for them to understand ours

  - A great excercise here is to connect with and talk to people outside of your circle -- designers, product managers, customers or people from other walks of life

Moving on
-->


---
layout: fact
---

## Debugging Effectively

<v-clicks>

Maintaining context

First Principles Reasoning

Knowing your tools

Taking a break

Seeking help

</v-clicks>

<!--
When it comes to debugging 

- Maintaining context 
  - Keeping track of the problem definition, your observations and understanding of it is
    extremely important to solving the problem
  - And there is no better way to do it than writing it all down, 
  - Especially since it gets difficult to manage all the complexity in the mind
  - Because you're not only asserting the problem exists, but also, most of the times,
  - Just by defining the problem clearly helps alot with finding the solution or understand the direction to pursue
  - Rubber Duck Debugging
    Insights are often found by simply describing the problem aloud. It surprisingly works a lot of times :)

- Reasoning
  - Approaches
    - Natural tendency, especially when you are early in your developer journey, is to use trial and error to fix problems
      - Change something and log system behaviour
      - It is still helpful when dealing with poorly documented or highly complex systems

    - First Principles Reasoning
      - What do we know about the system?
      - What is the exepected behaviour?
      - What is the actual behaviour?
      - Formulating and testing different hypothesis while making observations and reasoning

    - Elimination
      - Add logs in various parts of the system and try to eliminate the parts that are not the cause.
      - "Once you eliminate the improbable, whatever remains, no matter how impossible, must be the truth."
  - Validation
  - Understanding

- Tools
  - Logging
    - Logging at multiple parts of the system helps understand more about the problem and narrow down where the issue would be happening
  - Debugger mastery
    - helps not only with fixing bugs but also, with understanding a range of aspects:
      - performance tuning
      - identifying and fixing memory leaks
      - improving load times
  - The amount of work that went into debugging and instrumentation tools is crazy, although a good design and tests suite helps you avoid debugging, it's a great skill to have and certainly helps see the bigger picture of how things work under the hood.

- Taking a break
  - If a problem takes more than an hour, usually taking a break for 5-10 minutes and then giving it another shot helps.
  - When we come back, we look at the problem in a new pespective, rather than hanging on to old perspective and the problem will be solved.

- Seeking help
  - And when that doesn't happen either, it's a good idea to get help, from a colleage or posting it online, on stackoverflow
  - Communicate the most information with the least amount of words. This requires a lot of mental energy on your part but will increase the likelihood of getting help back
  - Being able to Google well is a super power without a doubt

-->

---
layout: fact
---

## Managing Complexity 

<v-clicks>

Documentation

Clean Code

Short term hacks

Performance

</v-clicks>

<!--


Documentation
  - Coding explains you 'how' and documentation explains you 'why
  
  - Nothing beats a great documentation when it comes to making a project or a library a easy to work with

  - Writing clear documentation means being able to simplifying concepts and communicating them clearly, and that requires a lot of effort

  - This is also why I love precis writing in English --
  - which is basicall summarizing a longer paragraph into a shorter one without leaving any critical detail out



Short term hacks

  - Often, when you're working on adding features to an existing product, you find yourself in a dilemma:
    - You can do a quick hack or take time to refactor the system
      - The short hack makes a small mess in the code, but you feel very clear about it now.
      - But the problem is, these small hacks have a tendency to accumulate and the code becomes ugly to read
      - And refactors tend to get harder to do over the period, making the codebase unmaintainable.

  - Which brings us to the next point on writing clean code


Clean Code

  - Writing clean code is mostly about showing empathy to the maintainer and others working on the code base.
    - Have you not felt the pain in understanding bad code written by others?
    - Have you not seen ugly code only to find out it was us that wrote it long back?
    
  - I certainly did, and I've learnt the hard way that
    - in most of the cases, readability of code translates to clarity of the mind of the developer writing it
    - and clarity inturn translates to the stability of the system

  - With all the code formatters, linters, and code quality evaluation tools available,
    it's not an acceptable excuse to write poorly formatted on logically unsound code

  - A well written piece of code conveys the clarity of the coder which directly translates to the stability of the system

  - Actively allocate time to clear tech debt and work on refactoring the codebase.
  - A clean codebase is the fertile soil where beautiful flowers (products) grow.


- On performance
  - Over the years I've realized that writing efficient code is equally important
  - Saying I don't care about the time-complexity of this is easy to do
  - but it indicates of lack of empathy to the users and the environment,
  - and, I do say empathy to the environment because,
  - by writing slightly resource efficient code, you have a direct impact on the enviornment  
  - So, always choose the right solution, not the easy one


-->

-->

---
layout: fact
---

## Being Productive

<v-clicks>

Finding motivation

Setting expectations

Making progress

Maintaining Focus

</v-clicks>

<!--
- Finding Motivation
  - Motivation can be many things
    - Creating something, getting things done, solving hard problems
  - But I find understanding the impact of my work helps me do it a lot better
    - Understanding what motivates you helps you stay connected with the problem

  - Opportunity to do great work is it's own reward, sometimes we've got to do grunt work 
  - Rewarding yourself, we're humans after all
    - Allocate time for exploring new things is a great motivator
    - We learn a lot of things and have fun automating some drudgery
      - How we've automated react native builds with Github actions

- Setting expectations
  - Something I've learnt the hardway is, planning is very important, to keep all the stakeholders
    on the same page with what's happening
  - Estimating things correctly is still elusive to me, but I do believe it to be the most important aspect
    of maintaining a healthy work-life balance and avoiding burnout

- Making progress
  - Breaking down work helps a lot to tackle it in parts

  - It's also important to say no to scale when you are starting from scratch
    - Premature Optimization as it is the root of all evil
    - You are going to need it, is not a good excuse to add complexity to system early on

  - Important to prioritize progress over perfection since usually the effort to go from good to great increases sharply
    - Following the Pareto principle
      - looking for and prioritizing work which creates 80% value with 20% effort

  - It takes discipline to stay focussed on what you need to solve
  - One of those aspects is avoiding exploring shiny things that we come across when researching for solutions
    - Noting down these things and exploring them later helps both ways: to stay focussed and also to broaden your knowledge

- Maintaining Focus
  - Also, on doing Deep Work
    - Time tracking tools like Qbserve worked well for me, to help build a habit of doing undistracted work, letting me do 15 hours of focused work when necessary.
    - Investing in creating a peaceful and conducive environment
      - Removing attention sinks
        - Case of the refridgerator
        - Meetings
        - Adhoc issue reports
        - Support calls
    - It may take time, but find your own flow, understand how you can consistantly get into a flow state and do the best work of your life.
-->

---
layout: fact
---

## Seeking Feedback

<v-clicks>

Priorities

Design

Code

Mentoring

</v-clicks>


<!--

Seeking feedback early and often is the greatest factor for improving anything:
  product, design, or even ourselves. (5 min)

- Priorities
  - Having high level objectives avoids uncertainty and existential criseses
      - Stakeholders and customers might have a different intuition than you
    - Challenging your limits
      - Being ambitious, back it up with competency

- Design
  - Seeing how users use the product
    - Is it easy to use? Does it solve all the problems?
      - Nothing is a better motivator than hearing your someone love your work
    - Helps you develop empathy for the users
      - Writing efficient code
  - Being your own user
    - Does the design make sense?

- Code
  - Code Reviews
    - A fresh perspective to make sure we didn't miss anything
    - It's also a good way to stay up to date with changes happening in a pr
    - Reading old prs is definitely a good way to learn about the code base and understand why & how changes are being made.

  - Allocating time for tech debt/refactoring

- Mentoring
  - Getting feedback
    - Asking for advice / pointers
    - It's a gift, cherish it
      - Taking feedback impersonally
    - Being humble, everyone has somethiing to teach
  - Giving feedback
    - Paying it forward, being grateful to all the great support you've received

-->
