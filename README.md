# OVERWRITE

A free browser arena shooter where every wall is destructible. Three teams race to crack a Cache, grab the Data Core and upload it, while the arena comes down around them.

**Play:** open `index.html` in Chrome, Edge, Firefox or Safari on a computer, phone or tablet, or on Xbox in Microsoft Edge.

## Features
- Six destructible arenas: Meridian Downtown, The Stackyard, Harbor Nine, Glitch Galleria, Loop Line, Test Site Seven
- Three builds (Light, Medium, Heavy) with balanced weapons, abilities and frag grenades
- Solo against bots (Easy to Expert), or party up with friends using a 5-letter code or invite link
  - Friends vs Bots: up to 3 friends on one team
  - Custom match: up to 9 players, pick teams, bots optional with per-team difficulty
- Gunsmith: five optics and five finishes per weapon; character customization
- Mouse and keyboard, controller, or touch screen (phones and tablets, played sideways). Keyboard and controller are fully remappable

## Controls (defaults)
WASD move · Mouse look · Left click fire · Right click aim · Shift sprint · Space jump · C/Ctrl crouch (slide while sprinting) · R reload · E interact · F throw the core · Q ability · G grenade · V melee · Tab scoreboard · Esc pause. Change them in the Controls tab.

Touch: drag on the left to move (push all the way forward to sprint), drag on the right to look, and use the on-screen buttons. The fire button also aims while you drag it.

## Hosting notes
- Single file, no build step. Needs an internet connection for the 3D library (three.js), fonts and party connections (PeerJS).
- Party play is peer-to-peer: the host's browser runs the match. The host should keep the game tab in front.

## Credits
- [three.js](https://threejs.org) (MIT License)
- [PeerJS](https://peerjs.com) (MIT License) and its free public connection server
- Fonts: Saira, Saira Extra Condensed and JetBrains Mono via Google Fonts (SIL Open Font License)
- Everything else, including all textures, models, maps and sounds, is generated in code.
