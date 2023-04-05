# KIM-1 Dual 6530-6532 adapter

## Introduction

Welcome to the KIM-1 Dual 6530-6532 adapter repository. This adapter replaces both 6530 chips on the KIM-1 with a single board that contains a couple of 6532 chips, an EPROM and a few logic ICs.

As far as I know, this is the only board that allows you to replace both 6530 chips simultaneously.

## About

I designed this board for [my KIM-1 PCB replica](https://github.com/eduardocasino/kim-1), but it will also work with real KIM-1s that have both RRIOTs missing or broken.

The schematic is based on Ruud Baltissen's KIM-1 replica, with very minor modifications. The PCB features hand-traced tracks to seamlessly integrate with the KIM-1 board:

![board installed](https://github.com/eduardocasino/kim-1-dual-6532-adapter/raw/main/images/kim-1-with-daughterboard.png)

WARNING: I have not yet sent the board to fabrication, so it is untested!

## Licensing

This is a personal project that I am sharing in case it is of interest to any retrocomputing enthusiast and all the information in this repository is provided "as is", without warranty of any kind. I am not liable for any damages that may occur, whether it be to individuals, objects, KIM-1 computers, kittens or any other pets. It should also be noted that this design has not been tested and may contain errors, therefore anyone who chooses to use it does so at their own risk.

[![license](https://i.creativecommons.org/l/by-nc/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc/4.0/)

This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](http://creativecommons.org/licenses/by-nc/4.0/).

EXCEPTION: The electrical schematic and all the associated symbols are licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

See the LICENSE.md file for details.

## Acknowledgements

* Hans Otten and his [Retro Computing blog](http://retro.hansotten.nl/). Everything you need to know about the RRIOT and RIOT.
* Ruud Baltissen for [the original schematic](http://www.baltissen.org/newhtm/buildkim.htm).