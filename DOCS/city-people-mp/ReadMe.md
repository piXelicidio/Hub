![](images/IsoCity_screenShot_820w.png)
# City People Mega-Pack

Welcome to the **City People Mega-Pack**! This package provides a diverse collection of city characters to bring life to your Unity projects. Below you'll find all the information you need to get started, including details on new updates, demo scenes, and how to integrate the assets into your project.

## Table of Contents

1. [Introduction](#intro)
2. [What's New](#whats-new)
3. [Characters Specs](#Characters-specs)
4. [Getting Started](#getting-started)
5. [Demo Scenes](#demo-scenes)
   - [Demo Scene 1: Character Showcase](#demo-scene-1-character-showcase)
   - [Demo Scene 2: Isometric City](#demo-scene-2-isometric-city)
6. [Character Groups](#character-groups)
7. [Animations](#animations)
8. [CityPeople Component Script](#citypeople-component-script)
9. [Palette System and UV](#palette-system-and-uv)
10. [URP Support](#urp-support)
11. [Unity 6 Compatibility](#unity-6-compatibility)
12. [Support](#support)

---

## <a id="intro"></a>Introduction

The **City People Mega-Pack** is designed to populate your urban environments with a rich variety of animated characters. Whether you're building a bustling cityscape, a serene town, or an interactive simulation, this pack offers the assets you need to create a dynamic and inclusive world. The Polyart style provides optimized characters, making them suitable for low-end devices and AR/VR simulations.

## What's New in v1.4.0

![](images/xmas_update.png)

- Added **Santa Claus** and **Mrs. Claus** characters in costumes.
- Added Christmas props: Snowman, tree, and gifts.
- Now demo scenes supports both input systems.
- Included material converter patch both ways URP and Built-in.
- Added **new demo scene** for construction workers with tool handling animations.

## Characters Specs

- Humanoid system compatible. (Original rig from 3ds Max Biped system)
- Small texture dimensions 256x256 (Texture as palette color)
- 2,000 average triangle count.
- Characters are most time single optimized mesh, non-modular and without additional LODs.

## Quick Start

1. **Import the Package**: Download and import the **City People Mega-Pack** into your Unity project.
2. **Explore *Demo_Scenes* folder**: Open the demo scenes to see the characters in action!
3. **URP/Built-in Setup**: Package materials import by default as URP (Models will appear pink on Built-in), to convert to Built-in go to **URP&Built-in** folder and double click the **convert-to-BUILT-IN** package patch.
4. From **Prefabs** folder drag & drop any character to your own scene.


## Character Groups | [WATCH VIDEO!](https://youtu.be/dUjK32yOMVo)

- (2) **Costumes:** Christmas theme characters and props. Santa Claus and Mrs. Claus. **(NEW!!)**
- (8) **People with disabilities:** Individuals using wheelchairs, crutches, prosthetic, etc. 
- (10) **Young adults:** Representing ages from 18 to 30.&#x20;
- (20) **City:** Everyday city people in casual and business outfits.
- (15) **Professionals:** Representing common professions.
- (8) **Construction:** Workers and tradespersons for building and maintenance.
- (20) **Downtown:** Similar to 'City', but a little bit more fresh and modern.
- (6) **Kids:** Young boys and girls about 10 to 15 years old.​
- (10) **Elders:** Older individuals aged about 60-70 years old.
- (10) **Beach:** A set of characters from 'Downtown' but dressed in swimsuits.
- (6) **Little Kids:** Younger kids from 3 to 5 years old.
- (8) **Xtras:** A miscellaneous group representing additional professions.&#x20;

## Animations

- **Standard Characters**: A set of common animations suitable to most characters.
  - Walking (6)
  - Running (4)
  - Idle (6)
  - Dancing (5)
  - Warming Up

- **Characters with disabilities**:
  - Each has 3 tailored animations specific to their design and mobility aids: Idle, forward and talk.

## Scripts (Included for demonstrative purposes)

**CityPeople Component Script**

This component script offers basic functionality to show the basic animations and switch palette material. 

**SwapAndToolController**

Located For the construction worker demonstrate how to periodically switch to a random tool and play the matching animation in a loop.

## Palette System and UV
![](images/PaletteTextures.png)
The characters UV have been mapped in a way to make easy the switching of palettes. These textures (acting as palettes) have a standardized structure with areas corresponding to different surfaces of the characters:

- Skin colors
- Hair colors
- Clothes colors
- Dark and Light details.

A single texture/material pair can be applied to all the characters in this package. And any texture/material can be applied to any character.

Free tool [DA Poly Paint](https://assetstore.unity.com/packages/tools/painting/da-polypaint-low-poly-customizer-251157) can be used to further modify the UV 'painting' by model with ease.

## SRP Support

Current version default to URP (Universal Render Pipeline).
Follow the steps to convert to Built-in or rollback to URP at any time.

1. Navigate to folder **CityPeople/URP&Built-in**
2. Double click one of the following packages to apply the patch:
- **Convert-to-BUILT-IN**
- **Convert-to-URP**

Note about HDRP: While not converter patch is provided, supporting HDRP would need a few standard steps. Using the material conversion wizard and adjusting lighting accordingly. 

## Unity  Compatibility

The **City People Mega-Pack** has been thoroughly tested with the following versions:

- **2022.3 LTS** ✅ Native project.

- **6000.0 LTS**: ✅ Tested and ready.
- **6000.3 LTS**: ✅ Tested and ready.

## 3ds Max source files

Source files are not included to keep the package light for the majority of users. If you need all the characters in .MAX format just drop an email to my address bellow and **please include your invoice number.**

## Support

If you have any questions or need assistance:

- **Email**: [denys.almaral@gmail.com](mailto\:denys.almaral@gmail.com)
- **Website**: [DenysAlmaral.com](https://denysalmaral.com)
- **Forum**: [GitHub Discussions](https://github.com/piXelicidio/Chat/discussions/2)

---

Thank you for choosing the **City People Mega-Pack**. We hope these assets help you create engaging and diverse urban environments in your Unity projects!
