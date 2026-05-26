# Cactus Stand Programs

## Cut In Pos X (For Wires)

[Download](./gcode/CactusStand/WireCoversCutInPosX.gcode)

**Bit: 1/4".**

Zero point 1.25" toward -Y from the non-CNC cut.

![Program image](./img/CactusStand/CutInPosXZeroPointDistance.png)

![Program image](./img/CactusStand/CutInPosX.png)

## Cut In Neg X (For Wires)

[Download](./gcode/CactusStand/WireCoversCutInNegX.gcode)

**Bit: 1/4".**

Zero point 1.25" toward -Y from the non-CNC cut.

Same program as Pos X but mirrored across X axis.

![Program image](./img/CactusStand/CutInNegX.png)

## Cut Out Covers Array

[Download](./gcode/CactusStand/WireCoverCutOutChain.gcode)

**Bit: 1/8".**

Zero point arbitrary but the cuts will be +Y from the zero point. Zero point is offset the same way that [Cut In Pos X](#cut-in-pos-x-for-wires) is offset.

Cuts four covers in one program.

![Program image](./img/CactusStand/WireCoverArrayCutOut.png)

## Wire Covers Screws Array

[Download](./gcode/CactusStand/WireCoversScrewCut16.gcode)

**Bit: 1/16".**

Zero point the same as with the [Cut Out Covers Array](#cut-out-covers-array).

Zero point arbitrary but the cuts will be +Y from the zero point. Zero point is offset the same way that [Cut In Pos X](#cut-in-pos-x-for-wires) is offset.

Cuts the screw positions for four covers in one program.

![Program image](./img/CactusStand/ScrewCuts16Array.png)