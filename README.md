# Firmware & Macros

This repository also includes my full Klipper macro setup.

⚠ Important – Please read carefully

These macros are:

Experimental

Highly customized

Specifically tuned for my personal 6WD Tridex system

Optimized for extreme speed and high acceleration setups

They are not plug-and-play.

The configuration is built around:

A 6WD AWD motion system

IDEX architecture

High motor currents

High acceleration values

Advanced homing logic

Aggressive performance tuning

Using these macros on a different machine without proper adaptation can:

Cause crashes

Damage hardware

Lead to skipped steps or desync

Overstress motors or drivers

You must fully understand what the macros do before using them.

These files are shared for reference, learning and development purposes only.

# 6WD Tridex – Full CAD Release

This repository contains the full CAD files of my custom 6WD Tridex (CoreXY AWD hybrid) project.

The concept combines a Tridex-style IDEX layout with a 6-wheel-drive motion system, focused on high acceleration, drivetrain rigidity and experimental high-speed performance setups.

This is a development platform and research build — not a finished commercial product.

# Base Projects & Credits

This project builds on several open-source foundations and community contributions:

Tridex base platform
👉 https://github.com/FrankenVoron/Tridex

Y motor / belt tensioner mounts (AWD integration parts)
👉 https://github.com/mandela64/Tridex-AWD/tree/main

Tridex macros (modified for my own requirements)
👉 https://github.com/joseph-greiner/tridex_mods

Toolheads – Sphinx Toolhead project (modified)
👉 https://github.com/riley-github/Sphinx-Toolhead/tree/main

The Sphinx toolheads included here are adapted for IDEX usage.
They are specifically designed around the CHC XL Hotend.

Important notes regarding the toolheads:

The IDEX modifications are not perfect.

Mounting geometry was adjusted to fit this 6WD Tridex layout.

Designed specifically for CHC XL.

Compatibility with other hotends is not guaranteed.

Further refinement may be required for ideal airflow and alignment.

Skirt design (Cheese Grater / Honeycomb variant)
👉 https://www.printables.com/model/670769-voron-trident-stealth-skirts-cheese-grater-honeyco

Huge respect to all original developers and contributors of these projects.

# Motion System

The drivetrain is designed around six NEMA17 stepper motors (1.8°) for the XY AWD configuration.

The AWD mechanical foundation originates from the LDO Motors AWD CNC system.

Official AWD gantry reference:
👉 https://github.com/VCProjects/LDO_AWD

This project integrates that AWD concept into a Tridex-style architecture and expands it into a custom 6WD configuration.

# Part Cooling

Each toolhead runs an independent CPAP-based part cooling system.

For this build, I used the BIQU Universal Turbo Kit (CPAP solution):

👉 https://biqu.equipment/products/universal-turbo-kit

Both toolheads are equipped with separate CPAP blowers to allow high and consistent airflow at extreme print speeds.

# What’s Included

Complete mechanical CAD

Custom motor mounts and AWD integration layout

6WD drivetrain structure

Structural frame components

Modified IDEX toolhead setup

Experimental design iterations

# Important

This is not a polished commercial release.

The design:

is experimental

may contain imperfections

is not fully optimized for manufacturing

has not been validated for long-term reliability

requires advanced mechanical and firmware knowledge

This repository is meant as a reference and inspiration platform, not a finished kit.

If you build from it, you do so at your own responsibility.

# Purpose

The goal of sharing this CAD is to:

Provide a starting point for advanced builders

Document the development process

Encourage experimentation in AWD / multi-drive CoreXY systems

Contribute back to the open-source hardware community

Feel free to fork, modify, improve and experiment.
