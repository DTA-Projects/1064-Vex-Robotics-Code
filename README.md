# 1064 VEX Robotics Code

Robot code for **North High Robotics — team 1064**, written in C++ for the VEX V5 platform using VEXcode Pro (V5).

This repository collects the programs I wrote across several seasons and teams. Currently active: **1064G (2025–2026)**. The older **1064X (2023–2025)** code is outdated and contains known errors, but it documents the growth of the codebase from season to season.

## Projects

| Folder | Team | Season | Notes |
| --- | --- | --- | --- |
| `1064G-PushBack` | 1064G | 2025–2026 | Main competition program (Push Back), used until March 2026 |
| `1064-Worlds` | 1064G | 2025–2026 | Final version — the end-state of `1064G-PushBack` |
| `1064-Create` | 1064G | 2025–2026 | New-robot variant of `1064G-PushBack` for the CREATE Foundation ruleset |
| `1064A-Code` | 1064A | 2025–2026 | Basic starter code written to help another team |
| `1064B-PushBack` | 1064B | 2025–2026 | Push Back variant |
| `1064X-High` | 1064X | 2023–2025 | Older code; known errors, historical value |

## Layout

Each project folder is a standard VEXcode Pro V5 template:

- `src/main.cpp` — the user-written program
- `include/vex.h`, `makefile`, `vex/` — VEX SDK boilerplate (identical across all projects)

## Building

Open any project folder in **VEXcode Pro (V5)** and build. Build artifacts are written to each project's `build/` folder, which is excluded from version control via `.gitignore`.

## Status

Revamped from the original backup repository: removed committed build artifacts, added `.gitignore` and this README, and re-published under a fresh history on a new account.