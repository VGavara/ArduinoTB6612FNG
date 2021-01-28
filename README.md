# Arduino TB6612FNG library
![License:](https://img.shields.io/github/license/vgavara/ArduinoTB6612FNG)
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/VGavara/ArduinoTB6612FNG?include_prereleases)

# Table of contents
- [Overview](#overview)
- [Repository structure](#repository-structure)
- [Contributions to the project](#contributions-to-the-project)
- [Attributions and references](#attributions-and-references)

# Overview
C++ library for controlling a Toshiba TB6612FNG motor driver throught the Arduino digital outputs. 

The Toshiba TB6612FNG is a motor driver capable of controlling two DC motors up to 15V (max) at 1200mA (avg). You can find the controller datasheet in the docs [datasheet](https://github.com/VGavara/ArduinoTB6612FNG/tree/main/docs/datasheet) directory.

This C++ library contains a set of classes for controlling the above driver by interfacing it through the Arduino digital outputs:
- The `Motor` class offers basic control on a brushed DC motor.
- The `Spinner` class adds acceleration/decceleration features to the `Motor` class.

# Repository structure
This repository is structured in these directories:
- [/docs](https://github.com/VGavara/ArduinoTB6612FNG/tree/main/docs): It contains the library documentation, as classes references and datasheets.
- [/examples](https://github.com/VGavara/ArduinoTB6612FNG/tree/main/examples): It contains usage examples of each class. It is a good place for getting a quick idea regarding what this library can do for you.
- [/src](https://github.com/VGavara/ArduinoTB6612FNG/tree/main/src): It contains the library source code.

# Contributions to the project
In case you were interested in participating in this project, read [CONTRIBUTING.md](https://github.com/VGavara/ArduinoTB6612FNG/tree/main/CONTRIBUTING.md) for further information.

# Attributions and references
* The documentation badges are generated by [shields.io](https://img.shiedls.io).
* The tables of contents are generated with the [Online GitHub Wiki TOC generator](https://ecotrust-canada.github.io/markdown-toc/).
* The library follows the coding style defined by the [Google ++ Style Guide](https://google.github.io/styleguide/cppguide.htm).
