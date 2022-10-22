# THE KBD2600

The KBD2600 is an Atari 2600 inspired 60% mechanical keyboard. The board is composed of main top and bottom assembly and uses a gasket mounting system for an improved typing experience. 

![KBD2600 Thumbnail 1](/RENDERS/Thumbnail.jpg)
![KBD2600 Thumbnail 2](/RENDERS/Thumbnail2.jpg)

This repository is divded into three main sections. The `CAD FILES` directory contains the CAD files for the project, the `DRAWINGS` directory contains the technical drawings for the overall assembly and each part, and the `DOCUMENTATION` directory contains overall documentation and documentation for each specific part.

## Part Naming

Parts are named using the following naming convention:

`YEAR - PROJECT NUMBER - PART NUMBER - SUFFIX`

The suffix options are as follows:
- _o: The overall assembly for the project
- _pp: A part that will be purchased rather than custom manufactured for the board, but will still be included in the
product the buyer receives.
- _rp: A reference part that won't be included in the product the user receives and merely exists to make the CAD more
complete.

## Standard Parts

The board uses a variety of standard M2 screws avialble from Mcmaster Carr.

The board is designed with a Wilba Tech PCB in mind, however, the board should be compatible with any PCB that uses the [C3 Unified Daughterboard standard](https://github.com/Unified-Daughterboard/Unified-Daughterboard). The feet used in the design are the [Silicon Keyboard Universalized Feet](https://github.com/Zambumon/SKUF) or SKUF.

## Manufacturing

In theory this board is fully manufacturable, ableit very expensive to machine. Finding a machine shop capable of manufacturing the board would involve finding a shop with a 5 axis mill with large enough travels to accomodate the top of the case ( part 2021-01-003)
