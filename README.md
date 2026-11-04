# Cardboard Lake

A self-contained, top-down cardboard boat battle game. Open `index.html` in a modern browser, or enable GitHub Pages to play online.

## Controls

- WASD or arrow keys: move.
- Mouse: aim; hold left click to fire.
- 1 / 2 / 3: cannonball, chainball, or grapeshot.
- Shift or Space: dash, with a 4.5-second cooldown.
- Esc: pause or resume a solo game.

Choose light, medium, or heavy boats. Collect repair chests for up to 35 health. Watch for whirlpools and kraken strikes.

## Publish the game

In this repository, open **Settings → Pages**. Select **Deploy from a branch**, choose **main** and **/(root)**, and save.

After GitHub finishes publishing, the game will be available at:

[https://jsquiggles.github.io/cardboard-lake/](https://jsquiggles.github.io/cardboard-lake/)

[GitHub Pages setup documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

## Multiplayer

Solo play works without a server. The optional multiplayer mode requires a compatible WebSocket relay and the same room code for all players. When playing from an HTTPS website, use a publicly reachable **wss://** relay; an unsecured **ws://** classroom relay is intended for the locally opened HTML game on the same network.
