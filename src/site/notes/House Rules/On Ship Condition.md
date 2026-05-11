---
{"dg-publish":true,"permalink":"/house-rules/on-ship-condition/","dg-note-properties":{}}
---

#### Core Stats
The rules apply to anything from a stolen SCUM skiff to a salvaged torchship.

| Stat                       | Meaning                                                                           | Example                             |
| -------------------------- | --------------------------------------------------------------------------------- | ----------------------------------- |
| **Hull Integrity (HP)**    | Structural damage. At 0 the ship is a debris field.                               | 15                                  |
| **Armor**                  | Reduces incoming damage from attacks.                                             | 2 (corrugated plating and spite)    |
| **TWR**                    | Acceleration in g. Affected by damage and encumbrance.                            | 0.05g (0.04g if a thruster is down) |
| **dV Cap**                 | Maximum delta-V when fully fueled (km/s). Actual remaining dV tracked separately. | 500 km/s (5 argon cells)            |
| **Reactor Integrity (RI)** | Health of the power plant. Scale and danger depend on reactor type.               | 6/6 (Volatile)                      |
| **Active Conditions**      | A list of specific problems: cracked loops, dead thrusters, haunting whispers.    | Usually empty, sometimes tragic     |

---
#### Reactor Types
Every ship has a reactor type and a new attribute called Reactor Integrity. It starts at its maximum and ticks down when things go very wrong. Think of RI not as "safety" but as "how many times can this thing break before it kills you." Standard reactors are stable but brittle - fewer failure modes before catastrophic shutdown. Volatile reactors are ancient nightmares with so many redundant failure points that they take longer to fully die, bleeding Rads the whole way.

| Reactor Type                                          | Max RI | Degradation Effects                                                                                                                                                                                      | Example                                          |
| ----------------------------------------------------- | ------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------ |
| **Standard** (fission/fusion, common freighters)      | 4      | At 2/4 RI or lower: Reactor Maintenance failures cause +1 Rad. At 1/4: Crew must make Physical saves vs Acute radiation each segment. At 0/4: Catastrophic failure                                       | Belter hauler, DAVE-registered trader            |
| **Volatile** (ancient, salvaged, or military-surplus) | 6      | 3/6: reactor maintenance failures cause +2 Rads. 1/6: Acute save per segment + all Rad gains doubled. 0/6: Prompt criticality. The reactor achieves an uncontrolled chain reaction. Evacuate immediately | The plutonium nightmare from a 23th century ship |
| **Advanced** (antimatter, high-end torchships)        | 8      | 4/8: containment flickers; maintenance failures add +1 Rad. 2/8: Acute save per segment. 0/8: containment loss; the annihilation wave takes the ship and a few kilometers of surrounding vacuum with it. | POS courier, military interceptor                |
RI recovery cannot exceed the reactor’s maximum. RI only drops from combat damage, critical failures, or prolonged neglect.

---
#### Active Conditions
Conditions are temporary or semi-permanent debilities that befall a ship through combat, critical failures, or the Travel Table. Each has a **Fix DC** to remove, and a mechanical effect until then. A crew member can attempt to clear one condition by taking the **Ship Maintenance** downtime action or spending an appropriate amount of time during a crisis.

| d10 | Condition                     | Effect                                                                                                                                                                                                                                         | Fix DC                                            |
| --- | ----------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------- |
| 1   | **Cracked Coolant Loop**      | -1 to all Reactor Maintenance checks. On a critical failure, everyone in the engine compartment gains 1 Rad. If this condition remains untreated for 3 consecutive travel segments, the leak worsens. Lose 1 RI, then reset the segment count. | 10                                                |
| 2   | **Thruster Offline**          | One thruster dead. TWR reduced by 20% (or 0.01g, whichever is worse) per offline thruster. If all are offline, ship cannot maneuver.                                                                                                           | 12                                                |
| 3   | **Sensor Array Damaged**      | -2 to all Nav and Comms checks. Cannot detect ghost signals or approaching ships beyond visual range.                                                                                                                                          | 10                                                |
| 4   | **Life Support Degradation**  | CO2 scrubbers failing. -1 to all crew skill checks from sluggishness. After 2 segments without repair, crew gains 1 Rad per segment from contaminated air.                                                                                     | 10                                                |
| 5   | Fuel Line Fissure             |                                                                                                                                                                                                                                                |                                                   |
| 6   | **Hull Breach**               | A compartment is open to vacuum. Lose 1 HP per segment until patched. Crew cannot access that compartment without vacc suits.                                                                                                                  | 8                                                 |
| 7   | **Berth Microfractures**      | Lead lining compromised. Resting does not remove Rads.                                                                                                                                                                                         | 12                                                |
| 8   | **Comms Array Damaged**       | Cannot send or receive long-range transmissions. Vega may lose contact with the crew's ship entirely until fixed.                                                                                                                              | 10                                                |
| 9   | **Weapon System Malfunction** | One weapon (if any) becomes inoperable. The multifocal laser now produces only a faint, judgmental hum.                                                                                                                                        | 12                                                |
| 10  | **Strange Resonance**         | The ship is resonating weirdly. Low-level vibrations, odd sensor echoes. -1 to all Mental saves for the crew. May attract… attention.                                                                                                          | 14 (requires investigation, not just wrench work) |

* A ship can have multiple conditions at once. They're written on the dashboard in plain language: *"Thruster 3 offline. Cracked coolant loop. Strange resonance (ongoing)."* 
 
---

#### Used & Derelict Ships
**Used ship (second-hand, "runs great, minor wear"):** Roll **1d4** on the d10 table. The result is the pre-existing condition. The seller's price already "reflects" it. The seller definitely didn't mention it.

**Derelict ship (dead in space, salvage, ghost ship):** Roll **2d10**. Take both results. If you roll doubles, add a **Cracked Coolant Loop** for free on top, because the universe finds neglect funny.