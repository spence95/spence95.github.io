---
layout: post
title:  "The Strategy Pattern"
date:   2017-01-04
categories: design patterns
---

I've started reading a design patterns book to boost my software architecting ability. Really, it's the 
main design patterns book my company recommends. After reading the first chapter I found that it's a surprisingly 
entertaining read. The first chapter has a superb duck pun which is the fastest way to my heart. At the beginning
of the chapter, they gave this golden advice about how to do this whole design pattern thing well:

"The best way to use patterns is to load your brain with them and
then recognize places in your designs and existing applications where you can
apply them."

The first design pattern in the book, "Head First Design Patterns", is the Strategy pattern.
It's basically the mother of all patterns. The gist of it is to "do ya code good". Ok, seriously though,
it's composed of these three patterns (all great advice):

* Identify the aspects of your application that vary and separate them from what stays the same. 
* Program to an interface, not an implementation
* Favor composition over inheritance

They really beat a dead horse with that last point. They hit on it by going through a whole example of a fake duck program to show that
inheritance is not the only way, and often not the best way, to do code-reuse. Often, composition is better which is really taking
functionality and making it a variable of another class among a few other principles. 

My favorite quote from this chapter was about change:

"The one constant in software development is change"

This is the whole reason we even care about architecting software in the first place. 
If software never needed to be changed, we would all care a whole lot less about designing.
Good design cuts down maintainability time thereby increasing feature development. It's what we all should aim for and the purpose behind
design patterns.
	