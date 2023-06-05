# Last Bee Standing
- Elie Hofer, Huiwen Zang
- Master Media Design, HEAD–Genève

## Pitch
A 500 character (or less!) description of the project. 

You are a bee who returns home after a long while and finds everything has died in the garden where your hive resides. You pay your last homage with tears in eyes. However, as the tears fall to the ground, the remains miraculously regrow into a beautiful flower. You decide to do the same for the rest. Soon the tears of sorrow turn to tears of joy, as each time a plant is reborn, leaves appear on the tree again, and your hive revives. Your garden slowly becomes as lush and marvelous as before.

(Before: You are a bee that hasn't been home in a long time and decide to come back. As you arrive in the garden where your hive resides you discover that everything has died while you were away. You pick up a remain of the garden and burry it in the ground as a last homage. While the water of your tears of nostalgia touch the soil, you realise with that the remain had regrown into a beautiful flower. You decide to do the same with the other remains. Soon tears of sadness become tears of joy as you realise that everytime a plant is reborn, the main tree and your hive are being restored : slowly leafs are appearing again on the branches and bees start to come back. Together you start rebuilding this garden until it's as lush and marvelous as it was before you left.)



## Synopsis
This is a "1 pager" that explains all the basics in one page. This is a text-based description of the project with maybe one illustration that accompagnies the text.

?
MAP:Maquette

## Visual Interaction Loop
There should be *one simple basical funamental interaction loop* to your project. Please describe this fundamental interaction in a paragraph.

- Palm up, a drop of water (your tears) falls on your hand. You place it on the remains of a dead plant and it revives into a living plant. Meanwhile, in the middle of the garden, the honey tree grows a few leaves and becomes a bit healthier.

## POV

POV == Points of view. Describe all the POVs where the player can stand/float/be in the scene. Who are you, where are you, what do you see?

- I am a bee. I am in front of the dead plants，behind which there's a honey tree. I collect my tears and water it on the remains of the plants. The plants gets back to life, the main tree gets healthier, my garden is gradually revived...

## Assets
- Models
	+ Tree (big)
	+ Tree (small)
	+ Leaves
	+ Hoeny
	+ Water Drop
	+ Green Sponge
	+ Grey Sponge
	+ Chestnut
	+ Nut Shells
	+ Black Cohosh
	+ Seeds
	+ Fringed Orchid
	+ Dry Flowers 1
	+ Blue Sun Star Orchid
	+ Dry Flowers 2
	+ Underground Orchid
	+ Dry Flowers 3

- Gestures
	+ Palm up 🫴
	+ Drop

- Sounds
	+ Bzzzzz (Every step you move, you make a BeeSound)
	+ gluglugluglu (water)


## State Machines
Describe all the objects in a Scene that need to have a "state". Don't worry about objects that don't change state.

- Honey tree
	+ Gets healthier (less dusty?) each time the water is dropped

- Leaves (on the honey tree)
	+ Increase each time the water is dropped

- "dead" object turns into the "live" object each time the water is dropped:
	+ Grey Sponge (Disappear) ➡️ Green Sponge (Shows up)
	+ Nut Shells (Disappear) ➡️ Chestnut (Shows up)
	+ Seeds (Disappear) ➡️  Black Cohosh (Shows up)
	+ Dry Flowers 1 (Disappear) ➡️ Fringed Orchid (Shows up)
	+ Dry Flowers 2 (Disappear) ➡️ Blue Sun Star Orchid (Shows up)
	+ Dry Flowers 3 (Disappear) ➡️ Underground Orchid (Shows up)

