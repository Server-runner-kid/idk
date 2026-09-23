# Rooftop Rumble instructions

You are editing an existing single-file HTML5 Canvas game.

## Files

- Main game file: `Rooftop-Rumble-Parkour-Tag.html`
- Read-only networking reference: `elementa-reference.html`
- Full requirements: `MASTER-PROMPT.md`

Do not modify `elementa-reference.html`.

## Rules

- Do not rebuild the game from scratch.
- Preserve unrelated working features.
- Use vanilla HTML, CSS, JavaScript, HTML5 Canvas, and optional Web Audio API only.
- Do not add frameworks, build tools, npm packages, external art, paid services, secret keys, or external asset requirements.
- Keep the game self-contained in one HTML file whenever practical.
- Make small, focused changes.
- Use Git before major changes.
- Do not remove a feature simply because it is difficult.
- Do not claim browser, keyboard, multiplayer, or WebRTC testing happened unless it was actually tested.
- Check for JavaScript syntax errors and obvious undefined references after edits.

## Controls

Player 1: A left, D right, W jump, S down/slide/slam.
Player 2: J left, L right, I jump, K down/slide/slam.
Player 3: Left/Right/Up/Down arrows.
Player 4: G left, U right, Y jump, H down/slide/slam.

Dash must use double-tap left/right, not a separate default dash key.

## Development order

1. Local movement, collision, game modes, 2–4 player reliability, names, HUD, maps.
2. Only after local mode is stable: PeerJS/WebRTC lobby using Elementa as reference.
3. Finally: host-authoritative online gameplay synchronization.

## Output

When editing:
- State files to change.
- Make actual edits through the agent.
- Explain briefly what changed.
- Give a short browser test checklist.