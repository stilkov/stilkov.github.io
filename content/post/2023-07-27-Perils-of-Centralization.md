---
title: 'Perils of Centralization'
date: '2023-07-27T17:00:00+01:00'
lang: 'en'
---

A long time ago, I wrote [a blog post](https://www.innoq.com/en/blog/thoughts-on-a-canonical-data-model/) about reasons to avoid a canonical data model. It keeps getting referred to and still creates some interesting conversations, so I thought it might make sense to write my current thoughts about the topic.

First of all, the idea of simplifying an organization’s IT structure and architecture
by “just” standardizing the data models is alive and well (though still as misguided
as ever). These days, there are two places where it appears.

The first one is in connection with some sort of API-first strategy. It’s still
extremely tempting to believe that once you’ve managed to give everyone access to the same
pool of well-managed, well-described APIs, they’ll be able to simply build their applications
by using those APIs. It still considers efficiency by avoiding redundancy as the central tenet,
and just as described in the discussion about CDMs in my old post,  misses the
much larger benefits of autonomy. 

The second area where standardizing and centralizing models is firmly rooted as
a best practice is in the data analysis space. Luckily, there is a counter-movement:
The [data mesh approach](https://www.datamesh-architecture.com) fundamentally adopts the
idea of decentralized responsibility, and is a great match for organizations that have
adopted the concept of self-containend, value-stream oriented teams.

I believe that especially as money has become more expensive, creating
centralized pools of (meta) data will be harder and harder to justify to
stakeholders. It’s much better to do things that allow end-to-end teams
to work in fast iterations that provide immediate feedback to the value
they create. To my mind, this has been the defining characteristic of
many successful architectural approaches in the past few years.
