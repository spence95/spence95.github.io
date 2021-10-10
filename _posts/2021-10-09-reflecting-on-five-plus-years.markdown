---
layout: post
title:  "Reflecting on 5+ years of software development"
date:   2021-10-09
categories: career
---

A lot of things resonated with me while reading <a href="https://www.simplethread.com/20-things-ive-learned-in-my-20-years-as-a-software-engineer/">this blog post</a> from a guy who's been doing software engineering for 20 years. 

He has a lot of good nuggets of info like:

>The reason many of us love software is because we are lifelong learners, and in software no matter which direction you look, there are wide vistas of knowledge going off in every direction and expanding by the day. This means that you can spend decades in your career, and still have a huge knowledge gap compared to someone who has also spent decades in a seemingly similar role.

Boy that does help me keep things in perspective. There's also:

>The primary job of any software engineer is delivering value. Very few software developers understand this, even fewer internalize it. 

I read a comment on hacker news putting this last point differently:

> Software is a social service.  Its for other humans.

In that same post the author challenges us to do something similar and I thought the exercise would be fun.

All of these items are things I've learned yes but I also seem to always have to remind myself of these lessons continually.

### 1. Careers are long

As a newbie (still) to this profession, I can get inside my own head and beat myself up for all the mistakes I make or the things I don't know. I'm sure I'm not alone in feeling this. Assuming a 40 year career, I'm only ~13% of the way through it which helps me be a bit more self-forgiving. I still have a lot of time to leave my mark professionally and that thought helps both motivate me and calm my "programmer-anxiety". Maybe this is just waxing maturity and some of you will roll your eyes at this one but I find it incredibly helpful. Bad days will pass. Bad weeks will pass. Don't focus on external success like promotions or raises but on internal success and growth instead.

### 2. Deliberate practice is king

Everyone will tell you how important it is to keep learning in this profession. Less often do people talk about how to learn. I've found that the best way to really learn is to use deliberate practice. This means that you are constantly pushing the boundaries of your knowledge. I remember a metaphor that has solidififed this concept for me from some book or podcast whose name I can't recall. Imagine two people who are learning to play the guitar. They both progress to the point where they can play some of their favorite songs. One of them decides to continue their learning by figuring out how scales work, how guitar solos work, why chords are the way they are, and more. Meanwhile the other continues to just play their favorite songs day after day. The former will go on to be a master at playing the guitar even if both spend the same amount of time practicing. Similarly at work, if you feel too comfortable with your tasks then you are likely becoming the guitar guy who plays nothing but "Wonderwall" at parties. In short, deliberate practice basically means being borderline frustrated all the time (only half-kidding)

<p align="center">
![Wonderwall?](/assets/2021-10-09/lnsvz6ghgd031.jpeg)
</p>

### 3. You are the pilot of your career

![Airplane anyone?](/assets/2021-10-09/airplane-850x600.jpeg)

At my job right out of school I found myself tasked with writing an SSIS program to basically automate what an excel spreadsheet was doing (excel driven development???). If you know anything about <a href="https://docs.microsoft.com/en-us/sql/integration-servicessql-server-integration-services?view=sql-server-ver15">SSIS</a> then you'll know it's dreadfully boring to work in, very rigid in what it can do, and not really programming. Lesson 1 above hadn't really sunk into me yet and so I frantically and repeatedly annoyed the crap out of my then-manager to get me <i>real</i>™ programming work. Looking back, I realize now that I could've solved those same problems using programming instead of SSIS and the resulting solution would've been much better. Instead I mistakenly assumed it was someone else's problem to get me the work I wanted to do and thus missed out on the very opportunity I wanted to tackle as it sat right under my nose. As the next few years passed I sought to solve problems with programming while deepening my skills in it. Ultimately I landed an engineering job at AWS. This has led me to believe that most people can alter the course of their careers little by little over time by taking the initiative. 

### 4. Being deliberate is better than being fast, most of the time

![MEME](/assets/2021-10-09/5pvfup.jpeg)

Making informed decisions while carefully working towards a goal feels a lot different from just trying to get something done as fast as possible. Businesses typically put pressure on timelines for projects to the point where it feels like the only goal you have is to get something delivered before time runs out. It's taken some time to figure out how to divorce myself from that pressure in order to build something the right way. It's tricky because timelines exist for a reason and you don't want to spin your wheels "gold-plating" something. So how do you know when enough is enough or when not enough is not enough? Well, it's a work in progress and more of an art than a science ;) A rule of thumb I try to stick to is to make sure the code will be stable enough, will scale well enough, and is maintainable (readable and has good logging). Sacrificing too much on any of those things will only waste your time later.

### 5. Writing maintainable code takes zero added effort

![Will a gif work?](/assets/2021-10-09/1FcKXFz.gif)

As noted above, ultimately everything you build is for humans. Humans will use your software, humans will read your code, and humans may one day curse your name as they dig through your obtuse code to fix a pesky bug. I've found that you can build the habits of writing maintainable code so that it becomes automatic. These are habits I try to keep: reflecting for two minutes after finishing code on how to make it more readable, actually writing documentation like javadocs or pydocs or even just a one-page long README, building in robust logging, writing unit tests, and using try/catches with custom errors where it makes sense. Getting yourself to the point where this becomes automatic takes sometime but saves you (and others) a lot of heartburn later when things inevitable break as they always do. Once it's automatic, you'll find that you can get things done just as quickly or even quicker than just "code-slinging" it. This is because when you "code-sling" (quickly get something done by taking shortcuts) you give yourself blind spots to the subtleties of the problem you are fixing. All of this other maintainable work helps you get a better grasp of the problem.

Well, there's my list. I wonder what things I'll write in 5 more years?? Thanks for reading.


