# 3D Print Settings
---------------

## Summary
The primary purpose of 3D printing the part was simply just to confirm dimensions of the modelled part against the original broken part before having the replacement made by a metal fabricator.

The OEM tiller plate part is made from anodised 6061 aluminium.  As such, any 3D printed part will never be as strong.  Nevertheless, I optimised the 3D print settings and filament choice to improve the 3D part strength.

## Filament
PETG filament was used which should provide some strength improvements over PLA.

## Slicer Settings
The model was sliced with PrusaSliver V2.5 and the following settings were changed to optimised the part strength.

**Print Setting Changes to Prusament PETG profile:**
|Parameter|Setting|default|value used|
|---|---|---|---|
|Vertical Shells|Number perimeters|3|6|
|Horizontal Shells|Solid Layers - Top & Bottom|3|6|
|Infill|Fill density|20%|60%|
|Infill|Fill patter|cubic|gyroid|

## Orientation
Part was rotated 45 degrees on platter in an attempt to minimise stresses along weaker layer orientation planes 

![45 deg orientation](../images/print-orientation.png)