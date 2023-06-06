# Last Bee Standing

- Elie Hofer, Huiwen Zang
- Master Media Design, HEAD–Genève

## Pitch

You are a bee who returns home after a long while and finds everything has died in the garden where your hive resides. You pay your last homage with tears in eyes. However, as the tears fall to the ground, the remains miraculously regrow into a beautiful flower. You decide to do the same for the rest. Soon the tears of sorrow turn to tears of joy, as each time a plant is reborn, leaves appear on the honey tree again, and your hive revives. Your garden slowly becomes as lush and marvelous as it was before.

## Synopsis

In this game you play the role of a bee that wants to rebuild its garden. Basically its home has been destroyed by unknown events and its mission is to bring it back to life. The environment is a garden full of vegetation articulated around the main tree, the HONEY TREE. This tree and the bee hive that is attached to it are very important because they act as a mirror of the garden's decline : Each time a plant is revived, the honey tree becomes healthier. To be able to revive a plant, the bee has first to collect a drop of water from its tears. As a VR player you'll just have to put your hand in a certain position to generate the drop. Once the drop is collected the bee has to drag it and deposit it on the dead plant that will immidiately change state, transform into a healthy plant. Also, the parcel of floor where the plant resides will turn from grey to green. Each time a plant is revived, the honey tree becomes healthier, you can see it thank's to its colors and its shape. Once all the dead elements of the garden come back to life and that the honey tree is healthy again, you completed the game. In this experience you don't see directly that you are a bee since you'll play the bee as first person. However, There will be many hints alluding to it like the buzz sound when you move, the massive central honey tree, and antennas dangling on top of your head.

![maq](images/maquette7.jpg)
![maq](images/maquette8.jpg)

## Visual Interaction Loop

- Palm up, a drop of water unit is generated on your hand. You pick it up, place it on the remains of a dead plant and it will regrow into a living plant. Meanwhile, in the middle of the garden, the honey tree grows a few leaves and becomes a bit healthier by regaining warm colors as well, step by step, each time a plant regrows.

## POV

2 possibilities :

- I am in front of parcels of dead plants，behind which there's the honey tree. I never get close to the tree and only proceed to play around myself.

- I am under the honey tree and the parcels are surrounding it. I move around the tree to access the plants.

## Assets

- Models

  - Honey Tree (big)
  - Normal Tree (small)
  - Leaves
  - Hoeny
  - Water Drop
  - Green Sponge
  - Grey Sponge
  - Chestnut
  - Nut Shells
  - Black Cohosh
  - Seeds
  - Fringed Orchid
  - Dry orchid flowers 1
  - Blue Sun Star Orchid
  - Dry orchid flowers 2
  - Underground Orchid
  - Dry orchid flowers 3

- Gestures

  - Palm up 🫴
    Generating the water drop
  - Drag and drop 👌-🫳
    Depositing the drop on the plant

- Sounds

  - Bzzzzz
    Every movement creates a buzz

  - gluglugluglu
    Water generating

  - shinkssshinkss
    Sparkle/Glitter sound when the plants transform

## State Machines

Describe all the objects in a Scene that need to have a "state". Don't worry about objects that don't change state.

- Honey tree

  - Gets healthier by regaining its colors each time a plant regrows

  - Leafs on it increase in number each time a plant regrows

- "Dead" object transform into the "healthy" objects each time a water unit is dropped on them :

  - Grey Sponge (Disappear) ➡️ Green Sponge (Shows up)
  - Nut Shells (Disappear) ➡️ Chestnut (Shows up)
  - Seeds (Disappear) ➡️ Black Cohosh (Shows up)
  - Dry Flowers 1 (Disappear) ➡️ Fringed Orchid (Shows up)
  - Dry Flowers 2 (Disappear) ➡️ Blue Sun Star Orchid (Shows up)
  - Dry Flowers 3 (Disappear) ➡️ Underground Orchid (Shows up)
