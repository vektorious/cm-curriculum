---
layout: page
title: "Findability standards"
module: "6.4"
date: 2016-10-06 14:05:56
time: "20 min"
following: _articles/07-community-and-communication.md
summary: "How to help others find your project"
prereq: "Have completed all previous sections and modules"
materials: "Pen or pencil and paper"
---
<p align="center">
<img src="https://raw.githubusercontent.com/ohwmakers/OHM-curriculum/gh-pages/img/work_in_progress_banner.svg" width="80%"/>
</p>

* TOC
{:toc}

### Contents

#### Open hardware growth and multiple platforms/formats

While starting your project and considering how to place it online, you probably realised that there is a large number of platforms available, that are specialised for sharing hardware projects. While this is great, since they each have their own particularities and are tuned to a certain audience, which makes it so that there is a place for all projects out there, it also generates the problem that it becomes hard to know where to deposit your project, and also where to find them.

Here are some examples of different current platforms:


##### **(note from Andre: not sure if this is interesting in this format, but if it is, needs to be expanded)**


|Paltform|main interest|note|
|--|--|--|
|thingiverse.com|3D printing|allows users to share design files for parts that can be 3D printed|
|hackaday.io|hardware in general|allows users to share design files for complete projects, no matter how simple or complex they are|
|NHS 3D print exchange|3D printing| focused on medical/research/educational models|
|Instructables.com|Instructions in general (for building hardware or not)|freemium model|
|Wikifactory|||
|Wikifab|||
|GitHub|||
|GitLab|||





#### The need for findability standards

As the readers can see from the previous section, there is a large number of platforms available for sharing. While great for diversity and "consumer choice" this also creates an issue with findability. 

That is, how can we make sure we have searched everywhere for a project before we start something from scratch, and also, how can we make sure our project will be found by others? We tend to think that simply having a "google" for things will give us a pretty good overview of what is available, but this often times leads to projects being missed altogether, since sometimes they do not show in the first page of google. 

Also, relying on Google for this is problematic from another stand point, where we do not know what kind of algorithms are being used to bring up results, and we become dependent on this "black box" that might as well be gone tomorrow for whatever reason.

Luckly there are people working on solving this issue. Most prominent currently (as of 22/04/2021) is the [OpenKnowHow project](https://www.openknowhow.org/), which has organised a gathering with different networks working on open hardware so that they could collaboratively create and implement an [Open Hardware Standard](https://app.standardsrepo.com/MakerNetAlliance/OpenKnowHow/wiki), that is, among other things taking care of making OSH easier to find (see section below for more details).

#### OpenKnowHow project and derivatives, and how to implement it

The Open KnowHow project has created a system that allows projects to be found, no matter in which platform they are hosted, while giving developers the opportunity to add interesting meta-data to their projects, increasing the chances of people understanding at which stage the project is, if it has been replicated by people other than the developers, if it has documentation in more than one language etc. 

This meta data and increase findability are achieved when a small standardized text file (in YAML format) is created: It should contain contain links to where documentation is hosted, whether or not the project has been reproduced by a third party, what kind of tools are needed to build that specific project, if the documentation is available in different languages, if the work is a derivative of another project, keywords for the project, etc. 

Once a project has this file, a webcrawler finds and indexes it in a [searchable repository](https://search.openknowhow.org/) which serves as a unifying place for all the projects that live in many different platforms.

##### Note from Andre: Check details about the OpenHardwareObservatory and add it accordingly


### {{ site.assignment }} Add an open know how manifesto to your project

- Follow [these instructions](https://app.standardsrepo.com/MakerNetAlliance/OpenKnowHow/wiki) to create a .yml file to include your project in [openknowhow.org](https://openknowhow.org) (You can use [this online form](https://okh.makernet.org/form) to create the .yml file)

### Resources
- [Open Know-How manifest](https://app.standardsrepo.com/MakerNetAlliance/OpenKnowHow/src/branch/master/1)
- [Open Know-How searchable database](https://search.openknowhow.org/)
