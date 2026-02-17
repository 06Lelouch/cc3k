# CC3K - Dungeon Crawler

A roguelike dungeon crawler game built with C++20 modules.

## Features

- **5 playable races** — Shade, Drow, Vampire, Troll, Goblin, each with unique stats
- **9+ enemy types** — including Dragons, Merchants, Halflings, and more
- **Item system** — potions (heal, boost, poison, wound) and treasure drops
- **Procedural dungeon generation** — chamber-based floor layouts
- **Turn-based combat** — move, attack, or use items in 8 directions

## Building

Requires a C++20 compiler (g++ or clang++).

```bash
g++ -std=c++20 -fmodules-ts -o cc3k $(cat order.txt)
```

## Usage

```bash
./cc3k                      # uses default_floor.txt
./cc3k custom_floor.txt     # uses a custom layout
```

## Commands

| Action     | Input                                      |
|------------|--------------------------------------------|
| Move       | `no`, `so`, `ea`, `we`, `ne`, `nw`, `se`, `sw` |
| Attack     | `a <direction>`                            |
| Use potion | `u <direction>`                            |
| Quit       | `q`                                        |
| Restart    | `r`                                        |
| Freeze     | `f`                                        |
