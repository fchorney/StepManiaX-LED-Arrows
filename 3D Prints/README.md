# 3D Prints
This step requires you to print all the necessary models and put them together.

<img src="./Photos/Arrow 3 Piece.png" width="300" alt="Arrow 3 Piece">
<img src="./Photos/Arrow 5 Piece.png" width="300" alt="Arrow 5 Piece">
<img src="./Photos/Back Plate top and Connector.png" width="258" alt="Back Plate">
<img src="./Photos/Center Panel.png" width="300" alt="Center Panel">
<img src="./Photos/Center Panel Explode.png" width="300" alt="Center Panel Explode">

### Included Items
Breakdown of items included in this folder:
- [STL Model files for all pieces](./Models/STL/)
- [3MF Build Plate files specifically for the Bambu Labs X1-Carbon](./Models/3MF%20for%20Bambu%20Labs%20X1-Carbon)
- [A copy of the Fusion360 file used for modeling](./Models/SMX%20Items%20v2.f3d)

## Material
For this project I opted to print all of my models using OVERTURE PETG (Black, White, and Transparent).
I imagine you could very well print this in PLA or your material of choice, but keep in mind that PLA is stiffer and
more brittle. I feel like PETG is a good material for this as it's a little more forgiving to stress, bending, etc. 

I chose to use a Transparent filament for the top pieces so I get a good amount of light shining through, but I imagine
that you could just as easily use White, or some other light coloured material depending on how much light you want
to shine through. 

## What to Print
This guide assumes you want to print the full set of 4 cardinal arrows and 1 center arrow. 

The only bit of customization here would be the style of cardinal arrow you want to print. I have included
both a version with a single top piece, or a version with top piece split into three pieces. I believe the version split
into three pieces is the more "proper" design, but the single piece is most likely easier to print and simulates the
"cel" note skin for SMX. 

All that being said, here's what you'll need:
- 5 x Back Plate
- 4 x Back Plate Connector
- 1 x Center Base
- 1 x Center Insert Inner
- 1 x Center Insert Middle
- 1 x Center Insert Outer
- 1 x Center Top Inner
- 1 x Center Top Outer
- 4 x Arrow Base

If you want to print the three piece arrows you will also need:
- 4 x Arrow Insert for 3 Piece
- 4 x Arrow Top Head for 3 Piece
- 4 x Arrow Top Body for 3 Piece
- 4 x Arrow Top Tail for 3 Piece

If you want to print the one piece arrows instead, you will need:
- 4 x Arrow Insert for 1 Piece
- 4 x Arrow Top for 1 Piece

## Print Settings, Tips and Tricks

### Back Plate
The Back Plates can be a little tricky to print as they are not only very large, but need some considerable supports to
support the gap the wire channels on the bottom leave. I would suggest dailing in some good support settings and hope
for the best. At one point I tried using PLA as support material for my PETG Back Plates, but that didn't quite work
all that well. Your mileage may vary. 

General Print Settings:
- Layer Height: 0.2mm
- Walls: 4
- Surface Pattern: Monotonic Linear
- Top Layers: 5
- Bottom Pattern: Monotonic
- Bottom Layers: 3
- Infill: 25%
- Infill Pattern: Gyroid
- Support Type: Normal
- Support Interface Distance: 0.2mm
- Support Top Interface Layers: 3
- Brim Type: Outer Brim Only
- Brim Width: 10mm
- Brim-Object Gap: 0.08mm

### Back Plate Connector
Honestly, I found that this really wasn't enough to hold the plates together and I had to use a bunch of super glue, but
either way if you want a tight fit for this connector, you can try printing increasing the scale by small amounts until
you get the fit you are looking for. I suggest not scaling the height, so that it still ends up being flush.

Overall the print settings don't matter too much, but I suggest the following:
- Layer Height: 0.2mm or smaller
- Infill: 100%
- Brim Type: Outer Brim Only
- Brim Width: 3mm
- Brim-Object Gap: 0.2mm

### Insert Pieces
For the insert pieces, I opted to print them upside down and used supports for the overhangs. In this instance I found
using a different material for the interface layer (PLA for PETG) to work quite well.  The only reason I did this
was because I have a textured build plate and really like the texture on the bottom layers and wanted to have that
texture on the top side of my inserts. If you don't care about that, then just print them right side up and save
yourself the trouble. 

General Print Settings:
- Layer Height: 0.2mm
- Walls: 3
- Surface Pattern: Monotonic Linear
- Top Layers: 5
- Bottom Pattern: Monotonic
- Bottom Layers: 2
- Infill: 15%
- Infill Pattern: Gyroid
- Support Type: Normal
- Support Interface Material: PLA
- Support Interface Distance: 0 (This should probably be 0.2mm if you are using the same material)
- Support Top Interface Layers: 3
- Brim Type: Outer Brim Only
- Brim Width: 7mm
- Brim-Object Gap: 0.2mm

### Base Pieces
The Base pieces have an indent on the bottom for orientating them properly with the back plates. Again just try to find
some good overhang settings. In this instance I found using a different material for the interface layer (PLA for PETG)
to work quite well. 

General Print Settings:
- Layer Height: 0.2mm
- Walls: 3
- Surface Pattern: Monotonic Linear
- Top Layers: 5
- Bottom Pattern: Monotonic
- Bottom Layers: 2
- Infill: 10%
- Infill Pattern: Gyroid
- Support Type: Normal
- Support Interface Material: PLA
- Support Interface Distance: 0 (This should probably be 0.2mm if you are using the same material)
- Support Top Interface Layers: 3

### Top Pieces
For these pieces I would print them upside down (so the cavity is pointing up) and use a decently large brim. I 
personally had a lot of issues with bed adhesion as the surface area on the bed is fairly small. 

General Print Settings:
- Layer Height: 0.16mm
- Walls: 4
- Surface Pattern: Monotonic Linear
- Top Layers: 1
- Bottom Pattern: Hilbert Curve (For extra diffusion)
- Bottom Layers: 1
- Infill: 100%
- Infill Pattern: Aligned Rectilinear
- Support Type: None
- Brim Type: Outer Brim Only
- Brim Width: 15mm
- Brim-Object Gap: 0.2mm or 0.1mm if 0.2mm is giving you trouble still

# ⚠️ Warning ⚠️
At this point, I would suggest not gluing anything together. We will cover that in the `wiring` section.
