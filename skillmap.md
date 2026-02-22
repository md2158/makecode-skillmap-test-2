# ramadan-game

* name: Ramadan Game - MakeCode Arcade Skillmap
* description: Build a Ramadan-themed arcade game step by step! Learn to create a walking character, animated scenes, collectible items, and game flow — all inspired by the spirit of Ramadan. Perfect for intermediate game developers.
* infoUrl: https://arcade.makecode.com

## path-setup

* name: Path 1 — Setting Up the Game World
* description: Build the foundation of the game: custom sprite kinds, the intro screen, and your animated player character.
* completionUrl: https://example.com/certificates/setup-complete.pdf

### activity-spritekinds

* name: Create Custom Sprite Kinds
* type: tutorial
* description: Learn how to extend MakeCode Arcade with your own sprite categories. We'll define the custom SpriteKind types used throughout the Ramadan game.
* tags: sprites, setup, intermediate
* url: github:YOUR_USERNAME/YOUR_REPO/tutorials/01-spritekinds
* imageUrl: https://arcade.makecode.com/api/thumb/S36641-15321-53372-09817

### activity-intro

* name: Build the Intro Screen
* type: tutorial
* description: Create the opening scene with a "Ramadan Kareem" greeting banner, a start gate, and set the background color to get the game ready.
* tags: sprites, scenes, decoration
* url: github:YOUR_USERNAME/YOUR_REPO/tutorials/02-intro
* imageUrl: https://arcade.makecode.com/api/thumb/S36641-15321-53372-09817

### activity-player

* name: Animate Your Player Character
* type: tutorial
* description: Bring your boy sprite to life with a walking animation, controller movement, and screen boundary limits. Learn how to use runImageAnimation for multi-frame sprites.
* tags: animation, player, controller
* url: github:YOUR_USERNAME/YOUR_REPO/tutorials/03-player
* imageUrl: https://arcade.makecode.com/api/thumb/S36641-15321-53372-09817

### activity-directional

* name: Add Directional Animations
* type: tutorial
* description: Make your character look like they're really walking by swapping animations when moving left or right using controller button events.
* tags: animation, controller, events
* url: github:YOUR_USERNAME/YOUR_REPO/tutorials/04-directional
* imageUrl: https://arcade.makecode.com/api/thumb/S36641-15321-53372-09817

## path-gameplay

* name: Path 2 — Game Phases & Collectibles
* description: Implement the Sahur food-collecting phase, the Pahala coin-collecting phase, scoring, sound effects, and the Next button unlock mechanic.
* completionUrl: https://example.com/certificates/gameplay-complete.pdf

### activity-sahur-scene

* name: Build the Sahur Scene
* type: tutorial
* description: Set the Sahur background, destroy the intro sprites, and spawn trees around the scene to create an outdoor pre-dawn atmosphere.
* tags: scenes, sprites, environment
* url: github:YOUR_USERNAME/YOUR_REPO/tutorials/05-sahur-scene
* imageUrl: https://arcade.makecode.com/api/thumb/S36641-15321-53372-09817

### activity-food-collect

* name: Spawn & Collect Sahur Foods
* type: tutorial
* description: Randomly spawn Sahur food sprites across the screen and handle overlap events to collect them, update the score, and play a sound effect.
* tags: collectibles, overlap, score, sound
* url: github:YOUR_USERNAME/YOUR_REPO/tutorials/06-food-collect
* imageUrl: https://arcade.makecode.com/api/thumb/S36641-15321-53372-09817

### activity-pahala-coins

* name: Spawn Pahala Coins
* type: tutorial
* description: After Sahur is done, spawn 10 collectible Pahala (reward) coins at random positions with a delay between each spawn. Learn about loops and pause() timing.
* tags: coins, loop, collectibles, timing
* url: github:YOUR_USERNAME/YOUR_REPO/tutorials/07-pahala-coins
* imageUrl: https://arcade.makecode.com/api/thumb/S36641-15321-53372-09817

### activity-next-button

* name: Unlock the Next Button & Game Flow
* type: tutorial
* description: Trigger an animated Next button when the player reaches the score target. Wire up overlap events to chain game phases together and complete the full game loop.
* tags: animation, score, game-flow, events
* url: github:YOUR_USERNAME/YOUR_REPO/tutorials/08-next-button
* imageUrl: https://arcade.makecode.com/api/thumb/S36641-15321-53372-09817
