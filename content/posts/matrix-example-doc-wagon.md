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



```text
                  [C] - Paitent Records
                 /
                /     
[A] -> PLTG -> [B]-->[D] - HTR Tracking/Updates
                \
                 \
                  [E] - Paitent Biomonitoring Systems
```       
