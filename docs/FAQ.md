 # **Frequently Asked Questions**

# Table of Contents:
* Mechanics:
  * [Will the physical/special split be implemented?](#will-the-physicalspecial-split-be-implemented)
  * [Will new moves be implemented? New held items?](#will-new-moves-be-implemented-new-held-items)
  * [What are the shiny chances? Will they be improved?](#what-are-the-shiny-chances-will-they-be-improved)
* Pokémon Availability:
  * [Will you add later-generation Pokémon?](#will-you-add-later-generation-pokémon)
  * [How many Pokémon are available? Will *all* Pokémon be catchable?](#how-many-pokémon-are-available-will-all-pokémon-be-catchable)
  * [Is there a list of wild encounter tables?](#is-there-a-list-of-wild-encounter-tables)
  * [Can I obtain the other Kanto starters? Can I obtain the unchosen fossil?](#can-i-obtain-the-other-kanto-starters-can-i-obtain-the-unchosen-fossil)
  * [Can I evolve my Kanto Pokémon into their Johto evolutions without the National Dex?](#can-i-evolve-my-kanto-pokémon-into-their-johto-evolutions-without-the-national-dex)
  * [How do I evolve Eevee into Espeon and Umbreon?](#how-do-i-evolve-eevee-into-espeon-and-umbreon)
  * [Can I evolve trade evolutions without trading?](#can-i-evolve-trade-evolutions-without-trading)
  * [Are trade evolution items available before the postgame?](#are-trade-evolution-items-available-before-the-postgame)
  * [How do I get the other legendary beasts?](#how-do-i-get-the-other-legendary-beasts)
  * [Where do I get the event tickets so I can obtain Mew, Lugia and Ho-oh, Deoxys, and Latias and Latias?](#where-do-i-get-the-event-tickets-so-i-can-obtain-mew-lugia-and-ho-oh-deoxys-and-latias-and-latias)
  * [How do I get Sudowoodo to battle me?](#how-do-i-get-sudowoodo-to-battle-me)
  * [How do I get the other Fighting Dojo Pokémon? How do I get the missing Hitmonchan/Hitmonlee?](#how-do-i-get-the-other-fighting-dojo-pokémon-how-do-i-get-the-missing-hitmonchanhitmonlee)
* Gameplay:
  * [I just started the game, where is the Key System Menu? I can't change my difficulty after a new game!](#i-just-started-the-game-where-is-the-key-system-menu-i-cant-change-my-difficulty-after-a-new-game)
  * [Where do I unlock Gym Leader rematches?](#where-do-i-unlock-gym-leader-rematches)
  * [How does inviting a Gym Leader work? A Gym Leader I invited is gone! When is the rematch lady's Spearow coming back?](#how-does-inviting-a-gym-leader-work-a-gym-leader-i-invited-is-gone-when-is-the-rematch-ladys-spearow-coming-back)
  * [Can I rematch Giovanni? I can only invite seven Gym Leaders.](#can-i-rematch-giovanni-i-can-only-invite-seven-gym-leaders)
  * [What are the Challenge Mode boss trainer levels? I want to level cap my Nuzlocke run.](#what-are-the-challenge-mode-boss-trainer-levels-i-want-to-level-cap-my-nuzlocke-run)
  * [Where are the new Move Tutors and what moves do they teach?](#where-are-the-new-move-tutors-and-what-moves-do-they-teach)
  * [Is there a location list for all the Master Trainers?](#is-there-a-location-list-for-all-the-master-trainers)
* Troubleshooting Savefiles, Emulators, and Flashcarts:
  * [Is my vanilla FireRed or LeafGreen save compatible with FRLG Perfected?](#is-my-vanilla-firered-or-leafgreen-save-compatible-with-frlg-perfected)
  * [My emulator/flashcart doesn't work with FRLG Perfected! The game won't save!](#my-emulatorflashcart-doesnt-work-with-frlg-perfected-the-game-wont-save)
* Modifying FRLG Perfected:
  * [Can I use FRLG Perfected as a ROM Base?](#can-i-use-frlg-perfected-as-a-rom-base)
  * [How did you implement *x* feature? Can I use *y* feature for my hack?](#how-did-you-implement-x-feature-can-i-use-y-feature-for-my-hack)
* Miscellaneous:
  * [Where do I get TM10 for Hidden Power? Pickup doesn't give me TM10 for Hidden Power!](#where-do-i-get-tm10-for-hidden-power-pickup-doesnt-give-me-tm10-for-hidden-power)
  * [Will text be decapitalized?](#will-text-be-decapitalized)
  * [How do I link to other games? When is the earliest I can link?](#how-do-i-link-to-other-games-when-is-the-earliest-i-can-link)

## Mechanics:

### Will the Physical/Special split be implemented?
No. Many types lack sufficient Physical moves (such as Psychic) or Special moves (such as Dark and Rock,) so they miss out on the benefits of the split. This hack must maintain trade compatibility, so no new moves will be added to close these gaps.

### Will new moves be implemented? New held items?
No. This hack must maintain trade compatibility, so new moves and held items are not an option.

### What are the shiny chances? Will they be improved?
The shiny chance is currently 1/8192, but it will be modified to 1/4096 and the Shiny Charm will be implemented.

## Pokémon Availability:

### Will you add later-generation Pokémon?
No. This hack makes many Pokémon more available, but only those found in the Gen 3 National Pokédex.

### How many Pokémon are available? Will *all* Pokémon be catchable?
This is not a 386 hack, but all Gen 1 and 2 Pokémon will be obtainable without trading.

### Is there a list of wild encounter tables?
Yes, [wild encounters are found hrere](/src/data/wild_encounters.h). More complete documentation may be added down the line.

### Can I obtain the other Kanto starters? Can I obtain the unchosen fossil?
Yes, both in the postgame.
<details>
  <summary>The other Kanto starters:</summary>
  The Rival's starter can be obtained as an Egg on Four Island from the Day Care Man.
  The unchosen starter can be obtained from Daisy after fixing the Network Machine on One Island.
</details>
<details>
  <summary>The unchosen fossil:</summary>
  The unchosen fossil can be obtained in Three Isle Path from the prospector in the cave after becoming Champion.
</details>

### Can I evolve my Kanto Pokémon into their Johto evolutions without the National Dex?
Yes. The game will no longer prevent Pokémon from evolving into a Pokémon that is not in the Kanto Pokédex.

### How do I evolve Eevee into Espeon and Umbreon?
Eevee evolves into Espeon when leveled up outdoors with high friendship. Eevee evolves into Umbreon when leveled up indoors with high friendship.

### Can I evolve trade evolutions without trading?
Yes. A new key item, the Link Bracelet, is available. It is an unmissable key item that is obtained during the story and can be used like an evolution stone. To evolve Pokémon that need to hold an item while trading to evolve, have them hold the item before using the Link Bracelet on them.

<details>
  <summary>Exact location of the Link Bracelet:</summary>
  It is received from the Rival after defeating him in Silph Co.
</details>

### Are trade evolution items available before the postgame?
Yes. Most are available as wild held items. Items like the Up-grade have been moved to be available before becoming the Champion.
<details>
  <summary>Pokemon that hold trade evolution items:</summary>

  • Metal Coats can be found rarely on wild Magnemite and Magneton.

  • Dragon Scales can be found rarely on wild Dratini and Dragonair.

  • King's Rocks can be found rarely on wild Poliwhirl and Slowbro.

  • Deep Sea Scales can be found rarely on wild Chinchou underwater.

  • Deep Sea Teeth can be found rarely on wild Gyarados underwater.
</details>

### How do I get the other legendary beasts?
Every time you enter the Hall of Fame, an uncaught legendary beast will begin to roam Kanto if there are no legendary beasts currently roaming.

### Where do I get the event tickets so I can obtain Mew, Lugia and Ho-oh, Deoxys, and Latias and Latias?
<details>
  <summary>The Old Sea Map for Mew on Faraway Island:</summary>
  Become the Champion, then talk to Mr. Fuji in his home in Lavender Town.
</details>

<details>
  <summary>The MysticTicket for Lugia and Ho-oh on Navel Rock:</summary>
  Obtain the Extended Dex, then get the diploma for completing the Kanto Pokédex in Celadon Mansion.
</details>

<details>
  <summary>The AuroraTicket for Deoxys on Birth Island:</summary>
  Get a 28-win streak at the Battle Tower.
</details>

<details>
  <summary>The Eon Ticket for Latias and Latios on Southern Island:</summary>
  Get a 56-win streak at the Battle Tower. These Pokémon are version exclusive, so switch versions in the Key System Menu to obtain both of them.
</details>

### How do I get Sudowoodo to battle me?
<details>
  <summary>To get Sudowoodo to battle,</summary>
  have a Fresh Water in your bag and talk to it.
</details>

### How do I get the other Fighting Dojo Pokémon? How do I get the missing Hitmonchan/Hitmonlee?
Breed your Hitmonchan/Hitmonlee for a Tyrogue and then evolve that Tyrogue into the Fighting Dojo Pokémon that you didn't pick.

## Gameplay:

### I just started the game, where is the Key System Menu? I can't change my difficulty after a new game!
Once you have started a new game, you need to save and reset. The Key System Menu is on the Main Menu alongside the Continue and New Game options.

### Where do I unlock Gym Leader rematches?
There is an old woman in a house on Seven Island who will start the sidequest for you.

### How does inviting a Gym Leader work? A Gym Leader I invited is gone! When is the rematch lady's Spearow coming back?
When you show the old woman in the Battle House a full Fame Checker entry for a Gym Leader, her Spearow will leave to bring them an invitation. Once Spearow returns, the invited Gym Leader will periodically visit the Battle House basement where they can be rematched. Once beaten, a Gym Leader will return to their Gym, but will come back to the house automatically to train after some time.

Both Spearow returning and Gym Leaders visiting are based on steps taken while outside of the Seven Island town area. There is randomness involved in how many steps it takes to trigger a Gym Leader visit, but there is bad luck protection that will begin forcing visits to prevent long waits between visits.

The sign outside the Battle House will report which Gym Leaders are currently visiting.

### Can I rematch Giovanni? I can only invite seven Gym Leaders.
Giovanni is canonically on the run after he flees his Gym and is not seen again in FRLG Perfected. Only the first seven Gym Leaders can be rematched.

### What are the Challenge Mode boss trainer levels? I want to level cap my Nuzlocke run.
<details>
<summary>Their levels are as follows:</summary>
Brock: 15<br>
Misty: 22<br>
Lt. Surge: 26<br>
Rocket Hideout Giovanni: 31<br>
Erika: 31<br>
Koga: 46<br>
Silph Co. Giovanni: 44<br>
Sabrina: 46<br>
Blaine: 51<br>
Leader Giovanni: 54<br>
Lorelei: 58<br>
Bruno: 60<br>
Agatha: 62<br>
Lance: 64<br>
Champion: 67<br>

Rematch Lorelei: 71<br>
Rematch Bruno: 73<br>
Rematch Agatha: 75<br>
Rematch Lance: 77<br>
Rematch Champion: 80<br>
</details>

### Where are the new Move Tutors and what moves do they teach?
<details>
  <summary>New move tutor locations:</summary>

• Fury Cutter - Vermilion City

• Rollout - Route 24

• Swagger - Route 10

• Dynamic Punch - Saffron City

• Sleep Talk - Silph Co.

• Nightmare - Silph Co.

• Self-Destruct - Cinnabar Island

• Sky Attack - Mt. Ember

The tutors in Saffron City and Silph Co. will not appear until Team Rocket has been driven from the city.
</details>

### Is there a location list for all the Master Trainers?
The Master Trainers are all in the same locations as they were in LGPE, with the exception of Master Trainers who would have been on Cycling Road. Those that would have been on Cycling Road have been moved to Routes 16 and 18. Keeping that in mind, [refer to this list from Bulbapedia](https://bulbapedia.bulbagarden.net/wiki/Master_Trainer#Trainer_list) for the Master Trainer locations.

## Troubleshooting Savefiles, Emulators, and Flashcarts:

### Is my vanilla FireRed or LeafGreen save compatible with FRLG Perfected?
No. The save needed to be edited to add certain features, and therefore vanilla saves are incompatible with FRLG Perfected. Similarly, FRLG Perfected saves cannot be used in vanilla.

### My emulator/flashcart doesn't work with FRLG Perfected! The game won't save!
The recommended emulator for desktop is [mGBA](https://mgba.io/downloads.html).

If your emulator or flashcart isn't working properly with FRLG Perfected, follow instructions for that particular emulator or flashcart for playing vanilla FireRed or LeafGreen and apply them to getting FRLG Perfected to work. If a patch is required to get vanilla FireRed or LeafGreen to save properly, then FRLG Perfected is incompatible with that emulator or flashcart.

## Modifying FRLG Perfected:

### Can I use FRLG Perfected as a ROM Base?
All mods of FRLG Perfected are unauthorized and unsupported, but derivative works must be free and open source. If you choose to use FRLG Perfected as a ROM Base, I will not offer any support nor answer questions regarding developing a mod of this hack.

### How did you implement *x* feature? Can I use *y* feature for my hack?
Commits are descriptively labeled. If you want to grab something from FRLG Perfected, you must go back through the commits and find where it is implemented. I don't offer support or answer questions for lifting things from FRLG Perfected, but since the project is open source anyone can take from it.

## Miscellaneous:

### Where do I get TM10 for Hidden Power? Pickup doesn't give me TM10 for Hidden Power!

The TM for Hidden Power has been removed from the pickup table and is now sold in the Celadon Dept. Store.

The Pickup table has been changed to the following:<br>
  * 15% - Oran Berry<br>
  * 10% - Cheri Berry, Chesto Berry, Pecha Berry, Rawst Berry, Aspear Berry, Persim Berry<br>
  * &nbsp;&nbsp;5% - PP Up, Rare Candy, Nugget, Pomeg Berry<br>
  * &nbsp;&nbsp;1% - Kelpsy Berry, Qualot Berry, Hondew Berry, Grepa Berry, Tamato Berry<br>

### Will text be decapitalized?
No.

### How do I link to other games? When is the earliest I can link?
FRLG Perfected is compatible with trading, but the battle engine has been changed and is incompatible. If your emulator supports linking, refer to its documentation for how to initiate a link.

The player may link with all Generation III GBA and GCN games the moment they receive the Pokédex. Finishing the Net Center on One Island is no longer a prerequisite for trading with the Hoenn games, trading with the Orre games, using Pokémon Box: Ruby and Sapphire, or receiving Eggs or Pokémon that are not in the Kanto Pokédex.

