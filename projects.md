---
title: Projects
weight: 4
---

Below you will find a small sample of projects I've been involved with over the years. I've tried to put these into categories, but in many projects the role that I played was very cross discipline.

<hr />

## Printed Circuit Board Layout 

### Certified Avionics GPS / Nav / Com Systems
Developed and maintained all 14 board designs for an avionics GPS/NAV/COM systems. The system includes front and backplane boards, display and button boards, 16W VHF radio boards as well as I/O and computational boards. Board technologies involved include high-speed digital, RF (VHF band), differential pairs, up to 17 layer boards, blind and epoxy filled cap plated vias. Designs required jigsaw fitting of PCBs into one another due to limited space. The project was successful though very close integration of the mechanical and electrical teams due to aggressive packaging.

### Data Processor for Flying Projectile Sensor
The requirements for this board design were a very small tight package that could fit in a flying sensor that contained extremely sensitive RF circuitry as well as a vast number of high-speed digital circuitry for data processing. Board contained two 100+ pin quad flat pack chips followed by an array of four 300+ pin BGAs. The technology of the board was in the 4mil trace and 4mil space range and contained 12 layers of which two were power planes, four ground planes and 6 were routing layers. The board was done without isolating ground planes and was successful at keeping all high-speed switching noise from the large amount of RF circuitry and vice versa. Each BGA had over 200 data connections and the board was hand routed for optimal efficiency of particular critical data lines. Board design functioned to specification on the first spin of the design.

### WiFi Bluetooth Module
Requirements for this project were to create a very small SMT level board module that contained a WiFi and Bluetooth chipset, integrated power supply and dual band chip antenna. This board was sized at about 2 x 0.75 inches and had a sizeable 0.5mm pitch BGA as the main chip on the board. This drove technology down to 3mil trace and 3mil spaces, as well as blind and buried vias for BGA breakout. This board design was on a 0.063-inch thick board so the layer count needed to be as low as possible. This was all hand routed and critical care was taken to avoid any possible noise issue within the layout of the traces between layers. This product was successfully created and used by and end customer in the medical equipment field.

### Low Noise Switched Amplifier
The goal of this module was to take in 3 independent RF input signals at 2-3.75GHz and amplify a selected path while maintaining low noise specification, ensuring low return loss and high isolation between ports. I was the primary mechanical and printed circuit board designer of this project. The package was a 4.0 x 2.0 x 0.5-inch box with 4 SMA connectors on the leading face and one micro d-subminiature connector for power and communication on the rear face. This module required a very thin PCB while overlapping large areas of RF circuitry with limited layer count. The bottom side of the board was a switch bank feeding into an LNA on the top side of the board. Care was taken prevent RF signal isolation in the routing placement and layer configuration of the board. Blind vias on both sides of the board were required as was impedance matching of traces. This project was successful in meeting all specifications and due to its success future order were placed.

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

### [AviFish](http://slylion.com/avifish)
Designed and Developed an application to lighten the workload of generating links for a documentation control system. Avidyne uses a separate document control system from their configuration control system. This means to pull files from the configuration control system you need to link externally to it. This app runs a query based on a submitted changelist and given repository, opens a page and then the contents of the page can be copy and pasted into the app and the document links are extracted and formatted. Previously this has always been done manually. My original intent for this application was to query the page directly but due to cross-domains resource sharing restrictions I was unable to do this. This was designed in HTML, Sass, and JavaScript with a simdge of JQuery. I used Brackets which allowed for JSLint to be run on the JavaScript. A Jekyll template and a Gulp build process was used to do building, autoprefixing, minification, and browser sync during development. I have saved myself and another employee at Avidyne 5-15 mins of work each day by using this app rather than processing these links by hand.

<hr />



## Configuration Management / Document Control

### Transmit Amplifiers for IED Jamming System (10MHz-6GHz) 
The project was to design six mechanically identical 30W transmit amplifier modules each with a unique frequency band to cover overall the whole 10MHz to 6GHz spectrum. I severed as one of the project managers/coordinators on this job. My role was to manage the configuration of each unit how it was built and assembled, how all the pieces were being fabricated and delivered, as well as how that fit into our overall schedule. This was managed through multiple vendors as well as across many site locations throughout the company.

<hr />



## Component Engineering

### Component Engineering Team
A team was established to deal with all component obsolescence and end-of-life issues. The task was to track, manage and solve component issues in both new product development and maintenance of legacy products. The role I played on this team was the hardware engineering liaison. My responsibilities were to find alternate components and verify part equivalence through analysis or verification. Working closely with configuration control, purchasing, mechanical engineering and electrical engineering this project allowed the company to function without a dedicated component engineer.

<hr />



## Process Engineering

### Printed Circuit Board Standardization
The project started to bring 10 years worth of boards design under the same design and manufacturing standards. Improvements to the internal standards covered, documentation (fabrication, assembly, and bills of materials), data management (assembly data, metadata in schematics), component standardization (part count reduction, bills of material auditing), and design rules for fabrication, test, and manufacturing. To date, this project has been successful in not only saving money in cost reduction of current and legacy parts but cost reduced the design process.  Fewer mistakes are created and the overall company documentation has greater uniformity.

### Fabrication of Printed Circuit Board Prototypes
One project that covered multiple disciplines was the creation of a prototype fabrication line for printed circuit boards. The boards had two requirements, that traces and spaces on the board were very accurate (+/- .005mm) and that the boards had plated through holes. This project required quite a bit of chemistry setup and I was the principle engineer who created and maintained this fabrication line. This required learning the technologies associated with laser ablation etching (performed by an LPKF machine) to cut traces, pads and holes into circuit boards. After the boards were cut out there was a need to create reliable plated through holes. This required the development of a few plating setups. First was an electroless copper plating process setup to establish a thin layer of copper that could then be reinforced in an electrolytic copper plating bath. This process proved to be a large consumer of time and producer of a large volume of waste chemicals so another process, using conductive ink, replaced this. A manual process of coating the via holes with ink followed by an electrolytic plating process created reliable plated through holes in these laser-etched prototype boards. The fabrication line was successful in fabricating many high-frequency RF prototypes designs saving the company weeks of fabrication time and access to many experimental iterations of a design.

### Global Library Standardization Project
A team was created to incorporate the printed circuit board layout libraries of six divisions, originally of different company origin, into a single source that could be shared throughout the company. Along with this was the transitioning to single schematic and layout software across the company. I was one of three primary engineers on the team created to standardize the processes of each company. Upon reviewing component standards such as IPC, and the existing library setups created by each division we were able to craft a uniform library process that could be used by anyone in the company. A system was established to review and check parts. Also, a weekly teleconference was held to go over the challenges of the project and assign new tasks out to each division. The project took about 6 months to roll out in a complete form. Once setup and being used each of the six sites were able to create and edited library components (parts, schematic symbols, and footprints) that were available to all sites.


