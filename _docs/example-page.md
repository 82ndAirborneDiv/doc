---
title: Cloudable System Archetypes
description: What systems can go to the cloud? How long will it take?
---

# Cloudable System Archetypes

What systems can go to the cloud? How long will it take?

During Friday’s Workforce Transformation substream meeting, we started talking about how to measure how much of CDC is able to move to cloud, how it benefits programs, and how quickly systems will transfer to cloud from CDC prem. The general draft measure is something like “what % of CDC systems are clouded” and the discussion was about how to get a good estimate and timeframe, center ADIs have the best answer as to whether systems can move to cloud, how much resources that will require, and timeframe.

This is tough because we haven’t yet decided on specific cloud architectures that are supported and because CDC doesn’t have a standard system architecture of systems, we have wide variability in the technologies and patterns used across the 900+ systems. So Barton asked “What about the most common system types?” No one in the meeting was aware of a defined set of common systems so Barton asked me to come up with a few archetypes and start this document that others can extend.

The goal of this post is to describe a few standard system archetypes that hopefully system owners can review to see how similar their own systems are to these archetypes. This list is definitely missing details, probably wrong, but hopefully useful to serve as a skeleton and start a conversation among architects and business analysts who can flesh it out. We can measure the usefulness of this list by how many system stewards can use it to help estimate if cloud architectures planned and available will allow them to modernize to the cloud.

An archetype is sometimes called a “tech stack” 1 and follows the pattern of some front-end technology, some back-end technology, and some database technology.

