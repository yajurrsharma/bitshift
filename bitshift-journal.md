# BitShift — Journal


## Entry 1
- Created At: May 7th, 2026
- Worked for: 2 hours 3 minutes

### Content

i decided to make a keyboard!

where did the idea come from? well, i actually secured second position in Build Guild :) and for that, i got some brand new shiny keycaps, so i thought, might as well just use these somewhere.

today was pretty basic. first i started by making a BOM. then, i went ahead and drew a keyboard plate using the swillkb online tool!

im making a 60% keyboard, having 61 keys, no leds unfortunately, that would skyrocket the overall cost. 

anyways, then i made the schematic, drew the switch matrix, connected everything to the RPi Pico, and then assigned some footprints. i need to double check everything right now, so once i come to this again, i will recheck the footprints so all keys are correctly mapped.


<img width="1177" height="416" alt="image (7)" src="https://github.com/user-attachments/assets/53ea5b7e-7fb7-4565-a3bd-7f556a0e36a8" />

heres a ss of my plate that i designed using the swillkb website, its pretty cool


### Recording Links

- https://lookout.hackclub.com/api/media/5f3a849c-c17c-4469-9c85-4971cd376720/video.mp4


## Entry 2
- Created At: May 7th, 2026
- Worked for: 1 hour 18 minutes

### Content

continued on the work left yesterday, apparently i had done some blunders :P. anyways, redid the connections, edited footprints to match the keys, and added them all to the pcb editor. tomorrow, im going to fix, THIS.

<img width="1183" height="614" alt="image" src="https://github.com/user-attachments/assets/fbfd264a-72e4-4f55-aa6b-918fb9301bc2" />


YEAH, rats nest.

### Recording Links

- https://lookout.hackclub.com/api/media/ceab856b-4d7b-44f3-8d52-44b907fc9714/video.mp4

## Entry 3
- Created At: May 8th, 2026
- Worked for: 1 hour 56 minutes

### Content

i would be super happy but something crazier happened.

well today, i just setup the keys in the shape of my keyboard, and placed the diodes behind them, and then started routing.

i may have to change the location of some connections to make it simpler but thats not even the craziest part, RIGHT AS I WAS ABOUT TO SAVE WHATEVER I DID, MY POWER WENT OUT, AND I LOST EVERYTHING.

yes. all the diodes placements, connections, everything. i mean it is what it is and this kinda gives me a change to revisit my connections again.

anyway, ill come back to this later (with the connections fixed again) complete the pcb, and get to the firmware!


<img width="716" height="754" alt="image" src="https://github.com/user-attachments/assets/780803e7-8c04-4466-9dbb-e9d0f19dc980" />



heres the upsetting screenshot of my doom


### Recording Links

- https://lookout.hackclub.com/api/media/e40e3a29-ea73-4fb1-89ab-404a93e6737f/video.mp4

## Entry 4
- Created At: May 9th, 2026
- Worked for: 59 minutes

### Content


routing is kinda hard. i figured out that, well, today :P

i revised my BOM, coz i found some better quality AND less expensive switches, so right now, the bill stands at only around 43 dollars without the pcb.

anyway, i might have to change some connections in the schematic itself, to make the routing easier. ill probably open my old mechanical keyboard and have a look at it to understand it better.

<img width="1261" height="471" alt="image" src="https://github.com/user-attachments/assets/5edb98cb-8ca4-4bf0-9f00-1cedae6a734d" />


heres a current 3d model of my pcb, and hopefully today ill complete the routing.

### Recording Links

- https://lookout.hackclub.com/api/media/acc81f33-3858-4a29-ac13-3e9b230aa9a9/video.mp4
  

## Entry 5
- Created At: May 10th, 2026
- Worked for: 2 hours 27 minutes

### Content

so today was a pretty big day, and im only finishing because its about to be 12 and i need to journal for today. after this, ill start again.

anyway, i took apart my old mechanical keyboard to see how the routing is done and have an idea. heres a look!

<img width="960" height="1280" alt="WhatsApp Image 2026-05-10 at 11 56 38 PM" src="https://github.com/user-attachments/assets/883e5ba2-6255-47b3-aec2-1741c07c9bf5" />
<img width="1280" height="960" alt="image" src="https://github.com/user-attachments/assets/c742826d-6ab7-4a2e-8b3d-adcd83d67e7a" />


and then i fixed my pcbs routing, and it looks SOO much better now.

then added some art and text, and finally updated the BOM to remove the display component.

the biggest problem today was snapping the keys together in a grid, which i was facing for quite some time now, but asking around really helped, and now that problem is also fixed, that means, we are good to go with the pcb.

i need to edit the switch plate and the firmware now.


### Recording Links

- https://lookout.hackclub.com/api/media/a0695aca-4058-47ed-9e1c-43ae3a826b6a/video.mp4

## Entry 6
- Created At: May 11th, 2026
- Worked for: 2 hours

### Content

FIRMWARE IS COMPLETED!

<img width="600" height="412" alt="image" src="https://github.com/user-attachments/assets/8950b6b5-7a1a-4538-bb49-ca1c7e555fdf" />

and HERES THE FINAL PCB DESIGN!!


<img width="1364" height="589" alt="image" src="https://github.com/user-attachments/assets/760a303a-7307-4237-b673-aa148d6a7e00" />

im so insanely happy, because this means im actually extremely close to finishing this! the only things left is the switch plate, which ill edit and finalise very soon (today most probably)


### Recording Links

- https://lookout.hackclub.com/api/media/59a9abd1-e22c-4c48-9f89-76369608c2d8/video.mp4

## Entry 7
- Created At: May 13th, 2026
- Worked for 1 hour 22 minutes

### Content

did cad work today, pretty basic.

first i had to edit the switch plate to accommodate the increase in size of the pi. 



<img width="925" height="511" alt="image" src="https://github.com/user-attachments/assets/1b8e8d82-0593-4466-afe4-40bb99fc0505" />

### Recording Links

- https://lookout.hackclub.com/api/media/a5da7c6f-0a73-4071-98da-929c07a3b514/video.mp4
  

## Entry 8
- Created At: October 20th, 2026
- Worked for 1 hour 34 minutes

### Content

opened this project after so long, just to create the case for the keyboard, so i could finish this!

so i realised, removing the oled would be a good idea as it would overwhelm the look. right now, till the artwork looks clean!

anyways, i downloaded the dxf for the keyplate again, imported it to shapr3d, saw shapr's tutorial for 3d CAD modelling, made some screw holes for the screws, added a box around the plate stabilizers, and extruded it. this took long to figure out and make tho :( but now we're done with the switchplate!

im skipping on creating the top case, as i wanted to keep this a little raw (and coz i wanna cut in on the time to build the case coz i dont know how to 3D CAD) so as of now, till the switch plate, my project is all done!

heres how the final switchplate came out!

<img width="890" height="413" alt="image" src="https://github.com/user-attachments/assets/60f6da95-f131-441e-900e-78fad34d043e" />

<img width="895" height="485" alt="image" src="https://github.com/user-attachments/assets/65a2d5df-a351-4492-90a9-0d5cc0f8127c" />



i used M2 screw holes (which i later realised i will not be needing, as the switch plate and the switches clicking will keep the pcb stable as is (also to mention, soldering the keys will not move the pcb), keeping the plate 3mm in thickness!

### Recording Links

- https://lapse.hackclub.com/timelapse/3maGoJuVpEYr



## Entry 8
- Created At: October 21st, 2026
- Worked for: 1 hour 21 minutes

### Content

i had received some feedback regarding making a case :P so thats what i did! 

theres a story to that too, tho. when i first designed the case, i deleted the switchplate body :P, so i had no way of checking if the height was correct. redid it, and i FORGOT THAT MY PI IS NOT BEHIND THE KEYBOARD. so, AGAIN, took the total width of the pcb, redesigned the case, and exported a .step file for the case and switchplate. after that, exported the pcb from kicad, and realised the cherry mx key models are not being exported. great. tried to fix it but they just wouldnt budge, so i let it be as i had already taken a tolerance for the height during the case build. used onshape for the final assembly, with the pcb, case and switchplate! although, i didnt puncture a hole for the pi on the side yet, as i didnt know how to calculate the distance. so, inCASE i build this project, ill just cut it out with a sharp tool. finally, made a csv of the BOM so its easier to read, and we're all done!

heres a look of the final assembly! 

<img width="796" height="420" alt="image" src="https://github.com/user-attachments/assets/e0686297-4056-4160-8e48-33819983ef43" />

looks cool! ill have an acrylic plate to cover the top exposed part of the pcb, so only the pi, the artwork and the routing is visible. and that completes this project! (finally)




### Recording Links

- https://lapse.hackclub.com/timelapse/xMyQoOtKOCyX
- https://lapse.hackclub.com/timelapse/XOIqsHVFJ2Tc
