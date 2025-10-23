# Mechaboard
A   Custom 48-Key RGB Keyboard Build



<img width="942" height="521" alt="Screenshot 2025-10-23 082613" src="https://github.com/user-attachments/assets/d5a787dd-c733-44e7-a1d2-d069b916b356" />



Welcome to my custom 48 key RGB keyboard project. This is a personal build where I combined hands-on PCB design, Fusion 360 modeling, and custom components to create a fully functional and visually appealing keyboard. The keyboard uses Outemu Blue mechanical switches, SMD diodes, and one RGB LED per key. I added a rotary encoder with a knob for extra custom control, giving it that small personal touch I wanted.



<img width="1180" height="678" alt="Screenshot 2025-10-23 082652" src="https://github.com/user-attachments/assets/4b7e8bd3-29f6-48b0-adcf-b55f7344ab39" />


The case design is completely finished, key placement has been finalized, and I even completed renders to visualize the keyboard from multiple angles. The PCB is designed in EasyEDA and is ready for ordering. All components have been gathered in a complete BOM file, which is included in the repository. The README has been updated to reflect the current status of the project, so anyone looking at it can immediately understand how far the build has progressed.


<img width="1018" height="671" alt="Screenshot 2025-10-23 084156" src="https://github.com/user-attachments/assets/58443c3f-ecdd-4fd3-9ccd-a2f5f5bdd4a3" />



For assembling the keyboard, the workflow starts with ordering the PCB and all components as per the BOM file. Once the switches, diodes, and LEDs are mounted on the PCB, it can be installed inside the 3D-printed case. The keycaps and the rotary knob are then added, and finally, the functionality can be tested using the Arduino Pro Micro board. Seeing the keyboard go from just circuits on a PCB to a complete, almost ready-to-build model has been incredibly satisfying. Every detail, from switch alignment to key placement and the rotary knob, has been carefully considered to make it look and feel like a true custom keyboard.

<img width="802" height="458" alt="Screenshot 2025-10-23 231604" src="https://github.com/user-attachments/assets/422e984c-9bcc-47e4-bdbb-607cb664488f" />

<img width="1146" height="740" alt="Screenshot 2025-10-23 231533" src="https://github.com/user-attachments/assets/c9fd4b88-3063-43d0-9037-7a15fc73b6b2" />

<img width="1002" height="530" alt="Screenshot 2025-10-23 231554" src="https://github.com/user-attachments/assets/a2959e85-6f05-487c-843e-663ca82d946a" />


## BOM

| Component                                       | Source                      | Quantity               | Total Cost (INR) | Notes                                 |
| ----------------------------------------------- | --------------------------- | ---------------------- | ---------------- | ------------------------------------- |
| Blue Mechanical Switches (OUTEMU Blue, 32-pack) | Amazon.in                   | 2 packs (≈64 switches) | 4246             |                           48 keys     |
| PBT Dye-sublimated Keycaps (Black)              | NeoMacro.in                 | 1 set                  | 2200             | Estimate based on earlier pricing     |
| Hot-swap Sockets (Kailh MX Hotswap Socket v1)   | NeoMacro.in                 | 6 packs (≈60 sockets)  | 660              |             48 keys + buffer          |
| WS2812B RGB LEDs (individual)                   | Amazon.in                   | 48                     | 480              | One LED per key                       |
| SMD Diodes (1N4148)                             | Amazon.in / designated site | 48                     | 90               | One SMD diode per key                 |
| Rotary Encoder (EC11 type)                      | Amazon.in / NeoMacro.in     | 1                      | 170              |                                       |
| Encoder Knob                                    | NeoMacro.in / Amazon.in     | 1                      | 85               |                                       |
| Arduino Pro Micro (ATmega32U4 board)            | Robu.in / Amazon.in         | 1                      | 649              | Using latest listing from Robu/others |
| Custom PCB (5 pcs, Black, 1.6 mm, HASL)         | JLCPCB                      | 5 pcs                  | 4500             | Rough cost estimate                   |
| Shipping (PCBs)                                 | JLCPCB                      | 1                      | 425              |                                       |
| **Total Approximate Cost**                      |                             |                        | **12315**        |                                       |


