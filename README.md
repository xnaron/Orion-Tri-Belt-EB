# Orion Tri-Belt-EB

This is a fork of the awesome Orion bythorsthunder.  I wanted the electronics on the bottom.  

Changed CAD is in the EB-Mod folder.  I haven't exported any stl's.

![](Images/Orion-EB.jpg)

A mod of the Voron Trident that replaces the 3 leadscrews with belts and modified Z-Drives from a 2.4.  This is in the very early stages of development and though a fully-functional printer has been built, some of the parts are not yet fully tested.  The existing printer is producing excellent prints, though many changes will be coming in the following months.

This first version places the Low Voltage Electronics up top, though I do hope to create a version in the future which is more closely matched to a stock Trident Build.  The second version will have the Z drives and low voltage electronics located on the bottom, same as in a standard Voron Trident or 2.4.

A huge thank you to [@clee](//github.com/clee/) for lots of help in planning, designing and generally supporting the development of this 3Dprinter.

## Why?

Since this is the most common question when posting about this printer, I will get this out of the way.  

  1. Much higher Z speeds and accelerations when compared to lead screws.  Tested so far at 200mm/s and 1000mm/s^2 without issues.
  2. Avoids the usual drawbacks of leadscrews regarding wobble and backlash.
  3. Similar cost to a Trident with lead screws, given the relatively high cost of steppers with integrated lead screws.
  4. Why not?

The cost of this modification is approximately $145 USD.  If the 3 steppers with lead screws are not purchased, the cost over a stock Trident build is approximately $40 USD.

## CAD

Due to max size for files on GitHub, [the CAD file can be downloaded from Dropbox](https://www.dropbox.com/s/zwozwpm1h77wviw/Orion%20Tri-Belt%20v5.step?dl=0).  There is a greatly trimmed-down file available in the CAD folder, but this link contains the most up to date full model.  

## BOM

The following is a list of parts required in addition to the stock Trident Build.

### Electronics

| Item | Qty |
| - | - |
| NEMA 17 stepper motor	| 3

### Motion	

| Item | Qty |
| - | - |
| 6mmx188mm GT2 Belt Loop | 3 |
|9MM 2GT Belt (Meters)	|      3.5
|Pulley 2GT 16 Tooth, 6mm	|  3
|Pulley 2GT 80 Tooth, 6mm	|  3
|Pulley 2GT 20 Tooth, 9mm	|  3
|Idler 2GT 20 Tooth, 9mm	|  3
|5x60 D-Shaft	|  3
|Bearing 625-2RS	|  9

### Fastners	
Buy extras.
| Item | Qty |
| - | - |
|M5x30 BHCS	|  3
|M5x10 BHCS	|  12+
|M5x40 SHCS	|  6
|M3x16 SHCS	|  3
|M3x40 SHCS	|  18
|M3 Heatsets	|  20
|M3x8 SHCS | Yes

## STLs
Print all files in the STLs folder.  Review readme.md in the Skirts folder for additional information.
For a new build skip the following when printing parts from the Trident repo.
### Excluded Parts
|Z_Assembly|Skirt|Panels|Gantry|
| - | - | - | - |
|[a]_z_carriage...|12864 Parts|bottom_panel...|Front Idlers|
|z_bed...|
|z_carriage...|
|z_stepper...|

### Additional Parts
From the Voron 2.4 Skirts Repo print the following:
| - |
|[a]_belt_guard
|[a]_fan_grill
|[a]_fan_grill_retainer
side_fan_support
side_skirt_a and b (Print only one of each)

## Panels
Upper deck panel can be created from the bottom panel.  DXF is included.

Deck Panel remains the same.

Rear Panel may benefit from some cutouts below the gantry extrusion to allow easier routing of wires from below deck to above.

Top LV electronics panel is a square with the same outside dimensions as the bottom panel.
