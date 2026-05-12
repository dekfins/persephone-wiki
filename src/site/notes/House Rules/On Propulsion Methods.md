---
{"dg-publish":true,"permalink":"/house-rules/on-propulsion-methods/","dg-note-properties":{}}
---

Efficiency is measured in km/s dV per fuel unit. ~1:40 conversion to real-world Isp (seconds). Numbers tweaked for playability.

#### Clarification
- **TWR**: Abstracted acceleration in g. Constant across ship classes. Bigger ships mount proportionally larger/more engines in the same slot.
- **Power / Mass**: Scales with hull class. Hashmark: Base cost is for a Fighter. Frigate ×2, Cruiser ×3, Capital ×4. Round up. Fit Cost uses SWN mass-point abstraction.
- **Mode Toggle**: Free action at the start of a burn.

#### Chemical Engines
| **Engine**                       | Fuel                  | Efficiency | TWR (g) | Power | Fit Cost | Notes                                                                                                               |
| -------------------------------- | --------------------- | ---------- | ------- | ----- | -------- | ------------------------------------------------------------------------------------------------------------------- |
| **SABRE Mk22**                   | Atm. H2 + onboard LOX | 12         | 4       | 0     | 1        | Works in atmosphere. Required for Milk Skimming. Useless in vacuum without oxidizer.                                |
| **"Matchstick" Methalox Rocket** | Methane + LOX         | 10         | 5       | 0     | 1        | Launch vehicles/thrusters, emergency pods. High thrust, zero efficiency. No one uses these for interplanetary work. |

#### Electric Engines
| Engine                      | Fuel       | Efficiency                                 | TWR (g)                            | Power | Fit Cost | Notes                        |
| --------------------------- | ---------- | ------------------------------------------ | ---------------------------------- | ----- | -------- | ---------------------------- |
| **"Cockroach" Ion Cluster** | Ar, Xe     | 100/250                                    | 0.05                               | 1#    | 1#       | Cheap, reliable, everywhere. |
| **"Hummingbird" VASIMR**    | Ar, Xe, H2 | Mode 1: 100/200/300<br>Mode 2: 180/350/550 | **Mode 1:** 0.1 • **Mode 2:** 0.25 | 2#    | 1#       | Toggle modes per burn.       |

#### Fission Engines
| Engine                                   | Fuel                             | Efficiency                         | TWR (g)                      | Power | Fit Cost | Notes                                                                                                                           |
| ---------------------------------------- | -------------------------------- | ---------------------------------- | ---------------------------- | ----- | -------- | ------------------------------------------------------------------------------------------------------------------------------- |
| **"Hellspawn" Nuclear Saltwater Rocket** | Enriched Saltwater               | 500                                | 2                            | 1#    | 2#       | **You are riding a fucking nuke. Permanent 1* rating like in GTA.** Encumbrance penalty halved because nothing slows this down. |
| **"Ember" Fission Fragment<br>**         | Fission Pellets (+H2 for Mode 2) | Mode 1: 11k<br>Mode 2: 11k + 1k H2 | Mode 1: 0.01<br>Mode 2: 0.15 | 1#    | 2#       | Two modes. Dumping 11 units of hydrogen for every unit of pellets makes thrust tolerable. Requires rare, weaponizable pellets.  |

#### Fusion Engines
| **Engine**                         | Fuel   | Efficiency | TWR (g)                | Power | Fit Cost | Notes                                                     |
| ---------------------------------- | ------ | ---------- | ---------------------- | ----- | -------- | --------------------------------------------------------- |
| **"Old Faithful" Tokamak**         | D+He-3 | 1k         | Atm: 1.5<br>Space: 0.5 | 2#    | 2#       | Atmospheric flight consumes 1 fuel cell per segment/burn. |
| **"Starburst" Axial Flow Z-Pinch** | D+He-3 | 9k         | 0.8                    | 3#    | 4#       | Requires cruiser hull or larger.                          |

#### Antimatter Engines
| **Engine**                             | Fuel        | Efficiency | TWR (g) | Power | Fit Cost | Notes                                                                                                                                                  |
| -------------------------------------- | ----------- | ---------- | ------- | ----- | -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **"Firefly" AM-Catalyzed Microfusion** | AM + D+He-3 | 4k         | 0.5     | 2#    | 2#       | Uses picograms of antimatter to spark fusion. Each fuel cell requires a stabilized pellet.                                                             |
| **"Paperclip" Pure Antimatter**        | AM + H2     | 65k        | 1g      | 4#    | 4#       | The fastest thing built by humans. Requires cruiser hull minimum. Cannot be purchased outright. Leased via POS contract. Breach = faction retaliation. |

---

#### Fuel Prices
| Fuel                        | Base Cost     | Availability                                                |
| --------------------------- | ------------- | ----------------------------------------------------------- |
| **Argon (Ar)**              | 25 CR         | Trivial. Scoopable from any atmosphere with the right gear. |
| **Xenon (Xe)**              | 100 CR        | Civilized stations only. Better dV than Ar.                 |
| **Liquid Hydrogen (LH₂)**   | 250 CR        | Gas giants, water-rich moons. Bulky, boils off.             |
| **Nuclear Saltwater (NSW)** | 1,500 CR      | Black market only. Price fluctuates.                        |
| **Fission Pellets**         | Not sold      | DAVE-regulated. Mission rewards or black market.            |
| **Deuterium / Helium-3**    | 5,000 CR      | Terragrow & POS subsidiaries. ISRU possible.                |
| **Antimatter (AM)**         | Contract only | POS monopoly. No credit price. Faction leverage required.   |
