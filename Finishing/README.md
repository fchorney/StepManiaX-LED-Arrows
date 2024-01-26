# Finishing the project

At this point we can assume you have the following items from the previous sections:
- 4 x 3D Printed Arrow Bases + Connected (glued) Insert/Tops
- 1 x 3D Printed Center Base + Connected (glued) Inserts/Tops
- 5 x 3D Printed Back Plates
- 4 x 3D Printer Back Plate Connectors
- 1 x SMX Wire Harness/Splitter (already installed in SMX pad)
- 1 x SMX Molex -> JST XH-Series cable (already installed in SMX pad)
- 1 x Circuit Board (populated and soldered together)

Tools and products you will need for finishing:
- Hot Glue Gun w/ Hot Glue Sticks
- Super Glue
- [12v 7A DC Power Supply](https://www.aliexpress.us/item/1005006333977811.html) 
- [18/20/22 AWG Stranded Hookup Wire (Black, Red)](https://www.aliexpress.us/item/1005002288468147.html)
- [HSC8 6-4 Ferrule Crimper](https://www.amazon.ca/gp/product/B08CXT9Y8L/ref=ppx_yo_dt_b_search_asin_title)
- [Ferrule Terminal Kit](https://www.amazon.ca/Lytool-Insulated-Connectors-Terminals-Single-Line/dp/B0BY2CS16J/ref=sr_1_8)
- [Heat Shrink Tubing](https://www.amazon.ca/Wirefy-180-Heat-Shrink-Tubing/dp/B084GDLSCK/ref=sr_1_5)
- [1/2 Inch Braided Cable Sleeves](https://www.amazon.ca/Pack-33ft-Protector-Expandable-Sleeving/dp/B07ZT9PL72/ref=sr_1_12)
- [JST-SM Male/Female 2P Connectors](https://www.aliexpress.us/item/1005005780885587.html)
- Soldering Station
  - SN63/PB37 Solder
  - Solder Flux

Notes:
- For the 12v power supply, you won't need 7A for just one pad. It's up to you to figure out how many amps you'll need
based on how many LEDs you are powering. 
- For the hookup wire, I opted to use a thicker AWG for going from the circuit board to the LEDs as the distance
travelled is fairly long and I figured a thicker cable would be better in that case. From what I've read, 22 AWG
should realistically be more than enough to carry about 1A of power to each arrow.

## Power Supply
Assuming you bought a similar power supply to the one linked in the materials above, you will need to cut off the DC 
end of the cable and attach some Ferrule ends to the ground and live wires since we're using screw terminals rather
than a barrel jack. 

Simply snip off the barrel jack at the end, expose enough of the 2 wires (typically black and red), remove some of the
wire jacket and terminate with ferrules of the correct size using a ferrule crimper. These will simply go into the 
12v input screw terminals on our circuit board. 

If you are making 2 (for 2 SMX pads) you can terminate some 18AWG (or thicker) wire with ferrules on both ends to daisy
chain the 2 circuit board 12v supplies together. 

## 3D Prints
### Back Plates
At this point we can finish up our 3D prints and wiring for the LEDs. 

Firstly you'll want to super glue all the back plates together. I suggest lining them all up in the plus shape (
4 cardinal arrows and one center panel), use some super glue on the touching edges, add some super glue to the back
plate connector slot and put a back plate connector in each relevant slot (the 4 in the center panel). Leave this alone
to harden over time.

### Arrows
Once the back plates have been securely glued together, you can glue the arrow bases (not the insert/tops) to the 5
back plates. Simply add some super glue to the indent on the bottom of each center/arrow base, line it up with the back
plate so the nub in the middle of the back plate goes in to the base indent, line up the wire holes on the base with
the ones on the back plate, and leave it to harden. This might take a while to harden as the super glue won't really be
exposed to a lot of air there. 

## Wiring
So now we have the backplates and arrow bases securely glued to each other. At this point you're going to want to 
determine how much wiring you will need for each arrow to reach the circuit board for your specific setup. As you can
see in the picture in the base of the repo, my arrows are fairly high up my wall and the wire goes all the way down to
the ground. I determined how much stranded wire I would need for each arrow and cut the pieces. 

For each arrow, you will want to solder your stranded hookup wire (I suggest 18 or 20 AWG) to the opposite type of 
JST-SM connector that you used in the arrow LED section. If you used male for the LEDs, use female for these wires, or
vice versa. What I did was expose wire from the JST-SM connectors, as well as my stranded wire, connected them together,
by twisting, soldered them together and applied some heat shrink to protect the connection. Do this for all 5 pairs of
wire.

At this point you want to route your wire (the non connector side) through the cable holes of the arrow bases/back plates
so that you end up with the connector inside the arrow. Connect the 2 JST-SM connectors, and use some hot glue to provide
strain relief at the holes, and keep all wires down and in place. 

Now that we have wires coming out of the back of all 5 arrows, you essentially want to route them all through the cable
channels on the back of the backplates so they all come out of the bottom arrow. Use hot glue liberally here to keep
them in place and provide strain relief.

This step is optional, but I used 1/2 inch braided cable sleeves to contain all 10 of my wires coming out of the bottom
arrow until it hits my circuit board. Use the cable sleeves, as well as some heat shrink tubing to make it look nice.

Now you can clip the ends of the wire group to be flush if you'd like, and use the ferrule crimper to crimp ferrules
onto the 10 LED wires. 

### Glue Arrow Tops

You can now superglue the arrow inserts/tops onto the arrow bases.

❗Warning: Remember, this is essentially permanent at this point, so make sure all your wiring is correct and working.

## Connecting
Attach these to the circuit board screw terminals that match the arrows. 

⚠️ Remember: If the arrows are behind you, the "right" input should hook up to the "left" arrow if you are looking
straight at them. Thankfully this is easy to reverse if you put it in the wrong way by switching the wires to the other
screw terminal.

Attach the JST-XH 6 pin connector coming out of your SMX stage onto the circuit board. 

Connect the power inputs (and outputs if you have them) to the circuit board.

## Mount Arrows
Stick your arrows and backplates to your wall somehow! That's up to you to figure out.

What I did was use about 8 x [3M Command Strips](https://www.command.com/3M/en_CA/p/d/v000584005/) at various points
on the back of the backplates to stick to my wall. Fairly clean and easy to remove if necessary. 

# Enjoy

Congratulations! At this point you should be finished! Turn on StepManiaX, plug in your 12v power supply and dance your
heart out! 

⚠️ If you had any issues with this guide, questions, or comments I encourage you to please open up an issue in this
repository.
