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
* TOC
{:toc}


### Digital fabrication

"Digital modeling and fabrication is a design and production process that combines 3D modeling or computing-aided design (CAD) with additive and subtractive manufacturing." ([Wikipedia](https://en.wikipedia.org/wiki/Digital_modeling_and_fabrication)). With the rise of affordable additive and subtractive manufacturing machines like 3D-printers and CNC-mills, also non-commercial users were able to turn their garage, basement, backyard into a small factory to develop and produce hardware. Since most of the hardware design is done digitally it has become very easy to share builds online and thus enables distributed collaboration. Right?

Well, not so much. There are many different source and export file formats out there and compatibility is not very high. A short example: You find a great design for a 3D-printed cup holder but it just does not fit your cup. It is an open source project and want to contribute to it by creating a version which is compatible to types of cups. How easily this can be done depends on the kind of files which were shared. With the original CAD files from e.g. FreeCAD or Blender it's just a matter of seconds to change some parameters to make it compatible. However, if just the .stl file is shared, you are lucky if you can easily import in your CAD program without any error.

There is a difference between source and export formats. Be sure to know the differences and share both.
- *Export formats* are for example STP, STL or PDF. They often can be read/interpreted by different systems and are sufficient to produce the design. However, they are usually not easily editable and just contain a snapshot of the final design.
- *Source files* are your original design files like SVG, ODS. Unfortunately CAD software has it's own source file format. Share it nevertheless but try and use open CAD programs like [OpenSCAD](https://openscad.org/), [FreeCAD](https://www.freecadweb.org/), [KiCAD](https://www.kicad.org/).

Keep in mind where to share which file formats. While users might be fine with export formats, developers definitely need the source files to be able to work on the hardware design. For larger projects it might make sense to share them separately and reference them in the respective documentation. You will learn more about user and developer guides in the next sections.

### Proprietary vs. Open Source CAD

It's always a question of how far you want to go, but a "true" open source project should also use open parts, tools and software so every step and part can be understood, recreated and customized. We don't want to discuss here whether projects using a Raspberry Pi can ever be open source, but make you aware of this issue.

[KiCAD](https://www.kicad.org/) is an free and open source CAD tool for designing electronics and is widely used even outside the open source community. It breakthrough began when CERN started to invest the money they would have spent for software licenses into the development into this open source alternative. [KiCAD](https://www.kicad.org/) now is a match for proprietary electronics CAD software like Autodesks Eagle. But why are such commercial solutions actually a problem?

Well, foremost because of the format lock-in and the risk of a license change. Take Autodesks Fusion 360 as an example. It is a great CAD software for 3D-modelling and much more, which is reasonable easy to use. It had a license option for non-commercial users with access to almost all regular features. Fusion 360 was widely used in the open source community and a lot of extensions and plugins were developed by the community. However, sharing (easily editable) files outside the Fusion universe was not possible but this was no problem because almost everybody could just use the software. Then, in lated 2020, Autodesk announced a major license change ([hackaday article](https://hackaday.com/2020/09/16/autodesk-announces-major-changes-to-fusion-360-personal-use-license-terms/)) which cut back a lot of features of the non-commercial license, locked out many users and caused a uproar in the community.

Every bad thing has something good to it. Because of this action of Autodesk, [FreeCAD](https://www.freecadweb.org/), a free and open source alternative to Fusion 360, got a lot of attention and support. Now some developers of FreeCAD are payed for their work and the software is heavily improving in regards to usability and features. It is still some steps away to match Fusion 360 in all respects (as for today, in late 2021) but it will get there.

You can support the development and spread of free and open source CAD software simply by using it. Try to be open for learning new tools and give them a new chance from time to time.


### {{ site.assignment }} Improve your documentation 
- Revisit your documentation and take a look at the files formats you share, adjust if needed

### Resources
- [GOSH Forum Discussion "Open Source CAD and Open Science"](https://forum.openhardware.science/t/open-source-cad-and-open-science/2991/)
- [GOSH Forum Collection "Tested and tried Open Source tools for academic research"](https://forum.openhardware.science/t/tested-and-tried-open-source-tools-for-academic-research/3046)
**Guides:**
- [Digital fabrication 101](https://formlabs.com/uk/blog/digital-fabrication-101/)
- [CNC machining](https://get-it-made.co.uk/guides/cnc-machining-guide/)
- [3D printing](https://3dprintingindustry.com/3d-printing-basics-free-beginners-guide)
- [Laser Cutting](https://makerdesignlab.com/tutorials-tips/laser-cutting-beginners-guide/)
