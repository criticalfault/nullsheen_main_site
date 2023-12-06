---
title: "Matrix Example - Doc Wagon"
date: 2023-12-03T21:28:33Z
draft: true
---

As we continue with these examples we are going to continue to add more complexities to these systems. In this system we are going to introduce multiple nodes. Each node itself will have its own security sheaf. Each system will be marked with a letter and its Sheaf will be added in a table next to its letter. A new rule you will need to pick up as well is that security tally carries as the decker moves between different subsystems. The way SR3 explains it, is that until you leave the host wholesale or log in from a different RTG. This means however that each host only cares about its own tally. 

The practical example of this is if a decker logs into the Seattle Regional Telecom Grid (RTG) and then tries to log into his local Stuffer Shack to steal some snack coupons generating 4 security tally. When they leave the Stuffer Shack host and then log into Renraku's movie threater to steal some tickets. His security tally on Renraku's hosts don't care about his Stuffer Shack tally. Should they rack up 6 or so tally in Renraku and then heads back to Stuffer Shack, they will begin that hack with the 4 tally they had before. This lasts until they gracefully log off or switch RTGs to begin the hack from.

## Description
Doc Wagon is an incredible service for those with money to spare in the Shadowrun Universe. This armed medical response is one of the many aspects the distopian nightmare that is the 6th world. They represent some of the hardest targets for Deckers to hit. It contains a treasure trove of information for runners to use for paydata.

## Detailed look at Interrogation Tests
Locating a file or slave systems requires a Locate [File OR Slave] operation. This operation requires a computers test against the Index of the host they are in. If the file or slave is in the host they are in, after 5 successes (or I allow 3 if they have super detailed information) they find it. Otherwise, 3 successes will tell them the system (And its locally connected systems) doesn't contain what they are looking for.

If the file or slave node isn't actually on the system they are in, after 5 successes the host will point to the host that contains that icon they are looking for. This means they will need to move to that host in order to download/monitor/edit the icon in question.

## Extra Security
This brings us however to our first "local" to "private" systems. Private systems (PLTGs) carry something special. PLTGs DO care about Tally from other hosts. If your decker gathers up a load of tally stealing PayPerView cage match before heading into a PLTG, the first host will trigger all the IC the sheaf has to offer up to the current tally of course. This can mean firing off quite a few IC instantly as they log into the host. A nasty surprise. 

### Tiered Access
Any host within the system cannot be reached until they enter System B. If they then want to go into C, they can come B. However if they want to go to D and E, he will have to go back to B before proceeding. This will require the decker to bounce back and forth on the systems, each time potentially getting more tally as they break into each system.

This example below is a more "basic" example. When you want to switch it up or make it even more difficult. This kind of system would have deckers monitoring the system constantly. They may be alerted when the Scramble IC is deactived or crashes. 

### System Ops
Systems with this kind of important information will always be guarded by other system Ops. 
```text
Game Statistics
B Q S   I   W C  E    R
3 5 3 6 (7) 6 5 3.6  5 (6)
INIT: 5 (6) + 1D6, Matrix INIT (pure DNI): 7 (11) + 1D6 (3D6)
Dice Pool: Combat 9, Hacking 5 (10), Task 2
Karma Pool/Professional Rating: 3/2
Active Skills: Computer 6 (Decking 8), Computer B/R 3,
Electronics 4, Etiquette 4 (Matrix 6) (Corporate 5), Instruction 2
(Decking 4), Leadership 4, Pistols 4, Small Unit Tactics 4 (Matrix
Tactics 6)
Knowledge Skills: Decker Tricks 4, IC profiles 6, Matrix
Topography 5, 5 others at rating 5
Bioware/Cyberware: Cerebral booster 1, datajack, encephalon
2, headware memory (150 Mp), math SPU 3
Gear: Transys Highlander cyberdeck, various programs Ratings between 6 and 9. 

Programs to consider:
Scanner - For finding deckers
Validate - For invalidating users
Triangulation - Finding users in the real world
Track - Finding users in the real world
Armor   - Combat!
Cloak   - Combat!
Lock-On - Combat!
Attack-S- Combat!
Medic - Healing from Combat Damage
```

## Actions Deckers may find intriguing on this system
 - #### Research Medical Records
    - Files needing to be edited are located inside Host C.
    - [Locate File] p. 217 - SR3
        - 5 Successes needed if they just have only sporadic details about the person or their account (first and last name, phone number) 
        - 4 Successes needed if they know a specific detail about the account (Corp the Citizen belongs too, health record information)
        - 3 Successes needed if they know the Account Number or SIN of Account Holder
   - [Edit File] p. 216 - SR3
        - 1 Success is needed to download the files. 
 - #### Locate HTR / Attempt to Deploy HTR
    - Files needing to be edited are located inside Host D.
    - [Locate File] p. 217 - SR3
        - 5 Successes needed if they just have only sporadic details about the person or their account (first and last name, phone number) 
        - 4 Successes needed if they know a specific detail about the account (Corp the Citizen belongs too, driving record information)
        - 3 Successes needed if they know the plate or VIN number of vehicle registered or Account Number or SIN of Account Holder
   - [Edit File] p. 216 - SR3
        - 1 Success is needed to alter the file. This would allow the decker to upgrade an account to a premium account, remove accident histories to reduce payments, alter the vehicle the account is registered too, etc. Whole new accounts would require the decker to first get a copy of a legit record, then make whatever changes they want, then upload the new copy. You can also copy a file on the server and then make an edit directly against the copied file. 
 - #### Alter / Erase Records / Get Free Health Insurance
   - Files needing to be edited are located inside Host C.
   - [Locate File] p. 217 - SR3
        - 5 Successes needed if they just have only sporadic details about the person or their account (first and last name, phone number) 
        - 4 Successes needed if they know a specific detail about the account (Corp the Citizen belongs too, driving record information)
        - 3 Successes needed if they know the plate or VIN number of vehicle registered or Account Number or SIN of Account Holder
   - [Edit File] p. 216 - SR3
        - 1 Success is needed to alter the file. This would allow the decker to upgrade an account to a premium account, remove accident histories to reduce payments, alter the vehicle the account is registered too, etc. Whole new accounts would require the decker to first get a copy of a legit record, then make whatever changes they want, then upload the new copy. You can also copy a file on the server and then make an edit directly against the copied file. 
 - #### Find a paitent with a GPS Biomonitor / Remotely Trigger a BioMonitor Alarm
    - Files needing to be edited are located inside Host E.
    - [Locate Slave] p. 217 - SR3
        - 5 Successes needed if they just have the rough description of the car
        - 4 Successes needed if they know a specific detail about the car (dents, custom upgrades, etc)
        - 3 Successes needed if they know the plate or VIN number
    - [Monitor Slave] p. 218 - SR3
        - 1 Success needed to find the location of the vehicle. This would also allow them to get information about heading, speed, charge, etc.


## System Overview
```text
                  [C] - Paitent Records
                 /
                /     
[A] -> PLTG -> [B]-->[D] - HTR Tracking/Updates
               |\
               |  \
               |  [E] - Paitent Biomonitoring Systems
              [F] - Ambulance / Helicopter tracking/updating/Commlinks 


Host A (Green Average)

-----------------
Green-7/11/11/13/13/11

Step: Event
6   : Trace-8
11  : Scout-6 
15  : Passive Alert
21  : Tar Pit-10 
27  : Killer-8 
32  : Ripper-6 
36  : Active Alert
41  : Blaster-8 
47  : Blaster-6 
51  : Blaster-8 
55  : Ripper-6 
60  : Shutdown

Host B (Orange Average)
-----------------
Orange-8/13/14/14/11/14

Step: Event
4   : Tar Baby-10
7   : Trace-10
11  : Killer-8
15  : Scout-8
19  : Passive Alert
23  : Construct-10 
28  : Blaster-6 
32  : Active Alert
36  : Ripper-6 
39  : Blaster-6 
43  : Crippler-8
46  : Blaster-10 
51  : Blaster-8 
54  : Shutdown

Host C (Red Hard)
-----------------
red-9/14/13/12/13/15

Step: Event
2: Killer-8
6: Trace-10 
10: Trace-12
13: Passive Alert
17: Probe-6 
19: Tar Pit-12 
23: Construct-10 
25: Sparky-8 
27: Active Alert
29: Sparky-8 
33: Psychotropic Black IC-10
36: Ripper-8
40: Shutdown

Host D (Red Hard - With nasty extras)
-----------------
red-12/17/17/16/13/15

Step: Event
4: Trace-12
7: Trace-12
11: Tar Baby-6
13: Crippler-10
17: Tar Pit-8
21: Passive Alert
25: Trace-6
27: Killer-6
31: Blaster-8
35: Blaster-10
39: Non-Lethal Black IC-8 
41: Active Alert
44: Lethal Black IC-8
48: Lethal Black IC-8
50: Psychotropic Black IC-10
52: Crippler-10
54: Lethal Black IC-10
58: Shutdown

Host E (Red Hard)
-----------------
red-10/17/14/18/15/14

Step: Event
3: Killer-6
5: Killer-10
7: Tar Pit-10 
10: Crippler-8
12: Tar Pit-6 
14: Passive Alert
18: Trace-8 
21: Sparky-6 
23: Active Alert
27: Non-Lethal Black IC-6
29: Blaster-6 
32: Lethal Black IC-10
36: Killer-8
39: Shutdown
```