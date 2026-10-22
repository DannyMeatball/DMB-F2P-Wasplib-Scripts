# DMB Scripts

My OSRS scripts for Simba 2.0 + WaspLib. All F2P.

*Disclaimer* These are Vibe Coded Scripts. They are all thoroughly tested but may have issues. Use at your own risk.

## Scripts

### DMB's F2P Miner
*Skills: Mining*

Mines ore, then banks or power mines. Pick the mine and the ores you want. It goes for the best ore first and heads back to it when it respawns.
- Needs: a pickaxe. If you don't have one on you, it takes the best one you can use out of the bank.

### DMB's F2P Fisher
*Skills: Fishing, Cooking*

Fishes at Barbarian Village, Draynor, Lumbridge and Musa Point. Can cook before banking, or power fish.
- Needs: the gear for how you're fishing, in your inventory. Small fishing net, fishing rod and bait, fly fishing rod and feathers, lobster pot, or harpoon.
- Musa Point: 60 coins for the boat there and back.

### DMB's F2P Woodcutter
*Skills: Woodcutting, Firemaking*

Cuts trees at Lumbridge, Draynor, Varrock West and Edgeville, or wherever you're standing. Banks, drops or burns the logs.
- Needs: an axe. If you don't have one, it takes one out of the bank. Same for a tinderbox if you're burning.
- Anything else you start with stays in your inventory.

### DMB's F2P Smelter
*Skills: Smithing*

Smelts bronze up to rune bars at Edgeville, Al Kharid, Falador and Lumbridge.
- Needs: the ores in your bank.

### DMB's F2P Smither
*Skills: Smithing*

Smiths bars at the Varrock West anvils or Horvik's shop.
- Needs: the bars in your bank. It takes a hammer out of the bank if you don't have one.

### DMB's F2P Jewellery
*Skills: Crafting*

Makes gold and silver jewellery at a furnace: rings, necklaces and amulets (gold, sapphire, emerald, ruby, diamond), plus holy symbols and tiaras. Furnaces at Edgeville, Al Kharid, Falador and Lumbridge. Pick the item and it banks the finished jewellery.
- Needs: the gold or silver bars (and gems) in your bank. It takes the right mould out of the bank if you don't have one.

### DMB's F2P Cooker
*Skills: Cooking*

Cooks the food you pick at the Lumbridge Castle kitchen, the Barbarian Village fire, Al Kharid or Draynor, and banks it. Shrimps up to swordfish, plus bread, stew, pies and cake.
- Needs: the raw food in your bank. Bread, pies and cake need a range, so not the fires.

### DMB's F2P Firemaker
*Skills: Firemaking*

Takes logs out of the bank you pick (or the nearest one), walks to a spot just outside it where fires are allowed, lights one fire and puts all the logs on it. Banks at Varrock West, Varrock East, the Grand Exchange, Edgeville, Draynor, Falador West, Falador East, Al Kharid and Lumbridge Castle. Pick the logs, or let it burn the best ones you can.
- Needs: the logs in your bank. It takes a tinderbox out of the bank if you don't have one.

### DMB's F2P Runecrafter
*Skills: Runecrafting*

Crafts air, mind, water, earth, fire or body runes. Pick the altar and it banks at the one that goes with it: Falador East for Air, the Ruins of Camdozaal for Mind, Lumbridge Castle for Water, Varrock East for Earth, Al Kharid for Fire and Edgeville for Body. It banks everything in your inventory before it starts.
- Needs: rune or pure essence in your bank, and the altar's talisman or tiara (worn, in your inventory, or in the bank). It puts the tiara on for you.
- Mind: the Ruins of Camdozaal bank needs the Below Ice Mountain quest.

### Brutus Killer
*Skills: Attack, Strength, Defence, Hitpoints, Ranged, Magic, Prayer (buries the bones)*

Kills Brutus, the Lumbridge cow boss. Dodges his specials, eats, loots, and rings the cowbell amulet after each kill so he comes back faster. Works with melee, ranged or magic, using whatever combat style you've set.
- Needs: food and a charged cowbell amulet (worn or in your inventory). It checks the charges before it starts.
- When your food, runes or arrows run out, it teleports out with the cowbell amulet and logs out.

## All the scripts
- Walk there from anywhere on the F2P surface. Never go into the Wilderness.
- Get through the Al Kharid toll gate. Free with Prince Ali Rescue, otherwise 10 coins. If neither works, they walk the long way round.
- If you misclick something like a poll booth, they close it and carry on.
- If you get disconnected, they log back in and carry on (no password needed if you play through the Jagex launcher).

## Settings window
- **Runtime:** how long to run, in minutes.
- **LOCKED:** anything your level is too low for. It won't start on a locked choice.
- **Debug box:** turns off the level and item checks, so you can test the walking without the right gear or levels. Leave it off normally.
- The picture on the right comes from the `images` folder.

## Tools
In the `Tools` folder:
- **DMB's City Walker** - pick a city and it walks you there.
- **test_...** scripts - small tests I used while making the scripts (bank, stairs, teleport, walking). They mostly just check things and print to the log.

## Needs
- Simba 2.0
- WaspLib (latest)
- RuneLite
- Game settings the way WaspLib suggests (Fixed - Classic layout)

## Install
Put the files in your Simba `Scripts` folder, with the `images` folder next to the scripts. Start logged in or at the login screen.

## Problems
If a script stops and says to post the log, open an issue here. Paste the log and say what you were doing.
