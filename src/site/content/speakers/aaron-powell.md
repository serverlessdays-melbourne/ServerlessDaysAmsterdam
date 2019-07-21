---
title: Stateful Serverless through Durable Functions
description: "You're introducing Serverless as a component within your application architecture and it's great at solving the processing-at-scale problems that you have. But there's one sticking point, how do you handle an operation that takes more than a few seconds to run? What happens when we have an asynchronous operation that needs to complete before you can respond to the caller? We don't want our Serverless code waiting, that'll become expensive quickly, instead we want to sleep for a period of time. This is where event sourcing comes in, but do you want to be building your own orchestration engine or managing state across restarts?

Enter Azure Durable Functions; Durable Functions allow you to orchestrate a workflow of functions that can start background jobs and then sleep until they are needed.

From long running asynchronous operations in HTTP APIs to fan out, monitoring processes to human interaction, Durable Functions can be used to solve a variety of different problems without the need to build your own event sourcing platform.

In this talk we'll look at some of the patterns that Durable Functions helps to solve through a series of live coding exercises that you can take away and experiment with yourself and apply to your own problems."
speaker: Aaron Powell
bio: "Aaron is a Developer Advocate at Microsoft and former consultant at Readify. By day he spends his time in all facets of .NET development and by night he explores crazy ideas like writing your own implementation of numbers in .NET, creating IoC in JavaScript or implementing tic-tac-toe using git commits."
image: /images/speakers/aaron-powell.png
twitter: slance
---