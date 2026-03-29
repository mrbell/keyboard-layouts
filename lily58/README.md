# Lily58 Layout

## Features

- OLED dashboard (master)
- Typing dog (offhand)
- Mod-tap on Z and /
- Layer-based navigation

## OLED

Master:
- Layer
- Mods
- WPM

Offhand:
- Dog animation (idle, typing, fast, caps)

## Build

qmk compile -kb lily58/rev1 -km mike

## Flash

qmk flash -kb lily58/rev1 -km mike -bl dfu
