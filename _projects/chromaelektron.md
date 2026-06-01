---
title: CHROMA+ELEKTRON
link: https://store.steampowered.com/app/1020550/CHROMAELEKTRON/
---
## CHROMA+ELEKTRON

[Link (Steam)](https://store.steampowered.com/app/1020550/CHROMAELEKTRON/)

<div class="image-grid">
    <div class = "image-grid-box"><img src="/assets/images/exchange1.png" alt="CHROMA+ELEKTRON Screenshot 3"></div>  
    <div class = "image-grid-box"><img src="/assets/images/crystal1.png" alt="CHROMA+ELEKTRON Screenshot 3"></div>  
</div>

CHROMA ELECTRON is a fast-paced 2D platformer-shooter. Selected for Hand Eye Society's Super FESTival 2025 showcase.  

As the solo developer of the game, I created the concept, game design, programming, visuals, sound effects, music and marketing materials.

### Concept

Originally starting out as a student project, I initially wanted to make a game that reflects all of my influences as a sort of starting point. As development progressed, I wanted to express more fundamental aspects of the games ----------.

A key chracteristic is that the game is abstract, with no explicit expression of narrative. However, no game is created with complete detatchment from the world, and in aiming to create something abstract, interesting links to the real world will inevitably emerge. One design objective was to create a game that, with no explicit narrative, nevertheless expresses emotion. I felt the "flow state" inherent in the action game genre, and the intersection between effort and focus was a good starting point for evoking these emotions.

Key to the gameplay loop are its two main resources: Color and Energy. Every enemy drops a color powerup; when the player picks it up, the player's abilities change corresponding to its color.

Energy acts as a representation of several quantities. It acts as a resource that must be expended to use more powerup attacks, as well as to recover lost shields. However, high levels of Energy also increase the game's speed. At high levels of Energy, the game can run as fast as double speed. The Endless game mode removes the limit on Energy entirely, introducing new implications to the gameplay loop.

The interaction between these two resources and the rest of the system is where the game receives much of its complexity and novel decision-making, and these interactions permeate through much of the experience of playing the game. By interlocking the systems so closely and having them affect as many game elements as possible, I could no longer reliably predict how the game would behave in specific cases. The idea is to present the quantities as something inherent to the world. And finally, the idea is to take this system as a statement on what it means to play a game, and what it means to create a game.

### Weapons

There are six colors and six sets of abilities that a player can switch between during a level.

How to make each weapon memorable and fun to use? In CHROMA ELECTRON, this manifests in several ways:
- Each weapon presents a real-world physical aspect. Yellow weapons evoke ballistics, green weapons evoke gravity, purple weapons evoke plasma.
- Each weapon can be used in a 

Weapons should not have elements that make switching between them jarring; switching between weapons should feel like a change in momentum but not an obstruction to momentum. Accidentally swapping between weapons should still result in a net positive effect. For example, holding down the fire button will always fire a damaging projectile in a forward direction.

#### Example: Yellow 1 - Missiles

The Yellow 1 weapon fires a rapid barrage of missile-like projectiles. 

Upon impact, the missile explodes with a small radius; very tightly grouped enemies can be hit together but more often than not will only hit one enemy at a time, making the weapon less effective against groups of enemies.

#### Example:

### Level Design

The game is played linearly through levels.

At the beginning of a level, the player is required to reach a powerup that will trigger the start of the level. During this period, there's no music and players are encouraged to explore the layout of the level. 

In contrast with standard game design practice, there are no substantial moments of downtime to the gameplay loop; it isn't important that the player experiences the game in one continuous fashion.

Visually, each level should evoke some idea, an overall emotional impression; however, each level should also remain abstract, with some separation of concepts found in the real world. The order of the levels forms an arc, with smaller, secluded, abstract designs in the first third; expanded sizes and visuals referencing the outside in the second; and complex, antagonistic architecture, inexorable motion, a "descent" in the last third.

Because it's easier for players to drop to lower platforms than it is to jump higher, players will tend towards the lower areas of a level. Levels were designed either to compensate for this characteristic or emphasized as a challenge. In "Scaffold", the defining level element is a tower containing a jump pad that immediately launches the player to the top of the level. Since this is the easiest method of reaching the top of the level, the player's movements centralize around the tower at the bottom of the level, while being more free in decisions regarding how to traverse the level back down to the bottom. In "Stillwater", the fluctuating water levels forces a player to rise in altitude with the tide; the tendency for players to settle at the bottom of a level becomes a challenge that needs to be constantly managed.

#### Example: Blue Room

"Blue Room" is the first level in the game, and it needs to present many ideas to the player for the first time. It is small in size, and is tied for smallest level area with the second level. To complement the small space, the level is dimly lit, with a dark blue dominant color. The background visually centers around a small platform situated in the middle of the room, with a spotlight from above shining down. The overall effect is meant to be intimate and secluded, combined with an impression similar to being deep underwater. The ceiling is comprised of arches, somewhat evoking church archtecture while making the ceiling area spacious, making it easier for new players to experiment moving in open air.

There are relatively few platforms, and the level has no unique obstacles. No platforms are particularly long and there are gaps in between, giving players relatively unimpeded vertical movement through the level. In the bottom corners of map are sets of two jumppads; the first jumppad provides easy access to the lower platforms, and the player can decide whether to jump onto these lower platforms or take the second jumppad to reach the upper platforms.

Despite the simple layout, some familiarity with the level's layout will result in a general movement pattern; because the jumppads make it more difficult to travel downwards through those paths, the natural way to travel downwards through the map is through the middle of the stage, in between the platform gaps. The result is a naturally circular / figure-8 path through the level, rising through the level with the corner jumppads and descending down the center of the level without backtracking.

Stage powerups are introduced here for the first time, and always appear at pre-determined stations indicated to the player. Upon picking up a stage powerup, another powerup will appear at any nearby station.

Finally, the level introduces enemy rails, which grounded enemies can use to traverse across platforms. When a grounded enemy begins travelling on a rail, the entire rail flashes lightly, warning players of an incoming enemy. While not necessary for a new player to learn, for players more familiar with the game or for those seeking mastery, the layout of rails in a level is important for understanding specific points where levels can be particularly risky. Here, rails are placed on the edges of the level; since players are more likely to approach platforms from the sides and towards the center, this makes head-on collisions with grounded enemies leaving rails less likely.

### Visuals

The primary visual strategy is to use primitive shapes along with heavy use of particle effects. There are several advantages to adopting this visual style:

1. A simple visual style tends to be highly legible, easy to convey information quickly, which complements the action gameplay nicely.
2. A simple visual style dovetails nicely into the overarching concept of a game operating on its base elements.
3. It lets me easily leverage programmatic methods of creating visuals--particle systems in particular can be manipulated into an endless variety of interesting effects with some programming.

Level environments are 

### Sound Design and Music

Music has an outsized influence in how I design my games. There are eight total tracks that play during gameplay; each one is constructed such that they build in energy as the game progresses. 

I singled out weapon sounds as especially high-priority; these sounds are omnipresent through the experience of the game, punctuate the action at all times, and the overall rhythmic impression of the game will be these sounds. It was important that each color has its own sound identity as a way to convey the switching of abilites. Red weapons have a characteristic high-treble, gaseous and "sharp" signature, while purple weapons are more characterized by the "hum" reminiscent of electricity.