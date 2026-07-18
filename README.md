# 🔮 Neon Marble Battle

> 🎮 **Max's first authored game — made at age 7.**

A glow-in-the-dark marble brawl. A dozen neon marbles — each holding a different
fighter — drop onto the arena floor and smash, shoot, bite, lash and summon clone
allies until only one squad is left rolling.

## Play

Open `index.html` in any modern browser and hit **FIGHT!**

No build step, no dependencies — it's a single self-contained HTML file.

## Fighters

Each round picks a dozen fighters from the roster. Every type has its own look
and combat trait:

| Type | Look | Trait |
|------|------|-------|
| 🤖 **Robot** | Boxy body, antenna, glowing eye | Heavy — extra HP, mass, and impact damage |
| 🔫 **Gunner** | Stick figure braced with a machine gun | Fires homing neon rounds at the nearest enemy |
| 🦈 **Shark** | Torpedo body, dorsal fin, jagged teeth | Periodically lunges and bites for bonus damage |
| 🕴️ **Stick** | Classic tumbling stick figure | Fast, balanced all-rounder |
| 🛡️ **Tank** | Hull on treads with a turret and barrel | Lobs slow, heavy cannon shells |
| 🐙 **Octopus** | Domed head, two eyes, eight tentacles | Whips its tentacles, hitting every nearby enemy |

## Combat

- Marbles fall under gravity and brawl on a glowing neon floor; high-speed
  collisions do damage (scaled by the attacker's type).
- Each fighter periodically **summons a clone of itself** as an ally. Allies share
  a team and never hurt each other, so the win is **last squad standing**.
- Gunner bullets, tank shells, shark bites and octopus lashes add extra damage.
- Health bars sit at the top of the screen; a marble pops when it hits 0 HP.
- **Click / tap the arena** to drop a shockwave that shoves every marble away — a
  little player influence over the chaos.
- Synthesized sound effects and a confetti winner celebration round it out. Use
  the 🔊 button (top-right) to mute.

Built with plain HTML5 Canvas + JavaScript — no libraries, no build step.
