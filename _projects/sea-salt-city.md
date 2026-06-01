---
title: CHROMA+ELEKTRON
link: https://store.steampowered.com/app/1020550/CHROMAELEKTRON/
---

[Link (itch.io)](https://ericzdw.itch.io/sea-salt-city)

<div class = "image-grid">
    <div class = "image-grid-box"><img src="/assets/images/sea-salt-city_1.png" alt="Sea Salt City Screenshot 1"></div>
    <div class = "image-grid-box"><img src="/assets/images/sea-salt-city_3.png" alt="Sea Salt City Screenshot 3"></div>
</div>

Sea Salt City is a first-person shooter created in 10 days for Bigmode Game Jam 2026. It was voted #1 out of 647 entries in the Fun Category, and it was awarded as a finalist as the "Best Successor to Kingdom Hearts 2" (I've only played the first game).

As the solo developer of the game, I created the concept, game design, programming, visuals, sound effects and music.

### Concept

One issue with game jams is that, once the jam is over, nearly all games in one are immediately lost media that no one will play. Considering this, some questions going into the game jam included, "How can I create something that I can look back on positively? "Can I create something that I can come back to again?"

The theme of the game jam was "Slick", which immediately brings to mind two aspects: things that are "cool", such as movements in action games, expressions of skill; another is the slipperiness of a "slick" material. Combined with the questions posed above, and that a player likely only has ten minutes to play the game, my concept going into the beginning of the jam revolved around an action game condensed in a "song" format. Like a song, the game would be short, but you can come back to it again anytime you want to experience it again. The best songs are ones you can listen to at any time and be changed by it when it's done, for the rest of your day or for periods of your life. This is one aspect I really aspired to capture.

### Design

At first, in line with the theme of the jam, I wanted to create a loop that revolved around

Initially the game would be available to play in both first-person and third-person; the third-person view would eventually be cut.

The "song" format of the game extends to how progression works in the game. The game runs on a timer, with each level lasting 90 seconds. The music ramps up at each level as an indicator.

The game makes extensive usage of Unity's built-in HDRP water shader. While researching approaches to creating water suitable for what I needed, I stumbled across its documentation and was seriously impressed by its flexibility, ways to manipulate it and ways to interact with it through gameplay. While built for more realistic AAA applications, I wanted to push its limitations in a gameplay context and manipulate it in a more stylized, non-realistic manner.

### Movement

In Sea Salt City, the player can rotate in along all three degrees of freedom. The goal was to have unfettered rotational movement, to be able to frame targets in any orientation. However, if the camera was completely unlocked at all times, the game would quickly become unplayable. In order to achieve this while still having a sense of functionality, the game has two modes, a default mode that constraints the camera like a standard FPS, and a free mode that activates when the player rotates in the air, which unlocks all degrees of freedom. This was inspired by *Echo Point Nova*, an FPS that also allows for free range of motion, but only once the player moves the mouse in a vertical flipping motion. In this game, instead, rotation is mapped to keys (Q/E to roll, R/F to pitch). Combined with the implementation of inertia added to the rotational controls, the impression is closer to operating a camera rig on three separate axes, using the mouse for more precise adjustments.

### Visuals

I opted for a stark, white-blue palette, with a subtle blue tint. I made the water and the sky both a deep, frigid blue, and I chose white for most architectural elements, both to stand out against the water and sky, and also to evoke the water's erosion of structures (as if the architecture had been "bleached white"); I hoped to lightly tie together this "erosion" and subtle passage of time with the theme of memory.

### Sound Design

The game makes use of two effects: the slow-motion effects and underwater effects.

The underwater reverberation effect was an essential piece in the impression of being submerged; it's a universal experience to be submerged underwater for some length of the time, isolated by the muffling of sound.

### Music

The music was composed on the second-last day of the jam; I knew I wanted to compose the music as late as possible in order to release all of the emotions of creating the game into the music.

Like a musical piece, the music and levels advance regardless of the player's performance in the game; partially because of this, the emotion of the music is at a distance from the action of the game (*A Short Hike* is a good example of a soundtrack evoking a layer of sentimentality separate from the gameplay).