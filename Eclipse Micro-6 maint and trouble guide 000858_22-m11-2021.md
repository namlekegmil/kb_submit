# Eclipse

# RESIDENTIAL ELEVATOR

# (with Micro-6 Controller)

# MAINTENANCE AND TROUBLESHOOTING GUIDE

Part No. 00085822-m11-2021

# Standard notations

The following notations may be used throughout this guide to emphasize important safety information, mechanical concerns, and other important information. Please review and follow all of these messages.

# DANGER

Danger messages indicate an imminently hazardous situation, which, if not avoided, results in death or serious injury. All danger messages feature a standard ISO safety alert symbol followed by the signal word Danger in capitalized black lettering on a red background.

# WARNING

Warning messages indicate a potentially hazardous situation, which, if not avoided, could result in death or serious injury. All warning messages feature a standard ISO safety alert symbol followed by the signal word Warning in capitalized black lettering on a dark yellow background.

# CAUTION

Caution messages indicate a potentially hazardous situation, which, if not avoided, could result in death or serious injury. All caution messages feature a standard ISO safety alert symbol followed by the signal word Caution in capitalized black lettering on a yellow background.

# CAUTION

Caution messages that do not include the ISO safety alert symbol indicate a potentially hazardous situation for the machine only, which, if not avoided, could result in damage to the machine. All caution messages include the signal word CAUTION in capitalized black lettering on a yellow background.

# NOTE

Note messages provide information, such as reminders, general information about a previous statement, or additional guidelines that do not fit into the flow of the preceding text. All note messages include the signal word Note in capitalized white lettering on a blue background.

# Hazards and cautions

# WARNING

ELECTRICAL SHOCK HAZARD

Do not connect or disconnect wiring while the power is on. Failure to comply will result in death or serious injury. Before servicing, disconnect all power to the equipment. The internal Capacitor remains charged even after the power supply is turned off. The Charge indicator LED extinguishes when the DC bus voltage is below 50 V DC. To prevent electric shock, wait at least five minutes after all indicators are OFF and measure the DC bus voltage level to confirm safe level.

# WARNING

FIRE HAZARD

Do not use an improper voltage source. Failure to comply could result in death or serious injury by fire. Verify that the rated voltage matches the voltage of the incoming power supply before applying power.

# WARNING

CRUSH HAZARD

Never connect or disconnect the motor from the controller while the controller is outputting voltage. Improper equipment sequencing could result in damage to the controller.

# WARNING

SUDDEN MOVEMENT HAZARD

System may start unexpectedly upon application of power, resulting in death or serious injury. Clear all personnel from the drive, motor, and machine area before applying power. Secure covers, couplings, shaft keys, and machine loads before applying power to the drive. Unpredictable equipment operation may result in death or serious injury.

# WARNING

Make sure the building ground is connected to the controller ground bus before turning the disconnect on. Improper or no ground can result in shocking hazard and unsafe operation.

# WARNING

ELECTRICAL SHOCK HAZARD

Do not attempt to modify or alter the variable frequency drive in any way not explained in the drive unit manual. Failure to comply could result in death or serious injury. Savaria is not responsible for any modifications of the product made by the user. Do not allow unqualified personnel to use equipment. Failure to comply could result in death or serious injury. Maintenance, inspection, and replacement of parts must be performed only by authorized personnel familiar with installation, adjustment, and maintenance. Do not remove covers or touch circuit boards while the power is on. Failure to comply could result in death or serious injury.

# Eclipse (Micro-6 Controller) Maintenance and Troubleshooting Guide

Part No. 000858 (22-m11-2021)

# Disclaimer

Savaria Concord Lifts, Inc. disclaims liability for any personal injury or property damage resulting from the operation of a product that has been modified from the original Savaria design. No person or company is authorized to change the design of this product without written authorization by Savaria.

# NOTE

When replacing parts, use genuine Savaria parts only.

# Revision history of this guide

- January 6, 2009 – Initial release
- January 19, 2010 – Added motor brake adjustment
- April 16, 2010 – Updated company logo and name
- November 14, 2011 (initial release of revised manual with new P/N 000858) – Revised manual to reflect new Micro-6 controller
- April 29, 2013 – Added motor brake information as Appendix B
- June 25, 2013 – Added new STEP 18, chain maintenance on page 22
- July 14, 2015 – Added grounding warning on pages 2 and 12
- December 4, 2015 – Revised motor brake air gap procedure on pages 20 and 21
- February 2, 2016 – Added new Appendix A - Diagnostic Beep Codes
- April 29, 2016 – Revised Warning in drawing on page 6
- June 29, 2017 – Added NOTE above to use only genuine Savaria parts when replacing parts
- January 30, 2018 – Added new controller board (772401) layout on page 7 and new controller board silkscreen on page 9
- April 30, 2018 – Revised car top board drawing on page 11
- October 11, 2018 – Corrected sub-step 4 of STEP 15 on page 23
- November 22, 2021 - Updated page -11

# List of steps in this guide

|Step|Page|
|---|---|
|Wiring harnesses|4|
|Main controller board connections|5|
|Main controller board LEDs and switches|8|
|Car top board connections|11|
|Car top board LEDs|12|
|Selector board connections|13|
|COP board connections|13|
|Power and motor connections|14|
|Sling disassembly|16|
|Sling assembly|18|
|Bottom shoring bracket attachment|18|
|Guide shoe replacement|19|
|Slack chain test for maintenance|20|
|Motor wiring|22|
|Motor brake air gap adjustment|22|
|Rail lubrication|24|
|USB copy tool|24|
|Chain maintenance|25|
|Appendix A Diagnostic Beep Codes|26|
|Appendix B Yaskawa V1000 Fault Tables|26|

Part No. 000858 (22-m11-2021) Eclipse (Micro-6 Controller) Maintenance and Troubleshooting Guide

# Step 1

# Wiring harnesses

Purpose: To illustrate the wiring harnesses. Use this drawing as a general reference when checking the wiring.

# Figure 1 Wiring harnesses — use as reference

|Motor harness 326046|Motor access door harness 326008-XX|
|---|---|
|Top shoring bracket|Door operator|
|Magnetic tape|Hall landing station harness 326009-XX|
|O|Hall call|
|Car top box To selector asm (tape reader) behind cab|Top landing|
|COP|Door operator|
|If controller is remote, run all harnesses to remote mount area|Controller|
|Controller Mounted remotely|Lock|
|Hall landing station harness 326009-XX|Hall call|
|Controller Mounted between rails|Bottom landing|
|Pit|Main disconnect switch|
|Pit harness 326006|Travelling cable harness 326010-XX|
|(goes to either rail mounted or remote controller)|220 Vac|
|110 Vac|Hoistway disconnects (if required)|

Eclipse (Micro-6 Controller) Maintenance and Troubleshooting Guide Part No. 000858 (22-m11-2021)

# Step 2

# Main controller board connections

# Purpose

To verify the Eclipse main controller board connections.

# Procedure

1. The layout of the Micro-6 geared controller box is shown below.

|60w|60w|6074|V10oo|
|---|---|---|---|
|{5 FLUG}|{5 FLUG}|{5 FLUG}|{5 FLUG}|

2 Use the drawings on the next pages to check all connections to the main controller board.

Part No. 000858 (22-m11-2021) Eclipse (Micro-6 Controller) Maintenance and Troubleshooting Guide

# Eclipse (Micro-6 Controller) Maintenance and Troubleshooting Guide

# Part No. 000858 (22-m11-2021)

# Figure 2

Main controller board (772390) connections

# Figure 3

Main controller board (772401) connections

Part No. 000858 (22-m11-2021)

# Eclipse (Micro-6 Controller) Maintenance and Troubleshooting Guide

# Step 3

# Main controller board LEDs and switches

Purpose: To identify the main controller board LEDs and switches.

# Figure 4

Main controller board (772390) LEDs and switches

Eclipse (Micro-6 Controller) Maintenance and Troubleshooting Guide  Part No. 000858 (22-m11-2021)

# Eclipse (Micro-6 Controller) Maintenance and Troubleshooting Guide

# Figure 5

# Main controller board (772401) LEDs and switches

|zavana|PIN: 772401|J6| | |J5| |J4| | | | |
|---|---|---|---|---|---|---|---|---|---|---|---|
|JB|PHI 08|REV 000|6|8|9|3|6|9|9|2| |
|S/N:|PH2|SCTAL8|K2 #TAL*|K10|4A,250v| | | | | | |
|K1| | | |3AG| | |J3|J9|R48| | |
|TCRED|RvS| | | |WARNING|HIGH VOLTAGE DANGER_DISCONNECT POWER|V+|V-| | | |
|J30|TC29|R69|012|DC4|F4| | | | | | |
|TC27| | | | |2A250v| |PT1|DC3|3A,250V| | |
|TC26|R82|D9|R83|R127| | |TC30| | | | |
|TC25|AL|K20|052|3AG|U7| | | | | | |
|TC24|R6+|R63|BK|D54|DC2| | | | | | |
|TC22|07O|IU| |R125|3AG| | | | | | |
|D68|ILD|R5S|J28|FL6|J27| | | | | | |
| | |FL5| |J26|FL4|R47|R44|026| | | |
|TC20|D67|1P3|HDC|DC|R124| | | | | | |
|DC|R3E|TC19|D66|4p2|D56| | | | | | |
| | | |025| |021|R6z| |R92| | | |
|TC18|D65|HDL|DL|R123|DL| | | | | | |
|R8,0|R94|R9S|TC17|045|16C| | | | | | |
| |020|RI18|016|R12|018|R122| | | | | |
|TC16|042|R75|1EL|R74|2EL| | | | | | |
|R7| | | | | | |3|3EL|TC15|041|14C|
| |026| |027| |028|RNI6|R136| | | | |
|TC14|04g|13C| | |RIs-|TC13|039| | | | |
|120| | | | |R152| |R158Ri42|TC12|038| | |
|TC1|Rv9| | | |Ri06|TC10| | | | | |
|J14|R86| | | |Ri08|TC9|IOPF| | | | |
| |12|K16|K17|12|K18|Ri0g| | | | | |
|8|023|TC8|046|IOPR|8| | | | | | |
|RJi|R45|DS1|TC7|048|BZ| | | | | | |
| |R13s|R134|D63|R53|Rij8| | | | | | |
|TC6| |TC5|0z4|K6| | | | | | | |
| | | | | |1062|024|R135028|J15| |JP1| |
|TC4| | | | |R12| |J2| | | | |
|TC3|D59|ICC|Ok2|Ok| | | | | | | |
|TC2|055|IMSC|LE| |013| | | | | | |
|TP3|TPZ|TC1|R46|R65|R93| | | | | | |
|2|017|1J16|K7|R6G|HS| | | | | | |
| | | |DN|UP|DNX|UPX| | | | | |
|MAD2|R139|TPi| | | | | | | | | |
|MADI|R51|K14076|K12|K9072| | | | | | | |
|J17|EN50205|GCR|PS2|D14|GEAR| | | | | | |
|PST| | | | |TEST POINT|FC|J18|DE| | | |
|LPS2|2|Di23| | | | | | | | | |
|LPST|R67| | | |075|K13| | | | | |
|HHYDRO|025|J19|9|8|J20| | | | | | |
|8|8| |3 %|2|S|J21 %| | | | | |
|9|8| | |S|$|J22| | | | | |
|2| | | | | | | | | | | |

Part No. 000858 (22-m11-2021)

# Eclipse (Micro-6 Controller) Maintenance and Troubleshooting Guide

# Part No. 000858 (22-m11-2021)

# Table 1

# Main controller board LEDs

|LED|Description|
|---|---|
|DZ|Selector door zone indicator|
|UL|Selector up levelling indicator|
|DL|Selector down levelling indicator|
|P3|Selector P3 positioning (binary) indicator|
|P2|Selector P2 positioning (binary) indicator|
|P1|Selector P1 positioning (binary) indicator|
|AL|Cab lighting indicator|
|EL|Emergency light indicator|
|RP|Run pilot indicator|
|DC2|Fuse 2 status indicator|
|DC3|Fuse 3 status indicator|
|DC4|Fuse 4 status indicator|
|PT2|Overload/VFD status input indicator|
|CC|Motor auxiliary input indicator|
|IN1|NLD reset confirmation indicator|
|1EL to 6EL|Electric lock output indicators|
|DC|Doors closed contacts input indicator|
|DL|Doors locked contacts input indicator|
|HDC|All doors closed input indicator|
|HDL|All doors locked input indicator|
|1C|Floor 1 call input indicator|
|2C|Floor 2 call input indicator|
|3C|Floor 3 call input indicator|
|4C|Floor 4 call input indicator|
|5C|Floor 5 call input indicator|
|6C|Floor 6 call input indicator|
|OPF|Door open front input indicator|
|OPR|Door open rear input indicator|
|BZ|Buzzer output indicator|
|UT|Normal limit up input indicator|
|LT|Normal limit down input indicator|
|GC|Gates closed input indicator|
|MSC|Main safety chain input indicator|
|LPS1|Low pressure switch input indicator|
|DE|Drive enable indicator|
|LE|Levelling indicator|
|HS|High speed indicator|
|DN|Down direction indicator|
|UP|Up direction indicator|
|OK|Watchdog input indicator|

# Table 2

# Main controller board switches

|Switch|Description|
|---|---|
|SW1|Set to GEAR for geared controller Set to HYDRO for hydraulic controller|

# Step 4

# Car top board connections

# Purpose

To verify the car top board connections.

# Figure 6

Car top board connections

# AUTO PANEL FOLD

(Gatemate and Bifold 24 Vdc Gate Operator)

|LED|Description|
|---|---|
|LED1|Selector P1 positioning input indicator|
|LED2|Selector P2 positioning input indicator|
|LED3|Selector P3 positioning input indicator|
|LED4|Selector DL (down levelling) input indicator|
|LED5|Selector UL (up levelling) input indicator|
|LED6|Selector DZ (door zone) input indicator|
|LED7|Selector POWER (+24V) indicator|

Confirm voltage of gate operator IMPORTANT! before changing any car top wiring.

110H
110N
IN(H)
IN(N)
24VDC Relay

NOTE: Be sure to connect the 14-gauge green traveling cable wire to the car top ground lug.

|FLAT TC|ROUND TC|
|---|---|
|TCB20-ORG|TC29-BRN|
|TCB19-ORG|TC28-BRN|
|TCB18-ORG|TC27-BRN|
|TCB17-ORG|TC26-BRN|
|TCB16-ORG|TC25-BRN|
|TCB15-ORG|TC24-BRN|
|TCB14-ORG|TC23-BRN|
|TCB13-ORG|TC22-BRN|
|TCB12-ORG|TC21-BRN|
|TCB11-ORG|TC20-ORG|
|TCB10-YEL|TC19-ORG|
|TCB9-YEL|TC18-ORG|
|TCB8-YEL|TC17-ORG|
|TCB7-YEL|TC16-ORG|
|TCB6-YEL|TC15-ORG|
|TCB5-YEL|TC14-ORG|
|TCB4-YEL| |
|TCB3-YEL|TC12-ORG|
|TCB2-YEL|TC11-ORG|
|TCB1-YEL|TC10-YEL|

TO CONTROLLER

|TCB1-YEL|TC10-YEL|
|---|---|
|TCB2-YEL|TC11-ORG|
|TCB3-YEL|TC12-ORG|
|TCB4-YEL| |
|TCB5-YEL|TC14-ORG|
|TCB6-YEL|TC15-ORG|
|TCB7-YEL|TC16-ORG|
|TCB8-YEL|TC17-ORG|
|TCB9-YEL|TC18-ORG|
|TCB10-YEL|TC19-ORG|
|TCB11-ORG|TC20-ORG|
|TCB12-ORG|TC21-BRN|
|TCB13-ORG|TC22-BRN|
|TCB14-ORG|TC23-BRN|
|TCB15-ORG|TC24-BRN|
|TCB16-ORG|TC25-BRN|
|TCB17-ORG|TC26-BRN|
|TCB18-ORG|TC27-BRN|
|TCB19-ORG|TC28-BRN|
|TCB20-ORG|TC29-BRN|

P.N.:772392 REV004

# NOTES:

* IF TRUE MRL, PLACE REMOVABLE WALL SW. IN SERIES WITH 1N5404 DIODE AT T16. (010)

# REMOVE JUMPER FROM T19 IF REAR GATE OPERATOR IS REQUIRED

|L|N|GND|
|---|---|---|
|POWER SUPPLY|V-|V+|

NOTE: PI SERVICE INDICATOR CIRCUIT (SVC RELAY) REMOVED.

Part No. 000858 (22-m11-2021)

Eclipse (Micro-6 Controller) Maintenance and Troubleshooting Guide

# Step 5

# Car top board LEDs

Purpose

To identify the car top board LEDs.

# Figure 7

Car top board LEDs and switches

# Table 3

Car top board LEDs

|LED|Description|
|---|---|
|LED1|Selector P1 positioning input indicator|
|LED2|Selector P2 positioning input indicator|
|LED3|Selector P3 positioning input indicator|
|LED4|Selector DL (down levelling) input indicator|
|LED5|Selector UL (up levelling) input indicator|
|LED6|Selector DZ (door zone) input indicator|
|LED7|SELECTOR POWER (+24V) indicator|

Car top for a lift with a power gate includes a power supply that plugs into T20.

Eclipse (Micro-6 Controller) Maintenance and Troubleshooting Guide Part No. 000858 (22-m11-2021)

# Step 6

# Selector board connections

Purpose

To verify the selector board connections.

Figure 8: Solderer board connections

# Step 7

# COP board connections

Purpose

To verify the COP board connections.

Figure 9: COP board connections

|TO T12 ON|TO T6 ON|CAR TOP PCB|
|---|---|---|
|TO T11 ON|TO T13 ON|CAR TOP PCB|

(DT 2I: bIM: JJszd[ ZETECIOB ZV^VBIV {D} [62) (rif

Part No. 000858 (22-m11-2021)

Eclipse (Micro-6 Controller) Maintenance and Troubleshooting Guide

# Step 8

# Power and motor connections

Purpose: To verify power and motor connections. Refer to the illustrations on the next page.

1. Verify the light power connection – 120V, 15 Amp disconnect to the controller box.

**Table 4: Light power connections**
|120 V light|Connection in controller|
|---|---|
|Green|Ground|
|Black|H|
|White|N|
2. Verify the main power connection – 230V, single-phase 20 Amp disconnect to the controller box.

**Table 5: Main power connections**
|230 V main|Connection in controller|
|---|---|
|Green|Ground|
|Black|L1|
|Black|L2|
3. Verify the motor connections to the controller box.

**Table 6: Motor connections**
|Motor|Connection in controller|
|---|---|
|Black|T1|
|Red|T2|
|Blue|T3|

WARNING

Make sure the building ground is connected to the controller ground bus before turning the disconnect on. Improper or no ground can result in shocking hazard and unsafe operation.

Eclipse (Micro-6 Controller) Maintenance and Troubleshooting Guide Part No. 000858 (22-m11-2021)

# Eclipse (Micro-6 Controller) Maintenance and Troubleshooting Guide

# Figure 10

# Controller box power and motor connections

|Light power|H and N|
|---|---|
|Main power|L1 and L2|
|Motor|T1, T2, T3|

# CONTROLLER CONNECTIONS

# CONTROLLER CONNECTIONS

Part No. 000858 (22-m11-2021)

# Step 9

# Sling disassembly

CAUTION

Purpose

Perform this step only when sling is at pit bottom. To disassemble the sling to allow the base rail to fit through a tight doorway.

Procedure Considerations

1. Disassemble straps.
2. Disassemble the sling back bracket.

Sections to disassemble:

- Sling right and left arm assembly 227137-R and 227137-L
- Sling back 227580
- Bell crank assembly 227798 with safety linkage
- Lifting bracket assembly 227802

# Figure 11

Sling disassembly

|Bell crank|Lifting bracket|
|---|---|
|227119 with safety linkage|227124|

# Figure 12

Sling back bracket

Do not loosen guide shoes

Left sling assembly 227137-L

Right sling assembly 227137-R

Pull sling off of rail

1. 1---'' - 13 x 1'' hex head bolt
2. 2) 21--- - 13 x 11---'' carriage bolt
3. 1---'' flat washer
4. 2) 1---'' lock washer
5. 2) 1'' nut

Leave guide shoes attached to sling

CAUTION

Leave the guide shoes attached.

3 Disassemble the safety linkage (bell crank).

1. 1---'' - 13 x 1'' hex head bolt
2. 2) 21--- - 13 x 11---'' carriage bolt
3. 1---'' flat washer
4. 2) 1---'' lock washer
5. 1'' nut

3) ----- 165- '' x 2 '' bolt 21---

----- 325-Allen key

# Eclipse (Micro-6 Controller) Maintenance and Troubleshooting Guide

Part No. 000858 (22-m11-2021)

# Figure 13

Safety linkage (bell crank)

# NOTE

Note the position (up direction) of the counterweights travelling assembly when removing the assembly from the rails.

# Figure 15

Counterweights travelling assembly

# 2

| | | | |Part no. 227008| | | | | |
|---|---|---|---|---|---|---|---|---|---|
| |2)|-----|165- '' x 2 '' bolt|21---| | | | | |
| |-----|5-Allen key|32| | | | | | |
| |4|Disassemble the lifting bracket.| | | | | | | |
| |Figure 14|Lifting bracket| | | | | | | |
| | | | |1|1|1|1|1|1|
| |1)|21--- - 13 x 11'' carriage bolts|---2| | | | | | |
|1---'' lock washer| | |2| | | | | | |
|1---'' nut| | |2| | | | | | |
|5|Remove counterweights travelling assembly, if required.| | | | | | | | |

Part No. 000858 (22-m11-2021) Eclipse (Micro-6 Controller) Maintenance and Troubleshooting Guide

# Step 10

# Sling assembly

# Purpose

To reassemble the sling.

# Procedure

1. Place the left and right sling arms at the sides of the rail.
2. Place the lifting bracket over the sling sides and bolt loosely.
3. Place the counterweight housing.
4. Place the sling back bracket and bolt loosely.
5. Place the safety linkage (bell crank housing) between the sling sides and bolt loosely.
6. Place a level on the lifting bracket and ensure that it is level. Tighten the bolts.
7. Place a level on the back bracket and ensure that it is level. Tighten the bolts.
8. Raise the sling and engage the safeties.
9. Ensure the sling is plumb and square on the rails.
10. Assemble the straps.
11. Pull the straps outwards at the bottom assembly points.

# Step 11

# Bottom shoring bracket attachment

# Purpose

To insert the bottom shoring bracket onto the U-channels.

# Considerations

Raise the sling and insert the bottom shoring bracket onto the U-channels before assembling the controller, if required, and travelling counterweights.

There are a series of holes in the U-channels of the base section; use these holes to insert the bottom shoring bracket at various heights along the U-channels, as required.

Unlike the top shoring bracket, no bolts are necessary to attach the bottom shoring bracket.

# DANGER

# FALLING DANGER

Be sure to tie off the sling once you raise it to insert the bottom shoring bracket for controller and counterweight installation and service purposes.

# Procedure

1. Raise the sling approximately eight feet above the pit floor and tie it off.
2. Insert the shoring bracket into any of the U-holes. The bottom shoring bracket quick insert assembly no. 227564 allows you to use it at any point on the U-channels where holes are available.

# Figure 16

Bottom shoring bracket

Bottom shoring bracket insert Assembly no. 227564

Insertion points

# Step 12

# Guide shoe replacement

# Purpose

To inspect and replace the guide shoes.

# Considerations

Under normal use, friction wears the four guide shoes over time.

Figure 17: Guide shoe assembly

After inspection, if it is necessary to replace the guide shoes, replace only one guide shoe at a time. Replace the top guide shoes first before replacing the bottom guide shoes.

# Procedure

1. Locate a left or right top guide shoe.
2.

Figure 18: Top guide shoe location

1) Guide slide <br />
2) Shoe insert part no. 210129 <br />
3) Retainer clip <br />
1) Guide shoe bolts <br />
Do not remove these bolts

DANGER

FALLING DANGER<br />
Three guide shoes can support the elevator. Two guide shoes cannot. Replace only one guide shoe at a time.

At the top of the sling at ceiling height, remove the two guide shoe screws and retainer clip.

Part No. 000858 (22-m11-2021) Eclipse (Micro-6 Controller) Maintenance and Troubleshooting Guide

# Step 13

# Guide shoe retainer clip

# Slack chain test for maintenance

1. Run the elevator down 6". The plastic shoe insert should slide out of the guide shoe.

Purpose To ensure the safety brakes (safeties) are in good working condition.

Considerations The safety brakes are made of hardened steel, normally do not require maintenance, and are rarely used. During routine maintenance, check that the safeties do engage the rails. Periodically the safeties may show an increase in noise due to dried lubricant. Check if the safeties require lubricant.

# NOTE

If the shoe insert does not slide out of the guide shoe, you can pry it out or attempt to pull it out with pliers.

Insert a new shoe insert.

# Replacement shoe insert

|Wheel|Lubricant|
|---|---|
|contacts|Lithium grease|
|rail| |

# Brake assembly

Replace the guide shoe retainer clip.
Repeat the steps for the guide shoe on the opposite rail.
Repeat the steps for the bottom guide shoes. Work from the bottom with the lower two guide shoes.

# Brake

# Brake

Eclipse (Micro-6 Controller) Maintenance and Troubleshooting Guide Part No. 000858 (22-m11-2021)

# Procedure

1. Remove the car operating panel from the cab wall to access the slack chain (plank) switch and safeties bracket.
2. Use the pendant to lower the cab towards the pit.
3. Place a 4 x 4 that is at least 48'' long in the pit.
4. Lower the sling onto the 4 x 4.

NOTE

Ensure to place the 4 x 4 on an angle to aid in knocking it out when forcing the safeties to engage.

NOTE

If the brakes require replacement, refer to sling disassembly in this guide for information on how to remove the sling from the rails.

CAUTION

Ensure the 4 x 4 touches the metal sling, not the wooden cab floor.

Knock out the 4 x 4 with another block of wood. The safeties engage.
Run the elevator upwards to release the brakes.
Examine the marks made by the safety brakes on the sling. The marks should appear even on both sides.
File and clean the marks from the rails.
Oil the brakes, if necessary. There are two holes on either side of the sling that allow access to oil the brake wheel.

Part No. 000858 (22-m11-2021) Eclipse (Micro-6 Controller) Maintenance and Troubleshooting Guide

# Step 14

# Motor wiring

Purpose

To wire a replacement motor.

Procedure

1. Turn off all power.
2. Remove the motor wire cover.

Figure 26: Motor wire cover

Remove cover

# Step 15

# Motor brake air gap adjustment

Purpose

To adjust the motor brake air gap.

Considerations

In order to get maximum life out of the brake, the air gap must be set properly and checked at regular intervals. As the brake wears and decreases in thickness, the air gap will increase. If the air gap is too large, the brake coil may not have enough magnetic force to pull the metal armature disc across the gap and the brake rotor will drag. The nominal air gap is 0.3 mm. Adjust as required.

WARNING

IMPORTANT!

Be sure to support the counterweights and cab to ensure the elevator does NOT move during adjustment.

Procedure

1. Attach the motor harness wires to the motor.

Figure 27: Motor wiring

Red
Black
Blue
Ground

Remove the brake cover (4 screws).

Figure 28: Remove motor brake cover

|Brown|21|1|1|
|---|---|---|---|
|Orange| | | |

Remove the retaining clip and remove the fan from the shaft.

Figure 29: Remove motor brake fan

Eclipse (Micro-6 Controller) Maintenance and Troubleshooting Guide Part No. 000858 (22-m11-2021)

# 3

Move the black rubber O-ring out of the channel so you have access to check the air gap.

Figure 30: Move O-ring out of channel

# 4

Use a feeler gauge to check the air gap. It should be 0.3 mm. If you can insert a 0.35 mm gauge, then the gap is too big.

Figure 31: Check motor brake air gap

# 5

To adjust the air gap, use a 5 mm Allen wrench to loosen the three cap head bolts a 1/4 turn.

Figure 32: Loosen cap head bolts

# 7

After adjusting the nuts, tighten the cap head bolts and verify the air gap is still 0.30 mm. Re-adjust as necessary.

Figure 34: Adjust motor brake air gap

# 8

IMPORTANT: Be sure to move the black rubber O-ring back into the channel.

# 9

Reinstall the fan and secure it with the retaining clip.

# 10

Reinstall the motor brake cover (4 screws).

# 11

Run the elevator up and down twice and then recheck the air gap.

# 12

Secure the cap head bolts with Loctite 270 (type thermoplastic liquid).

# NOTE

Check and re-adjust the air gap if necessary after 3 months or at the first maintenance visit.

Part No. 000858 (22-m11-2021) Eclipse (Micro-6 Controller) Maintenance and Troubleshooting Guide

# Step 16

# Rail lubrication

Purpose

To keep the rails in good working order.

Procedure

1. Periodically, check the cab for a smooth ride.
2. File the rails, where required.
3. Grease the rails, where required.

# Step 17

# USB copy tool

Purpose

To upgrade the variable frequency drive (VFD).

Considerations

From time to time, Savaria may provide a copy tool to upgrade the software on the variable frequency drive (VFD) in the controller box.

Procedure

1. Plug the RJ-45 cable connector into the VFD connector slot.
2. Press and hold the copy button. The VFD LED displays COPY.
3. WARNING

You must hold the copy button down firmly for a minimum of 2 seconds to ensure the software copies from the copy unit to the VFD.
4. The VFD displays END when the software transfer is complete.
5. The display reads 5.00.

# Step 18

# Chain maintenance

# Purpose

To check chain wear and lubricate or replace as necessary (every six months).

# Measuring Chain Wear

Chain wear is determined by measuring the amount a chain has stretched. This can be done using a large digital caliper or by estimating using a wear scale as described below. The wear limit of a standard roller chain is 2% of the chain’s pitch. If the stretch is more than 2%, it’s time to replace the chain. Pitch is defined as the distance between the center of each bushing in a link.

# Figure 36

Pitch

# (2) Wear Scale Method

Using a chain wear scale (shown below) makes the process much easier. The wear scale is ‘T’ shaped, which allows you to butt the chain pin into the corner of the ‘T’. Using the different measurements marked along the stick portion of the ‘T’, you simply find the measurement for your chain and then check to see if the centre of that pin lines up with the measurement on the wear scale. If not, then you know the chain is stretched.

# Figure 38

Chain wear scale

Tslbaki CHAIN WEAR SCALE" Lee chain

# CAUTION

Closely examine every chain pin to ensure none of them is missing or making their way out of the link. Failure to do so may result in chain failure as shown in the image below.

# PITCH

# (1) Caliper Method

The easiest way to measure using a digital caliper is to measure from one reference point (for example, the centre of the bushing) to the same reference point a number of pitches away (see below). The key is to measure over as many pitches as possible, since 2% is a very small number. Measuring over many pitches makes the stretch more noticeable and easier to calculate. After measuring, you simply divide by the nominal pitch to get the stretch.

For example, measure a length of RS60 chain (3/4” pitch) from the centre of one roller to the centre of another roller 10P away. If this distance is measured as 7.6”, the nominal pitch is then calculated as (0.75” per pitch) x (10 pitches) = 7.5”. You then, divide 7.6” by 7.5” to get 1.01333, or a stretch of 1.33%. In this example, the chain is still usable since the stretch is below 2%.

# Figure 37

Digital caliper

# Lubrication

Proper lubrication depends on the operating conditions, temperature and size of the chain. The chain comes pre-lubricated with a lubricant developed to thoroughly penetrate all parts of the chain, especially the critical areas where the pin and bushing surfaces make contact under full load.

Proper lubrication is essential for peak performance and maximum chain life. Follow the lubrication schedule and recommendations carefully as improper lubrication will shorten chain life and decrease performance.

Since wear between pins and bushings of the chain causes chain elongation, lubrication must be maintained on all contact surfaces. The lubricant must be selected and applied according to the application and working conditions of the chain. Once applied, the lubricant should NOT be wiped off.

# Recommended Lubricants

Only high-grade oil of suitable viscosity should be used for chain lubrication. The amount and type depends on the chain specifications, working conditions and lubricating systems. DO NOT use heavy oil, low-grade oil, impure oil or grease, or used oil. These types will reduce chain life or cause chain damage or breakage.

Part No. 000858 (22-m11-2021) Eclipse (Micro-6 Controller) Maintenance and Troubleshooting Guide

# Appendix A

# Diagnostic Beep Codes

The Micro-6 controller can be set up to provide audible fault codes (diagnostic beep codes). These codes can help the user diagnose certain problems themselves and also provide information to the dealer as to why a lift isn’t functioning properly.

To enable the codes, use the P-Tool and set the parameter “call but.fault” to:

- 0 for no audible codes
- 1 for User codes only
- 2 for User and Service codes

User codes provide feedback to the user and do not require a service visit.

- 1 short beep - a gate is open or the in-car Stop switch is activated. Make sure the in-car Stop switch is in the Run position. Check that the car gate is closed.
- 2 short beeps - a door is open. Check that the landing door is closed.
- 3 short beeps - gate needs to be cycled. Manually open the gate.
- Single beep every 30 seconds - power failure, unit will only respond to calls/commands to go in the down direction.

Service codes are those that require a site visit. All Service codes begin with one long 2-second beep.

- 1 long and 1 short beep - possible problems are overload trip, run timer fault, safety circuit open, door lock fault or auto shutdown counter.
- 1 long and 2 short beeps - possible problems are re-level shutdown or low pressure switch activated.
- 1 long and 3 short beeps - possible problems are selector fault, selector encoding or position error.

# Appendix B

# Yaskawa V1000 Fault

# Tables

Refer to the sections listed below on the following pages for VFD fault descriptions.

# Sections

- Safety
- Drive alarms, faults, and errors
- Fault detection
- Alarm detection
- Operator programming errors
- Diagnosing and resetting faults

THIS PAGE WAS LEFT INTENTIONALLY BLANK

# Eclipse Residential Elevator

# (with Micro-6 Controller)

# MAINTENANCE AND TROUBLESHOOTING GUIDE

Part No. 000858

© Copyright 2021

www.savaria.com

# Support

2 Walker Drive

Brampton, Ontario, L6T 5E1, Canada

Toll free (800) 791-7999

Fax: (905) 791-2222

@ savaria