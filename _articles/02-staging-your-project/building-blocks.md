---
layout: page
title: "Building Blocks overview"
module: "2.3"
date: 2016-10-06 14:05:56
#time: "20 min"
following: _articles/02-staging-your-project/first-impressions.md
summary: "An overview of the constitutive elements of an open hardware project"
#prereq: "Have completed all previous sections and modules"
#materials: "Pen or pencil and paper"
---

* TOC
{:toc}

If you made it here, you have a broad idea about what open hardware is, a brief context of how the community emerged, different options for open hardware projects. You also had some time to think on the goals and scope of your work, if you are making a derivative or creating original designs, and you probably have a rough draft of the open hardware canvas. Congratulations!

In this submodule we are seeking to understand which are the basic elements that constitute an open hardware project, and give a brief overview of each of them.

### The minimum you need to get there

While you may have ideas or plans for an extended, enhanced version of your project– for example you may want to eventually expand from successfully measuring noise levels to having a fancy dashboard for users to visualize data– it’s always best to start small first. This way, you can test out the project and ensure the idea works before you spend lots of time and resources expanding it. If you find your project is too complex to fit into the Open Hardware Canvas model, it may be that you’re trying to do too much, and need to narrow your scope.

Depending on the type of approach you are taking, the first steps will vary. If you are creating original designs, you will probably want to make a proof of concept first - can your idea be achieved? Usually when you make a derivative you know the main concept works and you are looking to improve it, so you go directly to the next step, prototyping.

**Prototyping** is an incredibly valuable exercise that allows you to visualize how the project will function. The ability to quickly and easily prototype an idea is one of the drivers behind the incredible number of open hardware projects we see today. You will learn more about it in modules 3 and 4.

Think of the necessary materials and steps you need to follow, to achieve that minimum piece of work that satisfies the goal you defined in the previous module.

### The minimum you need to make it open

The prototype will allow you to test how your idea could be developed and worked. But which are the minimum requirements for your project to be **open**?

- **An overview/front page**: A description in plain language of what your project does and how to get involved, before getting too technical.

- **Original design files**: the necessary files anyone would need to modify your project, the heart of open hardware! Ideally, your open-source hardware project would be designed using a free and open-source software application (more on this in following sections). This includes, for example, 2D drawings or computer-aided design files (CAD), 3D designs, circuit board designs (schematics, layouts), component libraries. Exports are OK for helping visualization, but you have to share your files in **editable formats** so people can modify them.

- **Bill of materials**: a list of necessary items to build your project, as detailed as possible, and whenever you can, indicating alternatives for parts that are difficult to source.

- **Software and firmware**: if your project needs code to run, include the source, dependencies, version and state (stable or not?).

- **Instructions**: Your project documentation will have to include instructions for users, but also for contributors who want to build/tweak it. Including a design rationale helps contributors understand why you chose to do things in a certain way. More robust documentation makes it easier for downstream users to build, use, and iterate on your project. Best projects include documentation in multiple formats (pictures, videos), tutorials, and translations.

- **Licenses**: Properly applying an open source hardware license to your project ensures that downstream users can use it. Licensing hardware is more complicated than licensing software, as hardware projects usually include hardware plus software, documentation, branding. Each different component requires a different type of license.


### {{ site.assignment }} Reviewing the canvas

- Go back to your canvas, review what you wrote, see if you can put more detail into any of the boxes.
- Do you already have ideas for prototypes? Document your drafts! Taking pictures of drawings is a great way to do it.

### Resources
* [Overview of the Various Types of Hardware Prototypes](https://www.hackster.io/news/overview-of-the-various-types-of-hardware-prototypes-60d33d92e3a3)
* [OSHWA - Best practices for Open source Hardware 1.0](https://www.oshwa.org/sharing-best-practices/)
