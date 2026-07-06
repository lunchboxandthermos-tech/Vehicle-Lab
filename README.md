# Sebastian's Vehicle Lab

A small browser prototype for Sebastian's vehicle-collecting game.

## How to Play

Open `index.html` in a browser.

1. Click **Catch vehicle** to let a vehicle drive into the vehicle portal.
2. Open **Custom card creator** to build a specific year, make, model, and color card by hand.
3. Place the active card in **Inventory** to use it, or **Wish List** to save up to 4 copies for gifts.
4. Use **Race Track** to choose two Inventory vehicles and race them with realistic speed scoring.
5. Use **Gift** to give Wish List vehicles to another player. Gifts land in the friend's Inventory when there is room, or their Wish List if Inventory is full or they already own it.
6. Review **Activity** to see captures, races, gifts, favorites, deletes, custom cards, and logins.

Progress is saved in the browser on the same computer.

Players use local logins stored in the browser. Each player has their own Inventory and Wish List, and the Friend dropdown is populated from the other local logins.
Selected player profiles can be deleted from the login panel after a confirmation prompt. At least one profile is always kept.

Each starter vehicle now has its own blueprint, colorable body, and detail tags so Sebastian can notice what makes it special.

The vehicle list is a local, KBB-like seed catalog rather than a copy of Kelly Blue Book data. It now includes 290+ vehicles across everyday cars, classics, trucks, EVs, buses, motorcycles, emergency vehicles, construction machines, and supercars. Each vehicle includes make, model, year, type, default color, detail tags, and a base rarity level. The custom card creator filters known models by make and year. The current rarity ladder is Basic, Common, Rare, Mythic, and God. Final rarity is calculated by rules: vehicles made before 2000 are Rare or higher, vehicles made before 1980 are Mythic or higher, Hypercars can reach God, and custom paint raises rarity by one level.

Inventory holds one usable copy of each vehicle. It starts with 9 spots shown as a 3-by-3 garage grid. Owning a God-level vehicle in Inventory opens 18 Inventory spots; if there are no God-level vehicles left in Inventory, it returns to 9 spots. Extra copies of the same catalog vehicle go to Wish List, where up to 4 copies can be saved for gifts or moving into Inventory.

Inventory and Wish List items can be starred as favorites or deleted. Favorites sort to the top, and a favorited vehicle must be unstarred before it can be deleted. Each list can be sorted by name, year, make, color, or rarity while staying alphanumeric inside matching groups. Deleting a Wish List stack removes one copy at a time.

The Race Track lets the current player select two Inventory vehicles and watch them move around an oval track from a checkered start flag toward a red finish flag. Race results are based on vehicle type, year, performance details, and model traits, with only a small random factor for close matchups. Each Inventory card keeps its own race win count.

The Vehicle Database and Updates tools are hidden from the player-facing interface. Activity remains visible so players can see logins, captures, races, collection changes, gifts, favorites, and deletes.

The Activity panel includes an undo button for recent reversible changes such as adding/removing vehicles, favorites, list clears, gifts, race win updates, and local login creation.

## Good Next Updates

- Add player profiles for Sebastian, friends, and family.
- Add sound effects for catching, painting, gifting, and rare vehicles.
- Add more rarity rules such as limited editions, discontinued models, and one-of-one customs.
- Let Sebastian draw or choose custom vehicles.
- Add a garage view where Inventory vehicles can be arranged and used in pretend missions.
