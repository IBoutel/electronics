# Electronics
A collection of electronics projects

## Contents
- [Naming Convention](#naming-convention)
- [Microcontroller Board Standards](#microcontroller-board-standards)
    - [KS-001](#KS-001)
    - [KS-002](#KS-002)
- [Existing Project List](#existing-project-list)
- [Planned Project List](#planned-project-list)

## Naming Convention
Project are named in the following manner:

`K<t>-<n>-<v>`

Where `t` is the type of project; `n` is the project number; `v` is the project version. The type can either be `D` for a non-computer device (e.g. battery charger); `C` for a computer (e.g. microcontroller board); `E` for an extension module (e.g. arduino shield); `S` for devices designed for a specific project (e.g. rc car ECU).

An example could be `KC-2-3`, which would be the second computer I designed in its 3rd version.

## Microcontroller Board Standards

### KS-001
A standard for the GPIO pin layout for microcontroller boards

### KS-002
A standard for reserved GPIO pins for RP2040-based microcontroller boards

## Existing Project List

Type D:
- KD-1:
    - Versions: 1
    - Current ID: KD-1-1
    - Status: Awaiting production

Type C:
- KC-1:
    - Versions: 0
    - Current ID: N/A
    - Status: PCB design
- KC-2:
    - Versions: 1
    - Current ID: KC-2-1
    - Status: Awaiting production

## Planned Project List

Type D:
- KD-2: Brushed DC motor driver

Type E:
- KE-1: TFT touchscreen shield for KS-001 compliant boards
