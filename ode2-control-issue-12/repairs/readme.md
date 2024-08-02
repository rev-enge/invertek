# Repairs done.

These boards have been repaired multiple times.

## Sympthom: Some display segments do not light up or very dim.

Broken / increased resistance of one of the 470 E resistors in series with the
 (led) diplay.

These are located left above the display (4x) and reight below the display (4x).

## Sympthom: Display segments completely missing (or all segments very dim).

The boards are notorios for disconnected via's. So probably on one of the
 kathode side of the digits a trace is disconnected. The kathode side of the
 display is connected to the drain of an MMBF170 N-Fet (also use for button
 multiplexing).
So measure if the pin from the display is connected to the right fet (D) pin.

## Sympthom: A push button do not work.

The buttons switches tend to get bad over time. I have seen complete open
 switch contacts as well as contact resistances over a few hundred ohms.
Its best to replace them with a new switch if the contact resistance is over
 100-200 Ohms or so if you press them (actually they should be near zero Ohms).

A partnumber of the switch is:  FSM2JSMAAS (Brand TE)
The original switch actuator is orange, the above is pink (=260 gf). Probably
 the original has a small difference in the pressing force or it is just
 another brand using different colors.

### Back to main page [main](../../readme.md)