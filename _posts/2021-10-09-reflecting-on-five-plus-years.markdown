---
layout: post
title:  "Reflecting on 5+ years of software development"
date:   2021-10-09
categories: career
---

A lot of things resonated with me when reading this blog post on a guy who's been doing coding for 20 years: https://www.simplethread.com/20-things-ive-learned-in-my-20-years-as-a-software-engineer/

He has a lot of good nuggets like:

>The reason many of us love software is because we are lifelong learners, and in software no matter which direction you look, there are wide vistas of knowledge going off in every direction and expanding by the day. This means that you can spend decades in your career, and still have a huge knowledge gap compared to someone who has also spent decades in a seemingly similar role.

Boy that does help me keep things in perspective. There's also:

>The primary job of any software engineer is delivering value. Very few software developers understand this, even fewer internalize it. 

I read a comment on hacker news putting this last point differently:

> Software is a social service.  Its for other humans.

In that same post the author challenges us to do something similar and I thought the exercise would be fun (and also resurrecting my old "blog")

All of these items are things I've learned yes but I also seem to always have to remind myself of these lessons continually.

1. Careers are long

![MEME](/_assets/2021-10-09/5pvfrg.jpeg)

Strange to have this as my first lesson learned isn't it? As a newbie (still) to this profession, I can get inside my own head and beat myself up for all the mistakes I make or the things I don't know. I'm sure I'm not alone in this. Assuming a 40 year career, I'm only ~13% of the way through it. I still have a lot of time to leave my mark professionally and that thought helps both motivate me and calm my "programmer-anxiety" Maybe this is just waxing maturity and anyone over 30 years of age will roll their eyes at this one but I find it incredibly helpful to remind short-term brain. Bad days will pass. Bad weeks will pass. Don't focus on external success (promotions or money) but on internal success and growth.


2. Deliberate practice is king

![Wonderwall?](/_assets/2021-10-09/lnsvz6ghgd031.jpeg)

Everyone will tell you how important it is to keep learning in this profession. But rarely do people talk about how to learn. I've found that the best way to really learn is to use deliberate practice. This means that you are constantly pushing the boundaries of your knowledge. Imagine two people who are learning to play the guitar. They both progress to the point where they can play some of their favorite songs. One of them decides to continue their learning by figuring out how scales work, how guitar solos work, why chords are the way they are, etc. While the other continues to just play their favorite songs day after day. The former will go on to be a master at it even if they both spend the same amount of time playing guitar. Similarly at work, if you feel too comfortable then you are likely becoming the guitar guy who plays nothing but "Wonderwall" at parties. In short, deliberate practice basically means being borderline frustrated all the time (only half-kidding)


3. You are the pilot of your career

![Airplane anyone?](/_assets/2021-10-09/airplane-850x600.jpeg)

At my job right out of school I found myself tasked with writing a SSIS program to basically automate what an excel spreadsheet was doing. If you know anything about <a href="https://docs.microsoft.com/en-us/sql/integration-services/sql-server-integration-services?view=sql-server-ver15">SSIS</a> then you'll know it's dreadfully boring to work in and not really programming. Lesson 1 above hadn't really sunk into me yet and so I annoyed the crap out of my then-manager on doing <i>real</i>™ programming work. Working in IT consulting, I found that I could work myself into a software engineering career by continuously solving problems with it while getting better at it. Soon I was lucky enough to have an opportunity to work at AWS as an SDE and miraculously passed the interviews. Nowadays I'm definitely doing <i>real</i>™ programming work. This applies to everyone, you can alter the course of your career little by little over time through the reinforcment of your abilities. Seek after getting the abilities you need for the career you want by doing whatever you can in your current role. Obviously this won't apply to everyone or every situation but I think the general principle still works.

4. Being deliberate is better than being fast

![MEME](/_assets/2021-10-09/5pvfrg.jpeg)

Making informed decisions carefully working towards a goal feels a lot different from just trying to get something done as fast as possible. Businesses typically put pressure on timelines for projects to the point where it feels like the only goal you have is to get something delivered before time runs out. It's taken some time to figure out how to divorce myself from that pressure in order to build something the right way. It's tricky because timelines exist for a reason and you don't want to spin your wheels "gold-plating" something. So how do you know when enough is enough or when not enough is not enough? Well, it's a work in progress and more of an art than a science ;) A rule of thumb I try to stick to is to make sure the code will be stable enough will scale well enough, and is maintainable (readable and has good logging, oh and also no swallowing errors!) Sacrificing too much on any of those things will only waste your time later.

5. Writing maintainable code takes very little more effort and saves tons of time

![Will a gif work?](/_assets/2021-10-09/1FcKXFz.gif)

As noted above, ultimately everything you build is for humans. Humans will use your software, humans will read your code, and humans may one day curse your name as they try dig through your code to fix a pesky bug. I've found that making the habits of writing maintainable code makes it so it takes just a tiny bit more effort then code-slinging it while saving much time later. Habits like reflecting for two minutes after finishing code on how to make it more readable, actually writing documentation like javadocs or pydocs or even just a one-page long README, building in robust logging, and using try/catches with custom errors where it makes sense. Getting yourself to the point where this becomes automatic takes some time but saves you (and others) a lot of heartburn later when things inevitable break as they always do.

