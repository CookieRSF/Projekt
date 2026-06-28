to fix hitting the print/3d print warping
- z offset 
- slower print speed

temps should be 200-210 according to the latest temp tower test

CURRENT TEST:
Z is offset by 0.1mm
One cat has 40% print speed
One cat has 80% print speed

NOTES:
offset by 0.2mm
babystepped by 0.2mm
cat with 40% print speed looks less defined on straight walls, but superior in slopes and slants

NEXT TEST:
Fan speed decreased to 50%
80% speed decreased to 60% Speed
0.6mm Z offset

NEXT TEST:
Calibrate Flow Rate

NEXT TEST:
Repeat of Temperature Tower

Can you help me find out what this excerpt is describing and how to search for it online? 
The half-way-between method. That name was made-up by me on the spot, so you probably won't find any information regarding it online. Which is why i've written this to try to find information about it.  To find the desired value between two extreme values, the first which is too little (point A) and the second which is too much (point B), average the two values and try to find the middle value between. After we obtain this new value (let's call it "point C"), test if it has the desired effect. If the effect is inadequate, repeat the previously mentioned averaging process, except this time we average between point C and point B, to create point D. However, if the effect is excessive, do the same as the previous sentence, except average between point C and point A to create point D. Repeat this process over and over on a progressively smaller scale to iron out any imperfections until the difference between the remaining relevant values has converged to an imperceptibly small tolerance or until the tolerance is practical for use.

excessive retraction distance?
faulty/crooked nozzle?

" https://www.filoalfa3d.com/gb/blog/71_setting-retractions-in-3d-printing.html#:~:text=We%20suggest%20you%20use%20a,for%20each%20material%20you%20use.
We suggest you use a retraction length between 2 and 5 mm for direct-drive extruders and between 4 and 7 mm for bowdens. But be careful: each filament has a different behavior inside the nozzle extrusion chamber, so you will have to find the perfect value for your printer and for each material you use.
"

check saved posts on reddit

already tried:
- switching nozzles
- 2-3 cold pulls
- printed temperature tower
- printed speed tower
-- changed print speeds.
- printed retraction speed tower
-- decreased retraction distance
-- increased retraction distance
- levelling the bed with paper
- adjusting Z offset