---
layout: archive
title: "🚀 Junior Unity Programmer for Racerloop @ Maniac Panda Games"
excerpt: "Unity3D PC-mobile arcade racing game"
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
[**Web** <i class="fa-solid fa-globe"></i>](https://www.racerloop.com/) ||| [**Trailer** <i class="fa-brands fa-youtube"></i>](https://youtu.be/fLouIlEPH-s) ||| [**Epic Store** <i class="fa-solid fa-tag"></i>](https://store.epicgames.com/en-US/p/racerloop-4d3ab2)



<div style="width: 70%; margin: auto;">
  <img src="/images/Racerloop1.jpg" alt="full" style="display: block; margin: auto; width: 100%;">
</div>

I worked on **Racerloop** at Maniac Panda Games as a **Junior Unity Programmer**.
<br><br>Racerloop is a **PC/mobile 3D arcade zero-gravity racing game** with ship-building components, developed using **Unity (C#)**. We were a small remote-based team where I had to work both under lead directions and on my own.

<div style="width: 70%; margin: auto;">
  <img src="/images/racerloop/highlightedbetacreditsENG.png" alt="full" style="display: block; margin: auto; width: 100%;">
</div>
<br>
I had contributions all along the game since the first prototypes, but **my main work** was in:

**AI Systems**:
- **AI Movement**: Both using WayPoints and an AI track with ahead target position.
- **AI Track**: Made up by Links and Nodes, with UV coordinates. AI Track creation depending on track's curvature.
- **AI and Player position Tracking inside AI Track**: Using custom geometry functions. Ex: Calculating nearest point, calculating a projected point in the AI Link...
- **AI Look Ahead Position**: Target position for the AI movement, creating and ideal Lane that had an offset depending on AI skill.
- **Ideal Racing Lane**.
- **AI Player ideal inputs**: Such as ideal throttle, steering, brake, turbo... depending on AI track, ship parameters and AI Skill.
- **AI Respawn logic**.
- **AI Obstacle Avoidance and Crash Prediction**.
- **AI Power Up usage logic**.
- **AI Graphic Debug Systems**.
- **AI Manual fine tunning**.

<div style="width: 50%; margin: auto;">
  <img src="/images/racerloop/ezgif-1-b6f170d22e.gif" alt="full" style="display: block; margin: auto; width: 100%;">
</div>
<br>
**Synchronous Online Game Mode**: Developed the first full-working prototype.
- Using **Unity Networking Services, Unity Netcode for GameObjects, Unity Lobbies, Unity Relay, and both Client and Server RPCs**.
- Adapted the offline game to have all the **online workflow and logic**.
- Implemented online mode **UI**: This included the Online Screen, Lobby screen...
- **Game Synchronization between Players**: Ship type selection, Player position, AI position, race progress, race start, power up usage, race finish, Player's and AI's health turbo and shield...
- **Online Inputs**.
- **Missile Power Up Online Pool and Position sync**.
- **Online Event Propagation logic**.
- **Online Reconnection handling**.
- **Online playtest and debuging**.

<div style="width: 50%; margin: auto;">
  <img src="/images/racerloop/ezgif-3-2279a6cc27.gif" alt="full" style="display: block; margin: auto; width: 100%;">
</div>

<br>
**Gameplay Systems**: Implemented several gameplay systems, mainly in the first design fase.
- Customizable **Player Orbital Camera with Spring Damper System**.
<div style="width: 50%; margin: auto;">
  <img src="/images/racerloop/ezgif-2-50eed2125b.gif" alt="full" style="display: block; margin: auto; width: 100%;">
</div>
- Customizable **Ship’s hovering** prototype.
<div style="width: 50%; margin: auto;">
  <img src="/images/racerloop/ezgif-2-6595f0e17e.gif" alt="full" style="display: block; margin: auto; width: 100%;">
</div>
- Customizable **Dynamic Gravity System**.
<div style="width: 50%; margin: auto;">
  <img src="/images/racerloop/ezgif-5-32998c4530.gif" alt="full" style="display: block; margin: auto; width: 100%;">
</div>
- **Power Up System** and some **Power Ups logic**.
- **Graphical Debug Renderer** for some features.
- **Abstract Inputs** for Input Controller: Agnostic inputs that worked for controller, gamepad, keyboard, etc.

<br>
**Testing Automation**:
- **Automatic Testing** using **Unit Test Framework**.
- **Automatic Testing** from command line for automatic builds in **Jenkins**.
- Debugging, testing and code refactoring all around my own work and others'.
<div style="width: 50%; margin: auto;">
  <img src="/images/racerloop/racerlooptests.png" alt="full" style="display: block; margin: auto; width: 100%;">
</div>

<br>
**UI implementation**: Implemented some UI screens, such as:
- First **Register and Login** screen: Using PlayFab API.
- **Leaderboards** screen: Both local and global using a PlayFab server.
- **Online Menu and Lobby** screens: Search game, create game, join lobby with code or by name, lobbies list...
- Customizable **modular Pop-up Error Window**.

<br>
**Math Utils**: Several math scripts for game needs, such as:
- Calc Nearest Point in Segment.
- Calc Intersecting point between lines.
- Calc Projected point in certain area.
- 2DLine class.

<br>
**Third Party APIs implementation**:
- PlayFab API: Register, login and logout from PlayFab server, PlayFab metrics and stats load and save from server...
- Unity Networking Services.
- Unity Netcode for GameObjects.
- Unity Lobby.
- Unity Relay.

<br>
**Simple VFX**:
- Simple **Shaders**: First Hovering force, Shield...
- Simple **Particle Systems**: First kinetic lines for movement effect in the camera, crash particles...

<br>
**Offline Build**:
- Initial work with offline services that insted of loading from the server worked from files.
- Just for events where there was no internet (like an Expo)
- Setting it from the command line.

<br>

{% include gallery.html caption="Images from the Racerloop.com webpage." %}

You can play the demo at the Racerloop webpage or Wishlist the game in the [Epic Store](https://store.epicgames.com/en-US/p/racerloop-4d3ab2).