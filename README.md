# Basket League

An early browser prototype from **RingGam Studio**.

Basket League is a basketball dribbling prototype built around physical ball and hand interactions. Use each mouse button for a different hand, control bounce height with tap and hold timing, and aim across your body for crossovers. This build focuses on handling and movement.

## Play

Play the prototype: https://ringgam-studio.upbeat-lime-9149.chatgpt.site/games/basket-league/

Studio domain: https://ringgam.com (DNS connection pending).

Run locally with Python 3:

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000/ in a desktop browser with a mouse and keyboard. JavaScript is required. WebGL is required.

## What is in this build

- Separate left- and right-hand dribbling
- Tap and hold timing for low or high bounces
- Cursor-directed crossovers
- Movement, facing control, and adjustable dribble settings

## Controls

| Input | Action |
| --- | --- |
| WASD | Move relative to your facing |
| Left / right mouse | Dribble with left / right hand |
| Tap / hold | Low quick bounce / high heavy bounce |
| Cursor | Aim the bounce; cross your body to cross over |
| Shift + mouse | Turn to face |
| R | Reset |
| H / M | Toggle help / sound |

This is a dribbling experiment. It does not include a full basketball match.

## Development status

Experimental prototype, shared as part of RingGam's early game development. The supplied HTML build was developed with an AI-assisted workflow including Claude. This repository publishes that build; it is not a claim that a commercial release or online service is available.

The games use browser-local storage for settings, saves, or records. Hosted web fonts may require an internet connection; fallback fonts are provided by the original build.

## Credits and permissions

RingGam Studio. Contact: founder1@ringgam.com.

No open-source license is granted for RingGam's original game code or artwork by this publication. Third-party software retains its own license; see `THIRD_PARTY_NOTICES.txt`.
