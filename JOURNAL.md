---
title: "Binary adder"
author: "Traffic person"
description: "Binary adder: 2 binary inputs 1 binary output"
created_at: "2026-07-30"
---
# June 30: made the base schematics
Originally i wanted on off, reset button, 5 input A, 5 input B and a 8 LED output

but that wasn't very smart because with 2 5 bit inputs you can only achieve a maximum number of 62 and with a 6 bit output you will get a max of 63

I made a simple on off i 5 inputs on side A 5 on side B and a 6 LED output

I tried to make a reset button with a NOT gate but i realised that was kinda like too complex when you can just power it off and on again for the same result

I also learned about binary addition and it took me a bit to grasp but i think i understand the carry thing now

And i added a 10 kilo ohm resistor to every button and that goes to ground because the internet said if it wont have that it will be a floating input (randomly 0 or 1 from what i understood)

<img width="603" height="787" alt="Screenshot 2026-07-30 225113" src="https://github.com/user-attachments/assets/ba1165da-166b-476d-89f0-d86e459e0df0" />

[The Timelapse](https://lapse.hackclub.com/timelapse/Thh0iD-BY0wq)

**Total time spent: 46 minutes**

# June 31: Logic

I made the logic inside of minecraft to simulate it and it worked great so i transported it into my schematic

it works on a basis of 2 gates: XOR and AND basically it takes 2 inputs puts them through a XOR together and a AND together (in parallel)

The AND output is the Carry and the XOR output is the Sum (what gets printed)

The full adder formula: A B -> XOR -> (A XOR B) XOR Carry -> Sum

It uses half adders and full adders

I have also routed the pcb

The Minecraft Adder:

<img width="971" height="503" alt="Screenshot 2026-07-31 140710" src="https://github.com/user-attachments/assets/3c9927f4-9ff8-4ca1-ba34-4b72a4fd8bdc" />

The Reworked Schematic:

<img width="542" height="712" alt="Screenshot 2026-07-31 144446" src="https://github.com/user-attachments/assets/f8ffe7ca-db57-4286-8d25-ff46040889da" />

The pcb:

<img width="1282" height="536" alt="Screenshot 2026-07-31 181507" src="https://github.com/user-attachments/assets/728ee33a-91a2-447b-8405-4341aabadd0b" />

[Timelapse](https://lapse.hackclub.com/timelapse/kfTMp7sw0622)
[second timelapse](https://lapse.hackclub.com/timelapse/zCNVK4dlRbu3)

**Total time spent: 3 hours 6 minutes**
