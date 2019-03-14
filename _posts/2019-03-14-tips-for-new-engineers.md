---
published: true
title: Tips for new engineers
layout: post
author: Shakram02
category: life-of-an-undergrad
tags: undergrad-life
comments: true
---

NullPointerException, IndexOutOfBoundException and program crashes love you but you can't love them back?

<!-- end_excerpt -->

Here are some tips to save your time. 
Invest a couple of minutes reading the post rather than wasting hours trying to fix your code

Here's what you should do to save your time:

## Use a "debugger"

What is that? it's a program (usually embedded in the IDE you're using but you just don't know) that lets you examine the code and all the variables without using print statements, and also allows you to step through your code *you can skip "How does the debugger work?" section*

if you're feeling too lazy to read; investing 10 minutes is much better than wasting hours trying to find problems ;), [this](http://umich.edu/~eecs381/generalFAQ/Debugging.html) article discusses the reason behind why one should use a debugger. A video tutorial is available [here](https://youtu.be/drk_ldaRMaY) That's the shortest video I could find with an understandable accent. A text-based tutorial can be found [here](https://courses.cs.washington.edu/courses/cse143/11wi/eclipse-tutorial/debugging.shtml)

## You've used the debugger and searched the internet for your problem and it didn't work? 

Ask a human, it doesn't make sense to stay in a single bug more than 1.5 hours, this will just hurt you, don't be tough to yourself. after all the computer does what you wrote. 
Please avoid assuming that pointers are crazy or that Java is broken. People have been using those stuff for many years O:) take it easy and read the code **character by character**, try to explain your code to yourself and see if what's written matches what you want.

## Use the best available tools (don't switch now to save your time, use those in your next project)

You might be familiar with Eclipse IDE but have you tried using Intellij?

Intellij, which has a free community version, provides smart (pretty smart) code completion, UI designer and a debugger. Check it out [here](https://www.jetbrains.com/idea/download/) remember that it's not a smart idea to change you tools while you're in the middle of the project and the deadline is near. Use the new tools in your next project.

### You're already familiar with Eclipse or NetBeans? you can use them
Eclipse and NetBeans (use v8) can be used for C/C++ applications also, I believe that any of them is much better than CodeBlocks.
You might face some problems while installing C++ with Eclipse;
- Netbeans [v8, the most recent version doesn't have c++ built in] it can be downloaded [here](https://netbeans.org/downloads/8.0/)
- Adding C/C++ support tips [here](https://stackoverflow.com/questions/39283629/eclipse-ide-for-c-c-and-java). The answer is for an older version but the concept is the same

- You might face a "binary not found error", check out the steps [here](https://stackoverflow.com/questions/17023235/eclipse-cdt-project-built-but-launch-failed-binary-not-found)


*Eclipse and NetBeans are used in embedded systems development companies also, so getting used to the tools earlier is good for you*

**Note**: by using comfort tools you're risking mobility to move to other environments, use the correct tools for each task, don't let the task depend on the tools available.

## Embrace that you're still learning, 
It's okay to have as many mistakes done before you graduate. By making those errors now you'll gain experience and will avoid doing them again later, incrementally until your code works perfectly from the first time. *I always wondered about when that will happen when I started learning, but I can assure you that it will happen, be patient*

## Those errors are actually there to help you fix your code
You'd never want to write code and find it not working in production. Try to love those red lines 😂. By the way, the line numbers where the error happened are *clickable* in most cases, do use them and read the full error message, don't skip them because they're too many it's usually the "call stack" you just need to read the top -or bottom- lines only not everything.

## Tips from MIT Software Construction course
- Avoiding Debugging; what you should do to make your code good so bugs don't appear in the first place [link](http://web.mit.edu/6.005/www/fa16/classes/08-avoiding-debugging/)
- Debugging [link](http://web.mit.edu/6.005/www/fa16/classes/10-debugging/)

Full course material for those who're interested, can be found [here](http://web.mit.edu/6.005/www/fa16/)