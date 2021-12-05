---
layout: page
title: "Developer guides"
module: "4.5"
date: 2016-10-06 14:05:56
#time: "20 min"
following: _articles/05-roadmapping.md
summary: "Documenting for developers and contributors of your project"
#prereq: "Have completed all previous sections and modules"
#materials: "Pen or pencil and paper"
---
### Documentation for developers
If your project is very straight forward and there is no or not much developer-specific information, it might not benefit from separate developer guides. However, if project becomes more complex you also should not forget about documentation specific for developers and potential contributors which help to onboard them on the technical aspects of your project. Especially if it requires an API (application programming interface [-> Wikipedia](https://en.wikipedia.org/wiki/API)) or other features which are only important to know if someone wants to develop the project further or modify it to their needs. It is important to keep this kind of documentation separate from the user guides to not accidentally scare off newcomer users.

The documentation for developers/contributors should contain:
- detailed description of how your project was/is developed (e.g. which CAD software you are using)
- current state of development
  - open tasks (including priorities)
  - tasks currently worked on
- documentation/references for programming interfaces and libraries (e.g. API)
- contribution guidelines

### Formats
Developers of your project need access to the original design (source) files like SVG, ODS, MD, TXT, CSV. Unfortunately CAD software often it's own source file format. Share it nevertheless but try and use open CAD programs like [OpenSCAD](https://openscad.org/), [FreeCAD](https://www.freecadweb.org/), [KiCAD](https://www.kicad.org/).

### Contribution guidelines
The contribution guidelines should contain instructions on how to contribute to your project. The following instructions for writing great guidelines for contribution are based on the [Mozilla Open Leadership Training Series](https://mozilla.github.io/open-leadership-training-series/) with minimal edits.

The following elements should appear in your guidelines. If you don't know the details right now, it's OK to write "more details coming soon!" for that section. Remember, you'll often return to this document to update it as your project evolves.

1.  Restate your project vision, in one sentence. Redundancy is your friend!
2.  Welcome contributors to the project: Let them know that you are eager for contributions and happy that they've come. This is a great place to introduce yourself so people see that there's a name and face that goes with this project.
3.  Point people to your Code of Conduct for the project, and require users to read it before they go any further.
4.  List Important Resources where contributors can see what kind of work is currently happening on the project.
6.  List Communication Channels: if you are using forums, chat clients, email lists or other ways of communicating about the project, list those here and provide instructions on how to join. (more on this in section 7, don't worry if you don't have this all figured out yet)
7.  Tell readers how to submit changes: This is the process for adding your work or changes to the repository or collection of ongoing work
8.  Point out which parts of the project still need some work or which task have not been completed yet. It's a good practice to highlight easy tasks as a starter for new contributors.
9.  Tell readers how to report a bug: Ask your contributors to stay on the lookout for can any potential issue that might cause problems for the project. These could be problems in code , content omissions or copy errors, or any issues with the functionality or design of your project. Basically, by asking users to report bugs, you're asking for feedback on work that's been done. Most projects invite all contributors to tell the project lead about bugs, so "debugging" or fixing problems happens quickly and with the input of the community. Take a look at [Atom's example](https://github.com/atom/atom/blob/master/CONTRIBUTING.md#reporting-bugs) for how to teach people to report bugs to your project.
10. Tell developers about your recognition model - Remember, you need to acknowledge value of the time and work your volunteers give your project. Here, provide a pre-emptive "thank you" for interest contributing. List any recognition contributors might receive for participating in your project. You can also outline how contributors can "level up" to become project maintainers (a certain number of bugs resolved, a certain number of changes or contributions successfully submitted to the project). You can leave this blank for now, and fill it in later.
11. Let developers know where to go for help - provide clear contact info, and outline the process for getting in touch, for anyone with questions.

    Optional Elements:

12.  Templates: You might want to link to templates, which contributors can copy and add context to; templates help guide contributors on what information to include, and how.
13.  Info on how to request an "enhancement" - enhancements are features that contributors suggest for a project, but aren't necessarily bugs/problems with the existing work. Enhancements have not the same priority as a bug or current task, but are important as the community helps guide the project's design and evolution. See [Atom's example section](https://github.com/atom/atom/blob/master/CONTRIBUTING.md#suggesting-enhancements).
14.  Style Guide / Coding conventions - If your project includes a lot of code, it might be important to designate how a specific style.
15.  Who is involved? You might want to list the core contributors and their preferred methods of contact.

### {{ site.assignment }} Write documentation for developers (if it makes sense for your project)

Write up your contribution guideline. It is OK to leave some things empty for now. We will discuss a few of them again in detail in other sections.

### Resources
- https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors
- https://opensource.creativecommons.org/contributing-code/
- https://opensource.com/life/16/3/contributor-guidelines-template-and-tips