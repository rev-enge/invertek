# Invertek Drives

Reverse engineered (parts) of the Invertek frequency drive(s).

The drive consist of different printed circuit board assemblies (PCBA)
 which are all soldered together.

# Drive types and bords

Each type of drive is composed of at least 4 PCBAs. Some of these boards
 are common to a number of drives.
 
The E2 drives use 4 boards.
The P2 drives use 5 boards, the additional board is for the option module. 
 
These are the boards that are used:

* FILTER : The main input power.
* HV POWER : The board containing the IGBT's and the cpu that controls it.
* TERMINAL : The output connector, brake resistor are located on it.
* CONTROL : The display/keypad and input controller.
* OPTION : The pcb with the connector for the option/communication module. 
 
Here a list of drives and its type and the used variants of the boards.

| TYPE               | RATING | FILTER | HV-POWER | TERMINAL | CONTROL | OPTION |
|--------------------|--------|--------|----------|----------|---------|--------|
| ODE2-2-24400-3KA42 | 4kW    | FLT2-5 | HVPWR2-8 | TERM2-5  | CTRL-12 | N.A.   |


N.A. = Not applicable.

# Table of contents

Optidrive E2 and P2 PCB assemblies:

* CTRL-12 => [ODE2 CONTROL ISSUE 12](ode2-control-issue-12/readme.md)
* FLT2-5 => [E2/P2 S2 3-ph FILTER ISSUE 5](e2-p2-s2-filter-issue-5/readme.md)
* HVPWR2-8 => [ODE2 S2 HV POWER ISSUE 8](ode2-s2-hv-power-issue-8/readme.md)
* TERM2-5 => [ODE2 S2 TERMINAL BOARD ISSUE 5](todo.txt) TODO
* OPTION-7 => [P2 OPTION BOARD ISSUE 7](todo.txt) TODO
