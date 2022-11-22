---
layout: page
title: "Class 16"
permalink: /reading-notes/class-16/
---

## What is Serverless Computing

According to <https://www.ibm.com/cloud/learn/serverless>, serverless computing is an application deployment and execution paradigm that essentially abstracts away the underlying infrastructure needed to deploy and run an application. A developer using serverless computing only needs to focus on writing code that deals with business logic while the server creation and code execution are then managed by a cloud provider. The cloud provider will likely provision a container running in a virtual machine, which runs on a bare metal server in a data center somewhere and containerizes the application. By using serverless computing, application developers only need to focus on the business logic. At the same time, serverless functions can automatically scale based on traffic, thereby saving cost of keeping a server alive. However, because serverless functions need to spin up from a dormant state when it sees traffic, there is a latency cost involved. Additionally, serverless functions cause vendor lock-in preventing application developers from migrating their application to other cloud providers or on-prem servers seamlessly.

## Bookmark and Review

<https://vercel.com/docs/concepts/functions/serverless-functions>

<https://realpython.com/effective-python-environment/>

## Things I want to know more about

- The internals of what it takes for an infrastructure to be able to carry out serverless computing
