# BitShift — Journal


## Entry 1
- ID: 5893
- Author: yajur
- Created At: 2026-05-07T13:29:27Z
- Worked for: 2 hours 3 minutes

### Content

i decided to make a keyboard!

where did the idea come from? well, i actually secured second position in Build Guild :) and for that, i got some brand new shiny keycaps, so i thought, might as well just use these somewhere.

today was pretty basic. first i started by making a BOM. then, i went ahead and drew a keyboard plate using the swillkb online tool!

im making a 60% keyboard, having 61 keys, no leds unfortunately, that would skyrocket the overall cost. 

anyways, then i made the schematic, drew the switch matrix, connected everything to the RPi Pico, and then assigned some footprints. i need to double check everything right now, so once i come to this again, i will recheck the footprints so all keys are correctly mapped. i think everything might be well and good :)

although, one thing that bugs is that the minimum pcb orders are like 5, so idk what to do with the remaining 4 pcbs. but we'll see what to do about it later. right now, im pretty hyped up!

<img width="1177" height="416" alt="image (7)" src="https://github.com/user-attachments/assets/53ea5b7e-7fb7-4565-a3bd-7f556a0e36a8" />

heres a ss of my plate that i designed using the swillkb website, its pretty cool


### Recording Links

- https://lookout.hackclub.com/api/media/5f3a849c-c17c-4469-9c85-4971cd376720/video.mp4


## Entry 2
- ID: 5923
- Author: yajur
- Created At: 2026-05-07T17:04:12Z
- Worked for: 1 hour 18 minutes

### Content

continued on the work left yesterday, apparently i had done some blunders :P. anyways, redid the connections, edited footprints to match the keys, and added them all to the pcb editor. tomorrow, im going to fix, THIS.

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MTI0ODQsInB1ciI6ImJsb2JfaWQifX0=--55e185326acc3d4e0b1fc7d66c3ab681c1183519/image.png)

YEAH, rats nest.

### Recording Links

- https://lookout.hackclub.com/api/media/ceab856b-4d7b-44f3-8d52-44b907fc9714/video.mp4

## Entry 3
- ID: 6070
- Author: yajur
- Created At: 2026-05-08T10:46:37Z
- Worked for: 1 hour 56 minutes

### Content

i would be super happy but something crazier happened.

well today, i just setup the keys in the shape of my keyboard, and placed the diodes behind them, and then started routing.

i may have to change the location of some connections to make it simpler but thats not even the craziest part, RIGHT AS I WAS ABOUT TO SAVE WHATEVER I DID, MY POWER WENT OUT, AND I LOST EVERYTHING.

yes. all the diodes placements, connections, everything. i mean it is what it is and this kinda gives me a change to revisit my connections again.

anyway, ill come back to this later (with the connections fixed again) complete the pcb, and get to the firmware!


![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MTI3OTgsInB1ciI6ImJsb2JfaWQifX0=--9cd97444cd9d584b08db8e807b3d83c34ea5a164/image.png)


heres the upsetting screenshot of my doom


### Recording Links

- https://lookout.hackclub.com/api/media/e40e3a29-ea73-4fb1-89ab-404a93e6737f/video.mp4

## Entry 4
- ID: 6222
- Author: yajur
- Created At: 2026-05-09T08:05:57Z
- Worked for: 59 minutes

### Content


routing is kinda hard. i figured out that, well, today :P

i revised my BOM, coz i found some better quality AND less expensive switches, so right now, the bill stands at only around 43 dollars without the pcb.

anyway, i might have to change some connections in the schematic itself, to make the routing easier. ill probably open my old mechanical keyboard and have a look at it to understand it better.

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MTMxOTIsInB1ciI6ImJsb2JfaWQifX0=--b4a8a1f2ec2d3c6c1c346209ab3a96986bd3c640/image.png)


heres a current 3d model of my pcb, and hopefully today ill complete the routing.

### Recording Links

- https://lookout.hackclub.com/api/media/acc81f33-3858-4a29-ac13-3e9b230aa9a9/video.mp4
  

## Entry 5
- ID: 6470
- Author: yajur
- Created At: 2026-05-10T18:28:03Z
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
- ID: 6547
- Author: yajur
- Created At: 2026-05-11T07:05:58Z
- Worked for: 2 hours

### Content

FIRMWARE IS COMPLETED!

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MTQwODMsInB1ciI6ImJsb2JfaWQifX0=--149ce1874ba66de9d34669a4b283539a798f0764/image.png)

and HERES THE FINAL PCB DESIGN!!


![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MTQwODQsInB1ciI6ImJsb2JfaWQifX0=--472d8eeec0225bd425c7bdfabaaba6394ecc936f/image.png)

im so insanely happy, because this means im actually extremely close to finishing this! the only things left is the switch plate, which ill edit and finalise very soon (today most probably)


### Recording Links

- https://lookout.hackclub.com/api/media/59a9abd1-e22c-4c48-9f89-76369608c2d8/video.mp4

## Entry 7
- ID: 6914
- Author: yajur
- Created At: 2026-05-13T10:07:24Z

### Content

did cad work today, pretty basic.

first i had to edit the switch plate to accommodate the increase in size of the pi. then, i realised theres enough space to add an oled!

so thats what i did. added SSD1306 oled display, and positioned it.


![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MTUxMTMsInB1ciI6ImJsb2JfaWQifX0=--b86abb92ab81a7d20be9e82b9a98ce5a7987bd19/image.png)

### Recording Links

- https://lookout.hackclub.com/api/media/a5da7c6f-0a73-4071-98da-929c07a3b514/video.mp4
