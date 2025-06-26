# Codidactic Board Game

Codidactic is a programming-themed board game designed to teach coding concepts through visual programming blocks, cards, and interactive elements.

Codidactic transforms abstract programming concepts into tangible, interactive gameplay. Players learn fundamental coding principles.

- **Age Range**: 4+ years (with adult guidance).
- **Players**: 1-4 players.
- **Learning Level**: Beginner programming concepts.

- **Visual Programming**: Block-based programming similar to Scratch.
- **Mathematical Operations**: Addition, subtraction, multiplication, division, modulo.
- **Logical Operators**: Comparison operators (==, <, >, <=, >=).
- **Programming Functions**: Core functions like new(), screenshot(), redo(), undo(), erase(), select().
- **Problem Solving**: Algorithmic thinking through game mechanics.

## Game Instructions

[Instructions](https://codidactic.com/select) .

## /!\ IMPORTANT: Required Fonts

It’s important to have the required fonts installed for the components to display correctly.

Follow [FONTS.md](https://github.com/codidactic/board-game/blob/main/FONTS.md)

## Game Components

### Physical Components
- **Game Box**
- **Punchout Sheets**: 8 sheets containing programming blocks and game pieces.
- **Geometric Picture Cards**
- **Color Palette**

### File Structure
```
codidactic-game_cp/
|
├── FONTS.md                # Font documentation and resources
│
├── full-game-TGC/          # The Game Crafter production files
│   ├── box-*.png           # Game box designs
│   ├── punchout-*.png      # Punchout sheet faces/backs
│   ├── punchout-*-cut.svg  # Punchout cuts
│   └── cards/              # Drawing cards.
│
├── full-game-svg/          # Source SVG files for editing
│   ├── box-retail-*.svg    # Editable box designs
│   ├── punchout-*.svg      # Editable punchout sheets
│   └── cards*.svg          # All drawing cards (see layers)
│
├── programming-blocks.*    # Explanation of the programming blocks
└── color-palette.svg       # Game color scheme reference
```

## Printing & Manufacturing

### Print-on-Demand
The game is designed for print-on-demand services:
- **The Game Crafter**: Files in `full-game-TGC/` directory are ready for upload.
- **Custom Printing**: Use SVG files in `full-game-svg/` for modifications.

### File Formats
- **PNG**: High-resolution raster files for printing.
- **SVG**: Vector source files for editing and scaling.

## Customization & Modification

1. **Fonts**: Install required fonts. See [FONTS.md](https://github.com/codidactic/board-game/blob/main/FONTS.md).
2. **Graphics**: Edit SVG files in `full-game-svg/` directory using SVG-compatible software (Inkscape, Adobe Illustrator, web browsers).
3. **Colors**: Reference `color-palette.svg` for consistent theming.

## Online Resources

- **Website**: [codidactic.com](https://codidactic.com)
- **Games Selection and instructions**: [codidactic.com/select](https://codidactic.com/select)
- **YouTube**: [Codidactic Channel](https://www.youtube.com/@codidactic)
- **X**: [@codidactic](https://x.com/codidactic)
- **Facebook**: [@codidactic](https://www.facebook.com/profile.php?id=61559840279289)

## Contributing

This is an open-source educational game. Contributions welcome.
- **Variations**: Create themed versions.
- **Improvements**: Create new games.
- **Documentation**: Help improve instructions and educational materials.

## License

This work is licensed under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.

**Copyright © 2025 Alvaro Fernandez**

You are free to:
- Share and redistribute the material in any medium or format.
- Adapt, remix, transform, and build upon the material.
- Use for any purpose, including commercially.

**Attribution Required**

See [LICENSE.md](https://github.com/codidactic/board-game/blob/main/LICENSE.md) for full license details.

