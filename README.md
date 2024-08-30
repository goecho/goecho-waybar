# goecho-waybar

A sleek, modern Waybar configuration for Fedora, focusing on simplicity and essential information display.

![screenshots](./preview.png)

## Font Requirements
`style.css` of this Waybar uses the following fonts and expects them to be installed:

- **FontAwesome**: Required for displaying various icons. You can install it via your package manager:
  - Fedora: `sudo dnf install fontawesome-fonts`

- **Roboto**: A clean, modern font that complements the overall design. Install it with:
  - Fedora: `sudo dnf install google-roboto-fonts`

- **Helvetica**: A classic sans-serif font used as a fallback.
  - This font is often pre-installed, but alternatives like Arial can be used if not available.

- **Sarasa Gothic SC**: A well-rounded font for CJK characters, ensuring readability across languages.
  - Fedora: `sudo dnf install sarasa-gothic-sc-fonts`

Make sure all these fonts are installed on your system to ensure the best appearance for the Waybar configuration.

## Installation
1. Copy the `waybar` directory into your `~/.config`.
2. Restart Waybar with `pkill waybar`, followed by `waybar & disown`.

> **Note:**  
> Ensure all required fonts (FontAwesome, Roboto, Helvetica, Sarasa Gothic SC) are installed on your system for the configuration to display correctly.

