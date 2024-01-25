---
layout: default
nav_order: 5
title: LLM Action Palette
parent: Application Overview
---
# LLM Action Palette

The LLM action palette allows the user to build powerful pipelines that leverage LLMs.

### Chain

Chains connect different types of tools to extend their abilities. We currently support LLM chains, which gives the user the ability to connect tools such as vector databases and documents to an LLM to create more powerful generative AI experiences.

### Language Models

Language models are powerful AI models that perform next word prediction. These models are powerful reasoning engines capable of making decisions tasks and generating content. We currently support Open AI integration through an api key that can be found on your account through the openai website. 

### Prompt Templates

Prompt templates provide a configurable and repeatable way to align LLMs using prompt engineering, or written text. An prompt template helps to align a general LLM model to respond in a certain way or to focus on specific things in their output. An example prompt template might be: "You are a helpful AI bot employed by Sparkcognition. Answer questions politely and with great technical rigor."

### Tools

Tools empower LLMs to perform tasks outside their normal capabilities. We currently support SERP, which is a managed service that scrapes google searches. By combining LLMs with the SERP tool, user can create powerful generative AI experiences that give an LLM access to the internet to answer queries.

### Vector Stores

Vector Stores are a type of database that stores text by its semantic meaning. These are useful when combined with LLMs to give the model access to information that is outside the realm of its training data. Vector stores are integral to the "Chat with your PDF" usecase example. 

<img src="images/Screenshot_LLMActionPalette.png"/>
