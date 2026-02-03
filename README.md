# Wren Language Support for Sublime Text

This package provides language support for [Wren](https://wren.io/) via [wren-lsp](https://github.com/jossephus/wren-lsp).

## Features

- Diagnostics (syntax + semantic checks)
- Code completion
- Hover information
- Go to definition
- Find references
- Rename symbol
- Semantic tokens
- Document symbols (outline)
- Signature help
- Document highlights
- Code actions (quick fixes)
- Workspace symbols
- Folding ranges
- Selection range
- Inlay hints (type hints)

## Requirements

- [Sublime Text 4](https://www.sublimetext.com/) (build 4000+)
- [LSP](https://packagecontrol.io/packages/LSP) package (install via Package Control)
- [Wren](https://packagecontrol.io/packages/Wren) syntax package

## Installation

### Via Package Control (Recommended - when published)

1. Open Command Palette (`Cmd/Ctrl+Shift+P`)
2. Type "Package Control: Install Package"
3. Search for "Wren LSP"

### Manual Installation

1. Download/clone this repository
2. Copy/move the folder to your Sublime Text Packages directory:
   - macOS: `~/Library/Application Support/Sublime Text/Packages/`
   - Linux: `~/.config/sublime-text/Packages/`
   - Windows: `%APPDATA%/Sublime Text/Packages/`

### LSP Binary

The extension will auto-download the appropriate `wren-lsp` binary for your platform from GitHub releases if it is not already available. Alternatively, you can:

1. Download manually from [releases](https://github.com/jossephus/wren-lsp/releases)
2. Place it in your PATH, or
3. Set the path in settings (see below)

## Configuration

Access settings via: `Preferences > Package Settings > LSP-wren-lsp > Settings`

## Usage

1. Open a `.wren` file
2. LSP will automatically start the language server
3. Use LSP features via:
   - Command Palette (`Cmd/Ctrl+Shift+P`)
   - Right-click context menu
   - Keyboard shortcuts (see LSP package documentation)

## Troubleshooting

**LSP not starting?**
- Check the Sublime Text console (`View > Show Console`) for errors
- Ensure `wren-lsp` is in your PATH or set the correct path in settings
- Try disabling auto-download if behind a proxy

## License

MIT
