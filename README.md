# Thoughtworks Zed Theme

A theme for the Zed editor inspired by Thoughtworks branding, available in both **Dark** and **Light** modes.

## Installation

### Option 1: Local Installation (Recommended)

Copy the theme file to your Zed themes directory:

**macOS/Linux:**
```bash
mkdir -p ~/.config/zed/themes
cp themes/thoughtworks/thoughtworks-theme.json ~/.config/zed/themes/
```

**Windows:**
```powershell
mkdir -p $env:APPDATA\Zed\themes
copy themes\thoughtworks-theme.json $env:APPDATA\Zed\themes\
```

### Option 2: Use as Extension

1. Open Zed
2. Press `Cmd+Shift+P` (macOS) or `Ctrl+Shift+P` (Linux/Windows)
3. Type `Themes: Install Theme`
4. Select the `thoughtworks-theme.json` file from this repository

## Usage

After installation:

1. **Reload Zed** (quit and reopen, or press `Cmd+Shift+P` → `Zed: Reload`)
2. Press `Cmd+Shift+P` / `Ctrl+Shift+P` and type `Themes: Select Theme`
3. Choose **"Thoughtworks Dark"** or **"Thoughtworks Light"** from the list

## Themes

- **Thoughtworks Dark** - Dark mode with deep sea blue background
- **Thoughtworks Light** - Light mode with clean white background

## Configuration

You can also set the theme in your `settings.json`:

```json
{
  "theme": {
    "mode": "dark",
    "dark": "Thoughtworks"
  }
}
```

## Color Palette

| Color | Hex | Usage |
|-------|-----|-------|
| Onyx Black | `#000000` | Deep backgrounds |
| Talc White | `#ffffff` | Light backgrounds |
| Text Grey | `#666666` | Secondary text |
| Mist Grey | `#edf1f3` | Borders and separators |
| Wave Blue | `#003d4f` | Primary background (Dark mode) |
| Flamingo Pink | `#f2617a` | Errors, keywords, accents |
| Turmeric Yellow | `#cc850a` | Warnings, constants |
| Jade Green | `#6b9e78` | Success, comments, strings |
| Sapphire Blue | `#47a1ad` | Functions, info highlights |
| Amethyst Purple | `#634f7d` | Selection, special highlights |

## Author

- **zhongren.gu** ([@guzhongren](https://github.com/guzhongren))

## License

MIT
