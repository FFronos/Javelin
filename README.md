# Javelin

High-flow toolhead for 3D Printers at a relatively affordable cost.

**Note that this is both very unfinished and has not yet been tested. Use the design at your own risk.**

<img width="628" height="646" alt="image" src="https://github.com/user-attachments/assets/5a93df55-9ee6-480a-a51e-7485171d72fe" />


# What is this?

Javelin is a toolhead based on the Vesuvius Lite Hotend. *(Unreleased as of Febuary 3rd, 2026)*

Javelin is intended to be a structurally rigid, slim high-flow rate capable toolhead that can be dropped in to most MGN12H front-X-Rail front-belt based setups.

Current weight estimate for when its fully complete is around ~390g.

# Components

## Hotend
The hotend is the unreleased Vesuvius Lite designed and to be manufactured by Causality Manufacturing. 

The hotend is effectively the centerpiece of Javelin as its bent sheet metal shroud serves as a direct hotend mount to the MGN12H block, as well as mounting points for the ducts, belt fastening solutions, extruder, and any additional peripherals one may add.

The heatbreak is air cooled by a 2510 fan. Nozzle compatibility includes standard V6 style nozzles.

More information about Vesuvius Lite including cad files can be found on the page https://www.causalitymfg.com/downloads/vesuviuslitecad

## Extruder
I've opted for an Orbiter 2.5 *(The Orbiter 2 is also compatible)* due to its lightweight housing and great overall properties.

Truthfully any standard extruder works, but i tend to *gravitate* toward the orbiters. 

You can also add the orbiter smart sensor onto it if you prefer. 

You will need to modify the duct if you plan on using a different extruder (certain mounts may be made if i have the time), as it uses standoffs behind the motor as extra mounting points. You will need a pancake stepper motor.

More information about Orbiter : https://www.orbiterprojects.com/orbiter-v2-5/

## Belt mounting
This is super unfinished.

An idea for monolith exists that 3d printed guides on the side of the toolhead guide the belts further toward the front, so they can clamp on the inside of the toolhead on an SLM or 3D printed piece and then be compressed with a sheet metal piece. 

Dovetail mounts can fit over the button mounting screws, filling in otherwise occupied belt profile while allowing access to the screws that mount the belt mount and toolhead to the rail carriage.

After ducts, this is a priority.

## Duct
I am currently in the middle of designing this. Currently, CFD fine tuning for the performance of the duct itself needs to be done. (Currently, it is unprintable, for it lacks an actual flat surface for the first layer at this time.)

Single CPAP tube, passes under the X beam to fork into dual channels blowing at the nozzle at the end. The electronics will also mount here, plus a beacon mount. (Other probe mounts will be made in the future, such as standard inductive ones or cartographer.)

The duct should be easily 3D printable, with minimal supports required.



