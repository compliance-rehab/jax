# Cubi.Run - Platformer Game Documentation
**By Jackson Brown**

## Overview
A 100-level platformer game featuring Cubi, a cute cube character, battling through neon-themed worlds filled with unicorn enemies and epic boss battles.

## Controls

| Key | Action |
|-----|--------|
| Arrow Keys / WASD | Move left/right |
| Space / W / Up | Jump |
| Space (while falling) | Glide (level 5+) |
| Shift | Dash |
| X | Shoot laser |
| Down (in air) | Ground Pound |
| M | Toggle Music |
| U | Toggle Unlimited Lives |

## Game Features

### Core Mechanics
- **Coyote Time**: 8-frame grace period after leaving a platform to still jump
- **Jump Buffering**: 8-frame input buffer for jumps
- **Wall Sliding & Wall Jumps**: Slide down walls and jump off them
- **Dash**: Quick burst of speed (Shift key) with cooldown
- **Double Jump**: Unlocks at level 15
- **Ground Pound**: Slam down and create shockwave (Down key in air)
- **Shooting**: Laser gun to hit enemies and bosses (X key)

### Visual Effects
- Particle system (jumps, landings, coins)
- Animated starfield background
- Screen shake on damage
- Player trail effect
- Squash/stretch animations
- Glowing effects on coins/goal/portals
- Beat-synchronized visual pulse

### Player Character (Cubi)
- Cute cube with big eyes and rosy cheeks
- Eyes blink and track movement
- Squash on land, stretch on jump
- Trail effect when moving
- Catchphrases appear during actions

## Worlds & Themes

| Levels | Theme | Colors | Boss |
|--------|-------|--------|------|
| 1-25 | STEREO MADNESS | Neon Cyan | Sparkle Stomper |
| 26-50 | BACK ON TRACK | Neon Green | Rainbow Rager |
| 51-75 | POLARGEIST | Neon Magenta | Nightmare Prancer |
| 76-100 | DRY OUT | Neon Orange | Dark Unicorn Lord |

## Level Unlocks

| Level | Unlock |
|-------|--------|
| 5 | Glider |
| 10 | Moving Platforms |
| 15 | Double Jump |
| 20 | Disappearing Blocks |
| 25 | Boss Battle (Sparkle Stomper) |
| 30 | Ice & Lava hazards |
| 35 | Bounce Pads |
| 40 | Portals |
| 45 | Wind Zones |
| 50 | Boss Battle (Rainbow Rager) |
| 75 | Boss Battle (Nightmare Prancer) |
| 100 | Final Boss (Dark Unicorn Lord) |

## Enemies

### Mini Unicorns
- Appear from level 3+
- Patrol back and forth on platforms
- Rainbow comet trail when moving
- Defeated by: jumping on, shooting, or ground pound shockwave
- More unicorns spawn as levels progress (up to 6 per level)

### Boss Unicorns
Giant unicorn bosses appear at levels 25, 50, 75, and 100.

**Boss Behaviors:**
- **Level 25 - Sparkle Stomper**: Bounces up and down
- **Level 50 - Rainbow Rager**: Shoots homing projectiles
- **Level 75 - Nightmare Prancer**: Charges at player
- **Level 100 - Dark Unicorn Lord**: Multiple attack patterns, gets angry at half health

**Boss Features:**
- Full horse-like unicorn body with flowing rainbow mane and tail
- Glowing spiral horn
- Rainbow comet trail behind them
- Rainbow health bar
- Projectiles are rainbow orbs

## Music

The game features lofi chill music that changes per theme:
- Soft jazz chord progressions (7ths and 9ths)
- Mellow sine wave synths
- Warm bass lines
- Brush snare drums
- Vinyl crackle effects
- 68-78 BPM tempo

Press **M** to toggle music on/off.

## Sound Effects
- Jump sounds
- Coin collection
- Hit/damage sounds
- Dash whoosh
- Ground pound slam
- Win fanfare
- Glide sound

## Catchphrases

Cubi says catchphrases during actions:
- **Jump**: "WHEE!", "BOING!", "UP UP!", "YEET!"
- **Double Jump**: "DOUBLE!", "AGAIN!", "COMBO!"
- **Dash**: "ZOOM!", "FAST!", "NYOOM!"
- **Wall Jump**: "PARKOUR!", "NINJA!"
- **Coin**: "NICE!", "SHINY!", "BLING!"
- **Boss Hit**: "TAKE THAT!", "GOT EM!", "POW!"
- **Damage**: "OOF!", "OUCH!", "YIKES!"
- **Level Complete**: "WOOHOO!", "NAILED IT!", "GG!"

## Technical Details

### File Structure
```
my-first-platformer/
  index.html    - Complete game (HTML + CSS + JavaScript)
  platformer.md - This documentation
```

### Technologies Used
- HTML5 Canvas for graphics
- Web Audio API for procedural music and sound effects
- LocalStorage for progress saving
- Seeded random for level generation

### Pro Platformer Mechanics
The game implements professional platformer mechanics:
1. **Coyote Time**: Allows jumping for a few frames after walking off a ledge
2. **Jump Buffering**: Queues jump input before landing
3. **Variable Jump Height**: Jump height depends on how long button is held
4. **Responsive Controls**: Movement is snappy with appropriate deceleration

## Development History

This game was built iteratively with features added over multiple sessions:
1. Basic 100-level platformer with progressive unlocks
2. Visual improvements (particles, animations, cute character)
3. Pro mechanics (coyote time, wall jumps, dash)
4. Boss battles
5. Weapons (shooting, ground pound)
6. Geometry Dash neon themes
7. Lofi music system
8. Unicorn enemies with rainbow trails
9. Catchphrases and sound effects

## Tips

1. Use wall jumps to reach tricky platforms
2. Dash gives brief invincibility - use it to dodge
3. Ground pound damages nearby enemies with its shockwave
4. Collect all coins for bonus satisfaction
5. Bosses can be damaged by jumping on, shooting, or ground pounding
6. Press U for unlimited lives if you want to practice

---
*Game created by Jackson with Claude Code*
