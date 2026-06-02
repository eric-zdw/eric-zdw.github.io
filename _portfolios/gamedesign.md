---
title: Game Design Portfolio
layout: post
---

Hello, I'm Eric·ZDW. The initials "ZDW" come from the names of me and my parents. My goal is to make games that will stay with people, however that may look like. My design leans towards action games, but I make a point to take inspiration from any genre and nothing is off the table.

Email: [eric.zdw@gmail.com](mailto:eric.zdw@gmail.com)  
Discord: ericzdw

Table of Contents
- [CHROMA+ELEKTRON](#chromaelektron)
  - [Concept](#concept)
  - [Weapons](#weapons)
    - [Example: Yellow 1 - Missiles](#example-yellow-1---missiles)
    - [Example:](#example)
  - [Level Design](#level-design)
    - [Example: Blue Room](#example-blue-room)
  - [Enemy Design and Programming](#enemy-design-and-programming)
    - [Example: Boss 3](#example-boss-3)
  - [Sound Design and Music](#sound-design-and-music)
    - [Example: Track 6](#example-track-6)
- [Sea Salt City](#sea-salt-city)
  - [Concept](#concept-1)
  - [Design](#design)
  - [Level Design](#level-design-1)
  - [Sound and Music](#sound-and-music)
- [Feedbacker](#feedbacker)
  - [Concept](#concept-2)
  - [Design](#design-1)
  - [Sound Design and Music](#sound-design-and-music-1)

<hr>

## CHROMA+ELEKTRON

[Link (Steam)](https://store.steampowered.com/app/1020550/CHROMAELEKTRON/)

<div class="image-grid">
    <div class = "image-grid-box"><img src="/assets/images/exchange1.png" alt="CHROMA+ELEKTRON Screenshot 3"></div>  
    <div class = "image-grid-box"><img src="/assets/images/crystal1.png" alt="CHROMA+ELEKTRON Screenshot 3"></div>  
</div>

CHROMA+ELEKTRON is a fast-paced 2D platformer-shooter. Selected for Hand Eye Society's Super FESTival 2025 showcase.  

As the solo developer of the game, I created the concept, game design, programming, visuals, sound effects, music and marketing materials.

### Concept

A key chracteristic is that the game is abstract, with no explicit mention of narrative. How does the gameplay loop create drama without explicit narratives? No game is created with complete detatchment from the world, and in aiming to create something abstract, interesting, personal links to the real world will inevitably emerge. One design objective was to create a game that, with no explicit narrative, nevertheless expresses emotion. I felt the "flow state" inherent in the action game genre, and the unique intersection between effort and focus (the kind of experience I would get from games like *Quake*, *Devil May Cry*, and bullet hells), was a good starting point for evoking these emotions. The goal is to take this essence and push it towards a conclusive emotional experience; what it means to play a game, and what it means to create a game; finally to push the idea in a way that, if you're having fun playing the game, the "purpose" is already proven, it is self-evident.

Key to the gameplay loop are its two main resources: Color and Energy. Every enemy drops a color powerup; when the player touches it, the player's abilities change to its corresponding color. Energy acts as a representation of several quantities; it acts as a resource that must be expended to activate more powerful abilities, increase maneuverability, as well as recovering lost health. However, high levels of Energy also increase the game's speed. At high levels of Energy, the game can run as fast as double speed and can become uncontrollable unless the player expends it. The game features a scoring system that is closely tied to Energy. Points received by defeating enemies are multiplied proportionally to game speed. When aiming for a high score, the system is a constant push to play at energy levels as high as it can be harnessed.

The interaction between these two resources and the rest of the system is where the game receives much of its complexity and novel decision-making, and these interactions permeate the experience of playing the game. By interlocking the systems so closely and having them affect as many game elements as possible, I could no longer reliably predict how the game would behave in specific cases. The idea is to present these concepts as indivisible properties inherent to the world.

### Weapons

There are six colors and six sets of abilities that a player can switch between during a level.

How to make each weapon memorable and leave an impression? In CHROMA+ELEKTRON, this manifests in several ways:
- Each weapon presents a real-world physical aspect. Yellow weapons evoke ballistics, green weapons evoke gravity, purple weapons evoke plasma.
- Each weapon can be used in a 

Weapons should not have elements that make switching between them jarring; switching between weapons should feel like a change in momentum but not an obstruction to momentum. Accidentally swapping between weapons should still result in a net positive effect. For example, holding down the fire button will always fire a damaging projectile in a forward direction.

#### Example: Yellow 1 - Missiles

The Yellow 1 weapon fires a rapid barrage of missile-like projectiles. 

Upon impact, the missile explodes with a small radius; very tightly grouped enemies can be hit together but more often than not will only hit one enemy at a time, making the weapon less effective against groups of enemies.

#### Example:

### Level Design

Visually, each level should evoke some idea, an overall emotional impression; however, each level should also remain abstract, with some separation of concepts found in the real world. The order of the levels forms an arc, with smaller, secluded, abstract designs in the first third; expanded sizes and visuals referencing the outside in the second; and complex, antagonistic architecture, inexorable motion, a "descent" in the last third.

Because it's easier for players to drop to lower platforms than it is to jump higher, players will tend towards the lower areas of a level. Levels were designed either to compensate for this characteristic or emphasized as a challenge. In "Scaffold", the defining level element is a tower containing a jump pad that immediately launches the player to the top of the level. Since this is the easiest method of reaching the top of the level, the player's movements centralize around the tower at the bottom of the level, while being more free in decisions regarding how to traverse the level back down to the bottom. In "Stillwater", the fluctuating water levels forces a player to rise in altitude with the tide; the tendency for players to settle at the bottom of a level becomes a challenge that needs to be constantly managed.

#### Example: Blue Room

"Blue Room" is the first level in the game, and it needs to present several ideas to the player for the first time. It is smaller in size compared to the average stage. To complement the small space, the level is dimly lit, with a dark blue dominant color. The background visually centers around a small platform situated in the middle of the room, with a spotlight from above shining down. The overall effect is meant to be intimate and secluded, combined with an impression similar to being deep underwater. The ceiling is an arch shape, making the ceiling area more spacious and making it easier for new players to experiment moving in open air.

There are relatively few platforms, and the level has no unique obstacles. No platforms are particularly long and there are gaps in between, giving players relatively unimpeded vertical movement through the level. In the bottom corners of map are sets of two jumppads; the first jumppad provides easy access to the lower platforms, and the player can decide whether to jump onto these lower platforms or take the second jumppad to reach the upper platforms.

Despite the simple layout, some familiarity with the level's layout will result in a general movement pattern; because the jumppads make it more difficult to travel downwards through those paths, the natural way to travel downwards through the map is through the middle of the stage, in between the platform gaps. The result is a naturally circular / figure-8 path through the level, rising through the level with the corner jumppads and descending down the center of the level without backtracking.

Stage powerups are introduced here for the first time, and always appear at pre-determined stations indicated to the player. Upon picking up a stage powerup, another powerup will appear at any nearby station.

Finally, the level introduces enemy rails, which grounded enemies can use to traverse across platforms. While not necessary for a new player to learn, for players more familiar with the game or for those seeking mastery, the layout of rails in a level is important for understanding specific points where levels can be particularly risky. Here, rails are placed on the edges of the level; since players are more likely to approach platforms from the sides and towards the center, this makes head-on collisions with grounded enemies leaving rails less likely.

### Enemy Design and Programming

Each level consists of six increasingly difficult waves of enemies that must be cleared before proceeding the to the next wave. 

Enemies use a custom A* pathfinding algorithm to create a path to the player. This algorithm can accomodate different types of locomotion (grounded enemies vs. air enemies) and different enemy sizes. The pathfinding algorithm can pause calculation and resume on future frames, allowing for time-slicing and sharing execution time across several enemies.

The pathfinding grid is automatically populated with a grid of traversable nodes.

Some levels will end with a large boss on the last wave.

#### Example: Boss 3

Boss 3 (nicknamed "Snake") consists of a main Head piece and several Tail pieces that follow it. The tail pieces are physical rigidbodies and can be pushed around by forces such as explosions, but move back into position once pushed. The amount of distance between tail pieces can be adjusted dynamically as a parameter, allowing for stretching and squishing for specific movements (for example, the tail can be squished as the head rears back, preparing for a strike).

During its idle phase, the head moves in a slow, menacing circular motion around the player.

Some attacks detach the tail pieces completely. For example, one of its latter-phase attacks have the tail pieces separate and surround the player, reducing the space which the player can maneuver; the head then fires slow moving projectiles into the tail "arena".

### Sound Design and Music

I singled out weapon sounds as especially high-priority; these sounds are omnipresent through the experience of the game, punctuate the action at all times, and the overall rhythmic impression of the game will be these sounds. It's important that each color has its own sound identity as a way to punctuate switching colors; if the weapons sounded too similar, the feeling of switching colors would feel more monotonous in turn. Red weapons have a characteristic high-treble, gaseous and "sharp" signature, while purple weapons are more characterized by the "hum" reminiscent of electricity.

Music has an outsized influence in how I design my games. Each level is associated with one specific track, and each one is constructed such that they build momentum in parallel to the gameplay as the waves progress. 

#### Example: Track 6



<hr>

## Sea Salt City

[Link (itch.io)](https://ericzdw.itch.io/sea-salt-city)

<div class = "image-grid">
    <div class = "image-grid-box"><img src="/assets/images/sea-salt-city_1.png" alt="Sea Salt City Screenshot 1"></div>
    <div class = "image-grid-box"><img src="/assets/images/sea-salt-city_3.png" alt="Sea Salt City Screenshot 3"></div>
</div>

Sea Salt City is a first-person shooter created in 10 days for Bigmode Game Jam 2026. It was voted #1 out of 647 entries in the Fun Category, and it was awarded as a finalist as the "Best Successor to Kingdom Hearts 2" (I've only played the first game).

As the solo developer of the game, I created the concept, game design, programming, visuals, sound effects and music, with some SFX exceptions.

### Concept

One issue with game jams is that, once the jam is over, nearly all games in one are immediately lost media that no one will play. Considering this, some questions going into the game jam included, "How can I create something that I can look back on positively? "Can I create something that I can come back to again?"

The theme of the game jam was "Slick", which immediately brings to mind two aspects: things that are "cool", such as movements in action games, expressions of skill; another is the slipperiness of a "slick" material. Combined with the questions posed above, and that a player likely only has ten minutes to play the game, my concept going into the beginning of the jam revolved around an action game condensed in a "song" format. Like a song, the game would be short, but you can come back to it again anytime you want to experience it again. The best songs are ones you can listen to at any time and be changed by it when it's done, for the rest of your day or for long periods of your life. This is one aspect I really tried to capture here.

Visually, I opted for a stark, white-blue palette, with a subtly "overly" blue coloration. Many details were adjusted to keep in line with this palette; for example, shadows are adjusted to be a deeper blue. I made the water and the sky both a frigid blue, and I chose white for most architectural elements, both to stand out against the water and sky, and also to evoke the water's erosion of structures (as if the architecture had been "bleached white"); I hoped to lightly tie together this "erosion" and subtle passage of time with the theme of memory. 

### Design

At first, in line with the theme of the jam, I wanted to create a loop that revolved around

The game makes extensive usage of Unity's built-in HDRP water shader. While researching approaches to creating water suitable for what I needed, I stumbled across its documentation and was seriously impressed by its flexibility, ways to manipulate it and ways to interact with it through gameplay. While built for more realistic AAA applications, I wanted to push its limitations in a gameplay context and manipulate it in a more stylized, non-realistic manner.

The player can rotate in along all three degrees of freedom. The goal was to have unfettered rotational movement, to be able to frame targets in any orientation. However, if the camera was completely unlocked at all times, the game would quickly become unplayable. In order to achieve this while still having a sense of functionality, the game switches between two modes behind the scenes: a default mode that constraints the camera like a standard FPS, and a free mode that activates when the player rotates in the air, which unlocks all degrees of freedom. This scheme was inspired by *Echo Point Nova*, an FPS that also allows for free range of motion, but only once the player signals the intention to do so by moving the mouse in a vertical flipping motion; In this game, rotation is instead mapped to keys (Q/E to roll, R/F to pitch). Combined with the implementation of inertia added to the rotational controls, mapping rotation to keys is meant to emulate the inertia of rotating the entire body, with the mouse movements emulating the smaller motions of the head/neck. 

I drew from several inspirations for the use of free rotation. I was inspired by experimental film, in particular Michael Snow's *La Région Centrale*, a film made with a free-rotating camera filming an empty landscape; simply by using rotational movements in all directions, it manages to convey a full dramatic arc and unique intensity, each rotation as if freely rotating the world itself. I was also inspired by the Winter X Games, coincedentially watching the reruns of the Winter X Games leading up to the jam; I think the image of snowboarders sailing through the sky, rotating in several axes, was fresh in my mind.

### Level Design

The layout of the level resembles a park; each quadrant of the level is meant to have certain landmarks. In this game, it didn't matter that the player was sent equally to all areas of the map; it's more important that each element leaves some sort of impression. For example, one side of the map is isolated by the rest of the level, consisting only of a single rail loop held up by hexagonal supports; this rail can be ridden on indefinitely in a circle, like a roller coaster.

During gameplay, if the player drops through the water, they can catch a glimpse of structures submerged deep underwater; later in the last level, the water level decreases, revealing the structures underneath as new level elements.

### Sound and Music

The game makes use of two effects: the slow-motion effects and underwater effects.

The underwater reverberation effect was an essential piece in the impression of being submerged; anyone who has gone swimming in a body of water knows the feeling of being submerged underwater, isolated by the muffled distortion of sound. Note that the music is distorted by the underwater effect, but not by the slow-motion effect: 

Keeping in line with a musical piece, the music and levels advance regardless of the player's performance in the game; partially because of this, the emotion of the music is set at a distance from the action of the game (*A Short Hike* is a good example of a soundtrack evoking a layer of sentimentality that layers *over* the action on the screen like a memory).

The music was composed on the second-last day of the jam; I knew I wanted to compose the music as late as possible in order to release all of the emotions of creating the game into the music. Because

<hr>

## Feedbacker

<div class = "image-grid">
    <div class = "image-grid-box"><img src="/assets/images/feedbacker_1.png" alt="Feedbacker Screenshot 1"></div>
    <div class = "image-grid-box"><img src="/assets/images/feedbacker_3.png" alt="Feedbacker Screenshot 3"></div>
</div>

### Concept

The theme of this game jam was "Loop", which I first associated with "music loops". More specifically, when I thought of music loops, I thought of it in two ways; the way electronic music revolved around variations of a central loop, and toys such as music boxes which would loop for as long as you play with the toy. In the end, I wanted to create a sort of "music toy/game hybrid". You could either approach it as a game with a goal (earn enough points to make it to the next level), or as a self-directed toy where the motivation is making musical loops and experimenting for its own sake.

The temporal laying down of beats is combined with the spatial component of moving the cursor.

<div class = "image-grid-box"><img src="/assets/images/feedbacker_3.png" alt="Feedbacker Screenshot 3"></div>

### Design

This was an aspect of the game that I

The player can lay one of six different sounds, which spawn their own beat patterns. Each of these layouts are designed such that the player must move their cursor in a different space each loop, with the result that each loop must 

One key characteristic of laying down beats is that it's quite difficult to place beats exactly on the downbeat; this is intentional, though this ended up being a criticized element of the game. The main intention was to encourage players improvise having to live with the mistakes in the loop history; otherwise, the average player would simply set down a "proper" 4/4 beat. Making the timing more difficult simultaneously allows for a higher skill ceiling when aiming for a high score. It's worth noting that, for some commentators, this aspect of the game immediately clicked and they described the game as if they were experimenting.

### Sound Design and Music

I wanted the music to mimic how the 