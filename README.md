# Liquid Glass Theme

Apple-inspired **liquid glass / frosted glass** color theme for:

- Chenille AI IDE
- VS Code
- Cursor / other VS Code-compatible editors

## Themes

| Theme | Style |
|------|------|
| **Liquid Glass** | Light, frosted panels, system blue accents |
| **Liquid Glass Dark** | Dark glass, macOS-like night palette |

## Install

### Option A: VSIX (recommended)

1. Download `liquid-glass-theme-1.0.0.vsix` from [Releases](https://github.com/gg947919490-byte/liquid-glass-theme/releases)
2. In the editor:
   - `Ctrl+Shift+P`
   - Run **Extensions: Install from VSIX...**
   - Select the downloaded file
3. `Ctrl+K` then `Ctrl+T`
4. Choose **Liquid Glass** or **Liquid Glass Dark**

### Option B: Command line (Chenille)

```bash
chenille-ai --install-extension liquid-glass-theme-1.0.0.vsix
```

### Option C: VS Code CLI

```bash
code --install-extension liquid-glass-theme-1.0.0.vsix
```

## Optional settings

Add to `settings.json` for a smoother glass-like feel:

```json
{
  "workbench.colorTheme": "Apple Liquid Glass",
  "window.titleBarStyle": "custom",
  "editor.cursorBlinking": "smooth",
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.smoothScrolling": true,
  "workbench.list.smoothScrolling": true,
  "terminal.integrated.smoothScrolling": true,
  "editor.padding.top": 12,
  "editor.padding.bottom": 12
}
```

> Note: real OS-level blur is not available in VS Code-based editors. This theme approximates liquid glass with translucent colors, Apple-like accents, and smooth UI motion.

## Compatibility

- VS Code `^1.80.0`
- Chenille AI IDE
- Other VS Code forks that support standard color themes

## License

MIT
