---
layout: page
title: "Developer guides"
module: "4.5"
date: 2016-10-06 14:05:56
time: "5 min"
following: _articles/05-roadmapping.md
summary: "Documenting for developers and contributors of your project"
prereq: "Have completed all previous sections and modules"
materials: "Pen or pencil and paper"
---
### Documentation for developers
If your project is very straight forward and there is no or not much developer-specific information, it might not benefit from separate developer guides. However, if project becomes more complex you also should not forget about documentation specific for developers and potential contributors which help to onboard them on the technical aspects of your project. Especially if it requires an API (application programming interface [-> Wikipedia](https://en.wikipedia.org/wiki/API)) or other features which are only important to know if someone wants to develop the project further or modify it to their needs. It is important to keep this kind of documentation separate from the user guides to not accidentally scare off newcomer users.

The documentation for developers/contributors should contain:
- detailed description of how your project was/is developed (e.g. which CAD software you are using)
- current state of development
  - open tasks (including priorities)
  - tasks currently worked on
- documentation/references for programming interfaces and libraries (e.g. API)
- contribution guidelines (discussed later in section [7.1 "Managing Contributions"](link))

### Formats
Developers of your project need access to the original design (source) files like SVG, ODS, MD, TXT, CSV. Unfortunately CAD software often it's own source file format. Share it nevertheless but try and use open CAD programs like [OpenSCAD](https://openscad.org/), [FreeCAD](https://www.freecadweb.org/), [KiCAD](https://www.kicad.org/).

### {{ site.assignment }} Write documentation for developers (if it makes sense for your project)

### Resources
