# Jetson-Orin-Nano-Super-Case (v3.1a)
An Open Source Desktop Case Design for Nvidia's Jetson Orin Super Developer Kit. 3d printable or CNC machinable in STEP format. *Have Questions, Need Help, or Want One Printed? Email charles@threadandsignal.com*

V3.1a Standard Version - No GPIO/Pin Cutout ("sleek" desktop design)

<img width="1323" height="929" alt="image" src="https://github.com/user-attachments/assets/0584ca0d-01a9-49d7-8c1a-5b17495367dc" />

<img width="6144" height="8160" alt="PXL_20260918_170755337" src="https://github.com/user-attachments/assets/89d8df5a-59f8-4975-9d97-df59de85c011" />


------------------------------------------------------------------------------------------------------------------------------------------------------

*Some Key Features*

- Bellmouth fan duct and spacious exhaust ports for optimized air cooling. 
- Large cavity for NVMe devices in bottom half, can accomodate permanent heatsinks such as those on "Crucial T705" or SDR/Network cards that are NVMe compatibple
- Plenum system that cycles air from the top of the board to the bottom and out of the case:
<img width="1267" height="909" alt="image" src="https://github.com/user-attachments/assets/6279afaa-f9b2-4ea6-9d07-31071f3d8214" />


------------------------------------------------------------------------------------------------------------------------------------------------------

*Assembly Instructions*

- 3d print:
  - Select the STEP files that meet your needs, import into your slicer as you would an STL file, then print.
    - Slicer Tip: In slicers like Bambu Lab Studio and Prusa Slicer, the import settings will ask you to adjust two sliders. Drag them to be as low as possible, such that the "number of faces" is close to (but under) 1 million faces. More detail is higher resolution.
    - Printing Tip: The Figure can be printed oriented as in Fig 1, or can be printed at an angle (Fig 2). For angled printing, select the face indicated in Fig 1 and print at an angle with tree supports, inner and outer brim, and a skirt (see Fig 2). I recommend 3 outer layer walls and apprx 15% gyroid infill. High temp capable filaments like ABS, PA-CF, PC/PC-CF, or PPS-CF, are *strongly reccomeneded*.
    - Fig 1
      <img width="1071" height="627" alt="image" src="https://github.com/user-attachments/assets/84e9967f-d930-42f5-ab3f-323f6b17b132" />

    - Fig 2
      <img width="1475" height="990" alt="image" src="https://github.com/user-attachments/assets/82500565-ce4d-40bf-ba71-6e78e9c403ec" />

  - After printing, insert ruthex M3 threaded inserts (this model was made for these: https://www.amazon.com/dp/B08BCRZZS3?ref_=ppx_hzod_title_dt_b_fed_asin_title_0_3&th=1) in the top half's screw holes. Any standard M3 machine screws will work for this design.
    - Tip: The M3 Screws that work best with the file as is are ~15mm, but you can adjust the height of the "inner circle" with an extrude command (in Fusion, Solidworks, etc...) to match what you have on hand.
    - Fig 3
      ![IMG_9220](https://github.com/user-attachments/assets/99a4a72b-dc4c-41d6-85c0-35002fd225a5)
 
  - Place a jumper across pins 5 and 6, as in Fig 4, then take the buttons and cut the wires such that the total length is ~110-120mm and place the dupont jumpers on the ends of the cables, as in Fig 5. Attach these to the desired corresponding pins on the button header.
  - Fig 4
    <img width="6144" height="8160" alt="PXL_20260918_151950133" src="https://github.com/user-attachments/assets/887e5137-cf13-41e0-819e-fb468b9f4187" />
  - Fig 5
    <img width="6144" height="8160" alt="PXL_20260918_155231439" src="https://github.com/user-attachments/assets/d5a737c8-d1e5-4189-8e50-53ff74cde0b1" />

  - Place the Jetson Orin Nano Board *CAREFULLY* into the top half of the case. (Fig 4)
  - Fig 6
    ![IMG_9222](https://github.com/user-attachments/assets/f836c499-75dd-463c-b43d-0acc4dda9256)

  - Place the top half onto a sturdy table, or work surface, face down. Then, align the bottom half such that the plenum/recess is directly beneath the aux NvME port.
  - Insert the M3 machine screws, then tighten, to attach the two halves.
  - Use rubber feet, if desired, to minizmize sliding or wobble.
     
- CNC Machining:
  - Offset the screwholes on the top half down to a total diameter of ~2.6mm, \
  - hand tap.
  - Assemble as instructed above in "3d print".
 
Latest Updates (V2.1): 
- Altered IO access such that printing with supports is no longer required for the top half
- Added 12.2mm holes for power and reset buttons, available here: https://www.amazon.com/gp/product/B09BKWMNJ9/ref=ox_sc_act_title_1?smid=ALOZL3MQGX35O&th=1
