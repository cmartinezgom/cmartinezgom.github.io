---
layout: archive
title: "🚀 Junior Unity Programmer for Racerloop @ Maniac Panda Games"
excerpt: "Unity3D PC-mobile arcade racing game."
permalink: /portfolio/racerloop/
header:
  image: /images/Racerloop1.jpg
  teaser: /images/Racerloop1.jpg
gallery:
  - url: /images/racerloop/Racerloop2.jpg
    image_path: images/racerloop/Racerloop2.jpg
    alt: "Racerloop Screenshot"
  - url: /images/racerloop/Racerloop3.jpg
    image_path: images/racerloop/Racerloop3.jpg
    alt: "Racerloop Screenshot"
  - url: /images/racerloop/Racerloop4.jpg
    image_path: images/racerloop/Racerloop4.jpg
    alt: "Racerloop Screenshot"
  - url: /images/racerloop/Racerloop5.jpg
    image_path: images/racerloop/Racerloop5.jpg
    alt: "Racerloop Screenshot"
  - url: /images/racerloop/Racerloop6.jpg
    image_path: images/racerloop/Racerloop6.jpg
    alt: "Racerloop Screenshot"
  - url: /images/racerloop/Racerloop7.jpg
    image_path: images/racerloop/Racerloop7.jpg
    alt: "Racerloop Screenshot"
---
<!--
sidebar:
  - title: "   Role"
    image: /images/foto.jpg
    image_alt: "logo"
    text: "   Junior Unity Programmer"
  - title: "   Responsibilities"
    text: "   Implementing and designing different game systems, mainly on AI and the Synchronous Online Mode."
-->
![full](/images/Racerloop1.jpg){: full}

I worked on Racerloop at Maniac Panda Games as a Junior Unity Programmer.
<br><br>Racerloop is a PC 3D arcade zero-gravity racing game with ship-building components, developed using Unity (C#). We were a small remote-based team where I had to work both under lead directions and on my own.

I had contributions all along the game since the first prototypes, but my main work was in:
- **AI Players**: I implemented almost everything that had to do with AI ships. Their movement, pathfinding, progress tracking, obstacle avoidance, power-up usage, ideal racing lane, AI skill, fine tunning, testing...
<br>![full](/images/racerloop/ezgif-2-ce9b629215.gif){: .align-center}

- **Synchronous Online Game Mode**: I developed the first full-working prototype of the Synchronous Online Game Mode, this included working both on Unity Networking and UI. Implementing the Online Screen, the lobbies, remote connection, player synchronization, race progress, AI players and power up sync, reconnection handling...


- PlayFab: Implementation of PlayFab’s server initial login, user save and load along with their statistics, global leaderboards...

- Gameplay Systems: Player Orbital Camera with Spring Damper System, Ship’s hovering, Power Ups, Debug Renderer, AbstractInputs...

- Testing Automation: Automatic Testing of the game using Unity Test Framework.

- UI: Login, Leaderboards, Online and Lobby screens, as well as a general modular pop up error window.

- Math Utils: Several math scripts for needs such as working with 2D lines or projected positions for AI tracking and pathfinding.

- Offline Build: Worked on adapting back-end services from the server into the file system. Just for events with no internet connection.

- Hovering System: Developed the prorotype for the ship's hovering system.

- Dynamic Gravity System: Developed the dynamic gravity sistem for the zero-gravity races.

- Simple VFX: Simple shaders and particles.

{% include gallery.html caption="Images from the Racerloop.com webpage." %}

You can play the demo at the Racerloop webpage or Wishlist the game in the Epic Store:
https://store.epicgames.com/en-US/p/racerloop-4d3ab2