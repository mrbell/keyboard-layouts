# Keyboard Layouts

This repository contains my personal keyboard layouts across multiple boards, built primarily with QMK and Oryx.

## Keyboards

### Lily58
Custom QMK firmware:
- OLED dashboard (master side)
- Animated typing pet (offhand side)
- Linux/Windows-focused layout

### Moonlander
Oryx-based configuration:
- Source export from Oryx (JSON + QMK files)
- Mac-oriented modifier behavior
- Primary reference layout

## Design Philosophy

- Prefer layers over reach
- Use thumb clusters heavily
- Keep layouts consistent across boards

## Structure

keyboard-layouts/
├── lily58/
├── moonlander/
└── builds/

## Flashing (Lily58)

qmk flash -kb lily58/rev1 -km mike -bl dfu
