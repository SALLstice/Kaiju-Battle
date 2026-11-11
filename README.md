# Kaiju Battle

Prototypes for a cooperative phone fighting game: 2–4 pilots jointly control one combining robot against a kaiju. Each pilot has a distinct role (Head commands, Legs position, Right arm attacks, Left arm blocks). Every action is a short microgame whose score drives everything downstream.

**Play the prototypes:** https://sallstice.github.io/kaiju-battle/

| Page | What it tests |
|---|---|
| `roles.html` | You're the sword arm. Attack on your own initiative into a guard only the Head can see. Newest. |
| `fight.html` | Prompted attacks, combos open the weak point, tap-charged Hyper Beam with exponential damage. |
| `cockpit.html` | All four stations on one screen against a scripted timeline. The original test. |

All single-player with AI teammates. Single-file HTML, no build step. Balance knobs live in the `K` object at the top of each page's script.

The full design doc lives in the Claude project for now.
