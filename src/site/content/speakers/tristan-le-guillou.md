---
title: "Scaling serverless from MVP to production and beyond"
description: "We will walk you through a journey of developing a geo-challenge platform using serverless framework. 

Why did we choose serverless? 

\"Because everyone is using it..\" is the wrong answer! Because our target was to create a lean product, just to see how people would react to it. Our goal was to build it fast, before someone else builds something around the same idea, with minimum investments. And serverless ticked all these boxes!

We developed for 3 weeks, we launched our mobile game and people loved it! (There were some proud moments where we saw some people near the train station playing it.) And we even sold the product to a team building company. 

Challenges faced once the MVP becomes serious

First, we had to make our serverless architecture stable, and automate the infrastructure. As many developers were working on it, we introduced CI/CD. We also needed to have a test environment and a production environment, and this concept is completely different for serverless.

Our client then came up with requests for new features. We thus created new lambdas for each feature. After a while, we realised we just had a huge distributed monolith system.

When we decided to sell the game again to a different client, we needed to go multi-tenant. How did we manage it? 
One day we woke up to realisation that we had reached the limit of creating resources per stack on AWS! What? How come?

Lessons we learned

Serverless works great, but it needs a different mindset, discipline and a learning curve for the developers, and we will share our experience about the same."
speaker: Tristan Le Guillou
secondSpeaker: Aditi Phadke
bio: ""
image: /images/speakers/Tristan_Le_Guillou_(co_presenter).jpg
---