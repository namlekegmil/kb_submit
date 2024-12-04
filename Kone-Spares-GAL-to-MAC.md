# Door Operator Conversion

# GAL -to-MAC Door Operator Conversion

Product instruction

PAA8-604 (8/98)

63113-146 (R1)

# GAL®-to-MAC®

# Purpose

This product instruction provides a brief description of the features and components of GAL® -to-MAC ® Door Operator conversion package. This product instruction also provides Field Personnel with information on installation procedures, operational checks and adjustments, and diagnostic procedures. Although this instruction provides information on primarily one type of GAL® door operator, the instructions can be applied to other GAL® door operators.

A604-001 (1/95)

© 1998, 1996 MOLINE ACCESSORIES COMPANY

This volume is not intended for distribution, and not approved for use as a source of information for any purpose or procedure. All rights reserved. No portion of this volume may be reproduced or used in any manner without written permission from Moline Accessories Company -- 107 18th Street; Moline, IL 61265

2 PAA8-604 (8/98)

# Door Operator Conversion

# TABLE OF CONTENTS

- Purpose ................................................................................................................. 2
- Safety .................................................................................................................. 4
- Description of PM/SSC door operator with Board 1Ø4TM & auxiliary locking board .......... 5
- Removing GAL® door operator components ................................................................. 6
- - Remove GAL® MOM & MOH styles (side-opening) .................................................. 10
- Remove GAL® MOD style (side-opening) ................................................................ 6
- Remove GAL® MOD style (center-opening) .............................................................. 14
- Remove GAL® MOM & MOH styles (center-opening) ............................................... 18

Installing MAC® door operator (side-opening door) .................................................... 22
- - Install MAC® door operator (center-opening doors) ................................................ 24
- Wire door operator ............................................................................................... 26
- Wire gate switch .................................................................................................. 27

Wiring non-MIPROM logic controller ........................................................................ 28
- Adjusting door operator control Board 1Ø4TM ............................................................ 30
- - Toggle switches .................................................................................................... 30
- Measure current (optional) ................................................................................... 31
- Set potentiometers ............................................................................................... 31
- Adjust door speeds ............................................................................................... 32
- Adjust door closing force ...................................................................................... 34
- Adjust nudge speed .............................................................................................. 35
- Set microswitch cams .......................................................................................... 36
- Adjust Board 1Ø4TM with auxiliary locking board .................................................. 38

Replacement Parts ................................................................................................... 40

# GAL®-to-MAC®

# Safety

Participate in the successful installation of MAC® Car Door equipment—know the safety hazards related to any procedure, know what equipment is required, and know what tools and materials you should plan to have available beforehand.

- When working on the car canopy, be aware of tripping hazards.
- Use cords and power equipment protected by ground fault circuit interrupters.
- Make sure hoistways and work areas are adequately lighted.
- Make sure clearances exist in hoistway for equipment to be installed.

A604-002 (1/95)

# Recommended tools & materials

Pre-arrange to have the following available.

- Small hand tools to fit assorted screws, bolts, and nuts
- Levels
- Drill with assorted bits
- Hex keys 5/64 inch - 13/64 inch
- Socket set 3/8 inch - 1-1/4 inch in 1/16" increments
- Open or box wrenches 3/8 inch - 1 inch in 1/16 inch increments
- Tape measure
- Tap and Die set
- Vise-grip pliers

A604-SI1 (1/95)

PAA8-604 (8/98)

# Door Operator Conversion

# Description of PM/SSC door operator with Board 1Ø4TM & auxiliary locking

Current control. PM/SSC door operator control has a board® door operators are shipped with the GAL®-to-MAC current sensing circuit in both open and closed directions to supply feedback to the speed control circuit. This current sensing circuit regulates closing door force, and open/stall current caused by a hooked interlock. The current sensing circuit also guarantees that PM/SSC door operator control relay contacts do not break or make when motor armature current is present—helping to prevent damage to relay contacts. Motor direction is controlled by reversing the armature connection using a conventional relay system.

# Board 1 Ø4TM and auxiliary locking board kit

Board 1 Ø4TM and auxiliary locking board kit preinstalled and preadjusted, requiring only final adjustment. Auxiliary locking boards cannot be used with earlier versions of Board 1Ø4TM.

# Speed & travel limits

PM/SSC door operator control selects speed and travel limits with cam operated microswitches. These microswitches operate relays tied into the speed direction circuits.

# Acceleration & deceleration

PM/SSC door operator control has an internal soft-start circuit which regulates smooth acceleration and deceleration. Soft-start circuit allows average motor voltage to change gradually when speeds change.

# Diagnostics & adjusting switches

PM/SSC door operator control has two small toggle switches mounted on the common circuit board. The TEST/RUN switch and O-OFF-C switch are used to:

- Signal door opening or closing from the car top during diagnostics and adjusting
- Disconnect the door open and close signals
- De-activate the internal shutdown timer

# Door control power

PM/SSC door operator control uses a low voltage permanent magnet DC motor. The DC motor is powered by pulse width modulated power (high speed switching - 20,000 hz). The motor responds to average voltage of high frequency pulses, and not individual pulses.

# Auxiliary piloting

The PM/SSC door operator control also has a Form “C” Open and a Form “C” Closed relay contact for auxiliary piloting.

A604-003 (1/95)

# GAL®-to-MAC®

# Removing GAL® door operator components

There are several styles of GAL® door operators that can be replaced with the GAL®-to-MAC® door operator. The GAL® styles described in this manual are MOD, MOM, and MOH. All three styles are used for both side-opening and center-opening cab doors. The procedure for removing the MOM and MOH door operators is the same, but the procedure for removing the MOD door operator is different.

The following sections describe procedures for removing the GAL® door operator components.

- Remove GAL® MOD style (side-opening door)
- Remove GAL® MOM & MOH styles (side-opening door)
- Remove GAL® MOD style (center-opening doors)
- Remove GAL® MOM & MOH styles (center-opening doors)

Some GAL® door operators have a drive arm support (1) on the baseplate and others do not. Use the following procedures for removing a GAL® door operator with a drive arm support. If the GAL® door operator does not have a drive arm support, you can also use the following procedures, or remove the GAL® door operator and baseplate as a unit.

# REMOVE GAL® MOD STYLE (SIDE-OPENING)

When the GAL® door operator has a drive arm support, there are several dimensions to record before removing any components. These recorded dimensions make it easier to install the MAC® door operator. Use the following procedures to record the critical measurements and remove the GAL® components.

# Recording Critical measurements - MOD style (side-opening)

1. Turn off electrical power to the door operator.
2. Measure the diameter of drive sheave (1) from top to bottom. Divide diameter by two and measure down that distance to crank arm (2). Mark that point on crank arm (2) and label it “A”.
3. Measure the distance “B”, from center of pivot point (3) to point “A” on crank arm (2). Record dimension “B” for use when installing the MAC door operator.
4. Open the car doors until the pivot point (3) and the crank arm (2) are parallel to the edge of the baseplate (6). Measure the distance “C” between the back of the crank arm (2) and the edge of the baseplate (6). Record dimension “C” for use when installing the MAC® door operator.

# Record GAL door operator measurements

|sheave dia.|"B"|"C"|Car|
|---|---|---|---|
|divided by 2| | | |

# Door Operator Conversion

# MOD style (side-opening)

7

# GAL®-to-MAC®

# Removing components MOD style (side-opening)

If GAL® door operator has a drive arm support, ensure that all critical dimensions are recorded before removing any components. For more information on critical dimensions, refer to section titled: Recording Critical Dimensions - MOD style (side-opening).

1. Turn off electrical power to the door operator.
2. Remove two bolts and nuts (1) and crank arm (2) from drive sheave (3). Save bolts and nuts (1) and crank arm (2) for use when installing MAC® door operator.
3. Tag and disconnect the gate switch wiring before removing flexible conduit (4) from control box (5). Tag and disconnect the door operator control wiring from the car junction box.
4. Remove four bolts from bearing block (6) and two bolts from adjusting bolt bracket (7).
5. Remove chain (8) and belt (9) from intermediate sheave (10).
6. Remove bearing block (6), intermediate sheave (10), belt (9), and adjusting bolt bracket (7) from baseplate (11).
7. Remove hardware from motor mounting guide stud (12) and four bolts from motor mount assembly (13).
8. Remove motor (14) and motor mount assembly (13) from baseplate (11).
9. Use Vise grip pliers to remove the motor mounting guide stud (12) from baseplate (11).
10. Remove wingnut (15) and cover from control box (5).
11. Remove two bolts, control box (5), and mounting plate (16) from baseplate (11).
12. Remove four bolts from bearing block (17). Remove bearing block (17), chain (8) and drive sheave (3) from baseplate (11).
13. Remove two bolts and stop roller bracket (18) from baseplate (11).
14. After removing the MOD style components, drive arm support (19) is the only part on baseplate (11).

A604-006 (1/95)

PAA8-604 (8/98)

# Door Operator Conversion

# MOD style (side-opening)

9

# GAL®-to-MAC®

# REMOVE GAL ® MOM & MOH STYLES (SIDE-OPENING)

When the GAL® door operator has a drive arm support (1), there are several dimensions to record before removing any components. These recorded dimensions make it easier to install the MAC® door operator. Use the following procedures to record the critical measurements and remove the GAL® components.

# Recording critical measurements - MOM & MOH styles (side-opening)

1. Turn off electrical power to the door operator.
2. Measure the diameter of drive sheave (1) from top to bottom. Divide diameter by two and measure down that distance to crank arm (2). Mark that point on crank arm (2), and label it “A”.
3. Measure the distance “B”, from center of pivot point (3) to point “A” on crank arm (2). Record dimension “B” for use when installing the MAC door operator.
4. Open the car doors until the pivot point (3) and the crank arm (2) are parallel to the edge of the baseplate (6). Measure the distance “C” between the back of the crank arm (2) and the edge of the baseplate (6). Record dimension “C” for use when installing the MAC® door operator.

A604-007 (1/95)

# Record GAL door operator measurements

sheave dia. divided by 2
"B"
"C"
Car
Z604-T01 (11/94)

10

PAA8-604 (8/98)

# Door Operator Conversion

# MOM & MOH styles (side-opening)

11

# GAL®-to-MAC®

# Removing components

MOM & MOH styles (side-opening) If GAL® door operator has a drive arm support, ensure that all critical dimensions are recorded before removing any components. For more information on critical dimensions, refer to section titled: Recording Critical Dimensions - MOM & MOH styles (side-opening).

1. Turn off electrical power to the door operator.
2. Remove two bolts and nuts (1) and crank arm (2) from drive sheave (3). Save bolts and nuts (1) and crank arm (2) for use when installing MAC® door operator.
3. Tag and disconnect the gate switch wiring before removing flexible conduit (4) from control box (5). Tag and disconnect the door operator control wiring from the car junction box.
4. Remove four bolts from bearing block (6) and two bolts from adjusting bolt bracket (7).
5. Remove chain (8) and belt (9) from intermediate sheave (10).
6. Remove bearing block (6), intermediate sheave (10) and adjusting bolt bracket (7) from baseplate (11).
7. Remove hardware from motor mounting guide stud (12) and four bolts from motor mount assembly (13).
8. Remove motor (14) and motor mount assembly (13) from baseplate (11).
9. Use Vise grip pliers to remove the motor mounting guide stud (12) from baseplate (11).
10. Remove four bolts and control box (5) from baseplate (11).
11. Remove four bolts and terminal box (15) from baseplate (11).
12. Remove four bolts from bearing block (16). Remove chains (8 & 17), bearing block (16) and drive sheave (3) from baseplate (11).
13. Remove two bolts and stop roller bracket (18) from baseplate (11).
14. After removing the MOM & MOH style components, drive arm support (19) is the only part on baseplate (11).

A604-008 (1/95)

PAA8-604 (8/98)

# Door Operator Conversion

# MOM & MOH styles (side-opening)

13

# GAL®-to-MAC®

# REMOVE GAL® MOD STYLE (CENTER-OPENING)

Before removing any GAL® components, there are several critical dimensions that need to be recorded. These recorded dimensions make it easier to install the MAC® door operator. Use the following procedures to record the critical measurements and remove the GAL® components.

# Recording critical measurements - Record GAL door operator measurements MOD style (center-opening)

1. Turn off electrical power to the door operator.
2. Measure the distance “A”, from the center of the drive sheave mounting shaft (1) to the center of the pivot point (2) of the crank arm (3) and connecting link arm (4). Record dimension “A” for use when installing the MAC® door operator.
3. Measure the distance “B”, from the center of the drive sheave mounting shaft (1) to the center of the pivot point (5) of the crank arm (6) and connecting link arm (7). Record dimension “B” for use when installing the MAC® door operator.
4. Open the car doors until pivot point (2) is near the edge of the baseplate (8). Measure the distance “C” between the back of the connecting link arm (4) and the edge of the baseplate (8). Record dimension “C” for use when installing the MAC® door operator.

A604-009 (1/95)

Z604-T02 (11/94)

PAA8-604 (8/98)

# Door Operator Conversion

# MOD style (center-opening)

15

# GAL®-to-MAC®

# Removing components

# MOD style (center-opening)

Ensure that all critical dimensions have been recorded before removing any components. For more information on critical dimensions, refer to section titled: Recording Critical Dimensions - MOD style (center-opening).

1. Turn off electrical power to the door operator.
2. Remove bolts and nuts (1 & 2) and crank arms (3 & 4) from drive sheave (5). Save bolts and nuts (1 & 2) and crank arms (3 & 4) for use when installing MAC® door operator.
3. Tag and disconnect the gate switch wiring before removing flexible conduit (6) from control box (7). Tag and disconnect the door operator control wiring from the car junction box.
4. Remove four bolts from bearing block (8) and two bolts from adjusting bolt bracket (9).
5. Remove chain (10) and belt (11) from intermediate sheave (12).
6. Remove bearing block (8), intermediate sheave (12), belt (11), and adjusting bolt bracket (9) from baseplate (13).
7. Remove hardware from motor mounting guide stud (14) and four bolts from motor mount assembly (15).
8. Remove motor (16) and motor mount assembly (15) from baseplate (13).
9. Use Vise-grip pliers to remove the motor mounting guide stud (14) from baseplate (13).
10. Remove wingnut (17) and cover from control box (7).
11. Remove two bolts, control box (7), and mounting plate (18) from baseplate (13).
12. Remove four bolts from bearing block (19). Remove bearing block (19), chain (10) and drive sheave (5) from baseplate (13).
13. Remove two bolts and stop roller bracket (20) from baseplate (13).
14. After removing the MOD style components, there are no parts left on baseplate (13).

A604-010 (1/95)

PAA8-604 (8/98)

# Door Operator Conversion

# MOD style (center-opening)

17

# GAL®-to-MAC®

# REMOVE GAL ® MOM & MOH STYLES (CENTER-OPENING)

Before removing any GAL ® components, there are several critical dimensions that need to be recorded. These recorded dimensions make it easier to install the MAC® door operator. Use the following procedures to record the critical measurements and remove the GAL® components.

# Recording critical measurements - Record GAL door operator MOM & MOH styles (center-opening)

1. Turn off electrical power to the door operator.
2. Measure the distance “A”, from the center of the drive sheave mounting shaft (1) to the center of the pivot point (2) of the crank arm (3) and connecting link arm (4). Record dimension “A” for use when installing the MAC® door operator.
3. Measure the distance “B”, from the center of the drive sheave mounting shaft (1) to the center of the pivot point (5) of the crank arm (6) and connecting link arm (7). Record dimension “B” for use when installing the MAC® door operator.
4. Open the car doors until pivot point (2) is near the edge of the baseplate (8). Measure the distance “C” between the back of the connecting link arm (4) and the edge of the baseplate (8). Record dimension “C” for use when installing the MAC® door operator.

A604-011 (1/95)

Z604-T02 (11/94)

PAA8-604 (8/98)

# Door Operator Conversion

# MOM & MOH styles (center-opening)

19

# GAL®-to-MAC®

# Removing components - MOM & MOH styles (center-opening)

Ensure that all critical dimensions have been recorded before removing any components. For more information on critical dimensions, refer to section titled: Recording Critical Dimensions MOM & MOH styles (center-opening).

1. Turn off electrical power to the door operator.
2. Remove bolts and nuts (1 & 2) and crank arms (3 & 4) from drive sheave (5). Save bolts and nuts (1 & 2) and crank arms (3 & 4) for use when installing MAC® door operator.
3. Tag and disconnect the gate switch wiring before removing flexible conduit (6) from control box (7). Tag and disconnect the door operator control wiring from the car junction box.
4. Remove four bolts from bearing block (8) and two bolts from adjusting bolt bracket (9).
5. Remove chain (10) and belt (11) from intermediate sheave (12).
6. Remove bearing block (8), intermediate sheave (12) and adjusting bolt bracket (9) from baseplate (13).
7. Remove hardware from motor mounting guide stud (14) and four bolts from motor mount assembly (15).
8. Remove motor (16) and motor mount assembly (15) from baseplate (13).
9. Use Vise-grip pliers to remove the motor mounting guide stud (14) from baseplate (13).
10. Remove four bolts and control box (7) from baseplate (13).
11. Remove four bolts and terminal box (18) from baseplate (13).
12. Remove four bolts from bearing block (19). Remove chains (10 & 20), bearing block (19) and drive sheave (5) from baseplate (13).
13. Remove two bolts and stop roller bracket (21) from baseplate (13).
14. After removing the MOM & MOH style components, there are no parts left on baseplate (13).

A604-012 (1/95)

PAA8-604 (8/98)

# Door Operator Conversion

# MOM & MOH styles (center-opening)

21

# GAL®-to-MAC®

# Installing MAC® door operator

Before installing the MAC® door operator, refer to the appropriate style table where you recorded the critical GAL® door operator dimensions. These recorded dimensions make it easier to install the MAC® door operator. Use the following procedures to install the MAC® door operator on the GAL® baseplate.

# INSTALL MAC® DOOR OPERATOR (SIDE-OPENING DOOR)

1. Set the new MAC® door operator (1) on the existing GAL® baseplate (2).
2. Remove the three nuts and lockwashers (3) that hold adapter plate (5) to sheave (6). There are spacers (4) between the adapter plate (5) and sheave (6). Use caution so you don’t lose any of the spacers while removing the adapter plate (5) from sheave (6).
3. Remove adapter plate (5) from sheave (6).
4. On the top adapter bar (7), measure 6-3/4 inches from one end, and scribe a line.
5. Install the GAL® crank arm (8) on the adapter plate (5) with the bolts (9) and nuts (10) saved during the GAL® Removing Components procedure. Do not tighten the bolts at this time.
6. Measure the distance from the scribe line on top adapter bar (7) to the center of the pivot point (12). The measurement should be the same as the “B” measurement recorded during the GAL Recording Critical Dimensions procedure.
7. Adjust the position of the crank arm (8) on the adapter plate (5) until it is the same as the “B” measurement. Tighten bolts (9). The crank arm “B” measurement is the stroke of the operator. If the GAL® door operator measurement was accurate, then this is a good starting point for setting the stroke of the MAC® door operator.
8. Install adapter plate (5) with GAL® crank arm (8) on sheave (6) using bolts, lockwashers and nuts (3) and spacers (4).
9. Turn sheave (6) by hand until the pivot point (12) and crank arm (8) are parallel to the baseplate (2).
10. Measure the distance between the back of crank arm (8) and the mounting plate (2). The measurement should be the same as the “C” dimension recorded during the GAL® Recording Critical Measurements procedure. Move the MAC® door operator until the “C” dimension is the same.
11. Square the MAC® door operator to baseplate (2) while maintaining the “C” dimension for the crank arm (8). The “B” and “C” measurements should align the connecting link arm (13) and crank arm (8) with the MAC® door operator.
12. Temporarily clamp the MAC® door operator to baseplate (2) to prevent it from moving.
13. Turn sheave (6) by hand until the car doors are in a “completely open” position. If “completely open” position can’t be reached, loosen the hold-down clamps on the MAC® door operator. Carefully shift door operator from side-to-side until doors are “completely open”.
14. Turn sheave (6) by hand until the car doors are in a “completely closed” position.
15. Adjust the stroke and the side-to-side position of the door operator for “completely open” and “completely closed” positions. Stroke is the distance from scribe line on top adapter bar (7) to the center of pivot point (12) for crank arm (8) and connecting link arm (13). Increasing the stroke allows the doors to travel more in the open and closed directions. Decreasing the stroke allows the doors to travel less in both directions.
16. Use existing holes in MAC® door operator end brackets (14) as a guide for drilling holes in baseplate (2).
17. Install nuts and bolts (15) in drilled holes. Refer to section “Wire door operator” for information on wiring MAC® door operator.

A604-013 (1/95)

PAA8-604 (8/98)

# Door Operator Conversion

# GAL® -to-MAC® door operator (side-opening)

23

# GAL®-to-MAC®

# INSTALL MAC ® DOOR OPERATOR (CENTER-OPENING DOORS)

1. Set the new MAC® door operator (1) on the existing GAL® baseplate (2).
2. Remove the three nuts and lockwashers (3) that hold adapter plate (5) to sheave (6).
There are spacers (4) between the adapter plate (5) and sheave (6). Use caution so you don’t lose any of the spacers while removing the adapter plate (5) from sheave (6).
3. Remove adapter plate (5) from sheave (6).
4. On the top adapter bar (7), measure 6-3/4 inches from one end, and scribe a line. Install the GAL® crank arms (8 & 9) on the adapter plate (5) with the bolts and nuts (10) saved during the GAL® Removing Components procedure. Do not tighten the bolts at this time.
5. Measure the distance from the bottom of scribed line on adapter bar (7) to the center of the pivot point (12) for the crank arm (8). The measurement should be the same as the “A” measurement recorded during the GAL® Recording Critical Measurements procedure.
6. Adjust the position of the crank arm (8) on the adapter plate (5) until it is the same as the “A” measurement. Tighten one of bolts (10).
7. Measure the distance from the bottom of scribed line on adapter bar (7) to the center of the pivot point (14) for the crank arm (9). The measurement should be the same as the “B” measurement recorded during the GAL® Recording Critical Measurements procedure.
8. Adjust the position of the crank arm (9) on the adapter plate (5) until it is the same as the “B” measurement. Tighten the other bolt (10).
9. Install adapter plate (5) with GAL® crank arms (8 & 9) on sheave (6) using bolts, lockwashers and nuts (3).
10. Turn the sheave (6) by hand until the pivot point (12) and crank arm (8) are parallel to the baseplate (2).
11. Measure the distance between the back of connecting link arm (13) and the mounting plate (2). The measurement should be the same as the “C” dimension recorded during the GAL® Recording Critical Measurements procedure. Move the door operator until the “C” dimension is the same.
12. Square the MAC® door operator to baseplate (2) while maintaining the “C” dimension for the connecting link arm (13). The “A”, “B”, and “C” measurements should align the connecting link arms (13 & 15) and crank arms (8 & 9) with the MAC® door operator.
13. Temporarily clamp the MAC® door operator to baseplate (2) to prevent it from moving.
14. Turn sheave (6) by hand until the car doors are in a “completely open” position. If “completely open” position cannot be reached, loosen the hold-down clamps on the MAC® door operator. Carefully shift door operator from side-to-side until doors are “completely open”.
15. Turn sheave (6) by hand until the car doors are in a “completely closed” position.
16. Adjust the stroke and the side-to-side position of the door operator for “completely open” and “completely closed” positions. Stroke for crank arm (8) is the distance from the bottom of scribed line on adapter bar (7) to the center of pivot point (12). Stroke for crank arm (9) is the distance from the bottom of scribed line on adapter bar (7) to the center of pivot point (14).
Increasing the stroke allows the doors to travel more in the open and closed directions. Decreasing the stroke allows the doors to travel less in both directions.
17. Adjust door stop bolt (19) so it stops door roller (18) when the doors are fully closed.
Right-hand center opening. Door roller (18) shown as viewed from the top.

Left-hand center opening. Door roller (18) shown as viewed from the left end.
18. Use existing holes in MAC® door operator end brackets (16), for drilling holes in mounting plate (2).
19. Install bolts and nuts (17) in drilled holes. Refer to section “Wire door operator” for information on wiring MAC® door operator.

A604-014 (6/96)

PAA8-604 (8/98)

# Door Operator Conversion

# GAL® -to-MAC® door operator (center-opening)

25

# GAL®-to-MAC®

# WIRE DOOR OPERATOR

1. Install and secure field wiring conduit (1) to appropriate knockout (2) in operator base.
2. Pull traveling cable wires from elevator controller, and connect them to L1A, L2A, DO7, DO10, and DO3 of terminal block TB-1 (3).

If you are unable to direct-wire, connect one end of a line cord to L1A and L2A. Wire the other end into a separately fused, non-switched 115 VAC power supply from the elevator control system.
3. If the existing relay logic controller has circuitry for nudging, connect a traveling cable wire to DO4.
4. Connect a traveling cable wire to the Normally Closed contact (4) on cam microswitch DO17.
5. Connect a traveling cable wire to DO18 (5) on 104 Auxiliary Locking Board.

A604-015 (7/96)

PAA8-604 (8/98)

# Door Operator Conversion

# WIRE GATE SWITCH

Wire gate switch to existing car gate circuit from controller. Consult controller schematics for proper connections.

A604-016 (1/95)

# Input & Output Terminals & DO17 Cam operated microswitch

|L1A to L2A|120VAC @ 500VA input. If one of the input lines is grounded, it should be connected to L1A.|
|---|---|
|DO3 to L1A|Open limit signal. A relay across these terminals will be de-energized when the open limit microswitch is actuated. Relay will be energized at all other times.|
|DO7 to L1A|Signal to close. When a relay contact across these terminals is made up, the doors will close.|
|DO10 to L1A|Signal to open. When a relay contact across these terminals is made up, the doors will open.|
|DO17(NC) to L1A|Close limit signal. A relay across these terminals will be de-energized when the close limit microswitch is actuated. Relay will be energized at all other times.|
|F NC NO|Auxiliary C relay switching contact. Designates a Form “C” contact on a 1-C relay.|
|F NC NO|Auxiliary O relay switching contact. Designates a Form “C” contact on a 1-O relay.|
|DSD to SS|Optional - Used on some projects for load balancing or other customer requirements.|

A604-SI4 (1/96)

# Wiring to MIPROM controller

MIPROM controllers have terminals on I/O boards that connect to like terminals on the door operator.

A604-SI8 (1/96)

# GAL®-to-MAC®

# Wiring non-MIPROM logic controller

The existing door open limit contact, door close limit contact, and any connections used to feed the GAL door motor are no longer needed. The travel cable wires may be connected to other new functions. Remove the GAL door resistors, fuses, capacitors, and rectifier (if the door motor circuit was the only load). The Open and Close relays are used, but they are rewired. If the contacts are worn, replace the contacts or relays.

1. The MAC door operator requires 120VAC @ 500VA power. Review the existing controller wiring diagrams to see if this power is available from the controller. If not, a step-down transformer is required to step down the line voltage to 120 VAC.
2. For most conversions, three relays, (DOL, DCL and RUN) have to be added to existing relay logic controllers. The DOL (1) and DCL (2) relays require 120 VAC coils. The RUN relay requires a coil (3) with the same voltage as the Door Close relay on the relay logic controller. The relay contacts should be large enough to handle the voltage/current feeding the existing open and close relay coils.
3. Disconnect the existing DOL limit switch (4).
4. Connect the traveling cable wire from DO3 to one side of the DOL relay coil (1). Connect the other side of the DOL relay coil to L1A.
5. Wire a normally open contact on DOL relay (5) to the terminals previously used by the GAL door open limit contact on the existing relay logic controller.
6. Connect the traveling cable wire from the Normally closed contact of microswitch DO17 to one side of the DCL relay coil (2). Connect the other side of the DCL relay coil to L1A.
7. Disconnect the existing DCL limit switch (6).
8. Wire the Normally Open contact on one pole of DCL relay (7) to the terminal on the line side. Wire the common of that pole to the other terminal where the GAL door close limit was wired.
9. Wire the N.C. contact on the same pole of DCL relay (8) to one side of the RUN relay coil (3).
10. Wire the other side of the RUN relay coil (3) to the return line side (9) of the existing GAL door close relay coil (10) circuit.

Contacts off: Existing Open & Close relays (if both used) and Nudging

g2 X2i 2y22@ 2xy22 22A22x

PAA8-604 (8/98)

# Door Operator Conversion

1. The open and close relay contacts that were driving the old GAL door motor are not needed. Use those relay contacts to provide the open and close signals to the MAC operator. Remove existing wires from the contacts and rewire the N.O. contact on the open relay between L1A and DO10 on TB1 on the MAC door board.
2. Wire the N.O. contact on the close relay between L1A and the traveling cable wire from DO7 on TB1 on MAC door board.
3. Wire a N.O. contact on the RUN relay between L1A and the traveling cable wire from DO18 on 104 Auxiliary board.
4. If the existing relay logic controller has circuitry for nudging, wire a N.O. contact of the nudging relay between L1A and the traveling cable wire from DO4.

A604-025 (8/98)

# GAL®-to-MAC®

# Adjusting door operator control Board 1Ø4TM

The following describes instructions for adjusting the door operator control Board 1 Ø4 TM.

- Measure current (optional)
- Set potentiometers
- Adjust door speeds
- Adjust door closing force
- Adjust nudge speed
- Set microswitch cams

Damage to the door operator control board can result if the following adjustment instructions are not followed carefully. If you cannot complete any of the following procedures as they are described, stop and request assistance.

A604-017 (1/95)

# Toggle switches

To adjust and service the door control, use the two toggle switches on the door operator control Board 1 Ø4TM — the TEST-RUN switch and the O-OFF-C switch.

- TEST-RUN. The TEST-RUN switch is normally in the RUN position. When the TEST-RUN switch is in the TEST position, it disconnects the normal open and close input signals from the door control, and switches the O-OFF-C toggle switch into the circuit.
- O-OFF-C. The O-OFF-C switch is normally in the OFF (center) position. This OFF position does not indicate that input power has been removed, it only indicates there is no signal to open or close when the TEST-RUN switch is in the TEST position.

A604-SI5 (1/95)

30 PAA8-604 (8/98)

# Door Operator Conversion

# MEASURE CURRENT (OPTIONAL)

CAUTION: Do not install an ammeter in the power supply line.

Current measurements are not required to adjust the door operator control Board 1Ø4TM. Although, if you wish to measure current, do so as follows.

1. Connect a voltmeter to resistor R2 (.1 Ohm 5 watt resistor) located between heat sinks Q2 and D2.
- Viewing from the TB1 side of the control board, the right side of resistor R2 is (-) and the left side of resistor R2 is (+).
2. Set the voltmeter to a low range — 1 volt or 2.5 volt.
3. Read the measurement, keeping the following in mind.
- 1 volt on the meter indicates 10 amps of current.
- .5 volt on the meter indicates 5 amps of current.

A604-018 (1/95)

You will feel a click when potentiometers reach either end of their travel. It is acceptable to turn the potentiometer past these points because of a built-in slip clutch at each end. These multi-turn potentiometers require 25 turns to traverse their complete range.

A604-019 (1/95)

# Cutting top circuit trace on Door Board 104

To have the door operator function as required, a circuit trace on the Board 104 must be cut. The trace is the top trace of the eight jumper traces located immediately to the left of the green LEDs that indicate the speed potentiometers.

Cut this trace only. Use utility knife or pocket knife.

Check the board to make sure the top trace is cut before proceeding with any procedures.

A604-SI9 (8/98)

LED3

LED4

LED5

A604-113 (8/98)

31