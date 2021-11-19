---
layout: page
title: "Open Hardware licenses"
module: "6.2"
date: 2016-10-06 14:05:56
time: "20 min"
following: _articles/06-licenses-and-standards/oh-standards.md
summary: "Learn about the available options and their differences"
prereq: "Have completed all previous sections and modules"
materials: "Pen or pencil and paper"
---
<p align="center">
<img src="https://raw.githubusercontent.com/ohwmakers/OHM-curriculum/gh-pages/img/work_in_progress_banner.svg" width="80%"/>
</p>
* TOC
{:toc}



### Hardware licenses available (TAPR OHL, Solderpad, CERN-OH)

Similar to open software licenses, developers have the opportunity of choosing from more than one available license. At the moment, there are three main hardware licenses available:
- [TAPR OHL](https://tapr.org/the-tapr-open-hardware-license/) - similar to GNU GPL license
- [Solderpad](http://solderpad.org/) - similar to Apache license
- [CERN-OH](https://ohwr.org/cernohl) - the most recent version (v2.0) has three variants: 
  - A strongly-reciprocal variant, [CERN-OHL-S](https://ohwr.org/cern_ohl_s_v2.pdf)
  - A weakly-reciprocal variant, [CERN-OHL-W](https://ohwr.org/cern_ohl_w_v2.pdf)
  - A permissive variant, [CERN-OHL-P](https://ohwr.org/cern_ohl_p_v2.pdf)

Each of the CERN variants try give users options in terms of how derivatives of their projects should be re-shared. For example, the CERN-OHL-S requires derivative projects to be reshared under the same license. This is similar to Copyleft licenses, such as GNU GPL 3.0 and Creative Commons "share alike".

Another main difference between these licenses is when their last version and revision came out, with the CERN v2.0 being the most recently reviewed (as of 12/Nov./2021). 

### Examples of projects using different licenses

To give you a better idea of how different licenses are used in the existing projects, please have a look at these examples:

- [OpenFlexure delta stage](https://gitlab.com/openflexure/openflexure-delta-stage).
- [LED Zappelin'](https://github.com/BadenLab/LED-Zappelin)

Another good source for projects that are properly licensed and documented can be found on the [OSHWA repository](https://certification.oshwa.org/list.html), where all listed projects have been checked by OSHWA and conform with their definition of open source hardware (OSHWA and its certification program will be covered in the "standards" unit in this module).

### {{ site.assignment }} Choose licenses for your project
- Choose a license or several licenses depending on the types of content you are providing.
  - Remember a hardware project normally needs at least 3 licenses (hardware itself, software that accompanies the project, project documentation).
- If you are using parts of other projects with licenses check if you are attributing them correctly and also that the licenses you chose for your project do not conflict with the licenses from the other projects you are remixing.

### Resources
- ‘Licensing open source hardware’ by Michael Weinberg, in “Building open source hardware”
- https://choosealicense.com/
- ['Does your open hardware project need a license'](https://opensource.com/law/15/2/intro-open-hardware-licensing)
- https://ufal.github.io/public-license-selector/
- https://www.gnu.org/licenses/license-recommendations.en.html
