---
title: Practical tips on serverless security in Azure
description: |
  There is news of yet another data breach every other day. New cybersecurity threats are emerging almost daily. Serverless makes running apps on cloud very easy, perhaps too easy and developers can overlook security concerns. One small mistake and you may be in the next data breach report.

  **Security in cloud is everyone's responsibility**, it is not just for your cloud provider and cybersecurity team to manage, but application developers  should understand and own it as well.

  I will share with you a few practical tips for security when building serverless applications in Azure. My definition of serverless includes the usual azure functions but also other services like azure storage, service bus, cosmosdb and virtual network that are frequently used together in a microservices architecture.

  - Do you know how to authorize a function app with AzureAD?
  - Do you know how to allow a backend api app to be called from only a front-end web/function app?
  - Do you know the best practice to securely store application config values such as connection strings or API keys?
  - Do you know how to limit a service bus being accessible from only your function app and not from all of internet?

  If you would like to know answers to questions like this above then this talk is for you.

  *This talk will assume some experience in Azure Function Apps.*
speaker: Pratik Khasnabis
bio: |
  Pratik is a Solution Architect with a developer background and experienced in all things related to integration (web service, api, message/service bus, events). He has been tinkering on Azure since it was first announced and he is passionate about Azure and a strong advocate of cloud native architecture patterns. 

  Currently he is desgning and building a digital system on azure utlising many serverless services Azure has to offer.

  Pratik has following cloud certifications : 

  - MCSD - Azure Solutions Architect
  - MCSE - Cloud Platform and Infrastructure
  - AWS - Solution Architect Associate

  He has previously presented at DDD Melbourne, Vic.Net and Alt.Net Meetups
image: /images/speakers/Pratik_Khasnabis.jpg
twitter: softveda
---