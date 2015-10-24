# Javascript Beginner's Curriculum

## Table of Contents

[Notes on this Repo](#notes)

[Introduction](#intro)

### Start Here
[Syntax](#The Basics: Syntax)

[Loops, Conditionals, Basic Data Structures](#Loops, Conditionals, Basic Data Structures)

### Intermediate Learning

[Functions, Closures, Objects, and Prototypes](#Functions, Closures, Objects, and Prototypes)

[Best Practices](#Best Practices)

### Advanced Topics

[Higher Order Functions](#Higher Order Functions)

### Troubleshooting

[Debugging](#Debugging), **Added 10/24/2015**

### Further Learning

[Coding Challenges](#Coding Challenges)

[JS Fundamentals Workshop](#JS Fundamentals Workshop)

[Advanced Javascript Knowledge](#Advanced Javascript Knowledge)

[On-Site Learning](#On-Site Learning)

## <a id="notes"></a>Notes on this Repo

This repo is bound to be updated with more resources as I find the time to do so. If you fork it, be sure this repo is set as your upstream and run `git pull upstream master` every once in a while to grab the latest version. Github has some [great documentation for doing this](https://help.github.com/articles/fork-a-repo/).

Questions? Suggestions? [Create a Github Issue for this repo](https://github.com/rkho/javascript-beginners-curriculum/issues/new) and I'll address it.

## Introduction

I really believe in this quote:

```
Everyone should have the opportunity to learn to code.
But it's not the answer to everything.
Not everyone will like it or be good at it.
```
-[Sam Altman, Twitter](https://twitter.com/sama/status/646032444089503744)

If you're interested in learning how to code, I'd love to give you a set of resources to do so. If you enjoy it and feel you're ready for the next steps, I have a resource for that too.

```
That Hack Reactor thing you did sounds pretty cool, but where do I start?
```

This is what every friend who expresses even remote interest at what I've been up to for the past year asks. This list of resources is structured around one goal: To get you prepared to take Hack Reactor and its sister schools' (Telegraph Academy, MakerSquare, Hack Reactor Remote) admissions interview.

Some of these resources will be paid ones. I've used them myself and have found tremendous value in them. Sure there's free alternatives you can scrap together, but I'm not going to bother listing them because I don't think they're good enough.

You shouldn't be overwhelmed with a plethora of options when starting out, so I'm going to give this the Wirecutter treatment: The best resources, nothing less.

## Syntax

```
syn·tax
noun
the arrangement of words and phrases to create well-formed sentences in a language.
```

Every language has its own syntax. Javascript is no different.

Code School has a great course [Javascript Language Path](https://www.codeschool.com/paths/javascript) that helped me learn syntax and basic problem solving. It's a series of video lessons that are followed by live coding challenges. There's a helpful forum for people who are stuck.

The first course is free to complete:

[Code School - Javascript Road Trip Part 1](https://www.codeschool.com/courses/javascript-road-trip-part-1)

Read these while you go through the course, all from [Eloquent Javascript](http://eloquentjavascript.net):

[Eloquent Javascript Chapter 1 - Values, Types, and Operators](http://eloquentjavascript.net/01_values.html)

[Eloquent Javascript Chapter 2 - Program Structure](http://eloquentjavascript.net/02_program_structure.html) (part of this spills over to the next Code School lesson)

Code School normally costs $29/month, but follow [this link to get your first month for only $9](http://mbsy.co/cNwqQ). It's an affiliate link that I have from the site. I don't believe I get any sort of kickback unless you subscribe past the first month, and without it I would have pulled someone else's affiliate link off the internet. I think it's a fantastic program and it really helped me get pretty far when I was just starting out.


## Loops, Conditionals, Basic Data Structures

These are solid building blocks on your knowledge of programming. Continuing on our Code School path, we're going to take the following course (**paid subscription required**):

[Code School - Javascript Road Trip Part 2](https://www.codeschool.com/courses/javascript-road-trip-part-2)

Continue reading the following from Eloquent Javascript:

[Eloquent Javascript Chapter 2 - Program Structure](http://eloquentjavascript.net/02_program_structure.html)

[Eloquent Javascript Chapter 4 - Objects and Arrays](http://eloquentjavascript.net/04_data.html), primarily the part on Arrays -- Objects are covered in the next section


## Functions, Closures, Objects, and Prototypes

Now we're getting to some really fun stuff. This is a difficult course for beginners, but it's very necessary:

[Code School - Javascript Road Trip Part 3](https://www.codeschool.com/courses/javascript-road-trip-part-3)

Continue reading the following from Eloquent Javascript:

[Eloquent Javascript Chapther 3 - Functions](http://eloquentjavascript.net/03_functions.html)

[Eloquent Javascript Chapter 4 - Objects and Arrays](http://eloquentjavascript.net/04_data.html), primarily the part on Objects

If you're having a hard time on Closures, look into this blog post from the amazing [Javascript Is Sexy](http://javascriptissexy.com) blog:

[Javascript Is Sexy - Understand Javascript Closures with Ease](http://javascriptissexy.com/understand-javascript-closures-with-ease/)

## Best Practices

This is the closest thing to an optional course I will provide, but it's part of Code School's Javascript Path and you already have a membership, so why not? It goes over the best practices of Javascript: Useful alternate syntax, ways to improve performance, common Javascript pitfalls, and more. This will be a really helpful resource later down the line. Don't skip it:

[Code School - Javascript Best Practices](https://www.codeschool.com/courses/javascript-best-practices)

## Higher Order Functions

Okay. There's no Code School course for it, but don't panic. The following is Eloquent Javascript's chapter on Higher Order Functions (also known as Callback Functions):

[Eloquent Javascript Chapter 5 - Higher Order Functions](http://eloquentjavascript.net/05_higher_order.html)

Additionally, Javascript Is Sexy had a great post on the same topic:

[Javascript Is Sexy - Understand Javascript Callback Functions and Use Them](http://javascriptissexy.com/understand-javascript-callback-functions-and-use-them/)

## Debugging

Knowing how to debug is extremely important. When doing so, remember to talk through your entire code, line by line, as if you're explaining it to someone who has never seen it before.

A great way to do this is what's called **Rubber Duck Debugging**. It's where you explain your code to an inanimate rubber duck as a way of solving your problems. It works, and here are some great resources on learning more:

[Coding Horror - Rubber Duck Problem Solving](http://blog.codinghorror.com/rubber-duck-problem-solving/)
[Rubber Duck Debugging](http://www.rubberduckdebugging.com/)
[Wikipedia entry](https://en.wikipedia.org/wiki/Rubber_duck_debugging)

Get used to debugging -- the majority of what we do as programmers is debug code.

## Coding Challenges

Now that you've gone through all of these sessions, we're going to dive into some further learning. These are more advanced topics and the more you master these the more prepared you will be for your admissions interview.

You should be comfortable doing coding challenges and having fun with them. These are my favorite sites:

[Coderbyte](http://coderbyte.com/CodingArea/Challenges/) is an awesome set of algorithms challenges. See if you can complete all of the challenges under 'Easy'.

[Codewars](http://www.codewars.com/) is another really great site with community-built challenges. There's a coding challenge you have to take to get access to the site in the first place, and it's been very high quality. See if you can complete most 8-kyu through 7-kyu challenges, and some 6-kyu ones as well.

## JS Fundamentals Workshop

I attended an awesome Javascript workshop held at Hack Reactor last year. The good news is, you can watch it online and download the exercises. It's made available from a site called Frontend Masters, a tremendous resource in Javascript and other front-end related technology workshops. **A membership to the site runs $39/month**, and for just this single workshop alone it's worth the price of admission (I paid about $350 to take this in-person over the course of two Sundays). You get access to all of the workshops with this membership, and I think it's very well worth it:

[Frontend Masters - From Fundamentals to Functional JS](https://frontendmasters.com/courses/js-fundamentals-to-functional/)

## Advanced Javascript Knowledge

If you're done with everything else, it doesn't hurt to know about these:

[Eloquent Javascript - The Secret Life of Objects](http://eloquentjavascript.net/06_object.html)

[Javascript Is Sexy - Apply, Call, and Bind Methods](http://javascriptissexy.com/javascript-apply-call-and-bind-methods-are-essential-for-javascript-professionals/)
[Javascript Is Sexy - Understand the Keyword 'This' With Clarity and Master It](http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/)

## On-Site Learning
Okay. If you found the JS Fundamentals Workshop to be difficult to 'get' on your own, you can pay to take one of these prep workshops offered by Hack Reactor and its sister schools. Word of warning -- these are not cheap ($600-$1500+). I TA'ed the first iteration of Remote Prep, and think the curriculum is fantastic.

[Reactor Prep](http://www.meetup.com/hackreactor/)

[Remote Prep](http://www.eventbrite.com/o/hack-reactor-remote-beta-8260605281)

[Telegraph Prep](http://www.eventbrite.com/o/telegraph-academy-8184034008)

[MakerPrep](http://www.eventbrite.com/o/makersquare-8124287691)

I don't believe the curriculum is 100% consistent -- Telegraph Academy ran their own prep which was based off of the JS Fundamentals Workshop from Frontend Masters (the instructor, Bianca, is one of Telegraph's founders). All four are designed with the same goal in mind: to get you from "0 to 20". Your mileage may vary.

##Next Steps

If you got this far, you're basically ready to start interviewing with Hack Reactor. Start the [Admissions Challenge](http://www.hackreactor.com/) by following that link, hitting 'Apply Now', and schedule an interview once you pass it.