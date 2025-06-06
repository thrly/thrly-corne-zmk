# thrly's ZMK configuration

![](https://github.com/thrly/thrly-corne-zmk/actions/workflows/build.yml/badge.svg)

> This config is for a 6-col corne (wireless version from [Typeractive](https://typeractive.xyz/)), but I'm gradually trying to wittle it down to a smaller custom 36-key 5-col that I'm designing myself...

For more explanations and reflections on this customization, see [my blog post](https://thrly.com/blog/thoughts-on-customising-a-split-keyboard-layout/) on this keymap.

> [!WARNING]
> This is my personal daily driver keyboard config, it is under active development. Expect tweaking and occasional breaking changes. Documentation may be missing or out of sync with the latest commits. Proceed with caution.

![cat paws and keyboard closeup](./img/cat-corne.jpg)

## Key Features

- QWERTY alpha layout
- Homerow mods ([balanced flavour](https://zmk.dev/docs/keymaps/behaviors/hold-tap#option-3-balanced)) - `Gui-Alt-Shf-Ctl`
- Sticky shift
- Mouse behavior on Nav layer
- Horizontal Num layer
- Thumb keys transparent on layers (for `Ctrl` and `Shift`)
- Combos:
  - volume up / down (outer right top + middle / middle + bottom)
  - caps word / caps lock (`G`+`J` / `T`+`Y`)
  - escape (`Q`+`W`)
  - delete (`O`+`P`)
  - dash, underscore (`E`+`R`, `U`+`I`) 
- Macros:
  - double-tap `>` for `=>` arrow
  - en-dash (` -- `) combo (`W`+`E`+`R`)
  - `console.log(` combo (`Q`+`R`+`U`+`P`) via an AutoHotkey macro set to `F19` : `F19:: send "console.log("`
> [!IMPORTANT]
> Home Row Mods are now standard.

## Layers

### Base layer

![Base keymap diagram](./img/corne-base-layer.png)

### Symbol layer

![Symbol keymap diagram](./img/corne-symbol-layer.png)

### Nav layer

![Nav keymap diagram](./img/corne-nav-layer.png)

### Num layer

![Num keymap diagram](./img/corne-num-layer.png)

### Layer 4

Nothing special here, left side features bluetooth connection profiles, right side has mouse controls with more room for buttons than on the Nav layer. \[TODO: add image]

## Other

- https://github.com/M165437/nice-view-gem - This is purely aesthetic and gives some more user feedback on the nice!view displays.

## Notes

- Configure keymap with https://nickcoutsos.github.io/keymap-editor/
- Flash firmware from latest 'Actions' artifact
