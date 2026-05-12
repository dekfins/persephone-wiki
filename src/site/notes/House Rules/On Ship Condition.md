---
{"dg-publish":true,"permalink":"/house-rules/on-ship-condition/","dg-note-properties":{}}
---

#### Core Stats
The rules apply to anything from a stolen SCUM skiff to a salvaged torchship.

| Stat                       | Meaning                                                                        | Example                             |
| -------------------------- | ------------------------------------------------------------------------------ | ----------------------------------- |
| **Hull Integrity (HP)**    | Structural damage. At 0 the ship is a debris field.                            | 15                                  |
| **Reactor Integrity (RI)** | Health of the power plant. Scale and danger depend on reactor type.            | 6/6 (Volatile)                      |
| **Armor**                  | Reduces incoming damage from attacks.                                          | 2 (corrugated plating and spite)    |
| **TWR**                    | Acceleration in g. Affected by damage and encumbrance.                         | 0.05g (0.04g if a thruster is down) |
| **Active Conditions**      | A list of specific problems: cracked loops, dead thrusters, haunting whispers. | Usually empty, sometimes tragic     |

---
#### Active Conditions
Conditions are temporary or semi-permanent debilities that befall a ship through combat, critical failures, or the Travel Table. Each has a **Fix DC** to remove, and a mechanical effect until then. A crew member can attempt to clear one condition by taking the **Ship Maintenance** downtime action or spending an appropriate amount of time during a crisis.

| d10    | Condition                     | Effect                                                                                                                                                                                                                                         | Fix DC                                            |
| ------ | ----------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------- |
| **1**  | **Cracked Coolant Loop**      | -1 to all Reactor Maintenance checks. On a critical failure, everyone in the engine compartment gains 1 Rad. If this condition remains untreated for 3 consecutive travel segments, the leak worsens. Lose 1 RI, then reset the segment count. | 10                                                |
| **2**  | **Thruster Offline**          | One thruster dead. TWR reduced by 20% (or 0.01g, whichever is worse) per offline thruster. If all are offline, ship cannot maneuver.                                                                                                           | 12                                                |
| **3**  | **Sensor Array Damaged**      | -2 to all Nav and Comms checks. Cannot detect ghost signals or approaching ships beyond visual range.                                                                                                                                          | 10                                                |
| **4**  | **Life Support Degradation**  | CO2 scrubbers failing. -1 to all crew skill checks from sluggishness. After 2 segments without repair, crew gains 1 Rad per segment from contaminated air.                                                                                     | 10                                                |
| **5**  | **Hull Breach**               | A compartment is open to vacuum. Lose 1 HP per segment until patched. Crew cannot access that compartment without vacc suits.                                                                                                                  | 8                                                 |
| **6**  | **Berth Microfractures**      | Lead lining compromised. Resting does not remove Rads.                                                                                                                                                                                         | 12                                                |
| **7**  | **Comms Array Damaged**       | Cannot send or receive long-range transmissions. Vega may lose contact with the crew's ship entirely until fixed.                                                                                                                              | 10                                                |
| **8**  | **Weapon System Malfunction** | One weapon (if any) becomes inoperable. The multifocal laser now produces only a faint, judgmental hum.                                                                                                                                        | 12                                                |
| **9**  | **Strange Resonance**         | The ship is resonating weirdly. Low-level vibrations, odd sensor echoes. -1 to all Mental saves for the crew. May attract… attention.                                                                                                          | 14 (requires investigation, not just wrench work) |
| **10** | **Double Dip**                | Just because one condition wasn't enough. Reroll twice and take both results. Duplicates are rerolled.                                                                                                                                         | -                                                 |

* A ship can have multiple conditions at once. They're written on the dashboard in plain language: *"Thruster 3 offline. Cracked coolant loop. Strange resonance (ongoing)."* 
 
---

#### Used & Derelict Ships
**Used ship (second-hand, "runs great, minor wear"):** Roll **1d4** on the d10 table. The result is the pre-existing condition. The seller's price already "reflects" it. The seller definitely didn't mention it.

**Derelict ship (dead in space, salvage, ghost ship):** Roll **2d10**. Take both results. Duplicates are rerolled.