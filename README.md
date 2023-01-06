# A-One 286

Replica of a 286 Mainboard

# PCB Revision History

- V0.1 Initial revision 2022 made with Sprint-Layout
- V0.2 Silkscreen updated, component positions and mounting holes modified
- V0.3 First working revision

# Specs

This replica of a 286 motherboard is based on the Headland HT12P-16/A chipset. It supports 286 CPUs.

# Images

Top view
[![](images/top.jpg 'top view')](#topview)

# Bill of materials

| Quantity | Description                    | PCB/Schematic's Reference                                                                                                                                                                    |
| -------- | ------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 17       | CAP ELKO 10 uF 25 V            | C1, C6, C9, C11, C15, C17, C22, C24, C27, C30, C34, C36, C49, C66, C67, C68, C69                                                                                                             |
| 39       | CAP CER 100 nF RM 5,0          | C2, C3, C4, C7, C8, C13, C14, C18, C20, C21, C25, C28, C29, C31, C35, C39, C40, C41, C42, C43, C44, C45, C46, C50, C51, C52, C53, C55, C56, C57, C58, C59, C60, C61, C62, C64, C65, C70, CXX |
| 2        | CAP CER 15 pF RM 5,0           | C32, C33                                                                                                                                                                                     |
| 1        | CAP CER 27 pF RM 5,0           | C12                                                                                                                                                                                          |
| 3        | CAP CER 47 pF RM 5,0           | C38, C47, C48                                                                                                                                                                                |
| 1        | CAP CER 4.7 nF RM 5            | C19                                                                                                                                                                                          |
|          | n.c.                           | C5, C10, C16, C23, C26                                                                                                                                                                       |
| 4        | DIODE 1N4148                   | D1, D2, D3, D4                                                                                                                                                                               |
| 1        | CON 5 PIN                      | J1 Keylock & Power LED                                                                                                                                                                       |
| 2        | CON 4 PIN                      | J2 Speaker, J6 Battery                                                                                                                                                                       |
| 3        | CON 2 PIN                      | J3 Turbo LED, J4 Turbo switch, J5 Reset switch, JP1 Monochrome/Color                                                                                                                         |
| 1        | CON AT Power connector         | CN1 Power                                                                                                                                                                                    |
| 1        | CON DIN 5                      | CN2 Keyboard                                                                                                                                                                                 |
| 2        | Ferrite                        | L1, L2                                                                                                                                                                                       |
| 1        | Quarz 32 MHz                   | OSC1                                                                                                                                                                                         |
| 1        | Quarz 14.31818 MHz             | OSC2                                                                                                                                                                                         |
| 2        | 3904                           | Q1, Q3                                                                                                                                                                                       |
| 1        | 3906                           | Q2                                                                                                                                                                                           |
|          | n.c.                           | R15, R29, R37, R38, RP1, RP3                                                                                                                                                                 |
| 1        | RES 22 Ohm 5% 1/4W             | R27                                                                                                                                                                                          |
| 8        | RES 33 Ohm 5% 1/4W             | R1, R2, R21, R22, R23, R24, R26, R31                                                                                                                                                         |
| 1        | RES 47 Ohm 5% 1/4W             | R34                                                                                                                                                                                          |
| 2        | RES 150 Ohm 5% 1/4W            | R3, R4                                                                                                                                                                                       |
| 4        | RES 330 Ohm 5% 1/4W            | R10, R11, R16, R20                                                                                                                                                                           |
| 4        | RES 470 Ohm 5% 1/4W            | R5, R12, R14, R25                                                                                                                                                                            |
| 6        | RES 1 k Ohm 5% 1/4W            | R6, R13, R17, R30, R39, R40                                                                                                                                                                  |
| 6        | RES 10 k Ohm 5% 1/4W           | R8, R9, R18, R33, R35, R36 ??                                                                                                                                                                |
| 1        | RES 51 k Ohm 5% 1/4W           | R7                                                                                                                                                                                           |
| 1        | RES 100 k Ohm 5% 1/4W          | R28                                                                                                                                                                                          |
| 2        | RES 2 M Ohm 5% 1/4W            | R19, R32                                                                                                                                                                                     |
| 1        | RES Network 22 Ohm 4x parallel | SIP1                                                                                                                                                                                         |
| 4        | RES Network 47 Ohm 4x parallel | SIP2, SIP3, SIP4, SIP5                                                                                                                                                                       |
| 2        | RES Network 1 kOhm 9+1 Stern   | RP2, RP7                                                                                                                                                                                     |
| 7        | RES Network 10 kOhm 9+1 Stern  | RP4, RP5, RP6, RP8, RP9, RP10, RP11                                                                                                                                                          |
| 4        | CON 30 POL SIM                 | SIM1, SIM2, SIM3, SIM4                                                                                                                                                                       |
| 1        | CON 8 Bit ISA Socket           | SL1                                                                                                                                                                                          |
| 5        | CON 16 Bit ISA Socket          | SL2, SL3, SL4, SL5, SL6                                                                                                                                                                      |
| 1        | 74LS244                        | U1                                                                                                                                                                                           |
| 3        | 74HCT373                       | U2, U3, U10                                                                                                                                                                                  |
| 1        | 74LS245                        | U4                                                                                                                                                                                           |
| 1        | 74HCT14                        | U5                                                                                                                                                                                           |
| 1        | HD146818P                      | U6                                                                                                                                                                                           |
| 1        | 74LS245                        | U7                                                                                                                                                                                           |
| 1        | HT12P-16/A                     | U8                                                                                                                                                                                           |
| 1        | 80C286                         | U9                                                                                                                                                                                           |
| 1        | P8042AH                        | U11                                                                                                                                                                                          |
| 1        | 74F245                         | U12                                                                                                                                                                                          |
| 1        | BIOS HI                        | U13                                                                                                                                                                                          |
| 1        | 80287                          | U14                                                                                                                                                                                          |
| 1        | BIOS LO                        | U15                                                                                                                                                                                          |
| 2        | 41256                          | U18, U19                                                                                                                                                                                     |
| 8        | 44256                          | U20, U21, U22, U23, U26, U27, U28, U29                                                                                                                                                       |
| 0        | ???                            | U24, U25                                                                                                                                                                                     |
| 1        | 7406                           | U30                                                                                                                                                                                          |
| 1        | 74F125                         | UX1                                                                                                                                                                                          |
| 1        | 74LS86                         | UX2                                                                                                                                                                                          |
| 1        |                                | Y1                                                                                                                                                                                           |
| 1        | 8 MHz                          | Y2                                                                                                                                                                                           |

# Notice

# Licence

The project is free for non-commercial reproduktion. Do not sell it on ebay or other platforms for profit. Do not make a closed source. Share your experiences and ideas with the community.
