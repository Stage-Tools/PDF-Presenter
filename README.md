# PDF Presenter

PDF presentations for live events.

PDF Presenter is a Windows application that drives up to two output screens from one control window: a Presentation output for the audience and a Speaker output for the presenter. It can be controlled remotely from a phone, tablet or computer, and from Bitfocus Companion. Version 2 replaces the single-file browser version (v1.0) and works completely offline.

## Features

- Two independent outputs — Presentation and Speaker — each on the display you choose, fullscreen or windowed
- Speaker view with current slide, next slide, notes, elapsed time, clock and messages from the control room
- PDF library — open a whole folder, subfolders included, with live updates and filter
- Black — instantly black out the Presentation output
- Freeze — hold the audience picture while you change slide or switch PDF
- Crossfade between slides with adjustable duration
- All-slides grid and jump by typing a slide number
- Per-slide notes, saved automatically next to the PDF
- Remote control — speaker web page (previous / next), full operator web page, HTTP API for Companion and other control software
- Detection of a PDF replaced or modified while the show is running, with reload
- Keyboard shortcuts in every window, so a presentation clicker works on the outputs too

## Use cases

- Conference and corporate presentations with a separate speaker confidence monitor
- Several speakers in one session, each with their own PDF, switched without the audience seeing it
- Feeding a video mixer or media server input with a clean presentation output
- Remote slide control from the stage or from a Stream Deck through Companion

## System requirements

- Windows 10 / 11 (64-bit)
- One display is enough to run it; two or three for separate control, presentation and speaker screens
- Network only for remote control — no internet required

## Technical notes

- Fully offline: the PDF engine is bundled with the application
- A fullscreen output never opens on the display that holds the control window
- Remote control uses port 8080 by default; Windows Firewall asks for network permission the first time
- The Portable version unpacks to a temporary folder at each launch, so Windows may ask for network permission every time; the installed version does not
- Updating: run the new Setup over the existing installation; settings are kept

## Version

See the Releases tab for the full version history.

---

Made by Riccardo Nessi — [Stage Tools](https://stage-tools.github.io/stagetools/)
