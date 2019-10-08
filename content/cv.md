---
title: "Curriculum Vitae"
date: 2019-10-04T15:43:55+02:00
draft: false
---

## Education
2002 - 2006: Master Informatica at _Ghent University_  
1996 - 2002: Math - Sciences at _Sint-Andreasinstituut Oostende_

## Language Proficiency
Dutch: Mother tongue  
French: Fluent reading, speaking is good but a bit rusty  
English: Fluent reading, speaking and writing

## Core Competences
* Very experienced in agile development
* Customer-focused
* Committed & result-driven
* Team player
* Stress resistant

## Professional Training
2019-03: Developing in AWS (official amazon classroom training)  
2017-10: Apache Cassandra 2.x Core Internals  
2014-01: Principles of reactive programming (completed with distinction)  
2012-12: Functional Programming Principles in Scala (completed with distinction) 

## Experience
Experienced developer with many years of Java and scala development under his belt.
Most of his experience lies in developing reliable and scalable backend applications that deal with significant amounts of data.

Has experience working in both larger and smaller agile teams, has worked on improving "agileness" of teams and has lead a team.

As a big fan of Domain Driven Design, he tries to apply the principles whenever possible. Among other things, this lead to succesfully introducing CQRS using event-sourcing at Thomas Cook.

### Tech Lead at Thomas Cook
**Period:** 11-2018 until 10-2019

**Role:** Role: Tech Lead for a development team
In 2018, I was promoted to tech lead of the team. This was a distributed team across Belgium, Ukraine and The Netherlands.

In this role, I was responsible for technical decisions both the short and long term, working with the product owner and business to make sure business expectations were realistic and fulfilled. On the other hand there was also a significant portion of people management to keep everyone aligned, happy and in a role in which they were able to grow.

### Java/Scala developer at Thomas Cook (09/2013 until 10/2018)
**Role:** Java/Scala developer
As a senior developer on the project, I was the main driver behind the design and implementation of the current content distribution system at Thomas Cook.

When I started out at TC, I pushed hard for the improvement of the coverage and general quality of the tests. Over the years and together with our product owner, I also improved the ways of working of the team to become a truly agile team.

Over time I took on most of architecture work and became the person to contact with scala and akka questions in the team.

**Project:** Due to severe limitations, we replaced the old content distribution system with a new set of
backend services. These services were required to take in constant flows of hotel descriptions, facts, room information and images from various source systems in all kinds of formats.

The system served this information over a REST API to many different websites and services for the UK, BE, NL and DE markets.

The main challenges in this application were:

* Dealing with a significant inflow of data in all kinds of formats.
* Modeling everything in a sane API which served many clients, respecting very strict
backwards compatibility requirements.
* Very variable and potentially high volumes of queries on the API.
* Downtime was not acceptable (and never occurred either).
* Responding quickly to queries (95th percentile was generally within 30-50ms), with a
minimal amount of caching.
* Retaining a 3 year history of all hotel data for legal reasons.

**Technology:** Scala, Akka (http, persistence, streams), Cassandra, ElasticSearch, RabbitMQ, scalatest, scalamock, SBT, Kamon, Cucumber, Java 6-8, MySQL, Spring, Camel, Junit, Mockito

**Deployment:** Automted using Terraform and Chef, integrated with a jenkins CI/CD pipeline. Prepwork was done to use docker containers with Fargate on AWS, but sadly the project ended prematurely.

**Testing:** Unit tests, integration tests & BDD.

### ICTRA (NMBS Holding) (01/2012 until 06/2013)
**Period:** 01-2012 until 06-2013

**Role:** Java developer and Agile Coach.
My task on this project was not only to do java development, but also to help in the transition of an existing team to agile, domain driven and test driven development.

**Project:** The main purpose of the project was to create a new schematic view, on which an operator can drag and drop trains to adjust their planning in real time. This had to be built on top of an existing application that was already in use for many years.

The main challenges of this project were:

* creating very performant algorithms to find routes through the railway network based on the user input.
* successfully switching a team that did 15 years of waterfall to agile.
* speeding up and stabilizing releases through test driven development, continuous testing and automated deployments.

**Technology:** Java 6, Spring 3.1, Spring Data Graph with Neo4j, Hazelcast, JavaFX 2, Resteasy,Oracle DB, Jenkins, Git

### ADMBiS
**Period:** 10-2011 until 12-2011

**Role:** Java developer and coach for a junior developer.

**Project:** Creation of a small and fast web based search engine to search in the company’s large amounts of unstructured data.

**Technology:** Java 6, Lucene 3.1, Hibernate Search, Spring MVC, Subversion


### Argenta
**Period:** 10-2010 until 10-2011

**Role:** Java developer in an agile team.

**Project:** The goal of the project was to create multiple complex web applications to give the agents an integrated view and access point to the data and products of their clients. These applications communicate with a variety of databases and web services in a very performant and secure way.

The project's main features:

* Domain Driven Design
* Very strong focus on code quality
* Agile development with 3 big teams on a single codebase in biweekly sprints

**Technology:** Java 6, JSF 1.2 with Richfaces and JQuery, Hibernate (JPA), Spring Webservices, Spring Webflow, Hudson, Oracle DB, Git + Subversion

### Belgacom
**Period:** 07-2008 until 09-2010

**Role:** Junior Java developer.

**Project:** Development of a new order management application to be able to easily handle personalisation of large mobile phone contracts for big companies.

The main challenges were:

* the immense amounts of data involved.
* integration with an ancient legacy system which made transactionality and performance
requirements very complicated.

**Technology:** Java 5, Struts 2 with JQuery, Hibernate, Axis 2, Apache POI, Sybase DB, Oracle DB, BEA Weblogic and IBM Websphere app servers, Subversion, Clearcase


### ING
**Period:** 10-2006 until 05-2008

**Role:** Junior Java and Cobol developer

**Project:** Writing a new application based on the Calltaÿ & Wouters netbanking framework Kyudo.

**Technology:** Java 1.4, Tomcat, Cobol, C and Korn Shell Scripting