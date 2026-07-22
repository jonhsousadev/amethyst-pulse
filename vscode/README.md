# Amethyst Pulse

Amethyst Pulse is a VS Code theme pack focused on readable contrast, clear syntax hierarchy, and a consistent purple/cream/orange visual identity.

This extension includes five variants:

- Amethyst Pulse Classic
- Amethyst Pulse Soft
- Amethyst Pulse HC
- Amethyst Pulse Light
- Amethyst Pulse Kanagawa

## Theme Variants

### Amethyst Pulse Classic

- Dark amethyst base for a balanced contrast profile.
- Good default for long coding sessions.

### Amethyst Pulse Soft

- Slightly lighter background than Classic.
- Reduced visual weight for users who prefer gentler dark themes.

### Amethyst Pulse HC

- True black background for maximum contrast.
- Best for users who want sharper separation between foreground and background.

### Amethyst Pulse Light

- Light theme variant for daytime or bright environments.
- Inverted color scheme with warm cream backgrounds.

### Amethyst Pulse Kanagawa

- Inspired by the Kanagawa palette (ukiyo-e and *The Great Wave*).
- Warm sumi-ink backgrounds with pastel, organic colors.
- Softer, desaturated tones while maintaining WCAG AA contrast.
- Uses oniViolet for keywords, crystalBlue for functions, springGreen for strings, and carpYellow for identifiers.

## Design Characteristics

- Keywords and flow control are highlighted with warm orange accents.
- Primary syntax groups use amethyst and cool blue tones.
- Foreground text uses a soft cream color for readability.
- UI tokens (selection, borders, guides, badges) follow the same palette for consistency.
- The Kanagawa variant uses the traditional Japanese palette for a calmer, more organic feel.

## Installation

### Option 1: Marketplace

Install from Visual Studio Marketplace:

https://marketplace.visualstudio.com/items?itemName=JonhSousa.amethyst-pulse

### Option 2: Manual install

1. Clone or download this repository.
2. Copy the project folder into your VS Code extensions directory:
   - Windows: `%USERPROFILE%/.vscode/extensions`
   - macOS/Linux: `~/.vscode/extensions`
3. Restart VS Code.

## How to Activate

1. Open the command palette (`Ctrl+Shift+P`).
2. Run `Preferences: Color Theme`.
3. Select one of:
   - Amethyst Pulse Classic
   - Amethyst Pulse Soft
   - Amethyst Pulse HC
   - Amethyst Pulse Light
   - Amethyst Pulse Kanagawa

## Recommended Fonts

For best visual results, use a programming font with ligatures, such as:

- JetBrains Mono
- Fira Code
- Cascadia Code

## Project Structure

- `themes/Amethyst-Pulse-color-theme.json` (Classic)
- `themes/Amethyst-Pulse-soft-color-theme.json` (Soft)
- `themes/Amethyst-Pulse-HC-color-theme.json` (HC)
- `themes/Amethyst-Pulse-Light-color-theme.json` (Light)
- `themes/Amethyst-Pulse-Kanagawa-color-theme.json` (Kanagawa)

## Contributing

Issues and pull requests are welcome. If you find any token mismatch or language-specific highlight issue, open an issue with:

- Language name
- Sample snippet
- Screenshot (optional)