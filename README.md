**DEPRECATED**

This package is deprecated. Do not use it.

Recommended alternative: https://github.com/tarsius/minions

# Numeric minor modes (nummm)
  Display the number of minor modes instead of their names in Emacs mode-line.

  This mode replaces the `minor-mode-alist` in `mode-line-modes` with
  a custom one. `minor-mode-alist` is NOT modified. Also, a backup of
  `mode-line-modes` is done when enabling `nummm-mode` and is
  restored when is turned off.
  The face can be changed customizing `nummm-face`.

## Installation

  You can download the latest (archived) version at: https://atrebit.org/pub/releases/nummm-mode.tar.gz

  And then copy `nummm-mode.el` file in your load path and add the following in your `~/.emacs` startup file:
  ```lisp
    (require 'nummm-mode)
    (nummm-mode t)
  ```
