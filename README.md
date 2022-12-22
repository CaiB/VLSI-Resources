# VLSI Resources
Papers, videos, textbooks, documentation, and anything else that I find useful for VLSI folks. The first section lists general resources, the second is details about specific problems and implementations.

Essentially, anything to get you to see this more often:
```
 _   _
 *   *
   |
 \___/
```

## YouTube Channels
**Ben Eater**  
High-level digital design information, along with use of old CPUs  
https://www.youtube.com/@BenEater

**Sam Zeloof**  
DIY Photolithography and at-home basic silicon chip manufacturing  
https://www.youtube.com/@SamZeloof

**TechTechPotato**  
General discussion about the industry and end products  
https://www.youtube.com/@TechTechPotato

**Analog Layout & Design**  
Lectures about various aspects of analogue IC design and layout  
https://www.youtube.com/channel/UCBVINEwQ_dba3FaatbXVAug

**Jin-Lien Lin**  
RISC-V  
https://www.youtube.com/@jinl2


## Scientific Journals
**IEEE Open Journal of the Solid-State Circuits Society**  
Open-Access IEEE Journal related to IC design https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=8782712


## Blogs
**Chips and Cheese**  
Highly detailed articles, often about modern CPU and GPU architectures and their performance characteristics  
https://chipsandcheese.com/

**Ken Shirriff's Blog**  
Articles mostly about early CPUs and other ICs  
https://www.righto.com/


## Past Events
**OpenTapeOut** - November 2021  
Day 1 VOD: https://www.youtube.com/watch?v=wvPZREaP7E0  
Day 2 VOD: https://www.youtube.com/watch?v=sunruF6ryso



# Specific Problems/Implementations
## Digital Oversampling / Clock Recovery
https://docs.xilinx.com/v/u/en-US/xapp1294-4x-oversampling-async-dru
https://ieeexplore.ieee.org/document/5657866
https://past.date-conference.com/proceedings-archive/2010/DATE10/PDFFILES/IP2_04.PDF


## Abusing FPGA Device Characteristics
Quite possibly the most interesting paper I've ever read  
https://github.com/CaiB/VLSI-Resources/blob/main/Papers/10.1.1.50.9691.pdf


## GDSII Format Specifications
**V6**  
https://github.com/CaiB/GDStoSVG/blob/master/References/GDS_II_Stream_Format_Manual_6.0_Feb87.pdf

**V7**  
https://github.com/CaiB/GDStoSVG/blob/master/References/GDSII%20v7%20Specification.PDF  
Almost the same as V6, just with some limitations removed:
- polygons can have more than 200 points
- more than 64 layers and datatypes are supported
- more than 10 levels of hierarchy are supported


## MP3 Encoding/Decoding
Mostly software-focused, but also with explanations of the format standard and some hardware information  
http://www.mp3-tech.org/

## Quartus Timing Analysis
Setup of constraints and analysis in Intel Quartus  
https://github.com/CaiB/VLSI-Resources/blob/main/Documentation/mnl_timequest_cookbook-683081-666281.pdf  
Originally downloaded from https://cdrdv2-public.intel.com/666281/mnl_timequest_cookbook-683081-666281.pdf