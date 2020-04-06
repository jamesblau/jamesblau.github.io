---
layout: post
title: Week 1 at Metis
---

{{ page.title }}
================

<p class="meta">April 6th, 2020</p>

# Week 1 at Metis

I've just completed my first week at the [Metis](https://www.thisismetis.com/) data science bootcamp.

tl;dr: I'd recommend the program, based on my experience far! But stock up on coffee (if your supermarket even has anything in stock today).

The long version:

## Things That Should Have Been Obvious

### You will be very busy.

That's what "bootcamp" means, right? It was still surprising to put at least as many hours into week one as I put into a week of crunch time at college or at previous jobs.

Have you ever been so busy that you seriously consider presenting something like this?

![](images/commuter_ratios.png)
*oh no*

Of course, this is what I signed up for, and the hours are hardly being wasted. I'm learning things. And it's not like I'm missing any parties right about now.

## There Is Always Something You Don't Know About `git`

Everyone's `git` workflow is different. I got the Metis workflow wrong a couple of times.

One thing I'd never done before was to move a commit to a different branch. I never made a mistake that needed this fix, either because I wasn't *able* to (lacking permissions to push to the wrong branch) or because it didn't matter (I don't bother with branches in something simple like my dotfiles repo). The output of `git log --oneline --all --graph --decorate` in my fork looks like a four-dimensional dayglow mountain range. (And yes, I did copy that line from stackoverflow. I swear I took the time to learn at least half of those flags.)

I also had never run `git push --force` before. This was a good thing. I fear for my soul.

![](https://publicdomainvectors.org/photos/Prismatic-Floral-Motif-Silhouette-Vortex-No-Background.png)
*a typical git workflow*

## The Python Ecosystem Can Be Both Beautiful and Infuriating

Python can be a lovely language to use, and it's the standard tool in a number of situations. Using the most-used tools is usually wise.

Python idiomatically uses mutation. Python environments are not maintained solely within projects. Core libraries like `numpy` and `pandas` do things very differently compared to some other technologies I've used. I knew these things.

But still.

![](https://xkcd.com/353/)
*python: your first experience*

![](https://xkcd.com/353/)
*python: trying to do something serious after a decade of mostly using it only to casually install tools from source, `apt`, and three flavors of `pip`*

(Scientists expect that one day a blog post will be written about python without referencing xkcd, but the technology simply isn't there yet.)

## Data Exploration Never Gets Easier, or: The MTA Is Not Great at Doing Things

Week one saw us doing the only group project of the program, in which we analyzed NYC subway ridership data: swipes in and out of every turnstile in every station in the five boroughs. The goal was to recommend locations at which to place (imaginary) volunteers for an (imaginary) organization, who would accost commuters (you know the type) and invite them to an (imaginary) women-in-tech conference.

I've done fair amount of data-wrangling. I was still flabbergasted and bewildered to find the occasional run of swipe counts that steadily *decreased.* It is possible that the two-and-a-half-billion-dollars-per-mile cost of the Second Avenue Subway ([yes, really](https://www.nytimes.com/2017/12/28/nyregion/new-york-subway-construction-costs.html)) is due to the need to accomodate an increased number of time-travellers. That, or a jilted developer was very, very angry. Or...ghosts?

I'd like to give a shout-out to my partners Ethan and [Fong Wa](https://fw192020.github.io/), who did great work, shared the load equally, and kept me sane.

# Highlight of the week

Interrupting a group videoconference the evening before our presentation in order to solder my laptop's charger cable back into one piece.

![](images/good_dog_bad_shrink_wrapping.jpg)
*the output of a typical day of data science?*

# Stay tuned!
