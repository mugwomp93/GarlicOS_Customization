# Garlic OS Customization

Various overlays, boot logos, themes, etc for Garlic OS on the original RG35XX. Please let me know if you run into any bugs or have suggestions. You can also find me on Reddit (u/mugwomp_93).

# Contents
1. [Perfect Overlays for Garlic OS](https://github.com/mugwomp93/GarlicOS_Customization#perfect-overlays-for-garlic-os)
2. ***(NEW!)*** [Game Boy Bivert](https://github.com/mugwomp93/GarlicOS_Customization#game-boy-bivert)
3. [Game Boy Metallics Overlays](https://github.com/mugwomp93/GarlicOS_Customization?tab=readme-ov-file#game-boy-metallics-overlays)
4. [Other Overlays](https://github.com/mugwomp93/GarlicOS_Customization?tab=readme-ov-file#other-overlays)
5. [Boot Logos & Animations](https://github.com/mugwomp93/GarlicOS_Customization?tab=readme-ov-file#boot-logos--animations)
6. [Battery Charging Animations](https://github.com/mugwomp93/GarlicOS_Customization?tab=readme-ov-file#battery-charging-animations)
7. [Themes](https://github.com/mugwomp93/GarlicOS_Customization?tab=readme-ov-file#themes)

## [Perfect Overlays for Garlic OS](https://github.com/mugwomp93/GarlicOS_Customization/blob/main/Perfect_Overlays_for_RG35XX.zip)
<br>![github_banner2](https://github.com/user-attachments/assets/f5bcfdb1-2a82-4373-a33b-0d5b2ff9bd69)

<br>Adaptations of 1playerinsertcoin's brilliant [DMG-EX](https://www.reddit.com/r/MiyooMini/comments/18e2o0z/i_remastered_my_game_boy_dmg_overlay/), [GBC](https://www.reddit.com/r/MiyooMini/comments/1857xa7/i_made_a_game_boy_color_overlay/), and [GBA](https://www.reddit.com/r/MiyooMini/comments/18ovuld/i_made_a_game_boy_advance_overlay/?rdt=48158) overlays to correct for minor alignment issues on the **original** RG35XX. Please refer to the included README files for important settings information.
<br><br>**Not for use with the Miyoo Mini (Plus)!** - See the linked Reddit posts for the original MM files and recommended settings. Some versions are also preloaded in Onion OS.
<br><br>See my [muOS repository](https://github.com/mugwomp93/muOS_Customization) for the RG35XX Plus/H/SP/2024 and other 640x480 devices.
<br><br>DMG & GBP border options:
<br><br>![DMG_GBP_example_borders](https://github.com/user-attachments/assets/24659a6a-d214-4ff9-b672-eab4b18a8457)
<br><br>GBC border options:
<br><br>![GBC_example_borders](https://github.com/user-attachments/assets/6497b173-5520-479d-bda7-e0258e9c71b8)
<br><br>GBA border options:
<br><br>![GBA_example_borders](https://github.com/user-attachments/assets/b4fe01a8-cfec-4cfc-96d4-1a15bead594a)<br><br>

## [Game Boy Bivert](https://github.com/mugwomp93/GarlicOS_Customization/blob/main/GB_Bivert_640x480_garlic.zip)
![GB_bivert_examples](https://github.com/user-attachments/assets/045085d5-5fd8-4d05-8a1c-65607f04ee6e)<br>
![GB_bivert_irl](https://github.com/user-attachments/assets/4fa8e452-540c-45f5-91c1-45bf5e51a24e)<br>

Since I'm too paranoid of messing up to [bivert](https://share.google/9UfGI6dnuoHDZfPC1) [my](https://share.google/gKa4aEo0yrGUetiSJ) [Game Boy Pocket](https://share.google/ORsP1ffJJTIlNehBt), I thought I would make an overlay instead. This overlay works in combination with a custom palette and has an orange-purple gradient effect to help simulate more realistic lighting. The zip file includes versions both with and without the power light.<br>

### Configuration
<details>
  <summary>Click for installation and settings</summary>

  #### Installation:

  - Download [GB_Bivert_640x480_garlic.zip](https://github.com/mugwomp93/GarlicOS_Customization/blob/main/GB_Bivert_640x480_garlic.zip).
  - Copy the contents of the overlays folder to your retroarch > overlays folder.
  - Copy the palettes folder (containing default.pal) to your BIOS folder. Note that this will overwrite any custom palettes you are currently using, so make sure to rename or back them up if you don't want to lose them.

  #### Settings:

  ##### 1. Core Options

    Quick Menu > Core Options:

        GB Colorization > Custom

        Manage Core Options > Save Content Directory Options
  
  ##### 2. Apply the Overlay:
  
    Quick Menu > On-Screen Overlay

         Display Overlay > ON

         Overlay Preset...
           > Navigate to retroarch > overlays > mugwomp93 and select GB_bivert_640x480_garlic or GB_bivert_640x480_garlic_nolight
                          
         Overlay Opacity > 1.00

   ##### 3. Scaling Settings:
    
    Main Menu > Settings > Video > Scaling
    
        Integer Scale > ON
    
        Keep Aspect Ratio > ON
    
        Crop Overscan > OFF

  ##### 4. Save an Override

    Quick Menu > Overrides > Save Content Directory Overrides
    
</details>

#### Notes:
- The colors aren't intended to be 100% true to real life. Consider them "inspired by" instead of accurate representations.<br><br>

## [Game Boy Metallics Overlays](https://github.com/mugwomp93/GarlicOS_Customization/tree/main/Game%20Boy%20Metallics)
<br>![Game Boy Metallics Preview 2](https://github.com/user-attachments/assets/d34e6032-0dff-48ac-a8f7-a4076bc17442)

<br>***These overlays are identical to the ones found in my [muOS repository](https://github.com/mugwomp93/muOS_Customization)***

<br>This is the culmination of a couple of projects I've wanted to work on for a while: revisiting my first attempts at integer-scale Game Boy overlays and seeing if I could improve the default Game Boy palettes in Retroarch (which I've never been happy with on my RG35XX). These overlays are the result. They use colored grids to tweak the appearances of the internal Gambatte Game Boy palettes.

The final versions were a compromise of color, grid line visibility, and contrast within the constraints of the existing internal palettes (e.g., changing the overlay opacity affects also affects the color and contrast). As a result, I ended up creating some optional custom palettes to help improve the contrast and in some cases (DMG, GBL) further refine the color schemes.<br> 

<br>***Note that these are likely oversaturated on better screens***<br> 
<br><br>![Example - DMG](https://github.com/user-attachments/assets/86e042cd-f108-4878-98ad-e8ce099bd746)
<br><br>![Example - GB Pocket](https://github.com/user-attachments/assets/90c705dc-b28c-401e-92d0-a13915df43cf)
<br><br>![Example - GB Light](https://github.com/user-attachments/assets/28e9615f-5ae7-4b3a-959f-e20c4aa18a2d)
<br><br>![Example - Virtual Boy](https://github.com/user-attachments/assets/c14436ab-d522-4867-b194-943aedbb579b)<br><br>

The screenshots used in the pictures above were taken on an RG35XX Plus and edited to match (at least as closely as possible) what I see on my original RG35XX. Given the difficulties in conveying accurate colors (my display isn't calibrated, your display likely isn't calibrated, your handheld likely doesn't display accurate colors anyway, etc.), it's difficult to say whether the colors you see are representative of what these overlays and palettes will look like on your device; however, each image is internally consistent with the colors on my RG35XX, so you can likely compare the raw palette images with what those palettes look like on your device to get an idea of how the overlays will look.

If you just want the four overlays featured in the images, you can download my [preferred pack](https://github.com/mugwomp93/GarlicOS_Customization/blob/main/Game%20Boy%20Metallics%20-%20Preferred%20Pack.zip). Otherwise, I've uploaded all combinations of the borders x overlay grids, with and without power lights, as well as borders-only and no-borders versions, [here](https://github.com/mugwomp93/GarlicOS_Customization/tree/main/Game%20Boy%20Metallics). You'll need to download the custom palette(s) from the relevant subfolders if you decide to download individual overlays, or you can download a zip file with all of them [here](https://github.com/mugwomp93/GarlicOS_Customization/blob/main/GBM_Custom_Palettes.zip) (make sure to read the readme for instructions).

**Recommended settings and instructions for the custom palettes can be found in the readme files in both the preferred pack zip file and the top-level Game Boy Metallics folder.**<br><br>


## Other Overlays
1. **[Neo Geo Pocket Color](https://github.com/mugwomp93/GarlicOS_Customization/blob/main/NGPC_mugwomp93.zip)** - An integer-scale NGPC overlay that uses a repeated 3x3 pixel section of 1playerinsertcoin's Perfect GBA overlay to create an lcd effect<br><br>![NGPC_examples](https://github.com/user-attachments/assets/6f363fe0-6d2b-425f-b906-f4c6edf3bdc0)<br><br>


## Boot Logos & Animations
1. **[Garlic Gradius](https://github.com/mugwomp93/GarlicOS_Customization/blob/main/Garlic_Gradius_BootLogo.zip)** - Imaginary Gradius instruction manual<br><br>![Instruction Manual Version Preview](https://github.com/mugwomp93/GarlicOS_Customization/assets/143192398/de54deea-352f-408e-83eb-6c50b6604068)<br><br>
2. **[Wizardry](https://github.com/mugwomp93/GarlicOS_Customization/blob/main/Wizardry_BootLogo.zip)** - Apple II-style Wizardry intro screen<br><br>![CRT Preview](https://github.com/mugwomp93/GarlicOS_Customization/assets/143192398/247bb997-4e80-4c93-8405-a5afc9140596)<br><br>
3. **[Chrono Trigger](https://github.com/mugwomp93/GarlicOS_Customization/blob/main/Chrono_BootLogos.zip)** - A couple of Chrono Trigger-themed boot logos. There's also a white variant of the 1995 Square version.<br><br>![Square version dark preview](https://github.com/mugwomp93/GarlicOS_Customization/assets/143192398/ec0f0dca-b048-41e1-94f9-392891fcf721)<br>![Lucca version preview](https://github.com/mugwomp93/GarlicOS_Customization/assets/143192398/ac5a69c3-d8b3-41f3-96c0-68a7c9ca6bf5)<br><br>
4. **[Super Garlic Bros. 3](https://github.com/mugwomp93/GarlicOS_Customization/blob/main/Super%20Garlic%20Bros%203.zip)** - Super Mario Bros. 3 boot animation<br><br>![Super Garlic Bros 3](https://github.com/mugwomp93/GarlicOS_Customization/assets/143192398/7b224ef7-eb24-4fc4-bcf2-78573f564e0b)<br><br>
5. **[Purple Neon](https://github.com/mugwomp93/GarlicOS_Customization/blob/main/Purple_Neon_BootLogo.zip)** - Lower brightness purple boot logo<br><br>![purple_neon](https://github.com/mugwomp93/GarlicOS_Customization/assets/143192398/fe4c65cc-def1-424d-a75b-456c2c06324e)<br><br>
6. **[Game Boy Box Art](https://github.com/mugwomp93/GarlicOS_Customization/blob/main/Game_Boy_Box_Art_BootLogo.zip)** - Original Game Boy box art for the RG35XX. Why did I make this? Who knows. But it was fun.<br><br>![RG35XX_Game_Boy](https://github.com/mugwomp93/GarlicOS_Customization/assets/143192398/f181424f-47c1-4447-9a48-bcf07dccdaee)
<br><br>
7. **[RG35XX All-Stars](https://github.com/mugwomp93/GarlicOS_Customization/blob/main/RG35XX_All-Stars_BootLogo.zip)** - Super Mario All-Stars (SNES) title screen logo<br><br>![RG35XX_All-Stars](https://github.com/mugwomp93/GarlicOS_Customization/assets/143192398/f76dc2d4-3abb-4296-b6fe-0bd7915aad51)<br><br>


## Battery Charging Animations
1. **[Chrono Campfire](https://github.com/mugwomp93/GarlicOS_Customization/blob/main/Chrono_Campfire.zip)** (adapted from/inspired by [huor_fashmir's cute and cozy charging animation for the Miyoo Mini](https://www.reddit.com/r/MiyooMini/comments/1b19k49/i_made_this_cute_and_simple_chrono_trigger/))<br><br>![Chrono_Campfire](https://github.com/mugwomp93/GarlicOS_Customization/assets/143192398/4491aab3-7087-4445-898d-ac11ca2c5654)<br><br>


## Themes
1. **[Arcade Invaders](https://github.com/mugwomp93/GarlicOS_Customization/blob/main/Arcade_Invaders.zip)** - An arcade classic that never was. A work in progress.<br><br>![Arcade_Invaders](https://github.com/mugwomp93/GarlicOS_Customization/assets/143192398/739a5148-7b8e-40e1-8afb-ec5f88bfb201)<br><br>

2. **[Super Mario Evolution](https://github.com/mugwomp93/GarlicOS_Customization/blob/main/Super_Mario_Evolution.zip)** - Follows the graphical progession of SMB1 (NES) through SMW (SNES). This one was a lot of fun.<br><br>![Super_Mario_Evolution](https://github.com/mugwomp93/GarlicOS_Customization/assets/143192398/ce0a4164-03ec-457b-b23a-b3e226dd6509)<br><br>

3. **[Moving Dungeon](https://github.com/mugwomp93/GarlicOS_Customization/blob/main/Moving_Dungeon.zip)** - Wizardry-inspired theme based on Minimal Dungeon theme by 420AM. I had to figure out how Garlic OS displays oversized icons and other theme elements (see [Garlic OS theming notes](https://github.com/mugwomp93/GarlicOS_Customization/blob/main/GarlicOS%20Theming%20Notes.xlsx) and/or Moving Dungeon readme if you're interested).<br><br>![Moving_Dungeon](https://github.com/mugwomp93/GarlicOS_Customization/assets/143192398/2350ffc2-c406-4634-9168-2ba6c3c842f3)<br><br>

4. **[GBMini for Garlic](https://github.com/mugwomp93/GarlicOS_Customization/blob/main/GBMini_for_Garlic.zip)** (adapted from [GBMini Miyoo Mini theme](https://www.reddit.com/r/MiyooMini/comments/vdxg1a/gbonion_theme_and_customizations/?rdt=57022) by Kitsuvi)<br><br>![GBMini_for_Garlic](https://github.com/mugwomp93/GarlicOS_Customization/assets/143192398/7b175b24-5d18-40d9-971d-49b8819afa52)<br><br>

5. **[GBOnion for Garlic](https://github.com/mugwomp93/GarlicOS_Customization/blob/main/GBOnion_for_Garlic.zip)** (adapted from [GBOnion Miyoo Mini theme](https://www.reddit.com/r/MiyooMini/comments/vdxg1a/gbonion_theme_and_customizations/?rdt=57022) by Kitsuvi)<br><br>![GBOnion_for_Garlic](https://github.com/mugwomp93/GarlicOS_Customization/assets/143192398/1650fb02-9d23-4497-b53c-093d3740b474)<br><br>

6. **[GBOnion Multicolor](https://github.com/mugwomp93/GarlicOS_Customization/blob/main/GBOnion_Multicolor.zip)** (remix of the above two themes: dark background with multicolored active icons and logos)<br><br>![GBOnion_Multicolor](https://github.com/mugwomp93/GarlicOS_Customization/assets/143192398/0e7986cb-33e5-4fa6-adcf-4937ec17f8b4)<br><br>
