---
{"dg-publish":true,"permalink":"/house-rules/on-propulsion-methods/","dg-note-properties":{}}
---

#### Engine Tables
- **Efficiency:** Measured in km/s dV per fuel unit. ~1:40 conversion to real-world Isp (seconds). Numbers tweaked for playability.
- **TWR**: Abstracted acceleration in g. Constant across ship classes. Bigger ships mount proportionally larger/more engines in the same slot.
- **Hashmark (#):** Base cost is for a Fighter. Frigate ×2, Cruiser ×3, Capital ×4.
- **Asterisk (\*):** Base cost is for a Fighter. Frigate ×10, Cruiser ×25, Capital ×100.
- **Mode Toggle:** Free action at the start of a burn.

---
#### Chemical Engines
| **Engine**                       | Base Cost | Efficiency | TWR (g) | Power | Mass | Fuel                  | Class         | Notes                                                                    |
| -------------------------------- | --------- | ---------- | ------- | ----- | ---- | --------------------- | ------------- | ------------------------------------------------------------------------ |
| **SABRE Mk22**                   | 20k       | 12         | 4       | 0     | 1    | Atm. H2 + onboard LOX | Skimmers only | Works in atmosphere. Required for Milk Skimming.                         |
| **"Matchstick" Methalox Rocket** | 2k*       | 10         | 5       | 0     | 1    | CH4 + LOX             | Fighter       | Launch vehicles/thrusters, emergency pods. High thrust, zero efficiency. |

#### Electric Engines
| Engine                      | Base Cost | Efficiency                                 | TWR (g)                            | Power | Mass | Fuel       | Class   | Notes                        |
| --------------------------- | --------- | ------------------------------------------ | ---------------------------------- | ----- | ---- | ---------- | ------- | ---------------------------- |
| **"Cockroach" Ion Cluster** | 5k*       | 100/250                                    | 0.05                               | 1#    | 1#   | Ar, Xe     | Fighter | Cheap, reliable, everywhere. |
| **"Hummingbird" VASIMR**    | 15k*      | Mode 1: 100/200/300<br>Mode 2: 180/350/550 | **Mode 1:** 0.1 • **Mode 2:** 0.25 | 2#    | 1#   | Ar, Xe, H2 | Fighter | Toggle modes per burn.       |

#### Fission Engines
| Engine                                   | Base Cost | Efficiency                         | TWR (g)                      | Power | Mass | Fuel                             | Class   | Notes                                                              |
| ---------------------------------------- | --------- | ---------------------------------- | ---------------------------- | ----- | ---- | -------------------------------- | ------- | ------------------------------------------------------------------ |
| **"Hellspawn" Nuclear Saltwater Rocket** | 10k*      | 500                                | 2                            | 1#    | 2#   | Enriched Saltwater               | Fighter | **Permanent 1* rating like in GTA.** Encumbrance penalties halved. |
| **"Ember" Fission Fragment<br>**         | 60k*      | Mode 1: 11k<br>Mode 2: 11k + 1k H2 | Mode 1: 0.01<br>Mode 2: 0.15 | 1#    | 2#   | Fission Pellets (+H2 for Mode 2) | Frigate | Two modes. Mode 2 consumes Pellets and H2 in a 11:1 ratio.         |

#### Fusion Engines
| **Engine**                         | Base Cost | Efficiency | TWR (g)                | Power | Mass | Fuel   | Class   | Notes                                                     |
| ---------------------------------- | --------- | ---------- | ---------------------- | ----- | ---- | ------ | ------- | --------------------------------------------------------- |
| **"Old Faithful" Tokamak**         | 40k*      | 1k         | Atm: 1.5<br>Space: 0.5 | 2#    | 2#   | D+He-3 | Frigate | Atmospheric flight consumes 1 fuel cell per segment/burn. |
| **"Starburst" Axial Flow Z-Pinch** | 120k*     | 9k         | 0.8                    | 3#    | 4#   | D+He-3 | Cruiser |                                                           |

#### Antimatter Engines
| **Engine**                             | Base Cost | Efficiency | TWR (g) | Power | Mass | Fuel        | Class   | Notes                                                  |
| -------------------------------------- | --------- | ---------- | ------- | ----- | ---- | ----------- | ------- | ------------------------------------------------------ |
| **"Firefly" AM-Catalyzed Microfusion** | 80k*      | 4k         | 0.5     | 2#    | 2#   | AM + D+He-3 | Frigate | Uses picograms of antimatter to spark fusion.          |
| **"Paperclip" Pure Antimatter**        | -         | 65k        | 1       | 4#    | 4#   | AM + H2     | Cruiser | Cannot be purchased outright. Leased via POS contract. |

---

#### Fuel Prices
| Fuel                        | Base Cost     | Availability                                                |
| --------------------------- | ------------- | ----------------------------------------------------------- |
| **Argon (Ar)**              | 25            | Trivial. Scoopable from any atmosphere with the right gear. |
| **Xenon (Xe)**              | 100           | Civilized stations only. Better dV than Ar.                 |
| **Liquid Hydrogen (LH₂)**   | 250           | Gas giants, water-rich moons. Bulky, boils off.             |
| **Nuclear Saltwater (NSW)** | 1,500         | Black market only. Price fluctuates.                        |
| **Fission Pellets**         | Not sold      | DAVE-regulated. Mission rewards or black market.            |
| **Deuterium / Helium-3**    | 5,000         | Terragrow & POS subsidiaries. ISRU possible.                |
| **Antimatter (AM)**         | Contract only | POS monopoly. No credit price. Faction leverage required.   |

---
#### Fuel Fittings
| Fuel Fitting        | Base Cost | Power | Mass | Class   | Effect                                                                                                                                                                                                                                                                                 |
| ------------------- | --------- | ----- | ---- | ------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Fuel Bunker**     | 5k*       | 0     | 1    | Fighter | Stores **5 cells** of a single fuel type. Fuel types cannot be mixed.                                                                                                                                                                                                                  |
| **Cryofuel Bunker** | 10k*      | 1     | 1    | Fighter | A Fuel Bunker, but cryo‑cooled. Prevents hydrogen boil‑off. Also necessary for long‑term storage of NSW.                                                                                                                                                                               |
| **Pellet Magazine** | 20k*      | 0     | 1    | Frigate | Stores **5 cells** of Fission Pellets. Shielded, reinforced, and stamped with a DAVE compliance serial number. Carrying pellets without a magazine is a violation that earns a 1‑star wanted level.                                                                                    |
| Antimatter Bottle   | -         | 2#    | 1#   | Frigate | 1 cell of AM. Self-powered containment.                                                                                                                                                                                                                                                |
| **Fuel Scoops**     | 5k*       | 0     | 1    | Fighter | Allows atmospheric skimming of **Argon** or **Hydrogen**. Refuelling 1 cell takes one travel segment, plus a Piloting check (DC 12 for gas giants, DC 10 for planetary atmospheres). On a failure the ship takes 1 HP and gains nothing. On a critical fail, roll on the Travel Table. |
| **ISRU Refinery**   | 50k*      | 2#    | 2#   | Frigate | Synthesises **Deuterium‑Helium‑3** fuel cells from gas giant atmospheres. Produces **1 cell per week** of continuous operation. Requires the ship to be stationary (or in a stable parking orbit) and a working Fuel Scoop.                                                            |
