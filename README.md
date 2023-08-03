# reBALANCE-Tuning-Pack

With the current state of balance in Company of Heroes 3, my co-dev and I decided to develop a soft COH3 balance tuning pack for consideration in assisting with multiplayer balancing.

## Highlights
- Streamlined all AA performance to standardized range of 180 from 270. Damage greatly increased so a single magazine can down aircraft to encourage local airspace control.
- Limited ability for either factions to paradrop starting units at the start of the match
    - Wehrmacht Medical Bunkers can now auto reinforce
    - Grenadier’s merge ability should not be applicable to retreating units
- Added “Breach” ability to all grenade throwing units which include Gurkhas, Footguards, Commandos, Grenadiers, Stosstruppen and Paratroopers.
- Emplacements, towable heavy artillery, and offmaps should no longer attack HQs
    - Includes BL5.5 Artillery Emplacement, Cannone Da 105/28 Howitzer, Infantry Section’s Forward Observer Artillery Barrage, and Dingo’s Forward Observer Artillery Barrage
- Changed requirements for USF support companies to lock T4 rather than T2/3 to open more viable strategies.
    - Increased fuel price of T3 to 55 from 45
- Reduced hitpoints of 17pdr and Flak 36 to 350 from 600 to keep in line with standard heavy team weapons hitpoints
- Bazookas and GrB 39s no longer require initial weapon reload when deployed
- Updated SBPS and EBPS names of MG34 and MG42 to keep consistent with existing set naming conventions
- Fixed detect mines toggle missing on sappers (was overlapped by breach)
- Added missing towing to DAK medical truck
- Added handbrakes to Halftracks and Trucks
- Smoke added to units that were missing its upgrades
    - Fixed USF vehicle smoke launchers that canceled after additional player actions and is now brought in line with DAK vehicle smoke launchers
    - Added Smoke Launchers have to the Whizbang as it’s classified as a Sherman
    - Fixed missing smoke ability for DAK’s Mortar Halftrack
    - Added missing smoke ability to Carro Armato M13/40 Light Tank and Tiger
- Standardize ultra light vehicle camo detection range
    - Increased Dingo’s range to 4 from 1
    - Decreased Kettenkard’s range to 4 from 15
    - Decreased 221’s range to 4 from 15
- Increased Scout and Pioneer squad sizes to 4 from 3 to increase survivability, offensive power increase is minimal
- Decreased target size of Snipers back to 1.33 from 1.5
- Removed deflection damage to Boys and Panzerbusche39, but increased ROF, and increased max penetration by 10% to compensate for decreased DPS due to change
- Added Recon Sight ability for Pathfinders and Scouts at Vet 1 which gives them 10 extra LOS when stationary
- Fixed typos and missing effectiveness infos

## Faction Changes
### US Forces
- Air Support Center required rework
    - P-47 Strafing Run cost reverted to 60 from 50
    - P-47 Dive Bomb cost reverted to 90 from 70
    - P-47 Strafing Run Damage decreased to 20 from 30
    - Replaced ASC’s “Double Sortie” with “Improved Munitions” 
    - P-47 Strafing Run can be upgraded with rockets, cost increased to 120 from 50
    - Dive bomb can be upgraded with a heavier 2,500 lb bomb, cost increased to 150 from 70
- P-47 Rockets now cause light suppression on impact to replace reduced damage to infantry
- Scouts
    - Revert Smoke Grenade recharge time  to 120s from 180
    - Revert flare range to 50 from 40. Applies to Scouts and Pathfinders
    - Reduce Scout build time to 30 from 33
- Heavy Machine Gun Paradrop needs tuning relative to their timing
    - Can only be dropped within LOS
- Riflemen performance can be reduced
    - Removed 2nd BAR upgrade to encourage combined arms builds
- Assault Engineers required rework as USF lacked reliable SMG units
    - CP cost increased to 2 from 1 
    - Health increased to 100 from 90
    - Added Thompson (Gurhka stats) upgrade
    - Build time increased to 30 seconds from 25 seconds
    - Manpower cost increased to 280 from 200 
- SSF Commandos can be improved in performance
    - Added camouflage ability to keep in line with other Special Operations units
- Captain
    - Improved QoL for “Rally to Me!” ability to set on squad position rather than requiring a target
    - Reduced cooldown to 60 from 120
- 1/4-Ton 4x4 Truck needs tuning
    - Increased cost to 250 from 240
    - Added Command Truck upgrade to improve mid/late game utility
    - Increased Command Truck upgrade cost to 50 from 25
- M8 Scott role changed to a mobile ranged howitzer unit to expand indirect options for USF
    - Increased base range to 75 from 60, just out of reach of AT guns
    - Increased “Barrage” range to 90 from 60
    - Increased “White Phosphorus” range to 90 from 60
    - Decreased scatter to 0.05 to be in line with other light howitzers
    - Increased reload time to 5 from 4
    - Can only fire when stationary
    - Updated name to M8 Scott Howitzer Motor Carriage
- M18 Hellcat is under tuned comparatively to other TDs
    - Scaled down by 10% for on screen fluency of threat level
    - Increased max speed to 6.5 to match base PIII speed

### British Forces
- Engineer SMG profile is overturned
    - Increased cooldown duration to 2.5 from 1.375
- Infantry Section requires tuning
    - Gated Boys and Bren upgrades behind T2
    - Decreased cost of Bren LMG to 75 from 100
- Gurkhas manpower cost have been increased to 380 from 360 to reflect their performance
- Increased Centaur base range to 40 from 35 to kite AT Infantry more effectively
- Increased armor of M3 Grant to 195 from 170 to improve survivability of unit and attractiveness of unlock
- Perimeter Monitor cost have been reduced to 225 from 250 to reflect performance

### DAK
- Armored Support reworked to address “free” upgrades
    - Replaced Superior Fire Drills with Teller Mines
    - Replaced Vehicle Awareness with Spotting scopes 
- Kradschützen requires tuning to increase mid-late game utility
    - Included as a unit that provides combined arms
    - Increased cost to 240 from 200 as a result of new utility
- Panzerjaeger is undertuned after losing a squad member and is locked behind a call-in
    - Now buildable in T3 and gated by Support Armored Elements upgrade
    - Increased health to 100 from 85 to better align with other AT infantry
- Bersaglieri are overperforming early game with their permanent sprint passive ability
    - Decreased cost to 300 from 320
    - Removed “Quick March” ability
    - Swapped “Urra” with “Sprint” ability as it is not meant to be a CQC unit
    - Added fast capture to Bersaglieri to replace Vet 1 ability
    - Added combined arms ability to Bersaglieri to improve combined arms tactics
- 8 Rad is overtuned relative to their timing and unit type
    - Reduced base health to 360 from 420, same as Greyhound
- Semovente is underperforming in their TD roles
    - Armor increased from 100/55/40 to 60/45/30
- Flak 36 currently overperforms compared to Allied counterparts due to AA and AT role, alongside full 360 auto-targeting
    - Increased reload to 4.25 seconds from 2.125
    - Increased manpower cost to 380
- Infantry Battlegroup’s HMG bunker was overperforming for cost
    - Increased munition cost to 60 from 0
    - Increased build time to 45 from 15 to keep in line with standard bunker build time
- Booby trap is under performing relative to cost
          - Decreased cost to 50 from 55 to keep in line with specialized passive defense like the teller mine
  
### Wehrmacht
- Grenadier is undertuned relative to their role and cost with little late game viability
    - Reduced upgrade Grenadier to elite cost to 50MP
    - Added LMG42 upgrade to open late game options
    - Swapped “Sprint” with Bersaglieri’s “Urra!” ability
- Jaeger is overperforming against other infantry with the Panzerschreck upgrade
    - Give 2 weaker Panzerschreck (160 split between the two) to reduce the squad’s anti-infantry damage while maintaining their potency against vehicles
- Fallschirmpioneer Squad is overtuned relative to their timing
    - Can only be dropped within LOS
- Stoßtruppen needs tuning
    - Increase Stoßtruppen’s STGs ready aim time from 0.5 to 0.25 to improve upgrade desirability 
- 221 Scout Car is underperforming for its cost and should serve as a stopgap between AI/AT vehicles
    - Scaled model to approx. size of Humbar given the similar role for on-screen fluency.
    - Decreased damage to 100 to serve the new AI/AT role
    - Increased AOE
- MG42 cost increased to 280 from 240 to reflect performance
- Nebelwerfer scatter reduced to 8 from 12 so it’s DOT is less oppressive
- Decreased reload time of Stummel from 5 to 4 to improve upgrade desirability 
- Revert fuel costs of Panzer IV to 90 from 100 to match medium tank price to performance ratio
- Panther performance can be adjusted to be more dedicated against vehicles
    - Increased range to 45 from 40
    - Reduced speed to 5 from 5.2
- Increased Brummbar base range to 40 from 30 to kite AT Infantry more effectively

## Potential Future Changes
- Remove on the move repair with the USF Field Repairs ability

## Known Issues
- 221 Scout Car gunner and Hellcat crew are scaled incorrectly after unit scale change
- ASC’s “Improved Munitions” incorrectly calls in double P47’s for rocket strafe and a JU-87 for Bombing Run
