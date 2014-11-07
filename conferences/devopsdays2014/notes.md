---
layout: post
title: "DevOpsDays Belgium 2014"
description: ""
category:
tags: []
---
{% include JB/setup %}

Introduction

- Oversexualisation is interesting
-- Why does it still exist?
- Axelos
-- Sponsor coffee; is that an incentive to use ITIL?

Jeff Sussna

- Ultimately, DevOps is about continuous feedback
-- The history of DevOps as a cycle of continuous feedback loop is based on cybernetics
-- Wiener: feedback at run-time makes surface-to-air missiles self-target
-- DevOps is like frogs
--- Autopoiesis: feedback loop for self-creation and self-production

Bridget Kromhout

- Magritte
-- DevOps is not a finite thing; everyone is on a journey
-- DevOps ideas are rarely new
--- They are merely rediscovered or recycled
--- Not all rediscovered ideas are from IT etc.
-- "DevOps isn't something you can buy; it's something you do"
-- "People want DevOps you can see on a balance sheet. And that's not how it works."
-- "The single strongest signal you have somethign to learn is that..." (**GET QUOTE FROM SLIDES**)
-- "What we do is DevOps; we shouldn't focus too much on the word"
-- Nobody cares too much about certification
-- The landscape changes, but the community stays the same

Cognitive Biases, Nigel Kersten

- Systematic errors in how we process information leading to irrational conclusions
- Xerox "bad copy" bug - David Kriesel
- "Thinking Fast and Slow" - Daniel Kohneman
- The "Linda problem"
- Anchoring effect
- "Rewards quality of judgements, not outcomes"

Lindsay Holmwood

- Collection
-- collectd
-- statsd
- Storage
-- Graphite
- Aggregation
-- Riemann (realtime string processing for trend analysis)

- WTF IS WITH ALL THE GRAPHS?!?
- "The Elements of Graphing Data" - William Cleveland
- Pie charts are more error-prone than line charts

- Serverspec
- Opsweekly
- Nagios Herald

- "Monitoring systems need to be more avaialble than the systems they are
  monitoring" - Adrian Cockcroft

Open Space: DevOps and Security

- Mitigating risk by having measurable "security" is useful
- Ops people being security aware helps you win the organisational security battle
- Keeping regulators happy = requirement which can be done well
- Automating security checks at deploy time
-- People don't do this as much as they should because:
--- Time is the blocker, at deploy time
--- Time is the blocker, creating security checks
- PHSS for user key management; 3rd party key management = hard
- OH: "It's on a wiki somewhere"
- Immutability = closed wtf security silos
- OH: "Security is the ultimate silo"
- Y! Paranoids
- Linus tool

Open Space: DevOps Training

- DevOps training is two-fold:
-- cultural
-- technical
- Resources
-- OpsSchool
-- Etsy's Code as Craft blog
-- The Phoenix Project
-- DevOps for Dummies
-- DevOpsDays conference
- DevOps is continual learning

Open Space: From Junior to CTO

- Just do it
-- Pick things up that need doing
-- Run with them
-- Easier in a start-up environment as more stuff needs doing
-- Easier to ask for forgiveness etc.

- Career pathing in DevOps is two-pronged
-- People management and team leading
-- Technical architecture
-- Stick to one path; people who try to do both rarely succeed

- Admitting failure

- A good junior hire
-- Actually giving a shit
-- Trying
-- Listening
-- Receptive
-- Interested
-- Intuitive

- "Management is not a promotion"

- Resources
-- Mazz's tech talk
-- "First Break All The Rules"
-- "Drive"
-- "Peopleware"
-- "Managing Humans"

Open Space: Sysadmins; will we have to be developers?

- 50:50 split of:
-- sysadmins who code
-- "pure" sysadmins

- In config managed, infrastructure-as-code envs, it's CODE ALL TEH WAY DOWN
-- DSLs are the entry point to this

- Regular hackdays are good
- 20% time

- Distinction is no longer 'dev' and 'ops', it's:
-- System developers
-- Application developers
- Ops behaviour should be applied organisationally

- Code review
- Pairing
- Reading code

- DO NOT force people to write code
