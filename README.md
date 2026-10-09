<p align="center">
  <img src="icon.png" width="120" alt="VAMPULSE">
</p>

<h1 align="center">VAMPULSE</h1>

<p align="center">
  A fast, momentum-driven arena shooter.<br>
  Quake/CPMA movement, grapple swinging, a ball form you ram people with, portals,<br>
  and vampiric lifesteal on every hit.<br>
  <strong>Keep moving — standing still gets you punished.</strong>
</p>

<p align="center"><a href="https://vampulse.com">vampulse.com</a></p>

---

## The Arena

- **Movement:** Quake 3 / CPMA strafe-jumping and air control, a dash, and a grapple you swing on.
- **Ball form:** roll at speed, ram bodies out of the way, slam down from the air.
- **Guns:** lightning beam, railgun, rocket launcher, plus melee. Every hit heals you (lifesteal).
- **Portals** you place and shoot, walk and throw things through.
- **Ordnance:** a dozen rack weapons on pads around the map (Seeker Missile, Wildfire, Rebound Bomb, Arc Mortar,
  Sawblade, Frost Viper, Hydra, ...).
- **Ultimates:** charge up, then duel.
- **Bots** from Easy to Insane+5, their play tuned by self-play tournaments.
- **Match rules** the host sets per ability: on/off, damage, lifesteal and cooldowns.

## Built to run fast

- A custom fork of Godot 4.7, with all game code written in C++.
- Every release is benchmarked frame for frame against **Quake3e**: the busiest thread's work and the GPU's work per
  frame have to stay at Quake 3's level.
- The stress test is the worst case: 200 bots in one spot, all firing.
- Rendering, physics (Jolt) and game logic each run on their own threads.
- A handful of shared shaders, all compiled before you play: nothing stutters the first time you see it.
- Mesh detail levels and culling keep the triangle count within budget in a full fight.
- Dedicated servers with accounts.

## Download

Grab the latest build from the **[Releases](../../releases)** tab: the Windows or Linux zip. Unzip it and run
`vampulse.exe` or `vampulse.x86_64`. The game offers newer builds on its title screen and updates itself.

## Play together

Click **Multiplayer** on the title screen. Servers on your network show up in the list; you can also type an
address. **Host** starts your own.

## Report a bug

Found something broken? Open an issue on the **[Issues](../../issues)** tab. Search first, then hit **New issue**
with steps to reproduce, your OS and the build number.
