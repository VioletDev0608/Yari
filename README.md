# Yari
Yari is a 38 key columns-staggered choc split keyboard. It is designed to reduce the required thumb movement beneath the palm.
It has 2 LEDS to indicate battery levels, splayed pinky and row columns, and is meant to be used with a Supermini nRF52840 microcontroller.

## Features:
- 36 Keys
- Column staggered
- Choc v1
- Splayed pinky and row columns
- 2 LEDS for battery indication
- ZMK support
- Wireless

## CAD Model:

The assembly itself is quite simple
Use a soldering iron to heat up the threaded screw inserts and help it melt its way into the slightly undersized standoff holes. Secure the PCB using the M2 screws. 
<img width="523" height="438" alt="スクリーンショット 2025-11-27 002014" src="https://github.com/user-attachments/assets/e89d95b6-3443-4c6b-a5ac-4f6749703f23" />
<img width="1156" height="744" alt="スクリーンショット 2026-01-14 163927" src="https://github.com/user-attachments/assets/0913e862-746d-47d1-8dd4-c45baa73b8b8" />


## PCB

Most of the PCB was created using ergogen so I don't have a silkscreen to show!
There are quotes scattered around the PCB so make sure to enjoy them.
<img width="1227" height="843" alt="スクリーンショット 2025-11-23 235945" src="https://github.com/user-attachments/assets/35e2a5b3-6bbd-42ff-9691-34a4fa548881" />
<img width="1104" height="812" alt="pcb" src="https://github.com/user-attachments/assets/6ff2ea3e-0590-4769-9346-86cb7b52ef50" />

## Firmware

Firmware is based on ZMK!
Hasn't been tested yet...

## BOM
Here is everything you need to build the Yari.

- 2x Yari PCB
- 2x Supermini nRF52840
- 36x Choc v1 switches
- 36x 1N4148W Diodes (SMD diodes in the SOD123 package)
- 36x 1u Choc keycaps (MBK,LDSA,CFA etc)
- 2x Reset Button (Panasonic EVQ-PU[A|C|J|L]02K)
- 2x Power Switch (SSSS811101)
- 1x USB-C cable for charging
- 2x Lipo Battery (301230)
- 4x LED (SK6812mini-e)
- 36x Choc switch sockets(Kalih)
- Rubber feet

3D printed case parts(Optional)

- 2x 3D printed case (Right and Left)
- 10x Threaded screw inserts (M2x3x3.2)
- 10x M2 laptop-style flathead screws(M2x3)
