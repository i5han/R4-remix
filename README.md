# R4 Remix: Development build

This is a development build of the PC port of **R4: Ridge Racer Type 4**.
The project is still a work in progress. Please report any issues you come
across on [GitHub Issues](https://github.com/i5han/R4-remix/issues).

---

## Getting started

1. **Download** the latest release zip from
   [github.com/i5han/R4-remix/releases](https://github.com/i5han/R4-remix/releases)
   and extract it.

2. **Add the disc.** Copy the *R4: Ridge Racer Type 4 US Version* (SLUS-00797)
   `.bin` and `.cue` files into the root folder, next to `r4r.exe`. Only the
   R4 disc is needed, not the bonus disc. The disc image should match the
   Redump MD5:

   ```
   bf1d92037b1b2be83b459c11f0b89eb6
   ```

3. **Run** `r4r.exe` by double-clicking it.

   > **Note:** The first time, Windows may show *"Windows protected your PC"*.
   > Click **More info**, then **Run anyway**. This happens because the
   > program is not signed; it does not happen again.

4. **Pick a look.** To change how the game looks, close the game and open
   `settings.exe`:

   | Mode                | What you get                                                 |
   |---------------------|--------------------------------------------------------------|
   | **Original**        | The PlayStation's original picture                           |
   | **Clean** (default) | The same graphics style, rendered clean and sharp            |
   | **Remaster**        | Remastered quality with path-traced lighting (needs an NVIDIA RTX 20 series or better card) |

   Press **Apply**, close it, and start `r4r.exe` again.

   You can also press **`~`** while playing to switch to the next mode
   without leaving the game.

   Remaster mode currently only supported in Helter Skelter, Wonderhill and
   Out of Blue and about 10 cars.

---

## Controls

### Controller

Any XInput controller is supported (Xbox controllers and most modern PC
pads), and so are the PlayStation 4 and 5 controllers - DualShock 4,
DualSense and DualSense Edge - over USB or Bluetooth.

| Xbox       | PlayStation | Action        |
|------------|-------------|---------------|
| Left stick | Left stick  | Steer         |
| A          | Cross       | Accelerate    |
| X          | Square      | Brake         |
| Y          | Triangle    | Change camera |
| LB         | L1          | Shift up      |
| RB         | R1          | Shift down    |
| Start      | Options     | Pause         |

### Keyboard

| Key                 | Action                      |
|---------------------|-----------------------------|
| Left / right arrows | Steer                       |
| Up arrow            | Accelerate                  |
| Down arrow          | Brake                       |
| C                   | Change camera               |
| W                   | Shift up                    |
| S                   | Shift down                  |
| Esc                 | Pause                       |
| ~                   | Switch graphics mode        |
| F11                 | Toggle full screen / window |
| Alt+F4              | Quit                        |

---

## Saving

The game saves to a memory card just as on the PlayStation. The memory
card is the file `save.bin` in your `Documents\R4R` folder.

Any existing memory card with an R4 save file should work as well
*(untested)*.

---

## Your settings

Your setting files are in the same directory, `Documents\R4R`.
Changing these files directly is not recommended; please use `settings.exe`.

---

## If something goes wrong

Send these files from the game folder:

| File               | What it is                                  |
|--------------------|---------------------------------------------|
| `r4r.log`          | Debug logs from the game                    |
| `config\BUILD.txt` | Which build this is                         |

…and mention what you were doing when it happened.

---

## Follow the project

Progress updates, videos and behind-the-scenes looks at the work:

- **X:** [@Ishanv9hj](https://x.com/Ishanv9hj)
- **YouTube:** [@ishanantony5301](https://www.youtube.com/@ishanantony5301)
- **Reddit:** [u/Sad_Egg_2313](https://www.reddit.com/user/Sad_Egg_2313/)
- **Patreon:** [i5han](https://www.patreon.com/cw/i5han)

---

## Support the project

If you're enjoying playing the game and would like to help the project keep
moving, you can support its development on
[Patreon](https://www.patreon.com/cw/i5han). Every bit of
support is hugely appreciated, and so is simply playing, sharing it with
friends and reporting what you find. 

For a one time contribution use the below link. Thank you!

<a href="https://www.buymeacoffee.com/ishanantoo" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me a Coffee" style="height: 60px !important;width: 217px !important;" ></a>
