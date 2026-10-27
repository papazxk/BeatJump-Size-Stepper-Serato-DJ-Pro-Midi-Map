# BeatJump Size-Stepper: Serato DJ Pro MIDI Map for DJM-S11

_by IG: [@papazxk](https://instagram.com/papazxk) / TikTok: [@papazxk](https://tiktok.com/@papazxk)_

Change the beat jump size right from your pads. No mouse. No laptop.

Made for the **Pioneer DJ DJM-S11**.

## What it does

<img width="1280" height="720" alt="720export1_62e02cb0_v1" src="https://github.com/user-attachments/assets/d3be0995-1985-4b1c-962e-99b684adc0ad" />

Each deck uses four pads:

| Pad | Action |
|-----|--------|
| Size down | Steps to the next smaller beat jump size |
| Size up | Steps to the next bigger beat jump size |
| Jump back | Jumps backward by the current size |
| Jump forward | Jumps forward by the current size |

You change the size and jump from the same pads.

## Why this exists

Controllers like the XDJ-AZ, XDJ-XZ, XDJ-RX3 and DDJ-REV5 let you change the beat jump size from the hardware. Their pad colors also show where you are in the size range.

The DJM-S11 doesn't have this feature. To change the jump size, you have to use the laptop screen or the mouse.

This MIDI map brings the feature to the DJM-S11. Switch between a small nudge and a big phrase jump without looking away from your hands. The pad colors work like the controllers above.

## Features

- Two pads per deck to step the jump size up and down
- Two pads per deck to jump forward and backward
- Works on Deck 1 and Deck 2
- Pad colors match the controllers that have this feature built in:
  - Pads stay lit while you can still step further
  - The step-down pad turns off at the smallest size
  - The step-up pad turns off at the largest size

## How it works

Each step pad checks the active beat jump size and picks the next one.

At the smallest or largest size, the pad does nothing and its color goes to 0. That tells you that you've reached the limit.

## Installation

1. Download the `.xml` file from this repository.
2. Copy it into your Serato MIDI mappings folder.
3. Open Serato DJ Pro and go to the MIDI settings.
4. Select the map.

## Customizing

To change which pads are used, edit the `channel` and `control` values in each `<control>` line of the `.xml` file. Set them to match your pads.

## Notes

- Works with two decks (Deck 1 and Deck 2).
- Issues and suggestions are welcome. Open an issue or a pull request.

## Disclaimer

This is an unofficial, community-made project. It is not affiliated with or endorsed by AlphaTheta / Pioneer DJ or Serato. Use at your own risk.



