# [VimGolf][] in Emacs!

`vimgolf.el` provides a way to play VimGolf solo in the One True Editor™.

## Installation

Install `vimgolf` via your favorite version of [melpa][].

## How to Play

1. Find the challenge you'd like to play on [VimGolf][].

1. `M-x vimgolf CHALLENGE-ID RET`

    Point will be in the window containing the starting text and you'll
    have the goal text on a second window. Edit the starting text until it
    matches the ending text and then finish with `C-c C-v C-c`.

## Commands

| Command | Default Binding | Description |
| --- | --- | --- |
| `vimgolf` | `M-x vimgolf` | Input a challenge ID and play! |
| `vimgolf-browse` | `M-x vimgolf-browse` | Open an interactive buffer to browse challenge titles |
| `vimgolf-submit` | `C-c C-v C` | Finish and score the challenge |
| `vimgolf-revert` | `C-c C-v r` | Revert to the beginning of the challenge and clear your keystrokes |
| `vimgolf-diff` | `C-c C-v d` | Open an ediff session for the challenge |
| `vimgolf-pause` | `C-c C-v p` | Pause keystroke recording |
| `vimgolf-continue` | `C-c C-v c` | Start keystroke recording where you left off |
| `vimgolf-quit` | `C-c C-v q` | Stop the challenge |

[vimgolf]: https://www.vimgolf.com/
[melpa]: https://melpa.org/
