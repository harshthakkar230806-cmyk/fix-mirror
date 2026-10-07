# Mirror City

A Vercel-ready prototype for an original 1–6 player social adventure game.

## Run locally
1. Install Node.js 18+.
2. Open this folder in a terminal.
3. Run `npm install`
4. Run `npm run dev`
5. Open http://localhost:3000

## Deploy to Vercel
Import this project/repository into Vercel. The project is already structured with `package.json` at the root, so no Root Directory change is required.

## Current prototype
- Create room
- Join room by code
- 2–6 player room size
- Bot filling
- Character name/color/hat customization
- Original Oddville map
- Secret objectives
- Blue-token exploration
- Random city event
- Keyboard and mobile movement

## Next production step
For true cross-device multiplayer, connect the room/game state to Supabase Realtime. The current prototype intentionally keeps state local so it works immediately on Vercel without external credentials.
