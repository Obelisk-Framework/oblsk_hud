# Oblsk_hud Plugin

## Description
A placeholder HUD global element (health/armor/minimap, eventually). No real
readout yet, this just establishes the plugin, correctly wired into the
toggle/preferences mechanism by virtue of being a normal global-elements
registry entry. Real feature content is a separate future pass.

## Installation
This plugin loads as part of the `core` resource. After adding it under
`plugins/`, run `obelisk registry:generate` from `core/` on the host, then
restart `core` (or the whole server).
