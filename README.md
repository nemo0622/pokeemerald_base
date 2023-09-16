# nemo0622's pokeemerald Decompilation BASE Project

## What is this?

This repository is designed to act as an "ideal" base for Pokémon Emerald Rom
Hacking. There are dozens of amazing branches out there, but many are tedious or
borderline impossible to merge, so this will hopefully remove a lot of that work.

## What is included in this pokeemerald decompilation?

Note: All credit for this base goes to these creators!! I just did the merging and made some fixes, please support and thank the people below:
- [RHH's pokeemerald-expansion](https://github.com/rh-hideout/pokeemerald-expansion):
    - Fairy Type
    - Physical/Special Split
    - Data for all Pokémon up to Generation 8 (including Hisuian Forms!)
    - Much, MUCH more! Please check pokeemerald-expansion itself for all details/documentation
- [aarant's branches](https://github.com/aarant/pokeemerald):
    - Following Pokémon in the overworld! Currently supports almost all Pokémon from Generations 1-7, plus Alolan, Galarian, and Hisuian forms/evolutions of Pokémon!
        - Only Generations 1-3 were in original build - all further followers added by me, and created by the artists credited below! Please go support them!
    - Lighting! Day/Night system, shadows under all NPCs, and shining lamp posts.
    - Key item wheel, allowing up to 4 items to be registered.
- All Pokémon can evolve without trades, and can evolve into regional forms where applicable
    - Ex: Many Pokémon evolve into Hisuian evolutions when evolved at night, or with Dusk Stones
    - Note: "Daytime" evolutions start at 6 am, and "Nighttime" evolutions start at 8 pm
- Gen 6+ style EXP. Share, able to be toggled on/off!
- Decapitalization of all dialogue! (may be some errors/missed things)
- Show move type effectiveness in battle
- Nickname Pokémon from party
- Colored stats by nature
- Show EVs/IVs in summary screen by pressing A
- Better, less glitchy reflection System
- Press B to move arrow to "Run" option
- Keyboard switches to lowercase automatically
- Pace of battle slightly improved (mashing A decreases lengthy delays)
- Press A when viewing clock to change the time
- Fishing is always successful 
- Change player direction while moving, like in later generations
- Default "Fast" text speed
- PC Access in PokéNav through "Condition" menu (only in Fly-enabled maps, so it's restricted in "dungeon" areas for balance)
- Press Start in Bag menu to sort bag items!

## Known Issues, Future Plans, & Credits!

ISSUES:
- Most Pokémon with multiple forms only support a single form in the overworld
    - Ex: All rotom forms only show default rotom, all Burmy forms appear green, etc.
    - Only Vivillon's "Icy Snow" form is supported! All other forms load wrong palettes right now
    - Both male and female Pyroar's give male followers
    - NOTE: Alolan/Galarian/Hisuian forms *DO* work!!
- "Large" Pokémon sprites are currently not supported
    - Current Exclusions: Dialga, Palkia, Giratina, Arceus, Reshiram, Zekrom, Kyurem, Eternatus, Enamorus
- Some of the overworld sprites need to be improved (Sawk and Throh, for example, look ROUGH)
- NOT ALL GENERATION 9 POKÉMON INCLUDED YET! Also:
    - Sprites sometome glitch in animating a little, not a huge deal but worth mentioning
    - National Dex sorted by weight and height are not in correct order
    - Cries are incorrect! Reuses other Pokémon's cries
    - No shiny palettes yet, shinies just look like normal guys that sparkle

FUTURE PLANS:
- Follower improvements:
    - Add support for individual Pokémon forms (ex: Rotom forms, Oricorio forms, etc.)
    - Improve some follower sprites (Archeops is the most extreme case lol)
- More Generation 9 Pokémon

CREDITS:
- RHH Team for the pokeemerald Expansion project
- aarant on Github for the base following Pokémon, lighting, and key item wheel code
- Generation 5 Overworld Sprites: 
    - Most compiled by [Pokegirl4ever](https://www.deviantart.com/pokegirl4ever/art/Completed-pokemon-Unova-overworlds-212553542) on DeviantArt
    - Emolga by [Wolfang62](https://www.deviantart.com/wolfang62/art/Emolga-Sprite-Overworld-833896154) on DeviantArt
    - Larvesta + Volcarona by Princess Phoenix on DeviantArt
- Generation 6 Overworld Sprites:
    - [Princess Phoenix](https://www.deviantart.com/princess-phoenix/art/Gen-6-Kalos-Pokemon-Overworld-Sprites-525954409) on DeviantArt
- Generation 7 Overworld Sprites:
    - [Larryturbo](https://www.deviantart.com/larryturbo/art/Gen-7-Alola-Overworld-Sprites-805455576) on DeviantArt
- Generation 8 Overworld Sprites:
    - Galarian sprites by [Lasse00](https://www.deviantart.com/lasse00/art/Hgss-Galar-Pokemon-Overworls-Sprites-912208276)
    - Hisuian sprites compiled by [DarkusShadow](https://www.deviantart.com/darkusshadow/art/Hgss-Hisuian-Pokemon-Overworld-Sprites-908984387) 
        - Sliggoo, Goodra, Avalugg, and Decidueye by princess-phoenix
        - Basculegion, Braviary, and Growlithe by Ezerart
        - Samurott by Wolfang62
        - Wyrdeer by Anarlaurendil and Lasse00
        - Others by DarkusShadow
- Generation 9 Overworld Sprites:
    - DarkusShadow on DeviantArt
- Most smaller changes from the pokeemerald [list of simple modifications](https://github.com/pret/pokeemerald/wiki/Tutorials)
- Generation 9 sprites:
    - Most front battle sprites by [KingOfThe-X-Roads](https://www.deviantart.com/kingofthe-x-roads/art/Gen-9-Sprites-Pokemon-Scarlet-and-Violet-908341834)
    - Ceruledge and Roaring Moon battle sprites by QDylm on DeviantArt
    - Back sprites by Caruban
    - Icons by [Ezerart](https://www.deviantart.com/ezerart/art/Pokemon-Gen-9-Icon-sprites-3DS-Style-944211258) on DeviantArt