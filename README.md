# Synthwave Theme

[![Version](https://img.shields.io/badge/version-0.4.0-green.svg?style=flat-square&labelColor=2a2139&color=f92aad)](#)
[![Maintained](https://img.shields.io/maintenance/yes/2026.svg?style=flat-square&labelColor=2a2139&color=f92aad)](#)
[![PRs Accepted](https://img.shields.io/badge/accepting%20PR's-yes-x?style=flat-square&labelColor=2a2139&color=f92aad)](#)

> "Do you remember that endless summer back in '84? Cruising down the ocean highway with the top down, the wind in our hair and heads buzzing with neon dreams?"
>
> No? Well, neither do I, but with this experimental theme, we can pretend to go there.

Inspired by: [Synthwave VSCode Theme](https://github.com/robb0wen/synthwave-vscode)

Fork of [bbbenji/synthwave-hass](https://github.com/bbbenji/synthwave-hass), updated for modern Home Assistant (MD3 / HA 2026.4+).

---

## Installation

### HACS (recommended)

1. Add this repository as a custom repository in HACS:
   - **URL:** `https://github.com/bjrnptrsn/synthwave-theme`
   - **Category:** Theme
2. Install "Synthwave Theme" via HACS.
3. Restart Home Assistant.

### Manual

1. Copy `themes/synthwave.yaml` into your `<config>/themes/` directory.
2. Add the following to your `configuration.yaml`:
   ```yaml
   frontend:
     themes: !include_dir_merge_named themes
   ```
3. Restart Home Assistant.

### Important: use Light Mode

Although the theme looks dark, set Home Assistant to **Light Mode** in your profile. This is required for the climate card thermostat to render correctly.

---

## Screenshots

![Screenshot 1](https://i.imgur.com/DHbESc9.png)

![Screenshot 2](https://i.imgur.com/bLhZFHy.png)

![Screenshot 3](https://i.imgur.com/BcyjeJz.png)

![Screenshot 4](https://i.imgur.com/WXg2417.png)

---

## Contributions

Contributions are welcome! If you find any issues or have improvements to suggest, feel free to submit a pull request.
