# Claude Code Skills for Video Games

Research on tools and skills to help build games with Claude Code.

---

## Roblox

### Option 1: Roblox Studio MCP (Advanced)
Connect Claude Code directly to Roblox Studio so Claude can write Lua code and build games for you.

**What it does:**
- Create scripts (ModuleScript, Script, LocalScript)
- Execute Lua code directly in Studio
- Insert models into your game
- Build complete games with AI assistance

**Setup requires:**
- Linux/WSL
- Rust programming language
- Roblox Studio plugin installation

**Source:** [roblox-studio-mcp-claude-code on GitHub](https://github.com/ZubeidHendricks/roblox-studio-mcp-claude-code)

### Option 2: Lux Plugin (Easier!)
A free Roblox Studio plugin that works like Claude Code but inside Studio.

**What it does:**
- Reads your existing scripts and understands your project
- Makes changes directly (no copy-paste needed!)
- Shows you diffs before applying changes
- Can do up to 50 steps automatically per request

**How to get it:**
1. Create account at [openrouter.ai](https://openrouter.ai)
2. Add $1-5 credits
3. Install Lux from Creator Store
4. Paste your API key

**Cost:** Plugin is FREE. AI calls cost $0.02-$0.50 depending on task size.

**Source:** [Lux on Roblox DevForum](https://devforum.roblox.com/t/lux-cursorclaude-code-but-for-roblox-free-plugin/4207506)

---

## Geometry Dash

No official Claude Code skill exists for GD yet, but there are cool mods:

### Editor Mods Available
- **BetterEdit** - Makes the GD editor better ([betteredit.pro](https://betteredit.pro/))
- **Level Edit** - World Edit for Geometry Dash (fill operations!) ([geode-sdk.org](https://geode-sdk.org/mods/aceinet.level_edit))
- **Main Levels Editor** - Edit official levels ([GitHub](https://github.com/LatterRarity70/Main-Levels-Editor))

### AI Integration (Some Mods)
Some mod menus can connect to Claude API to:
- Generate trigger sequences from text descriptions
- Analyze level difficulty
- Suggest practice segments

---

## Unity (3D/2D Games)

### Unity MCP
Connect Claude Code to Unity Editor for AI-powered game development.

**What it does:**
- Generate C# code
- Debug errors with AI
- Automate game dev tasks
- Works in the running game too!

**Sources:**
- [Unity-MCP by IvanMurzak](https://github.com/IvanMurzak/Unity-MCP)
- [mcp-unity by CoderGamester](https://github.com/CoderGamester/mcp-unity)

---

## Godot (Free Game Engine - Great for Beginners!)

Godot is PERFECT for using with Claude because:
- Free and open source
- Human-readable config files
- GDScript is easy to learn
- Works great with AI assistance

### Godot Skills Available
Skills that make Claude an expert Godot developer:
- Scene tree architecture
- Physics systems
- GDScript patterns
- Full game development lifecycle

**Source:** [Godot Game Development Skill](https://mcpmarket.com/tools/skills/godot-game-development)

---

## Browser Games (HTML5)

### Built-in: web-artifacts Skill
Claude Code already has this! Create games that run in your browser.

**Just ask Claude to:**
- "Make a snake game"
- "Create a simple platformer"
- "Build a clicker game"

Works with HTML, CSS, JavaScript - no setup needed!

### Phaser.js
A popular game framework for browser games:
- Desktop and mobile
- Canvas and WebGL rendering
- Can export to YouTube Playables, Discord Activities, Steam, iOS, Android

**Source:** [phaser.io](https://phaser.io/)

---

## Pixel Art

### Pixel Plugin
Create pixel art using Claude and Aseprite!

**Features:**
- Natural language commands
- Animation support
- Retro color palettes
- Dithering effects
- Export for game engines

**Source:** [pixel-plugin on GitHub](https://github.com/willibrandon/pixel-plugin)

### Algorithmic Art Skill
Built-in skill for generative art with p5.js:
- Seeded randomness
- Flow fields
- Particle systems

---

## Other Cool Options

### Game Developer Subagent
A specialized Claude agent for game dev:
- Unity, Unreal Engine, web games
- Game mechanics & physics
- AI programming
- Performance optimization

**Source:** [game-developer subagent](https://www.buildwithclaude.com/subagent/game-developer)

### Claude Quest
Fun visualizer that shows Claude Code as an RPG:
- File reads = casting spells
- Bash commands = swinging swords
- Errors = taking damage

**Source:** [Claude Quest](https://michaellivs.com/blog/claude-quest)

---

## Quick Start Recommendations

| What You Want | Best Option |
|---------------|-------------|
| Roblox games | Lux Plugin (easiest) |
| 3D games | Godot + Claude Code |
| Browser games | web-artifacts skill (built-in!) |
| Pixel art | pixel-plugin |
| Quick prototypes | Just ask Claude to make HTML games |

---

## Useful Links

- [Awesome Claude Skills Collection](https://github.com/travisvn/awesome-claude-skills)
- [Claude Code Skills Docs](https://code.claude.com/docs/en/skills)
- [MCP Market Skills](https://mcpservers.org/claude-skills)