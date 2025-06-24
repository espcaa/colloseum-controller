---
title: "Colloseum controller"
author: "espcaa"
description: "A controller for undercity-colloseum, a smash-like tournament game at Highway"
created_at: "2025-06-22"
---

Total time spent: 11 hours

# The mysterious and very long (no) journal of the Colloseum controller

## Day 1 (of 2)

I started researching parts, finished the schematic!
I want this to be as cheap as possible so I went with a simple design and the cheapest component i could get on lcsc or simple to source leds/resistors with everything tht. I needed to find a good balance between shady and price :)
I ended up with a simple design with 4 buttons, 4 leds (Like the wii!!) and a usb port (usb-a at first then usb-c cause it's cooler) entirely made on the pcb to save even more costs (a usb port is 1.5$ on lcsc and very hard to solder yourself)
I spent a lot of time trying to understand the joystick schematic to wire it, the easyeda import wasn't very good :(

<img width="500" alt="Screenshot 2025-06-22 at 15 11 10" src="https://github.com/user-attachments/assets/2f36daa7-206c-4012-bb3b-2bdbc4f06a2d" />

Time spent: approx 5 hours

## Day 2 (also of 2)

I finished the PCB wiring, started the case design and finished it! I don't exactly like it but i'll try to iterate over it later!
The pcb is at approx 3$/unit so that's really cool!
I spent a long time on the case (pcb wiring was also hard to do due to the tight space with the usb port) because I first wanted to make it looked good and I also had a lot of issues with importing my pcb from kicad to onshape :pf:. I finally managed to get it working by using assemblies, the right scale and the right import method (every piece in one file)
I tried multiple size before settling on one (not sure if it's the best one but it works for now) and tried to design something that would be somewhat easy to print and wouldn't look that bad while also being (a little bit) ergonomic.
<img width="500" alt="Screenshot 2025-06-22 at 15 12 25" src="https://github.com/user-attachments/assets/03af94ab-572b-4f82-a1da-e22c0890a9a6" />
<img width="500" alt="Screenshot 2025-06-22 at 15 12 13" src="https://github.com/user-attachments/assets/6cf966bb-f9ad-4bc4-be44-9b17aa085534" />

Time spent: approx 6 hours
