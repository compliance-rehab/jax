# jaxmakes.games - Jackson's Project Space

This is Jackson's creative coding workspace powered by Claude Code.

## About This Project
- **Creator:** Jackson (age 12)
- **Purpose:** Learning to build cool stuff with code
- **Approach:** Start simple, have fun, keep experimenting

## Project Structure
```
games/
├── index.html          # Homepage - lists all games
├── current-games/      # All games live here
│   └── [game-name]/    # Each game in its own folder
│       └── index.html  # The game itself
└── ideas/              # Brainstormed project ideas
```

## Creating a New Game

When Jackson asks you to build a new game:

### Step 1: Create the game
Create `current-games/[game-name]/index.html` with the game code.

### Step 2: Add a card to index.html
Add a card to the grid in `index.html`:

```html
<a href="current-games/[game-name]/index.html" class="card">
    <div class="card-icon">🎮</div>
    <div class="card-title">Game Name</div>
    <div class="card-desc">Short fun description</div>
    <div class="card-tag"><span class="tag">Game</span></div>
</a>
```

**Make it awesome:**
- **Icon**: Pick an emoji that fits the game vibe (🎮 🕹️ 🎯 🚀 🐱 💨 🧊 etc.)
- **Title**: The game's actual name
- **Description**: One catchy line about what it does
- **Tag**: Category (Game, Music, Puzzle, Simulator, Creator, Rhythm, etc.)

The game count updates automatically via JavaScript.

## Sound Effects & Music

**WHEN JACKSON ASKS FOR SOUND EFFECTS OR MUSIC:**
- **USE THE FREESOUND MCP SERVER** - It's configured in `.mcp.json`
- Search Freesound.org for high-quality audio
- Download audio files directly to the game folder
- NEVER use synthesized Web Audio API sounds

## Guidelines
- Every project should be FUN first
- It's okay to make mistakes - that's how we learn
- Start small, then add more features
- If something breaks, we fix it together

## Deployment

The site deploys automatically to Cloudflare Pages when you push to main.

Just push your changes - GitHub Actions handles the rest!
