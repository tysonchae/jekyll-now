---
layout: post
title: 	The reason why it is hard to read code written by others
published: false
date: 2012-11-30
categories: [blogging]
tags: [blogging]
---



As a developer, You might experience to read other’s codes and have had to read them. Many developers may encounter difficulty in reading codes that other developers has written as I do.
Actually I am on the project, converting old version Trade Management System with this age’s circumstance. What I mean is the system was built about 20 years ago (Can you imagine the 20 years old program? I cannot even define which language was used) and I am really suffering from reading the old source code since I need to follow all the work.

I guess I need to analyze the causes myself.
Based on my experience (not only this time but during my developer’s life), I came with causes of difficulty in reading code.

1. You do not know the language or library

Absurd, but the grounds for difficulty in reading others’ code are due to a lack of understanding of the language, library, or API. You never follow others’ code if you don’t know the basic syntax, etc.  Among the programming languages, they have a lot of similarities but there exists a lot of differences. Surprisingly these differences hinder understanding code or make to write a wrong code. In order to understand others’ code, you should strive to understand more deeply in the programming language. In addition, understanding of the behavior of the library is essential as well. Even if you know Win32 API well, MFC code cannot be understood without MFC knowledge. Likewise, if adhered to OpenGL, even OpenGL expert is able to read code only if he knows and has studied OpenGL. Therefore, now that you should keep in mind to knowwhat library is used for the code you read on and beforehand, library studying have precedence over pre-reading the code.

2. You do not know what this program is

Sometimes, it’s hard to understand the meaning or purpose of the code through only reading the code. The reason is that it’s not easy to know what the program is and what function it has to have.Therefore,  this should be mandatory and essential : “Run the program first”. and then find the code related to what you just ran.  You feel that it’s easier to understand the code. This is one of the shortcut to analyze the code.

3. You do not attempt to read

Usually you take a look at others’ codes when you need to fix a bug or the codes should be taken over to you (have to keep coding following others). In this situation, I usually do not want to read the others and read it a bit. Every time I met this kind situation, I had trouble. Since I did get what the code said, I did not know how and what to write even ifI felt pressed to keep writing a code. Keep in mind that it’s impossible to understand others’ codes if you give a little effort (reading only a bit).

5. There has a problem in the code

Lack of your sill or effort can cause the difficulty of reading codes but sometimes the code itself has a problem.

In my experience, I met

1. there is a bug in the code

2. comments and the behave of code are different.

3. the unnecessary code were still remained.(probably it was not removed after requirement had been changed.)
