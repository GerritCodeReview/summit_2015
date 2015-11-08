# Sunday Agenda

|||---||| 7,5

#### Schedule
<iframe
  src="https://docs.google.com/spreadsheets/d/1k3Q_Jx-iSPlHzfeTmrYYuMrebripvkD98vknhhOth50/pubhtml?gid=811932605&widget=true&headers=false"
  width="510px"
  height="510px"
  frameborder="0"></iframe>

#### Sessions
[TOC]

|||---|||

## 8:45 am Breakfast

Coffee and breakfast in breakout area.

## 9:30 am Gerrit at Qualcomm

*Nasser Grainawi, Qualcomm*

## 9:50 am Scaling Gerrit at Ericsson

[Slides](https://storage.googleapis.com/gerrit-talks/summit/2015/Scaling-Gerrit-Ericsson.pdf)

*Vladimir Cantiru, Ericsson*

## 10:30 am Scaling Gerrit: active-active masters

[Slides](https://storage.googleapis.com/gerrit-talks/summit/2015/Multimaster-Gerrit.pdf)

*Shawn Pearce, Google*

## 11:00 am Break
## 11:30 am Tuning Gerrit

How to Properly Tune and Size your Gerrit Backend

So you decided to host your Git repositories yourself - great! How
many servers will you need? Which cloning protocols to offer? How
many CPUs and how much RAM will you need? What the heck is pack
size? How often should you run garbage collection?  Does it
make any difference whether you go with a native Git or JGit
based backend? How do you handle hundreds of polling CI users
without compromising performance for your human end users? What
about clustering and replication? This talk will provide you with
background knowledge to better answer those questions (and some
more). It is based on the scaling and tuning experience of many
companies with 10k+ Git repositories and users, dozens of servers,
terabytes of source code, and millions of fetch requests per day.

Every participant will get a Gerrit Performance Tuning Cheat Sheet
which summarizes the most important factors, gerrit.config options
and formula.

[Performance Tuning Cheat Sheet](http://bit.ly/1kmpO7V)

*Johannes Nicolai, CollabNet*

## 12:30 pm Lunch

Buffet served in breakout area.

## 1:30 pm Continuous Delivery in Big Data

BigData is now everywhere, from mobile media analytics, banking,
industry, avionics and even in medicine to monitor expansion of
epidemics.

We are showing how Code Review can be integrated with Continuous
Integration and Continuous Delivery  in a Big Data scenario that poses
new challenges to the existing Jenkins framework. We are going to
describe how we managed to implement our agile build and deployment
process working with distributed teams in BigData Software Development
Projects for media and financial organizations in London. The talk
will start with a presentation of our workflow and then will explain
how we leveraged Gerrit and Jenkins and how we integrated with Docker,
Mesos and the Hadoop ecosystem.

*Stefano Galarraga*, [GerritForge](http://www.gerritforge.com)

## 1:30 pm Monitoring Gerrit

*Stephen Williams, Qualcomm*

## 2:00 pm Prolog file-level whitelists

How I use Prolog to implement file-level whitelist and blacklist if
there are any interests. (I am a Prolog novice myself!)
[15 min]

*Kenny Ho, AMD*

## 2:30 pm Break and snack

Coffee and snacks served in breakout area.

## 3:00 pm Non-Prolog submit rules

You shall not pass – Control your code quality gates with a wizard.

For those of us who does not speak Prolog, there is an easier way
to configure your submit rules. The quality gate wizard lets you
to set up your submit rules in less than 3 minutes.

This presentation is about a gerrit plugin that provides an
alternative to writing submit rules in Prolog.

*Eryk Szymanski, CollabNet*

## 3:30 pm notedb: Code reviews in Git

*Dave Borowitz, Google*

## 4:00 pm Docker-ization of Gerrit

Packaging and Docker-ization for faster enterprise deployment.

*Luca Milanesio*, [GerritForge](http://www.gerritforge.com)

## 4:30 pm Jenkins & Gerrit

CloudBees has a fully integrated & Dockerized Gerrit/Jenkins
demonstration. This is based on the real-world use case of a mobile
development team using repo to manage multiple repositories in Gerrit.
It illustrates how Jenkins workflow can be tied into Gerrit processes
to simplify a complex review/build/test pipeline.

This builds on and uses the Dockerized Gerrit image that is being
presented by GerritForge, and I will discuss some of the challenges &
solutions, with an eye towards integrated solutions in Docker.

*Sam Van Oort, CloudBees, Inc.*

## 4:30 pm PolyGerrit: New Polymer UI

*Dave Borowitz, Google*
