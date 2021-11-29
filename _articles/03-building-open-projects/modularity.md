---
layout: page
title: "Modularity"
module: "3.2"
date: 2016-10-06 14:05:56
#time: "20 min"
following: _articles/03-building-open-projects/minimal-viable.md
summary: "A way to facilitate your work, contributions and repairability"
#prereq: "Have completed all previous sections and modules"
#materials: "Pen or pencil and paper"
---
<p align="center">
<img src="https://raw.githubusercontent.com/ohwmakers/OHM-curriculum/gh-pages/img/work_in_progress_banner.svg" width="80%"/>
</p>
* TOC
{:toc}

### Why is modularity useful?

When developing projects in the open, it is really useful to see what is available out there and how it could be incorporated in a project to save time and effort. In other words, if someone for example has already created a good system to measure temperature, there is quite often no point in starting from scratch and develop the same system again. More effective would be to replicate the already existing temperature measuring system and adapt it (where necessary) to the project's needs.

### Reusability :rocket:

To make this re-use/replicability possible, projects need to be developed with modularity in mind. That means, could this example (temperature sensor) be developed in a way that its documentation and building are done in a modular way? In documentation this would mean highlighting the exact components in the system that are responsible for temperature sensing, and how it communicates with the rest of the system. This way if another project wants to use just that, it can easily find out what parts are needed and how it can be implemented somewhere else.

Modularity is also useful within the project, as a certain module can be used more than one time in different parts of the system.

In short, once a module has been developed, it can be used by other projects (which increases the chances of that module being improved/supported over time), again in the same project and over time, in different projects by the same developers. Last but not least, this also helps with sorting components, as different projects with the same modules will require similar components.



### Examples and use cases

One good example of modularity comes from the world of hobby electronics, where companies sell "breakout boards". This little boards, normally contain all the components necessary to perform a specific function. For example, you could buy an [DC motor/Stepper motor controller](https://www.adafruit.com/product/2927), learn how to use it to control the axis on a 3D printer, but later on use the same module to control the motor that drives the wheels in a toy car.

### {{ site.assignment }} Review your project in terms of modularity

### Resources
- [modular design wikipedia](https://en.wikipedia.org/wiki/Modular_design)
- [modular hardware explained](https://resources.pcb.cadence.com/blog/2020-what-is-modular-hardware)
- [modular design for embbeded systems](https://www.toradex.com/blog/introducing-modularity-in-embedded-design?gclid=CjwKCAjwsNiIBhBdEiwAJK4khqsUEicW8ThJyKv_fBBH9KH4BTQRXG184uIM-_eKS0qxsCrQ5usCRRoCHwUQAvD_BwE)