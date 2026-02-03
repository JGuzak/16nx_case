# 16nx_case

<img src="images/promo_1.JPG" width=100%>

A fully enclosed 3d printable case for the [16nx](https://16n-faderbank.github.io/16nx).

- [16nx\_case](#16nx_case)
  - [DISCLAIMERS](#disclaimers)
  - [Credits](#credits)
  - [BOM](#bom)
  - [Models \& Printing](#models--printing)
    - [Post-Processing](#post-processing)
  - [Assembly Guide](#assembly-guide)

## DISCLAIMERS

This case was designed for the 16nx, I don't have a 16n and cannot confirm compatibility. If you have a 16n and want to contribute, please create a GitHub issue on this repo for tracking and give it a try. Share pictures and incompatibilities so I can update the models.

## Credits

Big thank you to 256k for putting together the group buy for the 16nx. Without you I wouldn't have one of these devices!

## BOM

<img src="images/bom.JPG" width=80%>

- 1x assembled 16nx PCB
- 1x 16nx_case part
- 8x M2 heatset inserts
- 8x M2x6mm M/F standoffs
- 5x 20mm x 2mm rubber feet
- 1x felt fader cover (optional)

## Models & Printing

As long as the print bed is at least *TODO: get exact dimensions* `260mm` x `130mm` the `16nx_case.stl` file can be imported into your slicer of choice and printed directly. Ideally, use `/src/16nx_case.3mf` because it contains recommended supports for rubber feet insets and overhangs on the sides of the case.

The part will not fit as is on printers that have medium/small print beds (`200mm` x `250mm` x `250mm`). To solve this, there is an alternative stl file, `16nx_case_diagonal.stl`, that orients the case at a 45 degree angle and includes custom fins to keep the part balanced while it prints.

For optimal results, use `/src/16nx_case_diagonal.3mf` because it orients the fins to run parallel with the print bed y-axis motion (reduces chances of fins releasing from the print bed prematurely) and includes recommended supports for rubber feet insets/overhangs/dynamic layer heights.

It is recommended to read instructions all the way through before following along with your case assembly.

*Make sure to test your 16nx board before assembling with the case. Once the boards are assembled in the case, troubleshooting will require disassembling!*

### Post-Processing

Remove all suports, debur sharp edges.

For cases printed with the diagonal model, use a deburring tool to clean up the beveled corner that printed on the print bed. This corner is the most likely to warp or develop anomalies while printing. Printed fins and supports can leave small marks, these are purely cosemetic but removing them with a fresh box cutter/exacto knife.

## Assembly Guide

1. Draw a circle
2. Draw the rest of the owl
3. Congratulations, you've won!

asdfasdf

1. Using a soldering iron, press all heatset inserts into the print.
2. Place the `16nx PCB` into the case.
   - Ensure that the PCB is sitting flush along the bottom of the case and the USB and TRS ports are lined up correctly with the cutouts in the case.
3. Insert and tighten the standoffs into place. This should secure the PCB in place.
   - Ensure the PCB has is no wiggle. If there is, double check PCB alignment; look for solder tall joints and or through hole misalignment with the channels in the case.
4. (Optional) Place the felt fader cover over the faders. Ensure it is laying flat and standoffs line up with the mounting holes on the felt cover.
5. Place the face panel ontop of the PCB and ensure it is sitting flush with the frame of the case.
6. Thread all 8 M2 bolts into their respective standoffs. *DON'T TIGHTEN THESE BOLTS JUST YET.*
7. Thread all TS jack nuts.
8. Starting with the middle 4 M2 bolts, tighten all bolts.
9.  Starting from the middle, tighten all jack nuts.
10. Apply rubber feet to the bottom of the case.
