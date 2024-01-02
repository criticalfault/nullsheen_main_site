---
title: "Matrix Example - Doc Wagon"
date: 2023-12-03T21:28:33Z
featured_image: "/images/DocWagonCommandCenter.png"
draft: false
tags: ['GM Help']
---

As we continue with these examples we are going to continue to add more complexities to these systems. In this system we are going to introduce multiple nodes. Each node itself will have its own security sheaf. Each system will be marked with a letter and its Sheaf will be added in a table next to its letter. A new rule you will need to pick up as well is that security tally carries as the decker moves between different subsystems. The way SR3 explains it, is that until you leave the host wholesale or log in from a different RTG. This means however that each host only cares about its own tally. 

The practical example of this is if a decker logs into the Seattle Regional Telecom Grid (RTG) and then tries to log into his local Stuffer Shack to steal some snack coupons generating 4 security tally. When they leave the Stuffer Shack host and then log into Renraku's movie theater to steal some tickets. His security tally on Renraku's hosts don't care about his Stuffer Shack tally. Should they rack up 6 or so tally in Renraku and then heads back to Stuffer Shack, they will begin that hack with the 4 tally they had before. This lasts until they gracefully log off or switch RTGs to begin the hack from.

## Description
Doc Wagon is an incredible service for those with money to spare in the Shadowrun Universe. This armed medical response is one of the many aspects the dystopian nightmare that is the 6th world. They represent some of the hardest targets for Deckers to hit. It contains a treasure trove of information for runners to use for paydata. One thing to consider is that not everyone uses Doc Wagon for their medical needs. Corporations tend to have their own medical services and more importantly, guard their own patient data. While bringing people in with medical needs, they may not even record anything, instead handing it over to the corp in question to deal with the specifics once the patient is stablized. So not everyone's data in Doc Wagon, but boy, there sure is a lot of people who are.

## Detailed look at Interrogation Tests
Locating a file or slave systems requires a Locate [File OR Slave] operation. This operation requires a computers test against the Index of the host they are in. If the file or slave is in the host they are in, after 5 successes (or I allow 3 if they have super detailed information) they find it. Otherwise, 3 successes will tell them the system (And its locally connected systems) doesn't contain what they are looking for.

If the file or slave node isn't actually on the system they are in, after 5 successes the host will point to the host that contains that icon they are looking for. This means they will need to move to that host in order to download/monitor/edit the icon in question.

## Extra Security
This brings us however to our first "local" to "private" systems. Private systems (PLTGs) carry something special. PLTGs DO care about Tally from other hosts. If your decker gathers up a load of tally stealing PayPerView cage match before heading into a PLTG, the first host will trigger all the IC the sheaf has to offer up to the current tally of course. This can mean firing off quite a few IC instantly as they log into the host. A nasty surprise. 

### Tiered Access
Any host within the system cannot be reached until they enter System B. If they then want to go into C, they can come B. However if they want to go to D and E, he will have to go back to B before proceeding. This will require the decker to bounce back and forth on the systems, each time potentially getting more tally as they break into each system.

This example below is a more "basic" example. When you want to switch it up or make it even more difficult. This kind of system would have deckers monitoring the system constantly. They may be alerted when the Scramble IC is deactivated or crashes. 

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
   - [Download Data] p. 216 - SR3
        - 1 Success is needed to download the files. 
 - #### Locate HTR Resources / Attempt to Deploy HTR
    - Files needing to be edited are located inside Host D.
    - This is the mack daddy of hacks. This is the kind of thing that leaves the Decker a legend, or a charred mess of neurons. 
    - [Locate Slave] p. 217 - SR3
        - 5 Successes needed if they just have only sporadic details about the person or their account or the accident (first and last name, phone number, type of emergency, rough area of the call) 
        - 4 Successes needed if they know a specific detail about the account (Corp the Citizen belongs too, health record information)
        - 3 Successes needed if they know the plate or VIN number of vehicle registered to Doc Wagon or Account Number of the Victim or SIN of Account Holder the call was made for.
   - [Monitor Slave] p. 218 - SR3
        - 1 Success is needed to monitor the vehicle. This would allow the decker to watch from the camera feeds of the vehicle, get the GPS location of the vehicle's transponder or even listen in on internal Mics of the Vehicle.
   - [Edit Slave] p 216 - 217 - SR3
     - 1 Success is enough to override the GPS transponder or edit the crew's location data in the computer to possibly swap where they need to go. 
 - #### Alter / Erase Records / Get Free Health Insurance
   - Files needing to be edited are located inside Host C.
   - [Locate File] p. 217 - SR3
        - 5 Successes needed if they just have only sporadic details about the person or their account (first and last name, phone number) 
        - 4 Successes needed if they know a specific detail about the account (Corp the Citizen belongs too, health record information)
        - 3 Successes needed if they know Account Number or SIN of Account Holder
   - [Edit File] p. 216 - SR3
        - 1 Success is needed to alter the file. This would allow the decker to upgrade an account to a more premium account, remove medical histories to reduce payments, etc. Whole new accounts would require the decker to first get a copy of a legit record, then make whatever changes they want, then upload the new copy. You can also copy a file on the server and then make an edit directly against the copied file. It should be considered that Platinum and Super Platinum accounts may trigger deeper investigations. So unless the decker is ready for that, the error may be caught and reverted.
 - #### Find a patient with a GPS Biomonitor / Remotely Trigger a BioMonitor Alarm
     - Files needing to be edited are located inside Host E.
     - Patients with specialized bio-monitors (including cyberware) all have to be monitored/logged some place. This is that place.
     - [Locate Slave] p. 217 - SR3
          - 5 Successes needed if they just have only sporadic details about the person or their account (first and last name, phone number) 
          - 4 Successes needed if they know a specific detail about the account (Corp the Citizen belongs too, health record information)
           3 Successes needed if they know Account Number or SIN of Account Holder
     - [Monitor Slave] p. 218 - SR3
          - 1 Success needed to find the location of the bio-monitor. This would also allow them to get information about the person, heart rate, blood pressure, O2, etc. If the Bio-Monitor is reporting it, the decker would have access to it.
     - [Edit Slave] p. 216-217 - SR3
          - 1 Success is needed to alter the readings on the Bio-Monitor. This would allow the decker to fake bad readings such as high heart rates, low or high blood pressure. The kind of things people tend to go to the hospital for. Excellent for moving a target into the open. 

## System Overview
```text
                 [C] - Patients Records
                /
               /     
[A] -> PLTG -> [B]-->[D] - HTR Tracking/Updates/Commlinks
               \
                \
                 [E] - Patients Biomonitoring Systems

```

### Host A (Green Average) - Public Host
This host is a front facing host for people to use for looking up public information, meet with Doc Wagon employees to inquire about their services, etc. Nothing important is kept in this host, it's simply a place for icons to gather to do business. Everything important to Doc Wagon is store within the P-LTG
```text
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
```

### Host B (Orange Average) - Hub Host
All hosts within the PLTG meet back to the Hub. Modeling, it may look like a busy hospital floor, with generic icons of doctors and nurses moving through the system. Files being moved may look like chart folders and large files looking like patients being moved between rooms.
```text
Orange-8/13/14/14/11/14

Step: Event
4   : Tar Baby-10 (Sleaze)
7   : Trace-10
11  : Killer-8
15  : Scout-8
19  : Passive Alert
23  : Scout-10 
28  : Blaster-6 
32  : Active Alert
36  : Ripper-6  (mark-rip)
39  : Sparky-6 
43  : Crippler-8 (acid)
46  : Non-Lethal Black-8
51  : Non-Lethal Black-10
54  : Shutdown

```

### Host C (Red Hard) - Patients Records
All records kept by hospital staff including payments, contract level, medical records, etc. This is where you would need to be to dig up dirt on enemies or attempt to update data for free medical service.

Something to note is p.216's rules for Editing Files. You need to be sure that files created will stick around, otherwise they can be noticed in hours.
> "After altering, inserting, or deleting a file, a decker may make a Control Test, with target number reduced by his read/write utility, to authenticate the file’s headers. Note the number of successes. If the decker fails to successfully take his step, make a Masking (Files) Test. The number of successes is the number of hours before the host notices the tampered file and reports it to the host’s supervisor. " p.216 SR3

```text
Red-9/14/13/12/13/15

Always Loaded IC: 
Scrambler-9 attached to File Icons

Step: Event
2: Tar Pit-8 (Browse)
6: Tar Pit-12 (Read/Write)
10: Trace-8
13: Passive Alert
17: Killer-8
19: Trace-12
23: Ripper-10 (Marker)
25: Sparky-8 
27: Active Alert
29: Sparky-10 
33: Psychotropic Black IC-8 (Positive Conditioning)
36: Lethal Black IC-8
40: Shutdown
```
Host D (Red Hard) - HTR Tracking/Updates
This is the brass ring of hosts. The knowledge within this system is worth its weight in gold. The IC here is set to kill or worse. It would take an incredible deck and skills to get into the system here. Notice the first few steps triggering Trace. Upon returning a good trace, an HTR team should visit the decker to explain the trouble they are in punctuated with ADPS rounds.

This host would also have Security Deckers which would begin investigating after a Passive Alert is triggered OR a Trace was completed.
```text
Red-12/17/17/16/13/15

Always Loaded IC: 
Data Bomb-9 attached to Slave Nodes

Step: Event
4: Trace-12
7: Trace-12
11: Tar Baby-6 (Sleaze)
13: Crippler-10
17: Tar Pit-8 (Spoof)
21: Passive Alert
25: Trace-9
27: Killer-8
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
```

### Host E (Red Hard) - Patients Biomonitoring Systems
This is the host where all bio-monitors are recorded at. Each would be their own slave within the system.  

```text
Red-10/17/14/18/15/14

Always Loaded IC: 
Scrambler-9 attached to Slave Nodes

Step: Event
3: Killer-8
5: Killer-10
7: Tar Pit-8 (Read/Write)
10: Crippler-8
12: Tar Pit-8 (Sleaze)
14: Passive Alert
18: Trace-8 
21: Sparky-6 
23: Active Alert
27: Non-Lethal Black IC-6
29: Blaster-6 
32: Lethal Black IC-9
36: Lethal Black IC-11
39: Shutdown
```