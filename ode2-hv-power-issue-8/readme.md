# Identification of the board

ODE2 S2 HV POWER ISSUE 8

# Description

This board contains the IGBT (includes the 3 phase brige inside) the IGBT gate
 drivers and the cpu that controls it.

An inrush current limit circuitry is built around a 2 ceramic thick film
 resistors and a relay to brige it after a small amount of time.

Also the board contains the (insulated) powersupply that supplies power to the
 display and input control board. These are 5.2V and 26V power supply voltages.
The circuitry is built around the small yellow ferrite transformer.

This board is also responsible to measure the temperature of the IGBT, the DC
 voltage and detecting any phase loss at the primary side.

The CPU communicates via 2 optocouplers to the display and input control board.

# Repair hints

[Found issues in the past](../todo.txt) => TODO (IGBT NTC failure, PSU failure, inrush current limiter)

# Utilities used to create the drawings

TODO: The schematic diagram is made with KiCad 6.0.0
