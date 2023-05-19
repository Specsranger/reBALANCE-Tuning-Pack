# reBALANCE-Tuning-Pack

With the current state of balance in Company of Heroes 3, my co-dev and I decided to develop a soft COH3 balance tuning pack for consideration in assisting with multiplayer balancing.

## Potential Future Changes
- Add breach ability to all units armed with grenades to increase utility and usage
- Add gun traversal to assault guns and TDs so they’re flankable
- Fix AOE damage to HMGs when occupying a building as it destroys the weapon earlier than the crew
- Fix Flare duration to match the lifetime of the flare model and sight
- Remove on the move repair with the USF Field Repairs ability
- Fix pintle MGs firing beyond their set range

## Highlights
- Increased max Camera distance by 33%
- Reverted most changes that have been affected by 1114 Balance Patch
- Limited ability for either factions to paradrop starting units at the start of the match
- Reinforcements require additional tuning:
  - Recrew team weapons ability should only be used out of combat and out of range of enemies to prevent fast recrewing of 17 pounders, Flak 36s, and emplacements
  - Wehrmacht Medical Bunkers can now auto reinforce
  - Grenadier’s merge ability should not be applicable to retreating units
- Reduced AA range by 55% to an average range of 120 from 720+ AA units should not be able to shoot down planes from anywhere on maps
- Reduced all flamethrower range to 15 from 20
- Emplacements, towable heavy artillery, and offmaps should no longer attack HQs:
  - Includes BL55 Artillery Emplacement, Cannone Da 105/28 Howitzer, Infantry Section’s Forward Observer Artillery Barrage, and Dingo’s Forward Observer Artillery Barrage
- Changed requirements for USF support companies to lock T4 rather than T2/3 to open more viable strategies
  - Increased fuel price of T3 to 55 from 45
- Reduced hitpoints of 17pdr and Flak 36 to 350 from 600 to keep in line with standard heavy team weapons hitpoints
- Marders overperform for their cost compared to other TD:
  - Increased manpower cost to 320 from 280 and fuel cost to 45 from 25
- Bazookas and GrB 39s no longer require initial weapon reload when deployed
- Updated SBPS and EBPS names of MG34 and MG42 to keep consistent with existing set naming conventions
- Fixed detect mines toggle missing on sappers (was overlapped by breach)
- Added missing towing to DAK medical truck
- Added handbrakes to Halftracks and Trucks
- Smoke has should be added to units that were missing its upgrades:
  - Fixed USF vehicle smoke launchers that canceled after additional player actions and is now brought in line with DAK vehicle smoke launchers
  - Added Smoke Launchers have to the Whizbang as it’s classified as a Sherman
  - Fixed missing smoke ability for DAK’s Mortar Halftrack
- Standardize ultra-light vehicle camo detection range:
  - Increase Dingo’s range to 4 from 1
  - Decrease Kettenkard’s range to 4 from 15
  - Decrease 221’s range to 4 from 15
- Increase Scout and Pioneer squad sizes to 4 from 3 to increase survivability, offensive power increase is minimal
- Decrease target size of Snipers back to 133 from 15
- Remove deflection damage to Boys and Panzerbusche39, but increased ROF, and increased max penetration by 10% to compensate for decreased DPS due to change
- Fix typos and missing effectiveness infos

## Faction Changes

### US Forces
- Scouts:
  - Added sprint to Scouts to improve unit effectiveness and late-game utility
- Bazooka squads are underperforming with their low health and firepower:
  - Increased damage to 75 from 60
  - Increased health to 110 from 90
  - Increased cost to 320 from 250
- Paratroopers:
  - Revert munitions cost to 90 from 75 with new damage output
  - Swapped M1 Carbines to M1 Garands to bring performance more in line as mainline infantry
- Heavy Machine Gun Paradrop needs tuning relative to their timing:
  - Can only be dropped within LOS
- SSF Commandos can be improved in performance:
  - Added camouflage ability to keep in line with other Special Operations units
  - Increased SSF Commandos' health to 110 to keep in line with elite infantry health
- Captain:
  - Improved QoL for “Rally to Me!” ability to set on squad position rather than requiring a target
  - Reduced cooldown to 60 from 120
- Increased 75mm HT range to 50 from 45 to improve combat performance compared with its fragility
- M8 Scott role changed to a mobile ranged howitzer unit to expand indirect options for USF:
  - Increased base range to 75 from 60, just out of reach of AT guns
  - Increased “Barrage” range to 75 from 60
  - Increased “White Phosphorus” range to 75 from 60
  - Decreased scatter to 005 to be in line with other light howitzers
  - Increased reload time to 5 from 4
- Chaffee:
  - Increased AOE area radius from 15 to 4 for better anti-infantry
- 1⁄4• Ton 4x4 Truck is missing a key upgrade:
  - Added command truck ability to allow mid/late-game utility
- Sherman Whizbang is greatly underperforming:
  - Increased range to 75, just out of reach of AT guns
  - Changed cost to match Bulldozer at 420 manpower and 90 fuel
  - Added 015 deflection damage for armored area denial
  - Increased penetration to 300
  - Improved precision barrage scatter as it is worse than regular barrage
- Sherman Bulldozer is underperforming:
  - Base range to 40 from 35 to kite AT Infantry more effectively

### British Forces
- Decreased cost of all Training Center upgrades by 5 fuel given the greatly decreased effectiveness
- Engineer SMG profile is overturned:
  - Increased cooldown duration to 25 from 1375
- Infantry Section required tuning:
  - Gated Boys and Bren upgrades behind T2
  - Decrease cost of Bren LMG to 75 from 100
- LMG Commandos are missing a key ability for Special Operations units:
  - Added camouflage ability to keep in line with other Special Operations units
- Increased Centaur base range to 40 from 35 to kite AT Infantry more effectively
- Increased armor of M3 Grant to 195 from 170 to improve the survivability of the unit and attractiveness of the unlock

### DAK
- Timing of Armored Reserves does not align with the current match cadence:
  - Adjusted manpower cost to 220 from 200 and fuel cost to 100 from 150
- Kradschützen required tuning to increase mid-late-game utility:
  - Included as a unit that provides combined arms
  - Increased cost to 240 from 200 as a result of new utility
- Panzergrenadier is underperforming relative to their cost:
  - Weapon profile updated for more optimal long-range combat similar to kar98k_jaeger_ak profile
- Panzerjaeger is undertuned after losing a squad member and is locked behind a call-in:
  - Now buildable in T3 and gated by Support Armored Elements upgrade
  - Increased health to 100 from 85 to better align with other AT infantry
- Bersaglieri are overperforming early game with their permanent sprint passive ability:
  - Decreased cost to 300 from 320
  - Removed “Quick March” ability
  - Swapped “Urra” with “Sprint” ability as it is not meant to be a CQC unit
  - Added fast capture to Bersaglieri to replace Vet 1 ability
  - Added combined arms ability to Bersaglieri to improve combined arms tactics
- 8 Rad is overtuned relative to their timing and unit type:
  - Reduced base health to 360 from 420, the same as Greyhound
- Semovente is underperforming in their TD roles:
  - Increased armor from 100/55/40 to 60/45/30
- Walking Stuka Rocket Artillery should be tuned against vehicles as well:
  - Added 015 deflection damage for armored vehicle area denial
  - Increased penetration to 300
- Flak 36 currently overperforms compared to Allied counterparts due to AA and AT role, alongside full 360 auto targeting:
  - Increased reload to 425 seconds from 2125
  - Increased manpower cost to 380
- Infantry Battlegroup’s HMG bunker was overperforming for cost:
  - Increased munition cost to 60 from 0
  - Increased build time to 45 from 15 to keep in line with standard bunker build time

### Wehrmacht
- Grenadier is undertuned relative to their role and cost with little late-game viability:
  - Reduced upgrade grenadier to elite cost to 50 MP
  - Added LMG42 upgrade to open late-game options
  - Swapped “Sprint” with Bersaglieri’s “Urra!” ability
- Jaeger is overperforming against other infantry with the Panzerschreck upgrade:
  - Give 2 weaker Panzerschreck (160 split between the two) to reduce the squad’s anti-infantry damage while maintaining their potency against vehicles
- Fallschirmpioneer Squad is overtuned relative to their timing:
  - Can only be dropped within LOS
- 221 Scout Car is underperforming for its cost and should serve as a stopgap between AI/AT vehicles:
  - Scaled model to approx size of Humbar given the similar role for on-screen fluency
  - MG34 damage increased to 4 from 3
  - Enabled MG34 as an AA weapon to match Dingo’s performance
  - Decreased damage to 100 to serve new AI/AT role
  - Increased AOE
- Mechanized Zeroing Artillery Barrage is overperforming for its cost and leaves little reaction time for players:
  - Decreased damage of each shot to 50 from 100
  - Increased scatter radius to 8 from 7 to increase survivability of units inside the barraged area
  - Increased ability cooldown to 100 from 60
- Fixed an issue where SdKfz 251 Mechanized Grenadier's “Break down” ability didn't require the vehicle to be stationary
- Fixed an issue where Panzer IV’s and Panther’s hull down abilities were not mutually exclusive
- Fixed an issue where Osttruppen had the MG34 upgrade button available despite not having access to it
- Fixed a bug where 251 Halftrack could retreat without losing its MG42
- Fixed a bug where Pak40 emplacement was unbuildable
- Fixed a bug where Osttruppen G43 could not fire on the move

## Known Issues
- 221 Scout Car gunner and Hellcat crew are scaled incorrectly after unit scale change
- Attack ground radius for flamers are incorrect
