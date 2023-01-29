---
layout: essay
type: essay
title: "Don't be afraid to ask questions"
# All dates must be YYYY-MM-DD format!
date: 2023-01-26
published: true
labels:
  - Questions
  - Answers
  - StackOverflow
---

<img width="300px" class="rounded float-start pe-4" src="../img/istockphoto-1139500641-612x612.jpg">

## No question is a dumb question

All throughout school from kindergarten all the way up through undergrad teachers have always used the phrase, "No question is a dumb question," which I've now learned is wrong. At least in the scope of software engineering there is such a thing as a bad question which can lead to not so helpful answers.

## What to look for in a good question?

Being able to ask a good question is something that has to be learned. A great place to look for examples is a website called Stack Overflow, a site used mainly by programmers looking for help with their code. 

In the following [example](https://stackoverflow.com/questions/75170936/error-with-websocket-connection-when-trying-to-add-dependencies) the user is able to describe what is happening in the code, the problem when running the code and what they have tried to resolve the problem:

```
Q: Error with websocket connection when trying to add dependencies

The useEffect() function receives data continuously through a websocket from a python program. The problem is that when I run the code via the npm start command, I get a data display with a very high frequency and this error continuously in the console :  WebSocket connection to 'ws:<URL>/' failed: WebSocket is closed before the connection is established. But the functions did receive changes to the selectedSection variable based on clicks on the different sections.

I should point out that I used the useEffect() function in this way before, it worked but I didn't have access to the updated version after clicking on one of the sections of the selectedSection variable:
```
Below the question they provided a snippet of code he believed was causing the problem along with the entire code for others to play around with to help figure out the issue. It is ideal to do both so that the users trying to answer your question aren't left with a lengthy code to search through and find what is going wrong. The user was able to get 2 answers to this question and resolve the issue so I think it's fair to categorize this question as a good one. 

## "Your question has been closed."

Believe it or not there are a lot more bad questions than good on StackOverflow (they've just got good at filtering them out). The [question](https://stackoverflow.com/questions/75252834/anydoes-anyone-know-how-to-program-a-sudoku-in-android-studio-with-c) below has -5 votes which means that it will soon be deleted by Stack Overflow since this would be considered a bad question. 

```
Anydoes anyone know how to program a sudoku in android studio with c++, with diferents dificulties

Actually I only know how to do with java
```
The reason this would be considered a bad question is that it's too broad. The simplest answer to this question would be yes because I'm almost positive there are users on this site completely capable of creating a sudoku program. To improve this question, the user should include some sort of code they've written in an attempt to create this program while stating what they know and then asking for help on a way to move forward. 

## Conclusion

When asking questions on Stack Overflow, the best thing to keep in mind is that others may run into the same problem in the future so it would be best to write your question in a way that would allow other users to help not only you but anyone else who might need the same answer.
