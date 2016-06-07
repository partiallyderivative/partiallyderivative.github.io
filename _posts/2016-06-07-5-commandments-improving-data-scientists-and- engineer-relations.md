---
layout: post
author: elisebreda
title: "Five Commandments: Improving Data Scientist and Engineer Relations"
date: 2016-06-07 08:06:00
categories: blog
tags:
- data science
- data
- technology
permalink: /resources/2016/2/17/5-commandments-improving-data-scientist-and-engineer-relations
---

# Five Commandments: Improving Data Scientist and Engineer Relations

On the surface, data science and engineering sounds like a match made in heaven. Data scientists create novel solutions for business problems while their engineering counterparts build the environments and integrations to take those solutions into the real world. What could go wrong?

Unfortunately, the relationship between data scientists and engineers is known for being a tenuous one. For most organizations, it “lies somewhere in the spectrum between non-existent and highly dysfunctional.”

Ouch.

So why is this and how can it be avoided? In this brief post we’ll introduce Five Commandments for improving communication and collaboration between data scientists and engineers. Feel free to etch them into stone tablets.

## 1. Know thy data.

Good models are dependent on good data. To build anything worth being put into production, data scientists need to know how reliable their data sets are, where they are created and stored, and how often they change. This information should be gathered and shared with the engineering team up front (before work is implemented) to avoid frustration down the road.

In an ideal world, both teams should know about upcoming changes (e.g. a change in variable format type) well in advance so they can work together to create, test, and deploy a new version accordingly. Even if every mishap can’t be preempted, sharing sources and discussing shortcomings early on will allow engineers to mitigate risk and troubleshoot errors should anything go awry.

## 2. Familiarize yourself with thy neighbor's tools.

Data scientists work predominately in scientific programming languages like R or Python, which are ideal for cleaning, exploring and modeling data. Engineers, on the other hand, use a different set of tools for building scalable web and mobile apps (think .NET, Ruby on Rails, Node.js or JVM). While it’s not realistic to expect any person to fully know both sets of tools, a basic understanding of the languages and processes used on the other side of the fence will go a long way toward collaboration.

Manually rewriting models from statistical code to another language is taxing, time-consuming and error prone, so it is absolutely critical to establish good lines of communication (both face to face and digital) for when questions and concerns arise.  

## 3. Acknowledge technical limitations.

Data scientists and engineers working with disparate tool sets are bound to encounter technical limitations. This is a frequent source of frustration, as no one likes being asked to rework a final product into something suboptimal, or worse, seeing their hard work go down the drain.

Once you’re clear on the languages your model will be developed and deployed in (see Commandment #2), take time to research what is and is not possible. Schedule regular cross-functional discussions to talk about what approaches you’re considering and what type of concessions may need to be made. What is entirely out of scope? What are other options? How much effort would be required to implement them? Is the effort justified by the business value?

For example, if you’re a data scientist writing a fraud detection algorithm in R for an app written in Ruby, you should know that R’s glm function (a command that fits a generalized linear model capable of predicting a True/ False outcome), has no native equivalent in Ruby (or Java, for that matter). Time to brainstorm other options.

## 4. Honor thy data scientist and thy engineer.

Any time your workstream is dependent upon another person, there will plenty of opportunities for misunderstanding to creep into the picture. Our advice? Like mom always said in regard to working with cross functional colleagues, do unto others as you would have them do unto you.

In the case of data scientists, write high quality code that is easy to maintain and productionize. Be open to suggestions about refactoring and alternative approaches. Ask engineers what a realistic implementation timeline would look like and how you can be helpful.

For engineers, work with the data science team to define clear must-haves and agree on a written  priority order. Maintain an up-to-date and realistic road map that incorporates time to test, refine, and implement data science models. Err on the side of over promising and under delivering.

## 5. Maintain thy accountability and responsibility.

It’s very dangerous to think that once a model is live in production that both the data science team that prototyped it and the engineers who implemented it are free to move on to the next big project. In reality, this is only the beginning of another phase of the analytics lifecycle.

At this point, it’s critical for data scientists and engineers to establish a plan for monitoring and managing models in production. Who will oversee the stability of the models and the servers in real time? How will input and output data be stored and shared? What is the roadmap for versioning, retraining and retesting?

Create a plan of action for probable situations that may arise. What will happen if model throughput increase? How much time and money would scaling require? Agree on a fair split of responsibility up-front and allocate team members’ time accordingly.

### Revelation

Data scientists and engineers are working toward the same goal: ship code that solves business problems. Unfortunately, misunderstanding and technical inefficiencies often cause people to lose sight of that goal. While there are no magic formulas when it comes to working with other people, the five commandments above will go a long way toward closing the gap between your data science and engineering teams.

At Yhat, we’ve taken it a step farther and developed a way to totally close that gap. Our software, ScienceOps, lets data scientists productionize models in minutes without the messy handoff to the engineering team. How? ScienceOps makes R and Python models accessible via REST API requests without any manual recoding. Data scientists simply send a code snippet to the engineering team to embed models hosted directly into production applications.

Beyond the initial step of implementing models, ScienceOps also gives data scientists, engineers, and sys admins the ability to monitor, audit and manage models and traffic. The platform scales horizontally to allow you to deploy additional models or add servers at any time to accommodate for seasonal or permanent increases in throughput. ScienceOps meets data scientists’ need for speed and autonomy while providing the reliability, efficiency and scalability that engineers require.

### Resources
[Engineers Shouldn’t Write ETL: A Guide to Building a High Functioning Data Science Department ](http://multithreaded.stitchfix.com/blog/2016/03/16/engineers-shouldnt-write-etl/) - Stitchfix

[Working Together at the Intersection of Data Science and Data Engineering Webinar](https://datascience.berkeley.edu/blog/webinar-data-science-engineering/) - Berkeley Data Science

[Applied Data Science: A Practical guide to building data-driven products beyond analysts’ laptops](https://www.yhat.com/whitepapers/applied-data-science) - YHAT

[Bridging the Gap Between Data Science and Data Engineering](https://www.youtube.com/watch?v=EtYv7zPyS2A&feature=youtu.be) - Josh Wills @Slack
