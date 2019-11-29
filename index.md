---
layout: default
---

# Hello!

Welcome to my project summary page for Google Season of Docs. This was an exciting experience that came along with many firsts:

* my first time contributing to open-source software (see https://github.com/aces/Loris)
* my first time using Github desktop
* my first time revisiting my undergraduate science degree since... udergrad
* my first time working in an academic research setting
* I was also the first professional technical writer to ever work on this team! 

It felt great to dive back into the world of academia and neuroscience after working in (mostly) tech startups for the past few years. My mentor, Christine Rogers, was very devoted to making this journey productive and organized, but also fun! Christine - thank you for showing me the ropes and being such a wonderful teacher in this. I was super happy to meet the rest of the LORIS team as well, and loved visiting their offices at the university dearest to my heart, McGill.

For GSoD, the details of my contributions are as follows!

## Organization
[INCF:](https://www.incf.org/) International Neuroinformatics Coordinating Facility

## Project Title
Simplifying LORIS how-to guides, tutorials, and workflow documentation

## What is LORIS?

[LORIS](http://loris.ca/) (Longitudinal Online Research and Imaging System) is an open neuroscience research data platform used by multi-site, longitudinal neuroscience studies around the world. Its [web-facing front-end](http://demo.loris.ca/) provides researchers with powerful customizable tools to handle, curate, visualize and export any format of data within a single platform.

## Project Overview

My technical writing specialty lies in turning complex ideas into accessible plain language. With LORIS being a robust software used in the orderly world of scientific research, this was a fun challenge! My ultimate goal was to make LORIS documentation that was helpful to its users, and possibly a little bit lighter than their typical reading material :)

## Deliverables

(Detailed descriptions to follow)

1. Total rewrite of all user-facing help text in LORIS
2. A comprehensive user guide for navigating LORIS
3. An internal onboarding document for new LORIS members
4. A Github Desktop guide for beginners
5. Style Guides for future reference
6. High-level online presentations about LORIS (done in Reveal.js)
7. Additional Tasks

### 1. Help Text Rewrite

In LORIS, every module and some additional pages have their own help content displayed as a beacon on the page. Users click a question mark to reveal Help text, which includes an overview and context of the page, along with instructions on how to use the features of that page.

There were around 40 pieces of help text to work on. Some of these were new modules, so I created the text from scratch. For the most part, however, I rewrote existing help text to make it more accessible and user-friendly.

This work is stored in [this GitHub issue](https://github.com/aces/Loris/issues/5576) - see all associated PRs.

### 2. LORIS User Guide

I created a comprehensive 40+ page document that describes a suggested workflow for using LORIS, along with detailed explanations on its every feature and function and associated screenshots. This can be helpful to users that need more context to supplement the in-site help text. In addition, it will be sent to potential research leads that want to learn more about LORIS' capabilities and interface.

[Take a look](https://docs.google.com/document/d/10zhryhdG0NX1ov65AypfxgcGXTp_FwDaPI1i6tkqkDg/edit?usp=sharing)

### 3. Internal Onboarding Document

Joining the LORIS team was a bit overwhelming due to the volume of information I needed to learn so quickly! They have a thorough onboarding guide for most people that join the team—most of them being developers or other technical roles. However, my non-technical background required something less... technica. So, I decided to compile existing resources into one helpful document for new non-technical members that join LORIS in the future. It's called the LORIS Brief.

[Take a look](https://docs.google.com/document/d/1MUDxILP5uU95wsycSWtLqTE4c5pI2oxXbE5Aoshgs-w/edit?usp=sharing)

### 4. Github Desktop 101

Upon joining the LORIS project, my Github exposure was minimal. I had used github.com to upload files, but that was pretty much it. My biggest challenge during this experience was learning how to use Github desktop (I couldn't use github.com due to the complex branching system used by the LORIS repo). With help from my mentors, along with endless forum-foraging, I put together a step-by-step guide on using Github Desktop with LORIS.

[Take a look](https://docs.google.com/document/d/1jYvOCl-0fnQ1tjhTsJFT9R3MXE4d0GjmIuPtT3A7wfk/edit?usp=sharing)

### 5. Updated LORIS Presentations

The LORIS team hosts a suite of informative presentations built in Reveal.js. These were designed to be presented in-person, but the team wanted them to live online, as high-level guides to LORIS, for anyone to access and learn from. I contextualized, re-organized, and re-formatted the content to be more user-friendly for this purpose. I revamped five of these presentations in total (in the link below, I worked on all except for *Big Brain* and *BrainBrowser*.

You can find these presentations [here](http://samirdas.github.io/#/)

### 6. Style Guides

I created a couple style guides for the team's future reference based on the documentation changes I made. One was a detailed guide for creating and updating the user-facing help text in LORIS. This guide includes guidelines on grammar and tone, markdown styles accepted in LORIS, and how to name/upload files into the LORIS repository. 

[Take a look](https://docs.google.com/document/d/1bbEf9nMBzd-8W3qHs47jAu3JDgvUrL_45F7-Y7A-xPY/edit?usp=sharing)

I also created a simple style guide for the html presentations, which exists as a README.md file in the presentation repo.

[Take a look](https://github.com/samirdas/samirdas.github.io)

### 7. And then...

I have a couple ad-hoc contributions worth mentioning.

##### The LORIS-dev Archives

My first task upon joining the LORIS team was to go through ["the LORIS mail"](https://mailman.bic.mni.mcgill.ca/pipermail/loris-dev/) and categorize emails based on type. The goal was to provide the team with some data surrounding development questions and issues, so they can prioritize updates and support.

##### Module Specifications

In the LORIS codebase, each module has a README so developers know its purpose, how it functions, its configuration, and more. Most of these READMEs were complete, except for a few. Through internal research and exploration of the platform, I created a README file for modules that didn't have it.

##### Flagged a Release-Critical Bug

I noticed a bug in the same week as a new release - tada! [Check it out here.](https://github.com/aces/Loris/issues/5676)

### THANK YOU TO GOOGLE AND LORIS FOR THIS VALUABLE GSOD EXPERIENCE! I'M STILL SMILING! 

![Profile](/images/me.jpg# profile bordered)
