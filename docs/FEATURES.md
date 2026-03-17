# Complete List of Changes

### Contents
* **National Pokédex**
  * Reorder Pokédex Entries
  * Disable Evolution/Trade Restrictions
  * Enable Evolutions
<br><br>
* **Pokémon**
  * Changes in Future Generations
  * Pokémon Encounters
  * Fishing Encounters
  * Surf Encounters
  * Legendary Pokémon
  * Shiny Pokémon
  * Version Exclusives
<br><br>
* **Moves**
  * Changes in Future Generations
  * TMs / HMs
  * Move Tutors
  * Move Relearner
<br><br>
* **Battles**
  * Fairy Type
  * Gym Leaders
  * Trainer Classes
<br><br>
* **Items**
  * Changes in Future Generations
  * Gen 3 Poké Balls
  * Respawning Items
  * New Merchants
<br><br>
* **Mechanics**
  * Abilities
  * Berry Spots
  * Breeding
  * Decorations
  * EV-Training
  * Following Pokémon
  * Fly
  * Game Corner
  * PC System
  * Weather
  * Quality of Life
<br><br>
* **World-Building**
  * Cameos
  * New NPCs
  * Map Changes
  * Master Trainers
  * Merchants
  * Ribbons
  * Tileset Changes
<br><br>
* **Visuals & Audio**
  * User Interface
  * Pokémon Sprites
  * Tileset Changes
  * GameBoy Sounds
  * Music
<br><br>
* **Options**
  * Auto-Save
  * Difficulty Modes
  * Nuzlock Mode
<br><br>
* **Bugfixes & Optimizations**
<br><br>
* **Optional Changes**
  * Fairy Type







<!--------------------------------------------------------- National Pokédex --
8b  8       w   w                  8   888b.       8             8
8Ybm8 .d88 w8ww w  d8b  8d8b. .d88 8   8  .8  d8b  8 dP .d88b .d88 .d88b Yb dP
8  “8 8  8  8   8 8’ .8 8P Y8 8  8 8   8wwP’ 8’ .8 88b  8 .P’ 8  8 8 .P’  `8.
8   8 `Y888 Y8P 8  Y8P  8   8 `Y88 8   8      Y8P  8 Yb `Y88P `Y88 `Y88P dP Yb
------------------------------------------------------------------------------>

<br><br>
## National Pokédex
* [ ] **National Pokédex is obtained** as soon as the player beats the Elite Four
<br><br>
* [ ] **Implement Pokémon sprites into the Pokédex interface** (may be too large)
<br><br>
* [ ] **Improve Sort Modes**
  * [ ] Use Pokédex # as secondary-sorting for Lightest, Smallest, and Type sorts
  * [ ] Update to reflect changes to the Pokédex entries
<br><br>
* [ ] **Add more information to the Pokédex**
  * [ ] Base Stats
  * [ ] Level-Up Learnsets
  * [ ] Evolution Methods
  * [ ] Weaknesses / Resistances

### Reorder Pokédex Entries
  * [ ] **Group Evolutionary Lines** (Baby Pokémon, Gen II Evolutions)
  * [ ] **Group "Counterparts" & Related Pokémon** (Clefable & Wigglytuff, Ninetales & Arcanine, Vileplume & Victreebel, Golem & Machamp, Cloyster & Slowbro, Magneton & Electrode, Scyther & Pinsir, Tauros & Miltank, Remoraid & Mantine, Claydol & Hoenn Fossils, Flygon & Salamence)
  * [ ] **Place Fossils before Pseudo-Legendaries**
  * [ ] **Place Pseudo-Legendaries before Legendaries** (Dragonite before Legendary Birds, Tyranitar before Legendary Beasts)
  * [ ] **Place Mew before Mewtwo**
  * Kanto Pokédex now has 171 Pokémon

### Disable Evolution/Trade Restrictions
  * [x] Allow non-Kanto Pokémon to evolve #️⃣Deokishisu
  * [x] Allow trades of non-Kanto Pokémon #️⃣Deokishisu
  * [x] Allow trades of Eggs & fateful encounter Mew/Deoxys #️⃣Deokishisu
  * [x] Allow trades with Ruby/Sapphire/Emerald regardless of progress #️⃣Deokishisu
  * [ ] Allow trades with Japanese Pokémon games

### Enable Evolutions
  * [x] **Implement friendship evolution for Espeon/Umbreon** (Level up with high friendship: indoors for Umbreon; outdoors for Espeon) #️⃣Deokishisu
  * [ ] **Implement an evolution method for Feebas**
  * Consider Level Up, Dragon Scale, Water Stone, Friendship, Sp. Attack increasing Nature?
  * [ ] **Allow Trade Evolutions to evolve by Level Up when holding its evolution item** (for example, a Scyther levelling up while holding Metal Coat)
  * [x] **Allow Trade Evolutions a way to be traded in game** (Use the Linking Cord Key Item) #️⃣Deokishisu
  <br><br>
  * [ ] **Direct-Use evolution items are available**
  * Consider Hold Items, Game Corner Prizes, Celadon Mall
    * [ ] Additional **Moon Stones** are available
    * [ ] **Sun Stones** are available
  <br><br>
  * [ ] **Trade evolution items are available**
  * Consider Hold Items, Game Corner Prizes, Celadon Mall)
    * [ ] **Dragon Scales** are available (on wild Horsea/Seadra/Dratini/Dragonair)
    * [x] **King’s Rocks** are available (consider Wild Poliwhirl/Slowbro) #️⃣Deokishisu
    * [x] **Metal Coats** are available (on Wild Magnemite and Magneton) #️⃣Deokishisu
    * [x] **Upgrades** are available (in Silph Co) #️⃣Deokishisu
    * [ ] **Deep Sea Scales** are available (Seafoam Islands, Chinchou/Lanturn)
    * [ ] **Deep Sea Tooths** are available (Seafoam Islands, Gyarados)








<!------------------------------------------------------------------ Pokémon --
    888b.       8
    8  .8  d8b  8 dP .d88b 8.8b d8b   d8b  8d8b.
    8wwP’ 8’ .8 88b  8 .P’ 8P Y8P Y8 8’ .8 8P Y8
    8      Y8P  8 Yb `Y88P 8   8   8  Y8P  8   8
------------------------------------------------------------------------------>

<br><br>

### Changes in Future Generations
* [ ] **Base Stats** are updated
* [ ] **Hold Items** are updated
<br><br>
* [ ] **Moves** are updated
  * [ ] **Base Learnsets** are updated
  1. Make learnsets as close to HeartGold/SoulSilver as possible
  2. Compare learnsets against Let's Go and US/UM learnsets, identifying any drastic differences
  3. Add Return into level-up set for friendship evolutions
  * [ ] ⚠️ Pay attention to how this affects Trainers and early-route Pokémon. For example, FRLG moved Zubat’s Supersonic to above the level cap that Zubat can appear in Mt. Moon, as is Paras’s Poison Powder. Using the revamped learnsets from Gen 4 would lead to a significant increase in players facing Confusion and Poison in Mt. Moon
  * [ ] **TM** learnsets are updated
  * [ ] ⚠️ Some Pokémon currently learn TMs only through Egg Moves. Make sure to remove these from the Egg Move list when they’re added to the TMs list
  * [ ] **HM** learnsets are updated
  * [ ] **Move Tutor** learnsets are updated
<br><br>
* [ ] **Egg Groups are updated**
  * [ ] Add Human-Like Egg Group for Ralts
  * Can now breed with Abra, Machop, Drowzee, Hitmon’, Mr. Mime, Jynx, Electabuzz, Magmar, Makuhita, Sableye, Meditite, Volbeat/Illumise, Spinda, Cacnea
  * [ ] Add Dragon Egg Group for Trapinch
  * Can now breed with Charmander, Ekans, Horsea, Magikarp, Dratini, Treecko, Swablu, Seviper, Feebas, Bagon

### Pokémon Encounters
* [ ] **Changes to Pokémon Locations**
  * [ ] Pokémon are more diverse on Surfing/Fishing routes
  * [ ] Pokémon are more diverse in caves
  <br><br>
  * [ ] **All Kanto & Johto Pokémon are available**
    * [ ] **Trade-Exclusives** have wild encounters (Mr. Mime, Lickitung, Jynx, Farfetch’d)
    * [ ] Additional **Starters** can be obtained (Bulbasaur, Charmander, Squirtle)
    * [ ] Overworld Encounters (Snorlax)
    * [ ] Gifts (Eevee, Tyrogue, Lapras)
    * [ ] **Safari Zone Exclusives** have wild encouters (Scyther)
    * [ ] **Fossil Pokémon** can be found in Rock Smash Rocks (Kabuto, Omanyte, Aerodactyl)
    * [ ] **Version Exclusives** are available (see Pokémon > Version Exclusives)
    * These are distributed more thoughtfully, but there will still be version differences in the encounter tables
    * [ ] **Professor Elm Gives a Johto Starter** when the player has obtained all Kanto and Johto Pokémon
  <br><br>
  * [x] **All Tickets are available** #️⃣Deokishisu
    * [x] **MysticTicket** is available (Lugia, Ho-oh) #️⃣Deokishisu
    * [x] **AuroraTicket** is available (Deoxys) #️⃣Deokishisu
    * [x] **Eon Ticket** is available (Latios/Latias - ported from Emerald) #️⃣Deokishisu
    * [x] **Old Sea Map** is available (Mew - ported from Emerald) #️⃣Deokishisu
  <br><br>
  * [ ] **Altering Cave Pokémon are available**
  * Consider making all available that cannot be found elsewhere, having them available at different rates based on TID/SID, rotating through groups of 3 (Zubat/Aipom/Mareep, Zubat/Teddiursa/Shuckle, Zubat/Stantler/Pineco, Zubat/Smeargle/Houndoom)
<br><br>
* [ ] **In-Game Trades are revised**
* Without trade-exclusive Pokémon, in-game trades should still feel special. This could be through Egg Moves, Version-Exclusives, Rare Items, or Johto Pokémon that aren’t otherwise available
<br><br>
* [ ] **Wild Pokémon level-curve is more balanced**
* Black2/White2 is touted as an example of a good level curve. Examine the levels of Black/White encounters compared to the # of gym badges the player has at the point they access each area.

### Fishing Encounters
* [ ] **Increase hook rate when Fishing**
<br><br>
* [ ] **Increase levels of Fishing Encounters**
  * [ ] Increase levels from **Old Rod** (from level 5 to level 3-15)
  * [ ] Increase levels from **Good Rod** (from level 5-15 to level 10-25)
  * [ ] Increase levels from **Super Rod** (from level 15-35 to level 20-45)
<br><br>
* [ ] **Fishing Encounters are divided into groups**
  * [ ] **Pond** encounters are more diverse
  * [ ] **Polluted Pond** encounters are more diverse
  * [ ] **Lake** encounters are more diverse
  * [ ] **Shore** encounters are more diverse
  * [ ] **Ocean** encounters are more diverse
<br><br>
* [ ] **Old Rod encounters are more diverse**
  * [ ] Poliwag, Remoraid (Rare) can be caught in **Ponds**
  * [ ] Grimer can be caught by Old Rod in **Polluted Ponds**
  * [ ] Goldeen can be caught by Old Rod in **Lakes**
  * [ ] Krabby can be caught by Old Rod in **Shores**
  * [ ] Tentacool, Qwilfish (Rare) can be caught by Old Rod in **Oceans**

### Surf Encounters
* [ ] **Increase levels of Surf encounters** (raised from level 5-40 to level 15-45)
* [ ] **Running Shoes mechanic adjusts Surf speed**
* [ ] **Default Surf speed is increased**
* [ ] **Surfing sprites exist for all Pokémon that can learn Surf**
* This project may help (if it's open-source): [surskitty/pokeemerald > surfable](https://github.com/surskitty/pokeemerald/tree/surfable/graphics/object_events/pics/pokemon/surfable)

### Legendary Pokémon
* [x] **Legendary Pokémon Respawn** when defeated once the player beats the Pokémon League again #️⃣Deokishisu
* [x] **All Legendary Beasts can be obtained** (Each time the Pokémon League is defeated, the next beast will roam) #️⃣Deokishisu
* [x] **Legendary Beasts are available as soon as the League is beaten** #️⃣Deokishisu
* [ ] **Special Music plays when Legendary Beasts are encountered** (ported from Emerald)
* [ ] **Fix Roar bug** when used by Roaming Legendaries  (when Roar is used, the battle will be over but the roamer will continue roaming)
* [ ] **Fix Roaming Legendaries IV bug** (Pokémon will no longer have 3 bad IVs)
* [x] **Deoxys Forms can be changed** by examining Meteorites in Pewter Museum of Science #️⃣Deokishisu

### Shiny Pokémon
* [ ] **Increase Shiny Odds**
  * [ ] **Shiny Odds are set to 1/4096**
  * [ ] **Consecutive/Chain Fishing**
  * [ ] **Shiny Charm is a Key Item**
  * Consider a gift from Professor Oak/Elm if the player has obtained all Kanto and Johto Pokémon
<br><br>
* [ ] **All Pokémon Graphics include shiny variations**
  * [ ] **Party Screen Sprites**
  * [ ] **PC Storage System Sprites**
  * [ ] **Starter Selection Screen**
  * ⚠️ It appears the starters are generated after the user confirms their choice. If this can be changed, make sure the Pokémon is generated after the player clicks on the Poké Ball but before the sprite is displayed
  * [ ] **Following Pokémon Sprites** (NEW)
  * [ ] **Daycare Sprites** (NEW)
* [ ] Add an icon to the HP bar if the players or enemy Pokémon is shiny
<br><br>
* [ ] **3 Poké Balls are available in the player’s PC** at the start, so if they encounter a shiny Pokémon before returning the parcel, they have a chance to catch it

### Version Exclusives
* [ ] LeafGreen can obtain FireRed exclusives
  * [ ] **Ekans line** is found
  * [ ] **Oddish line** is found
  * [ ] **Psyduck line** is found in Ponds and around Cerulean Cave in both games
  * [ ] **Growlithe line** is found
  * [ ] **Shellder line** is found around and inside Seafoam Islands in both games
  * [ ] **Electabuzz line** is found in the Power Plant in both games
  * [ ] **Scyther** is a rare encounter on Routes 14/15 in both games (Let’s Go Pikachu)
  * [ ] **Wooper line** is found on Route 10 and in the Safari Zone on both games
  * [ ] **Murkrow** is found
  * [ ] **Qwilfish** is found on the East Coast
  * [ ] **Delibird** is found
  * [ ] **Skarmory** is found
<br><br>
* [ ] FireRed can obtain LeafGreen exclusives
  * [ ] **Sandshrew line** is found
  * [ ] **Vulpix line** is found
  * [ ] **Bellsprout line** is found
  * [ ] **Slowpoke line** is found around and inside Seafoam Islands
  * [ ] **Staryu line** is found
  * [ ] **Magmar line** is found in Cinnabar Mansion in both games
  * [ ] **Pinsir line** is found in the Safari Zone in LeafGreen and the Game Corner in FireRed
  * [ ] **Marill line** is found in the Sevii Islands and Safari Zone in both games
  * [ ] **Misdreavus line** is found
  * [ ] **Sneasel line** is found
  * [ ] **Remoraid line** is found around the Southwest Sea in both games
  * [ ] **Mantine line** is found on all Sevii Islands routes in both games
<br><br>
* [ ] New Exclusives
  * [ ] **Heracross** is found in the Safari Zone in FireRed and the Game Corner in LeafGreen (taking the place of Scyther)
  * [ ] **Ledyba** is found in Viridian Forest as an uncommon encounter in FireRed and a rare encounter in LeafGreen
  * [ ] **Weedle/Kakuna** is found in Viridian Forest as a common encounter in FireRed and an uncommon encounter in LeafGreen
  * [ ] **Spinarak** is found in Viridian Forest as an uncommon encounter in LeafGreen and a rare encounter in FireRed
  * [ ] **Metapod/Caterpie** is found in Viridian Forest as a common encounter in LeafGreen and an uncommon encounter in FireRed








<!-------------------------------------------------------------------- Moves --
    8b   d8
    8YbmdP8  d8b  Yb  dP .d88b d88b
    8  “  8 8’ .8  YbdP  8 .P’ `Yb.
    8     8  Y8P    YP   `Y88P Y88P
------------------------------------------------------------------------------>

<br><br>
## Moves

### Changes in Future Generations
* [ ] Update **Move Names** (Dragonbreath to Dragon Breath)
* [ ] Update **Move Types** (Curse from ??? to Ghost, Hidden Power and Struggle from Normal to ???)
* [ ] Update **Move Power**
* [ ] Update **Move Accuracy**
* [ ] Update **PP Counts**
* [ ] Update **Move Priority**
* [ ] Update **Contact**
* [ ] Update **Move Targetting**
* [ ] Update **Interactions** for Magic Coat, Mirror Move, Protect, & Snatch
* [ ] Update **Contest Types** (if exists in codebase)
* [ ] Update **Secondary Effects**
<br><br>
* [ ] **Weather Interactions are updated**
  * [ ] Blizzard ignores accuracy checks during Hail
  * [ ] Growth increases Attack/Sp. Attack by 2 stages during Sunlight
  * [ ] Hail increases Defense of Ice types by 50%
  * [ ] Sandstorm increases Special Defense of Rock types by 50%
  * [ ] Weather Ball can be learned by Lugia, Ho-Oh, Castform, Snorunt, and Glalie
<br><br>
* [ ] **Type Interactions are updated** based on future generations
  * [ ] Grass Types are immune to Spore and Powder moves (Cotton Spore, Poison Powder, Sleep Powder, Spore, Stun Spore)
  * [ ] Ghost Types can always flee from battle
  * [ ] Electric Types are immune to Paralysis
  * [ ] Bide no longer hits Ghost Types
  * [ ] Whirlpool no longer traps Ghost Types
  * [ ] Toxic bypasses accuracy when used by Poison Types

### TMs / HMs
* [x] **TMs are reusable** #️⃣Deokishisu
* This open-source project may help: [tezemi/pokefirered-updated](https://github.com/tezemi/pokefirered-updated)
  * [ ] TMs do not display a quantity
  * [ ] TMs cannot be sold
  * [ ] Only 1 of each TM is available
    * [ ] Celadon Department Store no longer sells TMs (TM15 Hyper Beam was the only one not available elsewhere)
    * [ ] Game Corner TMs can only be purchased once
    * [ ] TM10 can no longer be obtained from Pickup
    * [ ] TM44 should be moved off of SS Anne where it can be mixxed
    * [ ] If player obtains a TM they already have, add it silently
  * [ ] Adjust the TMs/HMs option of the Debug Menu
  * [x] Using a TM does not reset available PP #️⃣Deokishisu
<br><br>
* [ ] **Changes to TM Locations**
  * [ ] TM10 Hidden Power is given by a Silph Co. NPC (dialogue suggests he designed it)
  * [ ] TM15 Hyper Beam has been added
  * [ ] TM36 Sludge Bomb has been moved (Venusaur should have access to a Poison STAB before the postgame)
  * Move TM36 Sludge Bomb to Fuschia Gym, then move TM06 Toxic to Silph Co. 4F, then move TM41 Torment to Five Island Rocket HQ

### Move Tutors
* [x] **Move Tutors are Reusable** but charge after the first use #️⃣Deokishisu
* [ ] **Move Tutor can overwrite HMs**
* [ ] **Additional Move Tutors** are added
  * [ ] Pikachu learns Surf from a tutor on Route 19 (South of Fuchsia)
  * [ ] Mew learns XD Moves from a tutor in Mr. Fuji’s home
  * [ ] Emerald Tutor Moves are available
  * Consider Platinum, HeartGold/SoulSilver, Black2/White2 tutor moves
  * New Move Tutors are divided in Pokémon Centers to mirror Let’s Go. They are a Juggler NPC found in Cerulean City, Celadon City, Fuchsia City, and the Pokémon League lobby
  * They may charge a valuable item (Mushrooms, Pearls, Stardust/pieces, Nugget) or money but should not be free
  * [x] Fury Cutter Tutor () #️⃣Deokishisu
  * [x] Rollout Tutor () #️⃣Deokishisu
  * [x] Dynamic Punch Tutor () #️⃣Deokishisu
  * [x] Sleep Talk Tutor () #️⃣Deokishisu
  * [x] Nightmare Tutor () #️⃣Deokishisu
  * [x] Self-Destruct Tutor () #️⃣Deokishisu
  * [x] Sky Attack Tutor () #️⃣Deokishisu
  * [x] Swagger () #️⃣Deokishisu
* [x] Ultimate Move Tutor does not require friendship #️⃣Deokishisu

### Move Relearner
* [ ] **Relearner Moves can be taught** (Level 1 moves given to Evolved Pokémon)
* [ ] **Move Relearner is located on the mainland**
* Consider adding to the Move Deleter’s house in Fuschia City
* an NPC may mention a move they don’t remember teaching:<br>_“My Ninetales remembered Flamethrower. I don’t remember teaching that.”_
* [ ] **Move Relearner is free**








<!------------------------------------------------------------------ Battles --
    888b.       w    w   8
    8wwwP .d88 w8ww w8ww 8 .d88b d88b
    8   b 8  8  8    8   8 8 .P’ `Yb.
    888P’ `Y888 Y8P  Y8P 8 `Y88P Y88P
------------------------------------------------------------------------------>

<br><br>
## Battles
* [ ] **Double Battles start** when two trainers see you at once
* [ ] **Major Trainers have custom dialogue when they get down to their ace**
* [ ] **All Rocket Grunts and Rocket Executives have names**
<br><br>
* [ ] **Trainers have more Hold Items**
  * [ ] Starting with Badge 3, Gym Leaders and significant trainers include a Sitrus Berry or Lum Berry on their ace (HG/SS)
  * [ ] High-level **Alakazam** can hold Twisted Spoon
  * [ ] High-level **Kingler** can hold King’s Rock (C)
  * [ ] High-level **Magcargo**, **Magmar**, **Rapidash** can hold White Herb (HG/SS)
  * [ ] High-level **Nidoqueen** can hold Silk Scarf (C)
  * [ ] High-level **Pikachu** can hold Light Ball (HG/SS)
  * [ ] High-level **Rapidash** can hold Focus Band (C)
  * [ ] High-level **Weezing** can hold Smoke Ball (R/S/E)
<br><br>
* [ ] **Trainer level-curve is more balanced**
  * [ ] Trainers have increased levels on their teams
  * [ ] Trainers have additional Pokémon on their teams
  * Black2/White2 is touted as an example of a good level curve. Examine the levels of Black/White trainers compared to the # of gym badges the player has at the point they access each area.
  * The stretch between Koga and Sabrina, between Sabrina and Blaine, and from Blaine to the Elite Four are particularly unbalanced. When updating make sure to weigh the need for additional EXP before the Elite Four alongside the concern about making already difficult locations more balanced
  * Also consider that the trainer has earlier access to STAB Moves, wider Learnsets, Stat Buffs for less viable Pokémon, Unlimited TMs and Tutors, Catching EXP, and more. Some trainers will need to become more difficult because of this, but THIS IS NOT A DIFFICULTY HACK
<br><br>
* [ ] **Trainers use Johto Pokémon**
* Referencing G/S/C/HG/SS, existing Trainer Classes are given Johto Pokémon to use. These are sprinkled across Kanto trainers
* In Kanto, only give trainers Johto Pokémon that can be captured in Kanto mainland. An exception can be given for SS Anne trainers if dialogue is included that they cannot be captured in Kanto
<br><br>
* [ ] **All Kanto Pokémon are used by at least 1 trainer**
* [ ] **Trainers may have HMs on their team**
* [ ] **Rocket Grunt in Cerulean City has Dig on his Pokémon**

### Gym Leaders
* [x] **Rebattle Gym Leaders** on Seven Island once Elite Four is defeated #️⃣Deokishisu
* When you complete a Fame Checker entry, an invite will be sent out
* [ ] **Gym Leader teams include Johto Pokémon** (related to their final appearances)
* For example, Misty has a Wooper and Erika has a Bellossom
* [ ] **Gym Trainers all use Pokémon of that Gym’s Type**
* No more Ground-only trainers in Btock’s Gym, Psychic-only trainers in Koga’s Gym, or Fighting-only trainers in Giovanni’s Gym
* [ ] **Animate Gym Leader sprites**
* [ ] **Gym leaders have custom dialogue when they get down to their ace**

### Trainer Classes
* [ ] **Each Trainer Class has a unique overworld sprite**
* This open-source project may help: [Poké Community thread](https://www.pokecommunity.com/showthread.php?t=407124)
* [ ] **Rocket Executives have custom sprites**
* They are identified in the Rocket Warehouse; consider the Game Corner Rocket Hideout, Mt. Moon, and Silph Co.
* [ ] **Custom Poké Balls are used by Trainers**
* Consider Net Balls for Bug Maniacs, Dive Balls for Fisherman,...
* Trainer sprites are updated to match their custom Poké Balls
* [ ] **Each trainer class has custom music that plays** before the battle starts (pull inspiration from Platinum)








<!-------------------------------------------------------------------- Items --
    888  w
     8  w8ww .d88b 8.8b d8b  d88b
     8   8   8 .P’ 8P Y8P Y8 `Yb.
    888  Y8P `Y88P 8   8   8 Y88P
------------------------------------------------------------------------------>

<br><br>
## Items
* [ ] **Running Shoes are available from the start**
* ⚠️ Be sure to give Professor Oak’s Aide in Pewter something else
* [ ] **Light Ball works for Pikachu clones** (Pichu, Pikachu, Plusle, Minun)
* [ ] **Mail is distributed across Poké Marts** (if not already?)
<br><br>
* [x] **Pressing Start can sort the bag** #️⃣Deokishisu
* [x] **Bag pockets wrap around when switching** #️⃣Deokishisu
<br><br>
* [ ] **Disposable items come in quantities**
  * [ ] When given by NPCs or found on the ground, give 1x, 3x, or 5x
<br><br>
* [ ] **Valuable items** are more common as hidden items
  * [ ] **Pearls** are more common on the coast
  * [ ] **Heart Scales** are more common on the coast
  * [ ] **Tiny Mushrooms** are more common in caves and forests
  * [ ] **Star Pieces** are found in Mt. Moon and Cerulean Cave
* [ ] Hidden Items are added across Sevii Islands
* Many maps don’t have hidden items despite having rocks, blank grass patches, and coasts)

### Changes in Future Generations
* [ ] **Rename Items**
  * [ ] “Stick” is renamed to “Leek”
  * [ ] “X Defend” is renamed to “X Defense”
  * [ ] “X Special” is renamed to “X Sp. Atk”
  * [ ] “Up-Grade” is renamed to “Upgrade”
  * [ ] “BlackGlasses” is renamed to “Black Glasses”
  * [ ] “BrightPowder” is renamed to “Bright Powder”
  * [ ] “DeepSeaScale” is renamed to “Deep Sea Scal”
  * [ ] “DeepSeaTooth” is renamed to “Deep Sea Toot”
  * [ ] “EnergyPowder” is renamed to “Energy Powder”
  * [ ] “NeverMeltIce” is renamed to “Never-Melt Ic”
  * [ ] “Paralyz Heal” is renamed to “Paralyze Heal”
  * [ ] “SilverPowder” is renamed to “Silver Powder”
  * [ ] “Thunderstone” is renamed to “Thunder Stone”
  * [ ] “TinyMushroom” is renamed to “Tiny Mushroom”
  * [ ] “TwistedSpoon” is renamed to “Twisted Spoon”
<br><br>
* [ ] **Increase boost from type-boosting items**
  * [ ] **Black Belt**’s boost is increased from 10% to 20%
  * [ ] **Black Glasses**’s boost is increased from 10% to 20%
  * [ ] **Charcoal**’s boost is increased from 10% to 20%
  * [ ] **Dragon Fang**’s boost is increased from 10% to 20%
  * [ ] **Hard Stone**’s boost is increased from 10% to 20%
  * [ ] **Magnet**’s boost is increased from 10% to 20%
  * [ ] **Metal Coat**’s boost is increased from 10% to 20%
  * [ ] **Miracle Seed**’s boost is increased from 10% to 20%
  * [ ] **Mystic Water**’s boost is increased from 10% to 20%
  * [ ] **Never-Melt Ice**’s boost is increased from 10% to 20%
  * [ ] **Poison Barb**’s boost is increased from 10% to 20%
  * [ ] **Sharp Beak**’s boost is increased from 10% to 20%
  * [ ] **Silk Scarf**’s boost is increased from 10% to 20%
  * [ ] **Silver Powder**’s boost is increased from 10% to 20%
  * [ ] **Soft Sand**’s boost is increased from 10% to 20%
  * [ ] **Spell Tag**’s boost is increased from 10% to 20%
  * [ ] **Twisted Spoon**’s boost is increased from 10% to 20%
  * [ ] **Sea Incense**’s boost is increased from 5% to 20%
<br><br>
* [ ] **Other Hold Item changes**
  * [ ] **Cleanse Tag**’s reduced encounter rate does not stack with the Abilities Arena Trap, Sand Veil, and White Smoke, but does stack with Intimidate and Keen Eye
  * [ ] **King’s Rock**’s flinch chance applies to all contact moves and stacks with Serene Grace
  * [ ] **Lax Incense**’s accuracy drop is increased from 5% to 10%
  * [ ] **Mental Herb** cures Taunt, Encore, Torment, Heal Block, and Disable
  * [ ] **Smoke Ball** no longer allows Pokémon to Teleport while trapped and its in-battle effect is nullified once the holder faints
  * [ ] **Soothe Bell**’s friendship boost stacks with bonuses from the Luxury Ball and Met Location
  * [ ] **Soul Dew** increases Psychic & Dragon type moves by 20% instead of increasing Special Attack and Special Defense by 50%. Description reads “A wondrous orb to be held by LATIOS or LATIAS. It boosts both Pyschic and Dragon-type moves.”
<br><br>
* [x] **EV-boosting berries are implemented** #️⃣Deokishisu
  * [ ] These lower their target EV to 100 after their 1st use and by 10 thereafter
  * [ ] These increase friendship by 10 pts up to 99 and by 5 pts thereafter
  * [ ] Descriptions are _“Makes a POKéMON friendly but it also lowers its base [xxx]”_
  * [x] **Pomeg Berry** lowers HP EVs #️⃣Deokishisu
  * [x] **Kelpsy Berry** lowers Attack EVs #️⃣Deokishisu
  * [x] **Qualot Berry** lowers Defense EVs #️⃣Deokishisu
  * [x] **Hondew Berry** lowers Special Attack EVs #️⃣Deokishisu
  * [x] **Grepa Berry** lowers Special Defense EVs #️⃣Deokishisu
  * [x] **Tamato Berry** lowers Speed EVs #️⃣Deokishisu
<br><br>
* [ ] **Repels can be chained**
<br><br>
* [ ] **Dive Balls work while Surfing and Fishing**
* Description should read _“A somewhat different Ball that works especially well on Pokémon that live in the sea.”_

### Cost Changes
* [ ] **Vitamins cost ¥4900** in the postgame
<br><br>
* [ ] **Status Berries** can be purchased for ¥150
* [ ] **Leppa Berries** and **Lum Berries** can be purchased for ¥1200
* [ ] **Stat-Reducing Berries** can be purchased for ¥1800
* [ ] **All Berries** sell for ¥50
* [x] **Game corner coins can be purchased in increments of 1000* #️⃣Deokishisu

### Gen 3 Poké Balls
* [x] **Premier Balls are gifted** when 10 of ANY Poké Ball is purchased #️⃣Deokishisu
<br><br>
* [ ] **All Poké Balls are available**
  * [ ] The TM Counter at the Celadon Department Store is replaced with a Poké Ball counter that includes most Gen 3 Poké Balls
  * [ ] Dive Balls are exclusive to coastal towns (similar to RSE/BW/B2W2)
  * [ ] Luxury Balls are exclusive to the Pokémon League (similar to DPPt/BW/B2W2)
  * [ ] Other Poké Balls are scattered throughout Poké Marts

### Respawning Items
* [ ] **Many items respawn** based on the step cycle
  * [ ] **Berry Spots** all respawn (see Mechanics > Berry Spots)
  * [ ] **Coins** on Game Corner floor may respawn








<!---------------------------------------------------------------- Mechanics --
    8b   d8            8                w
    8YbmdP8  d88b  d8b 8d8b   d88 8d8b  w  d8b d88b
    8  “  8 8  P’ 8    8P Y8 8  8 8P Y8 8 8    `Yb
    8     8 `Y88P `Y8P 8   8 `Y88 8   8 8 `Y8P Y88P
------------------------------------------------------------------------------>

<br><br>
## Mechanics
* [ ] Make disobedience slightly less annoying

### Abilities
* [ ] **Pickup tables are overhauled** (Base code on Emerald implementation with HG/SS tables)
<br><br>
* [ ] **Implement Overworld Ability Effects**
  * [x] **Arena Trap**: Raises encounter rate of wild Pokémon (lead spot) #️⃣Deokishisu
  * [x] **Compoundeyes**: Raises rates of held items (lead spot) #️⃣Deokishisu
  * [x] **Cute Charm**: Raises rates of opposite-gender Pokémon (lead spot) #️⃣Deokishisu
  * [x] **Flame Body/Magma Armor**: Halves the steps required to hatch eggs #️⃣Deokishisu
  * [x] **Hustle/Keen Eye/Pressure/White Smoke**: Lowers encounter rate of wild Pokémon (lead spot) #️⃣Deokishisu
  * [x] **Hyper Cutter**: Cut removes a larger area of tall grass #️⃣Deokishisu
  * [x] **Intimidate**: Lowers encounter rate for lower level wild Pokémon (lead spot) #️⃣Deokishisu
  * [x] **Lightningrod**: Charges VS Seeker twice as fast (lead spot) #️⃣Deokishisu
  * [x] **Magnet Pull**: Raises encounter rate for Steel types by 50% (lead spot) #️⃣Deokishisu
  * [ ] **Sand Veil**: Lowers rates of wild Pokémon during Sandstorms (Not Applicable?)
  * [x] **Static**: Raises encounter rate for Electric types by 50% (lead spot) #️⃣Deokishisu
  * [x] **Sticky Hold/Suction Cups**: Pokémon on fishing rod are easier to catch #️⃣Deokishisu
  * [ ] **Swarm**: Pokémon cries are heard more often (Not Applicable?)
  * [x] **Synchronize**: Raises rates of Pokémon with the same nature by 50% (lead spot) #️⃣Deokishisu
  * [x] **Vital Spirit**: Lowers encounter rate of high-level Pokémon (lead spot) #️⃣Deokishisu

### Breeding
* [ ] **Day Care outside Cerulean City fully functional**
  * [x] Daycare man raises his hand when an Egg is ready #️⃣Deokishisu
  * [x] Daycare will send Pokémon to the PC if party is full #️⃣Deokishisu
  * [ ] House is easy to access and no longer features ledges (take inspiration from [fan redesigns](https://www.reddit.com/r/PokémonRMXP/comments/qow1gb/my_rework_of_route_5_in_kanto_what_do_you_think/))
  * If this is achieved by switching the interiors of the Day Cares, give the Four Island Day Care a reason to use it. Maybe an Experience Boost?
<br><br>
* [ ] **Breeding Engine is revised**
  * [ ] Everstone passes the parent’s Nature 100% of the time, regardless of gender
  * [ ] Flame Body/Magma Armor makes Eggs hatch more easily
  * [ ] Mother’s Nature has increased odds of passing
  * [ ] The same stat can no longer be passed more than once (3 different stats are always passed)
  * [ ] Breeding a Pikachu with Light Ball gives the resultant Pichu Volt Tackle
  * [ ] Eggs hatch at Level 1
  * ⚠️ Make sure this doesn’t cause bugs. Eggs may have been set to Level 5 to avoid stat/exp underflow errors. Also test for problems when trading with genuine copies of RSE/FRLG
  * [ ] Poké Balls are passed from parents to offspring
<br><br>
* [ ] Eggs can be released
* Professor Elm appears in the daycare the first time the player visits
	<br>_"Hello there, I'm a Pokémon researcher who studies Eggs. There is so much we don't yet know about Pokémon breeding, so if you have any Eggs you no longer want, feel free to send them to me in your PC"_
* When releasing an egg, dialog should show that it was sent to Professor Elm

### Berry Spots
* [ ] **All Berry Spots respawn** during the step cycle
* [ ] **Berry Spots yeild 1-3 berries** at a time
* [ ] **Berry Spots have separate graphics** for if they are full or empty
* [ ] **Berry yield is randomly selected from pools** of possible berries
* Pools should include status berries and stat-reducing berries

### Decorations
* [ ] **The player can decorate their room** (ported from Emerald)
<br><br>
* [ ] **All Dolls of Kanto Pokémon can be obtained**
  * [ ] **Selected Starter Pokémon**: Given by the player’s mom once the starter evolves
  * [ ] **Blue’s Starter Pokémon**: Given by Daisy once the Elite Four is defeated
  * [ ] **Alternate Starter Pokémon**
  * [ ] **Small Kanto Dolls**, **Lapras**, **Rhydon**, **Snorlax**: gifted by an aide in Professor Oak’s lab if the player has caught them
  * [ ] **Small Johto Dolls**:
  * [ ] **Small Hoenn Dolls**, **Wailmer**: purchasable from a girl in the Two Island
  * [ ] **Regi’ Dolls**: gifted by a hiker in Ruin Valley if the player has caught the Legendary Titans
<br><br>
* [ ] **Silver Shield** and **Gold Shield** are obtainable

### EV-Training
* [x] **EVs per stat are limited at 252 instead of 255** #️⃣Deokishisu
* [x] A new area west of Cape Brink has rematchable trainers for the purposes of EV training. #️⃣Deokishisu

### Following Pokémon
* [ ] **Pokémon follow the player around**
* [ ] **Every Pokémon has following graphics**
* [ ] **Pokémon have interactions when spoken to**
* [ ] **Other trainers may have Pokémon beside them** referencing their Ace or dialogue

### Fly
* [ ] **Fly points are registered for all Routes**
* Fly point should be directly in front of any route signs
* There is already Fly data programmed in the game for each route in the [Debug Menu](https://tcrf.net/Proto:Pok%C3%A9mon_FireRed_and_LeafGreen/Debug_Menu)
<br><br>
* [ ] **Town Map/Fly Interface lists all landmarks**
* For example, Cinnabar Island can have Pokémon Mansion and Science Lab labelled
<br><br>
* [ ] **Connect Maps** so trainer flies freely fly Sevii Islands and the mainland
  * [ ] **Condense Sevii Islands to a single screen**
  * [Serebii has a map laying out](https://www.serebii.net/pokearth/kanto/3rd/) where these islands are in relation to the mainland. It’s okay to condense these islands into one screen if needed
  * Consider an interface where the map has an icon in the corner that allows the player to switch to the other map. If this is too difficult, the icon could be programmed to the Fly locations for Vermilion City and One Island
  * [ ] Update the Pokédex’s “Area Found” interface to use this map

### Game Corner
* [ ] **Game Corner rates are increased**
<br><br>
* [ ] **Game Corner payouts are increased**
  * [ ] Raise **Rockets** payout from 100 to 150
  * [ ] Raise **Pikachu** payout from 15 to 30
  * [ ] Raise **Magnemite/Voltorb** payout from 8 to 15
  * [ ] Raise **Shelder/Staryu** payout from 8 to 10
  * [ ] Raise **Single Poké Ball** payout from 2 to 3
<br><br>
* [ ] **Game Corner prize prices are standardized**
  * [ ] **Abra**      180 coins
  * [ ] **Clefable**  FR / **Clefairy**  LG 1000 coins
  * [ ] **Heracross** FR / **Pinsir**    LG 2800 coins
  * [ ] **Dratini**   FR / **Dragonair** LG 4600 coins
  * [ ] **Porygon**  6500 coins
  * [ ] **Larvitar** 9999 coins
<br><br>
* [ ] **Roulette Game is playable** (ported from Emerald)

### PC System
* [ ] **Move Pokémon is the 1st option**
* [ ] **Move Items feature**
* [ ] **Send Gift Pokémon to PC** if the player’s party is full
* [ ] **Retrieve Pokémon from PC during Trades**
* [ ] **Provide bulk options in PC** (release all, clear markings, clear nicknames, send items to bag)

### Weather
* [ ] **Current Weather thumbnail** is displayed during battle
* [ ] **Overworld sandstorm appears** on Canyon Entrance, Sevault Canyon, and Tanoby Ruins. Encounters are revised to more heavily feature Rock, Ground, and Steel types
* [ ] **Implement Weather Interactions** of moves (see Moves > Changes in Future Generations)
* [ ] **Weather Moves stop after 5 turns** unless Overworld or Abilities initiated it

### Quality of Life
* [x] **Catching Tutorial can be skipped** if player has already caught a second Pokémon #️⃣Deokishisu
* [ ] **Experience is gained from Catching Pokémon**
* [ ] **20% Boosted Experience is gained by Pokémon who rejected evolution**
* [ ] **Survive Poisoning**
* [ ] **Potions, Vitamins, Rare Candies remain on the party screen** after use
* [x] **Can Run Indoors** #️⃣Deokishisu
* [x] **Bike speed toggles between standard and Mach Bikes** like DPPt #️⃣Deokishisu
* [x] **Victory Road boulder puzzles no longer reset** #️⃣Deokishisu
* [x] **Repels can be chained** #️⃣Deokishisu
* [x] **Pressing B in battle moves cursor to `Run`** #️⃣Deokishisu
* [x] **Wireless minigame trainer star is now earned by a Battle Tower streak** #️⃣Deokishisu
* [x] **Switch Pokémon in party menu** by pressing `select` #️⃣Deokishisu
* [x] **There is a PC in the SS Anne** #️⃣Deokishisu

<br><br>
* [ ] **Rock Smash can give items and additional Wild Encounters**
  * [ ] Rock Smash rocks can give Fossils, Ethers, Star Pieces, and other items
  * [ ] Rock Smash rocks can encounter Geodude, Shuckle
  * [ ] Rock Smash Rocks are added throughout the region (Consider HGSS locations, but also caves and routes with dirt paths)
<br><br>
* [ ] Allow traded Pokémon to be renamed
* If nicknamed: _“[xxx] was given their name by [xxx]. Are you sure you want to change it? Y/N”_ else _continue as usual_
<br><br>
* [ ] **Shorten dialogue for interacting with HM objects**
  * [ ] Interactable objects are Trees (Cut), Boulders (Strength), Water (Surf)
  * [ ] If the player clicks on the object, do not show dialogue: Click on tree > Animation > Bellsprout used Cut
  * [ ] If the player walks into the object, provide a prompt
  * [ ] If the player enters a dark cave, provide a prompt “It’s hard to see. Would you like to use Flash?”
* [x] **Most warps load significantly faster** #️⃣Deokishisu
* [x] **Options can speed up battles** #️⃣Deokishisu
	* [x] **Battle Transitions** setting turns off the transition animation between the field and a battle. #️⃣Deokishisu
	* [x] **Battle Intro Animation** setting turns off the sliding animation that occurs at the start of every battle. #️⃣Deokishisu
	* [x] **Battle Scene** has been renamed to Move Animations and now also skips in-battle text delays when it is off. #️⃣Deokishisu
	* [x] **HP Bar Animation Speed** gives four options for how fast the HP bar animates, including instant. #️⃣Deokishisu
	* [x] **Exp. Bar Animation Speed** gives the player the choice to make experience bars animate instantly. #️⃣Deokishisu
* [x] **Pokémon Center nurses abbreviate their dialogue** after getting two Trainer Card stars #️⃣Deokishisu








<!----------------------------------------------------------- World-Building --
    Yb        dP            8    8    888b        w 8    8 w
     Yb  db  dP   d8b  8d8b 8  d88    8wwwP 8   8 w 8  d88 w 8d8b   d88
      YbdPYbdP   8’  8 8P   8 8  8    8   b 8b d8 8 8 8  8 8 8P Y8 8  8
       YP  YP     Y8P  8    8 `Y88    888P’ `Y8P8 8 8 `Y88 8 8   8 `Y88
                                                                   wwdP
------------------------------------------------------------------------------>

<br><br>
## World-Building
* [ ] On SS Anne, Rival brags about having 40 kinds of Pokémon. Change this dialogue so it reflects the number of lines available
* [ ] Oak should have custom dialogue if the player returns with the Parcel with an evolved starter
* [ ] A Charcoal can be placed in Victory Road where Moltres is found in Gen 1
* [x] Decensor "Gambler" trainer class #️⃣Deokishisu
<br><br>
* [ ] **Book Shelves have a lot more language**
* Bookshelves talk more about different features: overworld abilities, stat-reducing abilities, locations of NPCs such as Move Reminder or Hidden Power teacher
* This is a good place to bring up changes made in this hack
<br><br>
* [ ] **Revise Sevii Island Plot**
* Canonically, Celio is setting up the technology to trade with the Hoenn region. With trade restrictions lifted, this plot no longer makes sense. It may be possible to retain much of the plot by changing dialogue to focus on connecting with the whole world. Or to give Celio a bigger project that Team Rocket’s presence is directly conflicting with

### Cameos
* [ ] **“Black Belt Koichi” is renamed to “Karate Master Koichi”**
* [ ] **One Fighting Dojo Trainer is named Kiyo**
* Kiyo is Gen 2’s “Karate King” who takes over the dojo from Koichi
* Maybe replace Mike because his name is the least exciting or Aaron because he has 1 Pokémon and the team will need to be revised anyway
* [ ] **Janine is placed Koga’s Gym**
* This implies that Janine is working in Koga’s Gym before she takes it over
* In FRLG, she is outside the Pokémon Zoo _“My father is the GYM LEADER of this town. I’m training to use POISON Pokémon as well as my father.”_
  * [ ] Correct the typo in her name “Charine”
  * [ ] Replace her sprite with the appropriate Trainer Class
* [ ] **A trainer in Sabrina’s Gym is implied to be Will**
  * Give custom dialog. Obfuscate as William
* [ ] **A Victory Road trainer is implied to be Karen**
  * Give custom dialog. Obfuscate as Katherine
* [ ] **International Agent on S.S. Anne is implied to be Looker**
* [ ] **Victory Road trainers are implied to have started from Pallet Town**
* [ ] **All Rocket Executives should be present**
* Archer and Ariana will have custom sprites and their Johto teams
* Petrel and Proton will be Rocket Grunts but retain their Johto teams
* [ ] **A Silph Co Employee mentions radio waves** implying the forced evolution of Gen 2
* Silph Co Scientist: _“I’m a very important Scientist. I’m working on a frequency that can help Pokémon evolve.”_ (Give him Electrodes to parallel Johto setup)
<br><br>
* [ ] Implement Jigglypuff graffiti from Gen 1
* [ ] Implement Celadon Condominiums graffiti from Gen 2
* [ ] Change final Nugget Bridge trainer into a Rocket Costume with a twirl before battle starts and use Rocket music

* [ ] Can the Marowak Ghost be given the Ground/Ghost typing?
* [ ] Adjust Sara and Erik’s dialogue in Fuchsia City/Safari Zone (in Japanese version, their dialogue is a joke?)

### New NPCs
* [ ] Gym guy gives out Fresh Water
* [ ] An NPC gives the player a type-boosting item based on the starter they selected (Miracle Seed, Mystic Water, Charcoal)
* [ ] An NPC tells the player about their Hidden Power
* Consider separate messages for 35-46, 47-58, 59-70 ranges
* “I know all about Hidden Power. Do you want to learn about your Pokémon’s power? Your [Pikachu]’s Hidden Power is [Ice Type] [but it’s not very strong]”
* Consider placing this NPC in Silph Co’s lobby once Rocket has been cleared out. He can give the TM10 Hidden Power as a reward. “Thank you for rescuing us. I know all about Hidden Power. I developed its TM.”
* [ ] A Burglar in a Safari Zone safe house sells his unused Safari Balls (randomized between 1 and 30 per visit)

### Map Changes
* [x] **HM08 Dive is now available and usable in the field** #️⃣Deokishisu
* New underwater areas found on Route 20 and Bond Bridge.
* [x] **Safari Zone is expanded with 2 new zones** #️⃣Deokishisu
* [x] **Artisan Cave is ported from Emerald** (attached to the Battle Tower) #️⃣Deokishisu
* [x] **Battle Tower is ported from Ruby/Sapphire** (available as soon as player delivers Ruby to Celio) #️⃣Deokishisu
* [x] **Berry Forest is expanded** #️⃣Deokishisu

### Master Trainers
* [x] **Master Trainers appear around Kanto** after becoming the Champion (similar to Let's Go) #️⃣Deokishisu
	* [x] Master Trainers can be rematched immediately #️⃣Deokishisu
	* [x] Master Trainer Pokémon scale to the level of the Pokémon used to challenge them #️⃣Deokishisu
	* [x] The Master Trainers for Ditto, Articuno, Zapdos, Moltres, Mewtwo, and Mew want to see Pokémon with 100 total Effort Values. #️⃣Deokishisu
	* [x] Clearing a Master Trainer confers a title that can be used in link battles with other FRLG Perfected players. #️⃣Deokishisu
  * [x] Clearing all 151 Master Trainers unlocks a secret superboss Trainer. #️⃣Deokishisu

### Merchants
* [ ] **Mt. Moon Pokémon Center clerk**
* Consider Poké Ball, Potion, Cheri Berry (Paralysis), Repel, Escape Rope
* [ ] **Dark Tunnel Pokémon Center clerk**
* [ ] **Young Girl sells a selection of berries she picks**
* She may be located in the passage North of Viridian Forest. She can start by selling status-healing berries but can be given Leppa, Lum, and EV reducing berries later on
* [ ] **Channeler in Lavender Town sells Incense, Spell Tag, Cleanse Tag**
  * She may also sell additional Soothe Bells once the player has picked it up
  * She is unable to focus until the plot of Pokémon Tower is resolved
  <br>_“Here I sell tokens for mourners visiting Pokémon Tower. The spirits are restless and angry. You must stay away.”_
  <br>_“Apologies for my behavior. The spirits are at peace once more.”_
  <br>_“Here I sell tokens for mourners visiting Pokémon Tower.”_
* [ ] **Postman sells different mails**

### Ribbons
* [x] **Effort Ribbon is available** from a woman in the Move Reminder's house on Two Island #️⃣Deokishisu
* [ ] **Champion Ribbon is given** when the Pokémon League is beaten

### Tileset Changes
* [ ] **Colors are incorporated into each town to match its name**
  * [ ] Pokémon Center interior colors are based on town
* [ ] **Gym palette matches the color of its type specialty**
* [ ] **Dome and Helix fossils have separate overworld graphics**
* [ ] **Evidence of construction surrounds the man in Vermilion City**
* [ ] Cerulean Caverns graphics are updated to features crystals such as in the Let’s Go games and HGSS and a revised color scheme. The crystals flicker like candlelight
* [ ] Pokémon Mansion graphics are updated to feature laboratory equipment resembling the Let’s Go games
* [ ] **On Route 13, east of fence maze**, the grassy area should have a ledge to jump out onto the docks, like in Gen 4
* [ ] **Viridian Forest** features benches, fences, flowers, and rearrangements in grass to more closely resemble a park.








<!---------------------------------------------------------- Visuals & Audio --
   Yb    dP w                 8         dP8P       db             8 w
    Yb  dP  w d88b 8   8  d88 8 d88b    Ybww      dPYb   8   8  d88 w  d8b
     YbdP   8 `Yb  8b d8 8  8 8 `Yb     dP       dPwwYb  8b d8 8  8 8 8’  8
      YP    8 Y88P `Y8P8 `Y88 8 Y88P    Yb8b    dP    Yb `Y8P8 `Y88 8  Y8P
------------------------------------------------------------------------------>

<br><br>
## Visuals & Audio
* [ ] In-Game Trade Pokémon appear as following Pokémon next to their NPC. The sprite updates after the trade to reflect the new Pokémon
* [ ] Pokémon deposited at the Daycare are visible behind it
* [ ] **Route Change signs have backgrounds**
* [x] **Pokémon Summary Screen shows met location for any Gen 3 game** including Orre #️⃣Deokishisu
* [x] **Pokémon Emerald trainer sprite is visible in link room** #️⃣Deokishisu

### User Interface
* [x] **Stats are highlighted based on the Pokémon’s Nature** (boosted in red, reduced in blue) #️⃣Deokishisu
* [ ] **Pressing L on the stat screen replaces stats with IVs**
* [ ] **Pressing R on the stat screen replaces stats with EVs**
* [ ] **Mystery Gift displays on the home menu** as soon as the Save is created
<br><br>
* [ ] **Introduce Level-Up Animation** for when Pokémon are ready to evolve
* Flametix demoed a [level-up animation](https://www.youtube.com/watch?v=qFnQL1jPz8w). They found an unused animation in Ruby/Sapphire code to flash the EXP Bar on level up. They repurposed it with a more complex animation that only appears if the Pokémon is ready to evolve
<br><br>
* [ ] **Display stats in the New Move dialogue**
  * Presently, The Pokémon interface shows the small sprite, name, and type in the top-left, the list of moves on the right, and the move description on the bottom left. There's not a lot of space to work with
  * One solution would be to move the Pokémon sprite, name, and type to the right rail, put the moves beneath it (slightly smaller), then shrink the move description panel, and put the Pokémon's stats in the top-left
<br><br>
* [x] **Hidden Power** displays its current type #️⃣Deokishisu
  * [x] Hidden Power Type is displayed in the Pokémon summary screen #️⃣Deokishisu
  * [x] Hidden Power Type is displayed in the Move Selection in battle #️⃣Deokishisu
  * [ ] Hidden Power Type is displayed in “Choose a Move to Delete” screen
* [x] Return & Frustration's true power is shown on the summary screen #️⃣Deokishisu
* [x] Nature Power's type and power are visible #️⃣Deokishisu
* [x] Weather Ball's type and power are visible #️⃣Deokishisu

### Pokémon Sprites
* [ ] **Each Pokémon has an animated front-sprite**
* [ ] **Back-sprites of Johto Pokémon are retouched** (these got less attention in Gen 3 and often have rougher lines/shading
* [ ] **Pokémon have gender differences**

### GameBoy Sounds
* [ ] Implement GameBoy Sounds Key Item
* GameBoy Sounds can be gifted to the player by the Music Director at Game Freak in Celadon City
* [ ] GameBoy Sounds should have each music track
* [ ] GameBoy Sounds should be retained if the player powers off their machine

### Music
* [ ] **Custom Route Music for reused tracks**
* Repurpose tracks for Gen 2, such as the song for when chansey plays. Avoid iconic Gen 2 tracks, but other tracks are fair game
* [ ] **Incorporate Pokémon Cries into Route Music** (ported from Emerald)

### Pokémon Centers
* [ ] **Pokémon Center dialogue is shorter**
* [ ] **Pokémon Center dialogue is even shorter if the player has at least 1 trainer card star**
* [ ] **Pokémon Center heal animation is shorter**
* [ ] **Pokémon Center heal animation ignores Eggs**








<!------------------------------------------------------------------ Options --
     d88b        w   w
    8P  Y8 88b  w8ww w  d8b  8d8b  d88b
    8b  d8 8  8  8   8 8’  8 8P Y8 `Yb
    `Y88P’ 88P’  Y8P 8  Y8P  8   8 Y88P
           8
------------------------------------------------------------------------------>

<br><br>
## Options
* [ ] `FRAME` defaults to `TYPE 3` (red) for FireRed; `TYPE 4` (green) for LeafGreen
* [ ] `TEXT SPEED` has an `INSTANT` setting
* [ ] `TEXT SPEED` defaults to `FAST` (optionsTextSpeed)
* [ ] `RUNNING` options: `B TO RUN`, `ALWAYS RUN` (Hold B to walk)
* [x] `VERSION` can toggle between FireRed & LeafGreen #️⃣Deokishisu
* [x] `IV CALCULATION` switches between Real IVs, All 0, and All 31 and does not affect Hidden Power #️⃣Deokishisu
* [x] `EV CALCULATION` switches between Real EVs, All 0, and All 252 #️⃣Deokishisu
* [x] `EXP MULTIPLIER` can modify EXP yields by 0×, 1/2×, 1×, and 2× #️⃣Deokishisu
* [x] `NO FREE HEALS` disables free party heals, Lavender Tower purified zone, Pokémon Center heals, and heals from depositing in PC boxes #️⃣Deokishisu
* [x] `BATTLE MODE` adds a feature to prompt the user to switch but not say what Pokémon is coming next #️⃣Deokishisu
* [ ] This new `BATTLE MODE` is default

### Auto-Save
* [ ] **Create an `AUTO SAVE` Option**
  * [ ] `ALWAYS`: The game will automatically save every time the player heals at the Pokémon Center
  * [ ] `ASK` (default): The Pokémon Center Clerk will ask the player if they want to Save the game after their Pokémon is healed
  * [ ] `NEVER`: Auto-Save is disabled

### Difficulty Modes
* [x] An Easy Mode decreases the game difficulty #️⃣Deokishisu
* [x] A Challenge Mode increases the game difficulty by adding Pokémon and disabling badge boosts #️⃣Deokishisu
  * [ ] Ensure dialog is updated to reflect this

### Nuzlock Mode
* [x] Implement a Nuzlock Mode #️⃣Deokishisu

<details>
<summary>Special Nuzlock Rules (click for details):</summary>
<ul>
<li>Fainted Pokémon cannot be healed by any means (including depositing them in a PC Box).</li>
<li>The player is not asked whether to give a nickname to obtained Pokémon</li>
<li>Pokémon can be obtained at any time, but only the first Pokémon obtained in an area is usable barring duplicates (dupe clause).</li>
    <ul>
    <li>There is a UI element drawn to the enemy's healthbar to indicate if it counts as the first encounter in an area.</li>
   <li>Unusable Pokémon are automatically fainted if received and do not count toward dupe clause.</li>
   <li>In-game trades will be fainted if the Pokémon traded for them was fainted and do not count as a first encounter.</li>
   <li>Eggs set the encounter flag of the place the egg hatched. If that place already had a first encounter, the egg will hatch fainted.</li>
   </ul>
<li>The Dupe Clause is in effect. Pokémon that are already owned, or evolutionary relatives of already owned Pokémon, will not count if they are the first encounter in an area and not caught.</li>
    <ul>
    <li>In-game trades do invoke the dupe clause for additional Pokémon of that species.</li>
    </ul>
<li>If a white out occurs, the player will be prompted to grab a usable Pokémon from their PC Box.</li>
    <ul>
    <li>If there are no usable Pokémon left, they will be given a choice of soft-resetting or turning off the Nuzlocke toggle and healing their party normally.</li>
    </ul>
<li>None of these rules come into effect until after the player obtains Poké Balls.</li>
<li>Encounters are not tracked:</li>
    <ul>
    <li>While the Nuzlocke toggle is off,</li>
    <li>retroactively (starting a Nuzlocke midway through a regular playthrough will allow new "first" encounters) and,</li>
    <li>before the player obtains the Pokédex, to prevent losing the opportunity to catch Route 1 Pokémon before catching Pokémon is possible.</li>
    </ul>
<li>Each outdoor Safari Zone map counts as a separate area for the purposes of catching Pokémon.</li>
<ul>
</details>








<!------------------------------------------------- Bugfixes & Optimizations --
    888b              d8b w
    8wwwP 8   8  d88  8’  w Yb dP  d88b d88b
    8   b 8b d8 8  8 w8ww 8  `8   8  P’ `Yb
    888P’ `Y8P8 `Y88  8   8 dP Yb `Y88P Y88P
                wwdP
------------------------------------------------------------------------------>

<br><br>
## Bugfixes & Optimizations
* [ ] **Fix the held item loss glitch**
* Kadabra, Haunter, Machoke, Graveler lose their hold item when they evolve via trade
* [ ] **Player can retain S.S. Ticket** if they skip the Cut Master but start the Sevii Islands plot
* [ ] **All strains of Pokérus available**
* [ ] **Investigate Safari Zone Mechanics** and tweak them if needed. The optimal strategy should not be to just hurl Poké Balls
* [x] **Steps taken aren't counted inside Safari Zone Rest Houses** #️⃣Deokishisu
* [ ] **Nidoking can breed with Nidoqueen**
* [ ] **Cerulean City man has additional dialogue**. He is supposed to have several dialogue options and gives the player berries based on different conditions
* [x] **Correct typo in Teachy TV items program** “Key Items Pocket” is mis-spelled as “Key Items Pokcet” #️⃣Deokishisu
* [x] **Fix exploit with Icefall Cave tiles spawning encounters** #️⃣Deokishisu
* [x] **Moves that always hit should be marked as --- instead of 100%** #️⃣Deokishisu
* Assist, Block, Camouflage, Charge, Conversion 2, Follow Me, Grudge, Helping Hand, Imprison, Ingrain, Magic Coat, Mean Look, Memento, Mimic, Mud Sport, Nightmare, Pain Split, Recycle, Refresh, Role Play, Skill Swap, Slack Off, Snatch, Softboiled, Spider Web, Tail Glow, Vital Throw, Water Sport, Wish and Yawn 
* [ ] **Create a shortcut to open the [Debug Menu](https://tcrf.net/Proto:Pok%C3%A9mon_FireRed_and_LeafGreen/Debug_Menu)**
* [x] Fix the [evolution move-learning glitch](https://glitchcity.wiki/wiki/Evolution_move-learning_glitch) #️⃣Deokishisu
* [ ] Trace Ability can copy Intimidate
<br><br>
* [x] **Implement Softlock Fixes** #️⃣Deokishisu
  * [x] Player cannot trap themself on Cinnabar Island #️⃣Deokishisu
  * [x] Player cannot trap themself on Indigo Plateau #️⃣Deokishisu
  * [x] Free Poké Balls are available in potential softlock situations #️⃣Deokishisu
<br><br>
* [x] **Accept `REVISION 1` bugfixes** #️⃣Pret
  * [x] Fix errors in Pokédex description #️⃣Pret
  * [x] Fix Pokédex bug that crops category labels (Squirtle is the “Tiny Turtle” Pokémon, not the “Tiny” Pokémon) #️⃣Pret
  * [x] Accept text changes in Help System #️⃣Pret
  * [x] Check for memory in `main.c` #️⃣Pret
  * [x] Correction in `DaycarePrintMonLv1()` #️⃣Pret
  * [x] Correction in `IntroCB_GF_RevealLogo()` #️⃣Pret
  * [x] Use `REVISION 0` date for Build metadata #️⃣Pret
  * [x] Remove `REVISION` flag from build files and related documentation #️⃣Pret
  * [x] Remove `REVISION` flag #️⃣Pret
<br><br>
* [ ] **Accept `BUGFIX` bugfixes**
  * [ ] Fix Roar bug when used by Roaming Legendaries (when Roar is used, the roamer will now continue roaming)
  * [ ] **Fix Roaming Legendaries IV Bug**
  * [ ] Remove duplicate call to display speed after level-up
  * [ ] Fix order of `MAP_GROUP` and `MAP_NUM` arguments in Celadon Game Corner
  * [ ] Add missing call to display Special Defense stat after level up in Double Battles
  * [ ] Accept bug fix in Berry Crush minigame
  * [ ] Accept all bug fixes in Dodrio Berry Picking minigame
  * [ ] Add terminator to prevent intro scene from loading too many assets
  * [ ] Ensure the Trade Poké Ball animation runs correctly
  * [ ] Ensure that Pokémon HP cannot be negative when re-fetching stats
  * [ ] Ensure that a stat modified by a nature and boosts is never greater than the max u16 that stores it
  * [ ] Correct incorrect sprites for Agatha and Lance in the `FacilityClassToTrainerClass` tables
  * [ ] Prevent overflow error when reading Fishing data from the encounter table
  * [ ] Correction in `Cmd_recordLastAbility()`
  * [ ] Correction in `TryLoadObjectPalette()`
  * [ ] Correction in `MapPreview_CreateMapNameWindow()`
  * [ ] Correction in `DestroyCardSprites()`
  * [ ] Correction in `CB2_ReturnFromNamingScreen()`
  * [ ] Correction in `DexScreen_FlipCategoryPageInDirection()`
  * [ ] Correction in `TextWindowGraphics`
  * [ ] Correction in `GetAwaitingCommunicationText()` for the Union Room
  * [ ] Correction in `UpdateCommunicationCounts()`
  * [ ] Remove `BUGFIX` constant
<br><br>
* [ ] **Accept `UBFIX` bugfixes**
  * [ ] Fix division function so it cannot divide by zero
  * [ ] Avoid crashing in `GetObjectEventFlagIdByLocalIdAndMap`
  * [ ] Avoid out of bounds error in `SavedMapViewIsEmpty()`
  * [ ] Accept fix in Dodrio Berry Picking minigame
  * [ ] Accept all music player fixes
  * [ ] Correction in `Cmd_if_status_not_in_party()`
  * [ ] Correction in `InitEasyChatPhrases()`
  * [ ] Correction in `GetIncomingConnection()`
  * [ ] Correction in `MultiMove_GetMonsFromSelection()`
  * [ ] Correction in `IsPartnerActivityAcceptable()`
  * [ ] Remove `UBFIX` constant
<br><br>
* [x] AI Bugs #️⃣Deokishisu
  * [x] AI should use the target's type and stats and not its own #️⃣Deokishisu
  * [x] AI should not get confused around weather effects #️⃣Deokishisu
  * [x] AI should use its own status effect rather than the target's when choosing Facade #️⃣Deokishisu
<br><br>
* [ ] **Deprecate unused content**
  * [ ] Remove unused Pokédex descriptions (dummy text)
  * [ ] Remove unused Hoenn Pokédex data/functions
  * [ ] Remove unused `OLD_UNOWN_` code








<br><br>
<br><br>
## FRLG+ Changes to revert
* [ ] **Deprecate Extended Pokédex** as the improved Regional Pokédex fixes the issue
* [ ] **Deprecate R Button toggling auto-running** as this has been moved to settings (why dedicate an entire button to an option users would set 1 time?!)
* [ ] **Deprecate Cut Trees disappearing permanently** as this would make the world feel emptier. Instead, cut is used by walking into the tree if Cut is in your party
* [ ] **Deprecaste Item Pocket Expansion** and **Medicine/Held Item pockets** as it nukes compatibility with PKHex
* [ ] **Rework where TMs are found** as Celadon Dept. Store shouldn't sell TMs any more
* [ ] **Gen 3 Poké Balls should not be sold at Silph** as they should be incorporated throughout the region instead
* [ ] **Revert Infinite Nugget glitch patch** as it doesn't hurt anything. It's tedious to use to farm money but if a player wants to use it, they should be able to. Maybe if we do make additional items available around this time, it will have practical use.
