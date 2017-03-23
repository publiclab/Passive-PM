## Introduction to the Passive PM Monitor
A [passive PM monitor](https://publiclab.org/wiki/passive-pm) collects airborne particles deposited on its surface without the use of mechanical or electrical systems. 

This passive PM monitor collects particulate matter on a glass slide cover. The slide cover is then [imaged with a microscope](microscopy/README.md), each particle is measured, and an [analysis protocol](analysis) is used to extrapolate the airborne concentration of coarse PM (PM<sub>2.5-10</sub>) during the sample period. 

The Passive PM Monitor was developed at the University of Iowa based on the University of North Carolina Passive PM Monitor. Components developed at UNC are subject to US Patent 6,321,608 until April 7, 2020 and are not to be used unless under [license](license.md). Public Lab has an evaluation license from UNC for evaluating the use of the monitor for community science monitoring. [Contact Public Lab](staff@publiclab.org) about becoming an evaluation partner. 
 
## Components of the Passive PM Monitor

### Hardware
The core Passive PM Monitor hardware is an aluminum [SEM stub](SEM_stub) and machined aluminum cap and screen, underneath which sits a microscope slide cover. This component is subject to patent protection.

[image]

The SEM stub sits between a [housing](housing) consisting of two plates that protect the slide from inclement weather and also normalize the flow of air across the stub and enable the use of the Passive PM Monitor in outdoor environments.

[image]

### [Microscopy](microscopy)
Accurate measurements of PM<sub>2.5-10</sub> require that the slide surface where particles are deposited be imaged as completely as possible.  It is recommended to automate this process. We are using the [OpenFlexure]x(LINK) microscope for automated imaging.

Images must then be processed to isolate and measure each deposited particle. Processing is currently happening with ImageJ.  See more details in [Microscopy](microscopy)

[4-up image of processing]

### Analysis
Imaged and sized particles are entered into an analysis protocol that uses an atmospheric physics model to determine airborne concentration of coarse particulates (PM<sub>2.5-10</sub>) during the sample period.  This equation was developed at UNC and is subject to patent protections. 

### [how you can contribute](contributing.md)

### [Bibliography](Bibliography.md)

### About this project
The TALA repository is a project of [Public Lab](www.publiclab.org) to [collect ongoing research into kite anemometry](www.publiclab.org/tag/kite-anemometer) into a stable device replicating the TALA and licensed under [CERN OHL 1.2](LiCENSE.md).

To read more about using kite anemometers and find resources and sources used in this repository, visit the [Public Lab Wiki](publiclab.org/wiki/kite-anemometers). To learn more about contibuting, please read our [contribution guidelines](contributing.md).


>Manufacture, use, or sale of this device is protected by U.S. patent 6,321,608, owned by The University of North Carolina at Chapel Hill. Any party desiring a license to use the aforementioned patent for commercial purposes shall contact the Office of Commercialization & Economic Development at UNC at 919-966-3929.
