# Minimal Kiwi for Starship

A [Starship](https://starship.rs) prompt preset that brings the colors of the **Minimal Kiwi** VS Code theme to your terminal.

It's built on Starship's official [Gruvbox Rainbow](https://starship.rs/presets/gruvbox-rainbow) preset and keeps the same powerline layout, modules and icons, recolored with the Minimal Kiwi palette.

## Requirements

- [Starship](https://starship.rs)
- A [Nerd Font](https://www.nerdfonts.com) set as your terminal font, for the icons and powerline separators

## Installation

Copy the preset to your Starship config:

```sh
cp minimal-kiwi.toml ~/.config/starship.toml
```

To try it without replacing your current config, run this in a new shell:

```sh
export STARSHIP_CONFIG=/path/to/minimal-kiwi.toml
```

## Palette

| Segment | Color | Hex |
|---|---|---|
| OS / username | Kiwi green | `#82cd64` |
| Directory | Yellow | `#ffcb6b` |
| Git | Light blue | `#89ddff` |
| Languages | Lavender | `#b9adff` |
| Docker / conda / pixi | Dark gray | `#2b2b2b` |
| Time | Editor background | `#212121` |
| Prompt (success / error) | Green / red | `#82cd64` / `#ff6969` |

To change colors, edit the `[palettes.minimal_kiwi]` block in `minimal-kiwi.toml`.

## Credits

- **Minimal Kiwi** VS Code theme by [Pranjal Barnwal](https://github.com/pranjal-barnwal): [pranjal-barnwal/minimal-kiwi](https://github.com/pranjal-barnwal/minimal-kiwi). All colors in this preset come from that theme.
- **Gruvbox Rainbow** preset from the [Starship](https://github.com/starship/starship) project, which this preset uses for its layout.
