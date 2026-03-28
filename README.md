# Rofi-mixer

Rofi-mixer allows you to manage your speakers, apps and microphones on systems with
pulse audio (or pipewire with the pulse audio capabilities).

![rice-f009082](https://raw.githubusercontent.com//evandrofisico/rofi-mixer/blob/master/images/screenshot.png)

## Usage

1. Run rofi-mixer

```
rofi-mixer
```

2. Use it

There are three available modes, output (speakers and the default), applications and input
(microphones, you have to switch to). Shift+left or Shift+right are the default
keybindings for changing modes in rofi.


## Shortcuts

| Shortcut     | Action                |
| ------------ | --------------------- |
| '+', '='     | Increase volume by 5  |
| '-', '_'     | Decrease volume by 5  |
| 'Alt+m'      | Mute device           |
| 'Ctrl+equal' | Equalize L+R Speakers |

## Installation

```sh
yay -S rofi-mixer-git
```

Otherwise you can clone the repo and then run the `rofi-mixer` file

## Features that would be nice!

- Being able to move audio input/output around (like change the device a song is playing on)

If you have more feature ideas or want to implement one of them feel free to
submit a PR.
