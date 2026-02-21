# 🍄 Mycelium — VSCode Theme

A dark theme with deep navy backgrounds and indigo bioluminescence — born from the [Avant Media](https://avantmedia.uk/) palette, designed for long coding sessions.

## Color Palette

| Role       | Color      | Hex       |
| ---------- | ---------- | --------- |
| Background | Deep Navy  | `#0F0F23` |
| Surface    | Dark Slate | `#1A1A2E` |
| Panel      | Midnight   | `#0A0A1A` |
| Border     | Gray 700   | `#374151` |
| Primary    | Indigo     | `#6366F1` |
| Text       | Cool Gray  | `#D1D5DB` |

## Status Colors

| Role    | Color | Hex       |
| ------- | ----- | --------- |
| Error   | Red   | `#EF4444` |
| Warning | Amber | `#F59E0B` |
| Success | Green | `#22C55E` |
| Info    | Light Indigo | `#818CF8` |

## Syntax Highlighting

| Token         | Color      | Hex       |
| ------------- | ---------- | --------- |
| Keywords      | Purple     | `#C084FC` |
| Functions     | Indigo     | `#6366F1` |
| Strings       | Emerald    | `#34D399` |
| Types/Classes | Cyan       | `#22D3EE` |
| Numbers       | Amber      | `#FBBF24` |
| Properties    | Light Blue | `#93C5FD` |
| Parameters    | Rose       | `#FCA5A5` |
| Tags (HTML)   | Red        | `#F87171` |
| Comments      | Gray 600   | `#4B5563` |

## Running

```
code --extensionDevelopmentPath=$(pwd)
```

## Installation

### From VSIX

1. Download the `.vsix` file
2. Open VSCode
3. `Ctrl+Shift+P` → "Extensions: Install from VSIX..."
4. Select the downloaded file
5. `Ctrl+Shift+P` → "Preferences: Color Theme" → Select **Mycelium**

### From Source

1. Clone this repo into `~/.vscode/extensions/`
2. Restart VSCode
3. Select the Mycelium theme

## Building

```bash
npm install -g @vscode/vsce
vsce package
```

## License

MIT © [Avant Media Ltd](https://avantmedia.uk)
