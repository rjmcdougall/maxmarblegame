# 🔮 Neon Marble Battle

A glow-in-the-dark stick-figure marble brawl. Four neon marbles — each holding a
different fighter — bounce around an arena, smashing into each other until only
one is left rolling.

## Play

Open `index.html` in any modern browser and hit **FIGHT!**

No build step, no dependencies — it's a single self-contained HTML file.

## Fighters

Each round randomly picks 4 fighters from the roster. Every type has its own look
and combat trait:

| Type | Look | Trait |
|------|------|-------|
| 🤖 **Robot** | Boxy body, antenna, glowing eye | Heavy tank — extra HP, mass, and impact damage |
| 🔫 **Gunner** | Stick figure braced with a machine gun | Fires homing neon rounds at the nearest enemy |
| 🦈 **Shark** | Torpedo body, dorsal fin, jagged teeth | Periodically lunges and bites for bonus damage |
| 🕴️ **Stick** | Classic tumbling stick figure | Fast, balanced all-rounder |

## Combat

- Marbles take damage from high-speed collisions (scaled by the attacker's type).
- Gunner bullets and shark bites add ranged / burst damage.
- Health bars sit at the top of the screen; a marble pops when it hits 0 HP.
- **Click / tap the arena** to drop a shockwave that shoves every marble away — a
  little player influence over the chaos.
- Last marble standing wins.

Built with plain HTML5 Canvas + JavaScript.
