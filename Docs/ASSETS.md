# 🧩 Asset and Environment Setup Guide

This document lists the external assets used in the **Underwater Teleoperation Simulator (UE5.3.2)**.  
All Megascans and Marketplace assets must be downloaded through your Epic/Quixel account.  
They are **not redistributed** in this repository due to Epic Games’ licensing policy.

---

##  1. Quixel Megascans Assets

All assets were imported via **Quixel Bridge** under the following categories.

### 🪨 3D Assets (Rocks, Cliffs, Structures)
| Asset Folder | Type | Description / Use |
|---------------|------|--------------------|
| `Chapel_Piscine_scbgA` | Structure | Used as a reference architecture element. |
| `Huge_Nordic_Coastal_Cliff_venrdcga` | Rock Formation | Main cliff base forming the underwater walls. |
| `Modular_Arches_wjmgeddcw` | Structure | Used to build the ring-collection frames in the simulation. |
| `Nordic_Beach_Boulder_vcyqebjfa` | Boulder | Medium-sized boulders scattered on seabed. |
| `Nordic_Beach_Rock_Formation_*` | Rock Formations | Multiple Nordic rock variants blended to create natural terrain. |
| `Nordic_Beach_Rock_*` | Rocks | Small detail meshes for seabed variety. |
| `Nordic_Beach_Rocky_Ground_uknmbblmw` | Ground Asset | Used for ground surface blending and slope definition. |
| `Nordic_Coastal_Cliff_vi5lcjpfa` | Cliff | Edge cliffs to mark environment boundary. |
| `Roman_Arch_thedegxfa` | Structure | Decorative arch element used near the navigation path. |
| `RuddFish` | Mesh (Fish) | Animated mesh for dynamic underwater life. |
| `WoodRoadSign` | Prop | Placed near start zone for identification markers. |

---

### 🌿 3D Plants (Seaweed and Ocean Flora)
| Asset Folder | Type | Description / Use |
|---------------|------|--------------------|
| `Aloe_Vera_ve4tbbhra` | Plant | Coral-like background vegetation. |
| `Ginger_Lily_ud5fffjga` | Plant | Decorative plant used near seabed rocks. |
| `Ocean_Seaweed_sdGgS` | Seaweed | Long, floating seaweed clusters. |
| `Ocean_Seaweed_sdDkn` | Seaweed | Medium height, waving seaweed patches. |
| `Ocean_Seaweed_sdEh6` | Seaweed | Dense foliage variant. |
| `Seaweed_sdmmR` | Seaweed | Sparse, tall plants near ring formations. |
| `Seaweed_sdokF` | Seaweed | Medium-sized kelp. |
| `Seaweed_sdpIF`, `Seaweed_sdpJN` | Seaweed | Small clusters near terrain edges. |

> *All assets above are free to use in Unreal Engine projects via Quixel Bridge.*
> The other paid assets were the wooden arrow marks and the road signs on the seabed.

---

##  2. Unreal Engine Settings

| Feature | Setting |
|----------|----------|
| **Engine Version** | Unreal Engine 5.3.2 |
| **Lighting** | Lumen |
| **World Partition** | Enabled |
| **Physics / FX Plugins** | Chaos, Niagara, Gameplay Cameras |
| **Input System** | Enhanced Input |
| **Platform** | Windows |
| **Main Map** | `VehicleExampleMap` |
| **Pawn** | `BP_BlueROV` |
| **Lighting Model** | Lumen (Dynamic GI + Reflections) |

---

##  3. Setup Steps

1. Open **Quixel Bridge** → Log in with your Epic account.  
2. Set export target to **Unreal Engine 5.3.2** and select your project.  
3. Search for and **Add to Project** each asset listed above. It would download the content automatically under the "Content" folder. 
4. In Unreal, open **VehicleExampleMap**.  
5. If Unreal shows “Landscape actors need rebuild” → go to **Landscape Mode → Build All Landscapes → Save All**.

---

##  4. Licensing

| Asset Type | License |
|-------------|----------|
| Custom Blueprints, Code, Logic | **CC BY-NC 4.0** |
| Quixel Megascans Assets | Licensed under **Epic/Quixel EULA** (not redistributed) |
| Marketplace Assets | Owned by Epic Marketplace creators; download separately |

> This repository is distributed for academic and non-commercial research use.  
> Users must cite the original work when using or extending this simulator.


