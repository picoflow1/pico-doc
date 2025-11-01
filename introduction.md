---
title: Introduction picoflow . 
description: What is picoflow and why?
layout: libdoc_page.liquid
permalink: index.html
tags:
    - widgets
---
{% alert 'It seems to be the beginning of a great documentation story!', 'info', 'Howdy!' %}

## History
* Over the past 2.5 years, we have been designing and implementing LLM-driven systems from first principles. Our early implementations directly leveraged vendor-provided SDKs and APIs. When LangChain introduced a generalized abstraction layer for LLM orchestration, we adopted it to streamline model integration and prompt management.
Despite this, the orchestration of end-to-end business flows remained largely manual and application-specific. To address this, we incrementally developed an internal framework — a lightweight, homegrown version of an agentic flow engine — continuously refining it as our understanding of agentic patterns, prompt chaining, and contextual state management evolved.
Our primary domain of expertise lies in building mechanisms that enable non-AI developers to transform conventional business workflows into AI-augmented pipelines. This is achieved by programmatically injecting LLM-based decision and interaction nodes into existing deterministic processes, allowing organizations to “botify” legacy operations with minimal disruption to their underlying logic.
In parallel, we have engineered some of the most sophisticated conversational agents in production today — capable of replacing traditional web or mobile interfaces by translating user intent directly into actionable operations.
As the agentic ecosystem matured, we conducted a systematic benchmarking of our internal library against industry-leading frameworks, notably LangChain and LangGraph. The evaluation criteria included architectural modularity, abstraction clarity, traceability, observability, replayability, and developer ergonomics.
The resulting framework, Picoflow, diverges from LangGraph in both philosophy and architecture. Whereas LangGraph emphasizes graph-based task decomposition, Picoflow focuses on predictable, composable flow semantics optimized for JavaScript ecosystems. Despite these differences, both share the goal of enabling scalable, inspectable, and maintainable agentic systems.
Ultimately, Picoflow provides an opinionated, production-ready orchestration framework that enables JavaScript developers to build complex, AI-native business applications with minimal friction and maximum transparency — achieving rapid productivity without sacrificing control or observability.


## Let’s start!

1. {% iconCard 'Configure', 'Start entering your own settings into `settings.json` at the root of the project. <br>[Configuration documentation](https://eleventy-libdoc.netlify.app/configuration/).', 'faders' %}
2. {% iconCard 'Write', 'Easily write documentation with Markdown and <abbr title="Hyper Text Markup Language">HTML</abbr>. <br>[Create content](https://eleventy-libdoc.netlify.app/creating-content/).', 'pen' %}

## Foo

## Get help

LibDoc’s website contains a comprehensive documentation about how to install, configure and :

* [LibDoc’s homepage](https://eleventy-libdoc.netlify.app) <br>The website containing LibDocs’s presentation and comprehensive documentation.
    * [Front matter](https://eleventy-libdoc.netlify.app/front-matter/) <br>Documentation of all front matter settings related to a LibDoc page.
    * [Primary navigation](https://eleventy-libdoc.netlify.app/primary-navigation/) <br>Detailed features of LibDoc’s primary navigation.
    * [SEO](https://eleventy-libdoc.netlify.app/configuration/seo/) <br>How LibDoc’s configuration and pages parameters are applied for Search Engine Optimization.
    * [Credits](https://eleventy-libdoc.netlify.app/configuration/credits/) LibDoc could not work without these resources.