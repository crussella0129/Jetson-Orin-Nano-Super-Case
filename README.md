# Jetson-Orin-Nano-Super-Case
An Open Source Desktop Case Design for Nvidia's Jetson Orin Super Developer Kit. 3d printable or CNC machinable in STEP format. 

V2.0 Standard Version - No GPIO/Pin Cutout ("sleek" desktop design)
<img width="1163" height="913" alt="image" src="https://github.com/user-attachments/assets/adbb80b5-4fe0-4734-b6d6-bb37ca74543a" />

V2.0 GPIO/Pin Cutout Version ("prototyping friendly" desktop design) 

<img width="1114" height="881" alt="Screenshot 2026-01-29 162449" src="https://github.com/user-attachments/assets/7e72deba-b0b9-4b64-b40c-8fce767b22b6" />

V1.6 GPIO Cutout version (prototype focused design with max board accessibility)

<img width="1066" height="807" alt="image" src="https://github.com/user-attachments/assets/7345c499-3355-4811-9abc-9f051e52123c" />

I/O access (improved in 1.3)

<img width="977" height="648" alt="image" src="https://github.com/user-attachments/assets/1a3de593-4f46-4d22-8859-0b24b0bd1c50" />


------------------------------------------------------------------------------------------------------------------------------------------------------

*Some Key Features*

- Filleted fan duct and large exhaust ports for optimized air cooling. 
- Large pocket for NVME devices in bottom half, can accomodate permanent heatsinks such as those on "Crucial T705"
- Plenum system that cycles air from the top of the board to the bottom and out of the case:
  <img width="1339" height="898" alt="image" src="https://github.com/user-attachments/assets/dcc87b9a-f9f5-4b9d-a64b-facc6b31dc54" />


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
 
  - Place the Jetson Orin Nano Board *CAREFULLY* into the top half of the case. (Fig 4)
  - Fig 4
    ![IMG_9222](https://github.com/user-attachments/assets/f836c499-75dd-463c-b43d-0acc4dda9256)

  - Place the top half onto a sturdy table, or work surface, face down. Then, align the bottom half such that the plenum/recess is directly beneath the aux NvME port.
  - Insert the M3 machine screws, then tighten, to attach the two halves.
  - Use rubber feet, if desired, to minizmize sliding or wobble.
     
- CNC Machining:
  - Offset the screwholes on the top half down to a total diameter of ~2.6mm, \
  - hand tap.
  - Assemble as instructed above in "3d print". 
