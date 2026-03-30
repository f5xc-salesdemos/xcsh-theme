# xcsh-theme

F5XC theme for [OpenCode](https://github.com/opencode-ai/opencode) — Claude Code-style syntax highlighting with F5 brand UI chrome.

## Colors

- **UI chrome**: F5 brand palette (eggplant primary, river secondary, tangerine accent, bay borders)
- **Syntax**: Claude Code / One Dark style (purple keywords, blue functions, green strings, orange numbers, yellow types, cyan operators)
- **Diffs**: Standard green added / red removed with subtle dark backgrounds

### Syntax Palette (dark mode)

| Token | Color | Hex |
|-------|-------|-----|
| Keywords | Purple | `#c678dd` |
| Functions | Blue | `#61afef` |
| Strings | Green | `#98c379` |
| Numbers | Orange | `#d19a66` |
| Types | Yellow | `#e5c07b` |
| Variables | Coral | `#e06c75` |
| Comments | Gray | `#5c6370` |
| Operators | Cyan | `#56b6c2` |
| Punctuation | Light gray | `#abb2bf` |

## Installation

### Custom theme (any OpenCode install)

Copy the TUI theme to your OpenCode config directory:

```bash
mkdir -p ~/.config/opencode/themes
cp tui/f5xc.json ~/.config/opencode/themes/f5xc.json
```

Then select "f5xc" from the theme picker in OpenCode.

### Set as default

Create or edit `~/.config/opencode/tui.json`:

```json
{
  "theme": "f5xc"
}
```

## Files

| File | Purpose |
|------|---------|
| `tui/f5xc.json` | Terminal UI theme (40+ color properties) |
| `desktop/f5xc.json` | Desktop app theme (palette + overrides) |

## License

MIT
