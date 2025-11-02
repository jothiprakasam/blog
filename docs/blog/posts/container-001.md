---
# The blog plugin uses this for ordering and display
date: 2025-11-02
title: What is Container?
description: A quick start guide to using MkDocs for blogging.
author: Jothi Prakasam R
categories: [Tech, DevOps]
tags: [Container, Deployment]
---

Before we dive into the concept of containers, we need to understand the problem with the existing solution.

## Deployment issue

Deployment of Software is a crucial part of the business. Before containers, applications were typically deployed directly on virtual machines or physical servers, either in private data centers or cloud environments. The application is built on a host OS, and the application has source code, dependencies, and shared libraries. Suppose these applications are built on Linux Systems and it is deployed in a Windows system, it might not work because it is built on Linux.

## Scaling

For Example, an e-commerce site like Amazon, Flipkart is used by many people in many countries. These applications are getting a lot of traffic. Due to high traffic in the system, it may fail to respond to all the requests from customers, and the site may go down, the server may crash. To make it to handle more traffic to scale the application.

## Microservice Architecture

Microservice architecture is an application that consists of loosely coupled components, which can be removed and added to the application at scale .

To understand this
An e-commerce application follows a microservice architecture

1. Cart Service — manages items added by customers
2. Payment Service — handles transactions
3. Product Service — manages product listings
4. Offer Service — applies discounts and promotions

This architecture solves monolithic application problems.

## Dive into Containers

Containers were introduced as a solution to these deployment, scaling, and microservice challenges. A container is a lightweight, portable unit that packages an application together with all its dependencies, libraries, and configurations, ensuring it runs consistently across different environments. Unlike traditional virtual machines, containers share the host operating system’s kernel, making them faster, more efficient, and less resource-intensive. With containers, developers can build once and run anywhere — whether it’s on a laptop, a private server, or the cloud. This not only solves the compatibility issues but also makes scaling applications and managing microservices much simpler.
