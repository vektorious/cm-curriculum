---
layout: page
title: "Digital fabrication & electronics"
module: "4.3"
date: 2016-10-06 14:05:56
time: "5 min"
following: _articles/04-open-hardware-specifics/user-guide.md
summary: "Best practices for different fabrication methods & materials"
prereq: "Have completed all previous sections and modules"
materials: "Pen or pencil and paper"
---
<p align="center">
<img src="https://raw.githubusercontent.com/ohwmakers/OHM-curriculum/gh-pages/img/work_in_progress_banner.svg" width="80%"/>
</p>
* TOC
{:toc}


### Digital fabrication

"Digital modeling and fabrication is a design and production process that combines 3D modeling or computing-aided design (CAD) with additive and subtractive manufacturing." ([Wikipedia](https://en.wikipedia.org/wiki/Digital_modeling_and_fabrication)). With the rise of affordable additive and subtractive manufacturing machines like 3D-printers and CNC-mills, also non-commercial users were able to turn their garage, basement, backyard into a small factory to develop and produce hardware. Since most of the hardware design is done digitally it has become very easy to share builds online and thus enables distributed collaboration. Right?

Well, not so much. There are many different source and export file formats out there and compatibility is not very high. A short example: You find a great design for a 3D-printed cup holder but it just does not fit your cup. It is an open source project and want to contribute to it by creating a version which is compatible to types of cups. How easily this can be done depends on the kind of files which were shared. With the original CAD files from e.g. FreeCAD or Blender it's just a matter of seconds to change some parameters to make it compatible. However, if just the .stl file is shared, you are lucky if you can easily import in your CAD program without any error.

There is a difference between source and export formats. Be sure to know the differences and share both.
- *Export formats* are for example STP, STL or PDF. They often can be read/interpreted by different systems and are sufficient to produce the design. However, they are usually not easily editable and just contain a snapshot of the final design.
- *Source files* are your original design files like SVG, ODS. Unfortunately CAD software has it's own source file format. Share it nevertheless but try and use open CAD programs like FreeCAD or KiCAD.

Keep in mind where to share which file formats. While users might be fine with export formats, developers definitely need the source files to be able to work on the hardware design. For larger projects it might make sense to share them separately and reference them in the respective documentation. You will learn more about user and developer guides in the next sections.

### {{ site.assignment }} Revisit your contribution guidelines and files format, adjust if needed

### Resources
