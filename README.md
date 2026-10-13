# Beat Jump Size + Jump Pads

A Serato DJ Pro MIDI map that lets you change the beat jump size with just two performance pads per deck: one steps the size down, the other steps it up. It also includes forward and backward beat jump pads, so you can change the size and jump from the same pads.

Made for the **DJM-S9** and **DJM-S11**.

## Why this exists

Some controllers, such as the DDJ-REV5, XDJ-RX3 and XDJ-XZ, let you change the beat jump size straight from the hardware, with pad colors that show where you are in the range. The DJM-S9 and DJM-S11 don't have this by default, so changing the jump size means going back to the laptop screen or the mouse.

This map brings that workflow to the DJM-S9 and DJM-S11. You can switch between a small nudge and a big phrase jump, and do the jump itself, without looking away from your hands or the mixer. The pad colors work the same way as on the controllers that have this built in, so the pads look and behave the way you'd expect.

## Features

- Step the beat jump size up and down with two pads per deck (Deck 1 and Deck 2)
- Forward and backward beat jump pads for each deck
- Pad colors that follow the behavior of controllers with this feature built in:
  - Pads stay lit while there is room to step further
  - The step-down pad turns off at the smallest size
  - The step-up pad turns off at the largest size
- Steps through beat jump size slots 0 to 10

## How it works

Each step pad checks which beat jump size is currently active and selects the next one. At either end of the range, pressing the pad does nothing and the pad's color goes to 0, so you can see you've hit the limit.

## Installation

1. Download the `.xml` file from this repository.
2. Copy it into your Serato MIDI mappings folder.
3. In Serato DJ Pro, select the map in the MIDI settings.

## Customizing

- **MIDI channels and notes:** The pad assignments are set in each `<control>` line (`channel` and `control`). Change them to match your pads.

## Notes

- Made for two decks (Deck 1 and Deck 2).
- Tested on DJM-S9 and DJM-S11.
- This is an unofficial community project and is not affiliated with Serato or AlphaTheta (Pioneer DJ).
- Issues and suggestions are welcome. Open an issue or a pull request.
