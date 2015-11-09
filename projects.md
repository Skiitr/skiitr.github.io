---
title: Projects
weight: 4
layout: default
---

A small sample of projects I've been involved with over the years by category...

## Printed Circuit Board Layout 

### Certified Avionics GPS / Nav / Com Systems
Developed and maintained all 14 board designs for an avionics GPS/NAV/COM systems. The system includes front and backplane boards, display and button boards, 16W VHF radio boards as well as I/O and computational boards. Board technologies involved include high-speed digital, RF (VHF band), differential pairs, up to 17 layer boards, blind and epoxy filled cap plated vias. Designs required jigsaw fitting of PCBs into one another due to limited space. The project was successful though very close integration of the mechanical and electrical teams due to aggressive packaging.

### Data Processor for Flying Projectile Sensor
The requirements for this board design were a very small tight package that could fit in a flying sensor that contained extremely sensitive RF circuitry as well as a vast number of high-speed digital circuitry for data processing. Board contained two 100+ pin quad flat pack chips followed by an array of four 300+ pin BGAs. The technology of the board was in the 4mil trace and 4mil space range and contained 12 layers of which two were power planes, four ground planes and 6 were routing layers. The board was done without isolating ground planes and was successful at keeping all high-speed switching noise from the large amount of RF circuitry and vice versa. Each BGA had over 200 data connections and the board was hand routed for optimal efficiency of particular critical data lines. Board design functioned to specification on the first spin of the design.

### WiFi Bluetooth Module
Requirements for this project were to create a very small SMT level board module that contained a WiFi and Bluetooth chipset, integrated power supply and dual band chip antenna. This board was sized at about 2 x 0.75 inches and had a sizeable 0.5mm pitch BGA as the main chip on the board. This drove technology down to 3mil trace and 3mil spaces, as well as blind and buried vias for BGA breakout. This board design was on a 0.063-inch thick board so the layer count needed to be as low as possible. This was all hand routed and critical care was taken to avoid any possible noise issue within the layout of the traces between layers. This product was successfully created and used by and end customer in the medical equipment field.

{::comment}
### LMCO Amp boards
Description of project C and the challenges associated.

### Sea whip PCB Design
Description of project E and the challenges associated.
{:/comment}

<hr />

## Mechanical Engineering

### Low Loss Space Qualified Pre-filtered GPS LNA
This project was challenging due to the space qualification of the product. Everything on the design had to be designed to the highest standards. With soldered in tunable resonators for the cavity filter, custom transition tough a discrete low pass filter and finally going through a very low loss LNA, this project presented a muti-dimensional mechanical challenge. The final challenge of this project was that all qualification testing was required on every unit produced and the design passed all testing requirements.

### 30-512 MHz VHF / UHF 20W TX/RX Amplifier with Switched Filter Bank
Project difficulties presented here was a tight mechanical outline with many fixed ports for both the VHF in and out, UHF in and out, and GPS receive channel. The approach taken here was a 4 mezzanine layered structure with different circuits top and bottom sides of each layer. The design was built as individual levels and assembled together with flex circuit cables and flexible RF connections. A low-frequency discrete switched filter bank became the largest challenge to both fit in the design as well as connect the receive and transmit paths of the amplifiers. Placing one power amplifier on top of another presented a significant thermal challenge that was overcome through finite element analysis and experimentation. The design of the project was finished and the contract never went into production due to funding falling through for the end customer. 

### Avionics Front Panel Integration
Project involved working with two separate partner companies to customize two pieces of avionics equipment, an audio panel and transponder to match the company standards. During this process, it was required to create and design guide for a uniform style throughout each of five products currently under development as well as coordinate these developments to each of the partner companies we were working with. I was the principle engineer of these two products internally and worked closely with partner companies to ensure all specification were met to keep a standard look and feel to the products. The mechanical design required designing a usable customer interface with both backlit buttons and LCD display. These products were successfully developed internally and produced by our partner companies.

### RF Test Fixture Design (10MHz-21GHz)
Frequently I have been asked to design test verification fixtures for RF products. These fixtures require very precision design and any added performance degradation in signal strength or quality would affect product testing. I was responsible for mechanical design, fabrication, and assembly of these test fixtures. I worked closely with electrical engineering to understand all electrical specification required. These fixtures required a level of human interaction design as well because most of these required someone to manual process 10-100 units though the fixtures regularly. Types of product that required fixturing were mixers, amplifiers, VCOs, and DROs. Many fixtures would take a design or two to achieve full specification compliance but in the end the designs would be both cable of testing the product and be easy to use.

### Transmit Amplifiers for IED Jamming System (10MHz-6GHz) 
The project was to design six mechanically identical 30W transmit amplifier modules each with a unique frequency band to cover overall the whole 10MHz to 6GHz spectrum. I was the principle mechanical engineering on this project and was responsible for all the packaging and planning of the module configuration. I worked closely with electrical engineers and board layout designers to create a uniform layout throughout each module. Designing high and low-frequency amplifiers in identical packaging was a large challenge. Also, a sealing requirement for sand and dust was required which was achieved through a mezzanine system with laser cut conductive silicone gaskets. Integration of the heatsink for each amplifier also was challenging as the package was very aggressively sized. This product met all design requirements and was successfully delivered to the customer.

<hr />

## Web Development

### [Simplicity Sprouts](http://simplicitysprouts.com)
This site is a Wordpress blog I developed and maintain. This was the first full site I've helped create, publish and maintain. There was a steep learning curve to learn Wordpress development, understand PHP for theme modification and deploy a website. This site had a successful rollout and continues to serve as a solid blogging platform.

### [Calculist](http://slylion.com/calculist)
A simple web application whose purpose is to be both a simple calculator and a list program to store calculations. This is a simple JavaScript driven application and is all client-side. The application came into being as I found myself always needing a calculation I made 3 or 4 steps previous and would either have to write the info down as I went or re-calculate values. This application was to service that need. 

### [Personal Portfolio Page](http://dangallagher.xyz)
Designed and Developed the site this write up is on from scratch. I designed the mockup in Keynote. Jekyll was used both as a post processor for Sass and as a static site generator. Using Git for my version control, I was able to push this to Git Pages and deploy modifications easily.

<hr />

## Configuration Management / Document Control

### Transmit Amplifiers for IED Jamming System (10MHz-6GHz) 
The project was to design six mechanically identical 30W transmit amplifier modules each with a unique frequency band to cover overall the whole 10MHz to 6GHz spectrum. I severed as one of the project managers/coordinators on this job. My role was to manage the configuration of each unit how it was built and assembled, how all the pieces were being fabricated and delivered, as well as how that fit into our overall schedule. This was managed through multiple vendors as well as across many site locations throughout the company.


{::comment}
### Project B
Description of project B and the challenges associated.

### Project C
Description of project C and the challenges associated.
{:/comment}

<hr />

## Component Engineering

### Component Engineering Team
A team was established to deal with all component obsolescence and end-of-life issues. The task was to track, manage and solve component issues in both new product development and maintenance of legacy products. The role I played on this team was the hardware engineering liaison. My responsibilities were to find alternate components and verify part equivalence through analysis or verification. Working closely with configuration control, purchasing, mechanical engineering and electrical engineering this project allowed the company to function without a dedicated component engineer.

{::comment}
### Component EoL research Spectrum
Description of project B and the challenges associated.
{:/comment}

<hr />

## Process Engineering

### Printed Circuit Board Standardization
The project started to bring 10 years worth of boards design under the same design and manufacturing standards. Improvements to the internal standards covered, documentation (fabrication, assembly, and bills of materials), data management (assembly data, metadata in schematics), component standardization (part count reduction, bills of material auditing), and design rules for fabrication, test, and manufacturing.

{::comment}
### Global Library Standardization Project Spectrum
Description of project B and the challenges associated.

### Fabrication of Printed Circuit Board Prototypes
Description of project C and the challenges associated.
{:/comment}
