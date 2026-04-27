# Project Context

## Definitions
- Tone = Capture + IR pair
- Favorite = user-saved Tone
- Pre-Loaded Tone = Tone loaded on startup
- Channel = pinned Tone slot

## Current Features
- Favorites (save, dedupe, display)
- Folder memory (Capture vs IR)

## Architecture
- Favorites are the core data model
- Pre-Loaded Tone is independent from Favorites
- Folder memory is already implemented

## Constraints
- No DSP changes
- Minimal UI additions
- Focus on usability and fast startup

## Roadmap
1. Favorites: load selected tone
2. Pre-Loaded Tone: auto-load last tone
3. Channels: 3-tone UI slots (future)

## Reference
Full roadmap:
https://github.com/peott-fr/NeuralAmpModelerPlugin/issues/1