# Javascript Beginner's Curriculum

## Latest Update: 02/06/2016
+ Tweaked introduction
+ Added Subscriptions section, letting you know what we'll be covering
+ Removed Prep links
+ Added Mock Interview section

### Table of Contents

[Notes on this Repo](#notes)

[Introduction](#intro)

**Start Here**

[Subscriptions](#subscriptions)

[Syntax](#syntax)

[Loops, Conditionals, Basic Data Structures](#loops)

**Intermediate Learning**

[Functions, Closures, Objects, and Prototypes](#functions)

[Best Practices](#bp)

**Advanced Topics**

[Higher Order Functions](#callbacks)

**Troubleshooting**

[Debugging](#debugging)

**Further Learning**

[Coding Challenges](#challenges)

[JS Fundamentals Workshop](#fundamentals)

[Advanced Javascript Knowledge](#advanced)

**Next Steps**

[Next Steps](#next)

[Mock Interview](#mock)

***

## <a id="notes"></a>Notes on this Repo

This repo is bound to be updated with more resources as I find the time to do so. If you fork it, be sure this repo is set as your upstream and run `git pull upstream master` every once in a while to grab the latest version. Github has some [great documentation for doing this](https://help.github.com/articles/fork-a-repo/).

Questions? Suggestions? [Create a Github Issue for this repo](https://github.com/rkho/javascript-beginners-curriculum/issues/new) and I'll address it.

## <a id="intro"></a>Introduction

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

There's a severe problem with our tendency as humans to debate minutiae. *X is better than Y because of a marginal edge case of Z*. Please, that's one edge case that's not catch-all. *A combination of A, B, and C is just as good as paying for D*. I'm having none of it.

If you're serious about actually doing something instead of spending hours deciding to do it, then this is a great guide for you. I'm giving this guide the Wirecutter treatment: **The best resources, nothing less**.


## <a id="subscriptions"></a>Subscriptions

First things first, some of these resources are paid. I don't work for these companies. I don't get a kickback from these companies. They are objectively more effective than trying to build your own curriculum with free alternatives, because of two reasons:

+ They're being paid to give you quality content
+ You will (hopefully) motivate yourself with a small financial commitment

Let's look at the subscriptions you'll be signing up for:

1. [Code School](https://www.codeschool.com) is $29/month. Buy this first.
2. [Frontend Masters](https://www.frontendmasters.com) is $39/month. Buy this later.

## <a id="syntax"></a>Syntax

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

A Code School subscription runs $29/month. It helped me get pretty far when I was just starting out, and I heavily recommend it.


## <a id="loops"></a>Loops, Conditionals, Basic Data Structures

These are solid building blocks on your knowledge of programming. Continuing on our Code School path, we're going to take the following course (**paid subscription required**):

[Code School - Javascript Road Trip Part 2](https://www.codeschool.com/courses/javascript-road-trip-part-2)

Continue reading the following from Eloquent Javascript:

[Eloquent Javascript Chapter 2 - Program Structure](http://eloquentjavascript.net/02_program_structure.html)

[Eloquent Javascript Chapter 4 - Objects and Arrays](http://eloquentjavascript.net/04_data.html), primarily the part on Arrays -- Objects are covered in the next section


## <a id-"functions"></a>Functions, Closures, Objects, and Prototypes

Now we're getting to some really fun stuff. This is a difficult course for beginners, but it's very necessary:

[Code School - Javascript Road Trip Part 3](https://www.codeschool.com/courses/javascript-road-trip-part-3)

Continue reading the following from Eloquent Javascript:

[Eloquent Javascript Chapther 3 - Functions](http://eloquentjavascript.net/03_functions.html)

[Eloquent Javascript Chapter 4 - Objects and Arrays](http://eloquentjavascript.net/04_data.html), primarily the part on Objects

If you're having a hard time on Closures, look into this blog post from the amazing [Javascript Is Sexy](http://javascriptissexy.com) blog:

[Javascript Is Sexy - Understand Javascript Closures with Ease](http://javascriptissexy.com/understand-javascript-closures-with-ease/)

## <a id="bp"></a>Best Practices

This is the closest thing to an optional course I will provide, but it's part of Code School's Javascript Path and you already have a membership, so why not? It goes over the best practices of Javascript: Useful alternate syntax, ways to improve performance, common Javascript pitfalls, and more. This will be a really helpful resource later down the line. Don't skip it:

[Code School - Javascript Best Practices](https://www.codeschool.com/courses/javascript-best-practices)

## <a id="callbacks"></a>Higher Order Functions

Okay. There's no Code School course for it, but don't panic. The following is Eloquent Javascript's chapter on Higher Order Functions (also known as Callback Functions):

[Eloquent Javascript Chapter 5 - Higher Order Functions](http://eloquentjavascript.net/05_higher_order.html)

Additionally, Javascript Is Sexy has a great post on the topic:

[Javascript Is Sexy - Understand Javascript Callback Functions and Use Them](http://javascriptissexy.com/understand-javascript-callback-functions-and-use-them/)

## <a id="debugging"></a>Debugging

Knowing how to debug is extremely important. When doing so, remember to talk through your entire code, line by line, as if you're explaining it to someone who has never seen it before.

A great way to do this is what's called **Rubber Duck Debugging**. It's where you explain your code to an inanimate rubber duck as a way of solving your problems. It works, and here are some great resources on learning more:

[Coding Horror - Rubber Duck Problem Solving](http://blog.codinghorror.com/rubber-duck-problem-solving/)
[Rubber Duck Debugging](http://www.rubberduckdebugging.com/)
[Wikipedia entry](https://en.wikipedia.org/wiki/Rubber_duck_debugging)

Get used to debugging -- the majority of what we do as programmers is debug code.

## <a id="challenges"></a>Coding Challenges

Now that you've gone through all of these sessions, we're going to dive into some further learning. These are more advanced topics and the more you master these the more prepared you will be for your admissions interview.

You should be comfortable doing coding challenges and having fun with them. These are my favorite sites:

[Coderbyte](http://coderbyte.com/CodingArea/Challenges/) is an awesome set of algorithms challenges. See if you can complete all of the challenges under 'Easy'.

## <a id="fundamentals"></a>JS Fundamentals Workshop

I attended an awesome Javascript workshop held at Hack Reactor last year. The good news is, you can watch it online and download the exercises. It's made available from a site called Frontend Masters, a tremendous resource in Javascript and other front-end related technology workshops. **A membership to the site runs $39/month**, and for just this single workshop alone it's worth the price of admission (I paid about $350 to take this in-person over the course of two Sundays). You get access to all of the workshops with this membership, and I think it's very well worth it:

[Frontend Masters - From Fundamentals to Functional JS](https://frontendmasters.com/courses/js-fundamentals-to-functional/)

## <a id="advanced"></a>Advanced Javascript Knowledge

If you're done with everything else, it doesn't hurt to know about these:

[Eloquent Javascript - The Secret Life of Objects](http://eloquentjavascript.net/06_object.html)

[Javascript Is Sexy - Apply, Call, and Bind Methods](http://javascriptissexy.com/javascript-apply-call-and-bind-methods-are-essential-for-javascript-professionals/)
[Javascript Is Sexy - Understand the Keyword 'This' With Clarity and Master It](http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/)

## <a id="next"></a>Next Steps
If you're this far, congratulations! I think you have a good grasp on the basics of Javascript, and I encourage you to start interviewing for the program of your choice.

## <a id="mock"></a>Mock Interviews

I'm floating the idea of offering paid mock interviews if you're interested in having one. I find that the more interviews you do, the more prepared you are for them and I feel this is a valuable service.

If you're interested, leave me your name and email at [this helpful Google Forms survey](https://docs.google.com/forms/d/13k5eVm3QWhZr8yINb1xJYlYOpZQlbL1FRlQ3Hhv3Lb4/viewform?usp=send_form). It really helps gauge interest and I'll be in touch once I figure things out.