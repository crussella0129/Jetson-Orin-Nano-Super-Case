# Jetson-Orin-Nano-Super-Case
An Open Source Desktop Case Design for Nvidia's Jetson Orin Super Developer Kit. 3d printable or CNC machinable in STEP format. 


<img width="1207" height="832" alt="image" src="https://github.com/user-attachments/assets/99cc5d5a-38a9-47cc-a67c-cacf9ece3620" />

Standard Version (No GPIO Cutout)

<img width="1066" height="807" alt="image" src="https://github.com/user-attachments/assets/7345c499-3355-4811-9abc-9f051e52123c" />

GPIO Cutout version

<img width="977" height="648" alt="image" src="https://github.com/user-attachments/assets/1a3de593-4f46-4d22-8859-0b24b0bd1c50" />

I/O access (improved in 1.3)

------------------------------------------------------------------------------------------------------------------------------------------------------

*Some Key Features*

- Filleted fan duct and large exhaust ports for optimized air cooling. 
- Large pocket for NVME devices in bottom half, can accomodate permanent heatsinks such as those on "Crucial T705"
- Small Vent holes for nvme venting as well, fan drives cooling as the entire internal cavity acts as a plenum (see below)
  <img width="1339" height="898" alt="image" src="https://github.com/user-attachments/assets/dcc87b9a-f9f5-4b9d-a64b-facc6b31dc54" />


------------------------------------------------------------------------------------------------------------------------------------------------------

*Assembly Instructions*

- 3d print:
  - Select the STEP files that meet your needs, import into your slicer as you would an STL file, then print.

    -Tip: In slicers like Bambu Lab Studio and Prusa Slicer, the import settings will ask you to adjust two sliders. Drag them to be as low as possible, such that the "number of faces" is close to (but under) 1 million faces. More detail is higher resolution.
  - After printing, insert ruthex M3 threaded inserts (this model was made for these: https://www.amazon.com/dp/B08BCRZZS3?ref_=ppx_hzod_title_dt_b_fed_asin_title_0_3&th=1) in the top half's screw holes.
  - Place the Jetson Orin Nano Board *CAREFULLY* into the top half of the case.
  - Place the top half onto a sturdy table, or work surface, face down. Then, align the bottom half such that the plenum/recess is directly beneath the aux NvME port.
  - Insert the M3 machine screws, then tighten, to attach the two halves.
  - Use rubber feet, if desired, to minizmize sliding or wobble.
     
- CNC Machining:
  - Offset the screwholes on the top half down to a total diameter of ~2.6mm, \
  - hand tap.
  - Assemble as instructed above in "3d print". 
