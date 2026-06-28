potential causes:
- overextrusion
- incorrect bed levelling
- infill causing nozzle to hit
- underextrusion
- clogged nozzle (again)

- [ ] perform overhang test
- [ ] 

infill is too high and allat

using:
- 0.8mm nozzle
- 0.32mm layer height
- ender 5 pro
- the magnetic bed that came with the printer
problems:
- overextrusion on infill which causes the nozzle to hit the print. i'm using cubic subdivision pattern but might switch over to gyroid or lower the speed. not a big deal 
- terrible thick stringy overhangs
- stringing, oozing
- cylinders printing lopsided and messily
- bad z-seams

first we try with gyroid and reduced print speed, then for future prints we can try to adjust.

finished, but i had to adjust babystep Z by 0.2mm. nozzle at 235℃, bed around 85℃?

- strings and stuff getting stuck again.
- change temp to 235-240℃.
- perhaps reducing z offset by 0.2mm and adding 0.2mm to babystep Z after it finishes the first layers.
- remove overhang from bottom of shoes

PROCESS
1. boolean modifier + boolean object. intersect mode. top hole in bool object = 12.5mm edge lengths
2. duplicate model and hide previous model
3. change bool to difference mode, apply modifier, edit bottom peg of model to 12mm edge lengths. 
4. repeat
calibrate flow rate & e-steps?

reduce infill density.

peg size from 12mm to 11.75mm

moved +10mm on Z from print

11.75 = 12.5 * 94% = 0.94
12.5 = 11.75 * 106.383% = 1.06383