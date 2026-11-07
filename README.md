> This repo is fully AI generated. Nothing is guaranteed to work. Use common sense. The owner uses this for personal purposes, and doesn't care about the quality of the code.

# blitz

Keyboard-driven infinite-canvas Wayland compositor on `neuswc`. Hevel's invisible canvas fused with Hyprland-grade keybind configurability, in one hackable C file.

## Build

Needs `neuswc`, `neuwld`, `wayland`, `libxkbcommon`, `pkg-config`, and `stb_image.h` next to the sources.

```sh
cp config.def.h config.h   # or write your own config.h
make
sudo swc-launch ./blitz
```

## Controls

Super+Return terminal (`hst`), Super+r menu (`neumenu_run`), Super+q kill, Super+f fullscreen, Super+arrows scroll, Super+period center, Super+Tab next, Super+equal/minus zoom, Super+0 zoom reset, Super+Shift+q quit. Super+left-drag move, Super+right-drag resize.
