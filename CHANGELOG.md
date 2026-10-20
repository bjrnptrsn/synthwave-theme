# Changelog

## 0.4.1 - 2026-10-20

- Sync with upstream bbbenji/synthwave-hass 0.4.0
- Add `mush-rgb-disabled` for Mushroom cards
- Add `ha-switch-thumb-*` tokens to fix disabled toggle color
- Add `ha-color-fill-disabled-quiet-hover` (neutral-20): an enabled, switched-off toggle no longer flashes near-white on hover/keyboard focus
- Deliberately NOT taken from upstream: `disabled-color`, `grey-color`, `state-inactive-color`, `state-climate-off-color` — they recolor the thermostat slider track/off state, which must keep the HA light-mode look
- Add `app-header-edit-background-color` for the dashboard edit mode header
- Add `ha-color-fill-neutral-quiet-hover`, `wa-color-neutral-fill-normal` and `ha-color-surface-low` (avoids the white light-mode default)
- Use `primary-text-color` for `ha-color-on-neutral-normal`
- Fix typo'd `ha-color-fill-neutral-quiet-active` token
- Add missing `rgb-md-sys-color-surface-variant`

## 0.4.0 - 2026-05-02

- Add MD3 compatibility for HA 2026.4+
- Fix white background on focused input fields
- Update card border radius to 28px
- Add RGB palette for MD3 transparency effects
- Fix expansion panels, climate card neon colors
