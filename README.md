# xcsh-theme

F5XC theme for [OpenCode](https://github.com/opencode-ai/opencode) — Monokai Extended syntax highlighting with Claude Code-inspired UI chrome.

## Colors

- **UI chrome**: Purple primary, blue secondary, orange accent — derived from Claude Code's dark-daltonized palette
- **Syntax**: Monokai Extended (pink keywords, green functions, yellow strings, purple numbers, cyan types)
- **Diffs**: Standard green/red conventions

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
