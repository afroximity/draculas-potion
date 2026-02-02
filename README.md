# Dracula's Potion 🧪

An ultra-high contrast dark theme for VS Code with enhanced Elixir/Phoenix support.

![Dracula's Potion Theme](https://raw.githubusercontent.com/afroximity/draculas-potion/main/images/preview.png)

## Features

- **Ultra-dark background** (`#080B0E`) - even darker than other Dracula variants for maximum contrast
- **Enhanced Elixir support** - atoms, modules, sigils, HEEx templates, and more
- **Beautiful bracket colorization** - rainbow brackets with Dracula colors
- **Semantic highlighting** - intelligent coloring based on language server data
- **Complete UI theming** - sidebar, terminal, panels, and more

## Color Palette

| Color | Hex | Usage |
|-------|-----|-------|
| 🟦 Cyan | `#8BE9FD` | Types, atoms, links |
| 🟩 Green | `#50FA7B` | Functions, success |
| 🟧 Orange | `#FFB86C` | Parameters, module attributes |
| 🩷 Pink | `#FF79C6` | Keywords, operators |
| 🟪 Purple | `#BD93F9` | Constants, numbers, modules |
| 🟥 Red | `#FF5555` | Errors, deletions |
| 🟨 Yellow | `#F1FA8C` | Strings, warnings |

## Elixir Syntax Highlighting

This theme provides specialized syntax highlighting for Elixir:

- **Atoms** - Cyan (`:atom`)
- **Modules** - Purple (`MyApp.Module`)
- **Module attributes** - Orange (`@moduledoc`, `@impl`)
- **Functions** - Green (`def`, `defp`)
- **Keywords** - Pink (`do`, `end`, `fn`)
- **Strings** - Yellow (`"string"`)
- **Sigils** - With appropriate coloring for regex, HEEx, etc.

## Installation

### From VS Code Marketplace

1. Open VS Code
2. Go to Extensions (⌘+Shift+X / Ctrl+Shift+X)
3. Search for "Dracula's Potion"
4. Click Install
5. Go to Preferences → Color Theme → Dracula's Potion

### From VSIX

1. Download the `.vsix` file
2. Open VS Code
3. Go to Extensions → ... → Install from VSIX
4. Select the downloaded file

### Manual Installation

1. Clone or download this repository
2. Copy to your VS Code extensions folder:
   - **macOS**: `~/.vscode/extensions/draculas-potion`
   - **Windows**: `%USERPROFILE%\.vscode\extensions\draculas-potion`
   - **Linux**: `~/.vscode/extensions/draculas-potion`
3. Reload VS Code

## Recommended Settings

For the best experience, add these settings to your `settings.json`:

```json
{
  "editor.fontFamily": "'JetBrains Mono', 'Fira Code', Menlo, monospace",
  "editor.fontLigatures": true,
  "editor.fontSize": 14,
  "editor.lineHeight": 1.6,
  "editor.cursorBlinking": "smooth",
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs": true
}
```

## Credits

Inspired by and based on:

- [Dracula Official](https://draculatheme.com/) by Zeno Rocha
- [Dracula At Night](https://github.com/bceskavich/dracula-at-night) by Billy Ceskavich
- [Dracula Elixir](https://github.com/joaopsramos/dracula-elixir) by João Ramos

## License

MIT License - see [LICENSE](LICENSE) for details.
