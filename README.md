# zmk-config-adv360

This is my personal ZMK configuration for my Advantage 360. This is primarily
configured and maintained using [Nick Coutsos's keymap editor][editor], with
some hand editing where bulk editing of layers is useful or something is
unsupported at the time by the editor.

[editor]: https://github.com/nickcoutsos/keymap-editor

## Layers

### Layer 0 - Default

Layer 0 is the default keymap and is the layer through which all other layers
can be accessed. It is never toggled on or off. There isn't much distinct here
from the default layout except the following:

  * Delete is replaced with left control.
  * Capslock is replaced with a momentary numpad toggle.
  * Left clumb cluster modifiers are (left to right) left command and left alt.
  * Right thumb cluster modifiers are (left to right) right control and right
    command.
  * The position of the up and down arrow keys is swapped, with down on the left
    and up on the right, to match HJKL ordering.

![A screenshot of the default layer 0 key mappings](/static/layer-0.png)

### Layer 1 - Numpad

The numpad layer is mostly identical to defaults with only changes to the left
module's keys.

  * W, E, and R keys are volume down, toggle volume mute, and volume up.
  * S, D, and F keys are the previous, play-pause toggle, and next media keys.
  * The function key toggles layer 4.
  * The backspace key is forward delete.
  * Escape is the capslock key (i.e., in its traditional position).

![A screenshot of the number pad layer 1 key mappings](/static/layer-1.png)

### Layer 2 - Function Keys

The function layer is unmodified except to map the H, J, K, and L keys to the
left, down, up, and right arrow keys for convenience.

![A screenshot of the function key layer 2 key mappings](/static/layer-2.png)

### Layer 3 - Kinesis Mod Keys

This layer is unmodified.

![A screenshot of the Kinesis modifier key layer 3 key mappings](/static/layer-3.png)

### Layer 4 - Gaming

This layer is entirely translucent except to remap the left thumb cluster in the
following way:

  * The backspace key (from layer 0) becomes left control.
  * The left control key (from layer 0) becomes space.

This is primarily to accomodate games that do not support key remapping, or
which do support key remapping but still have some hardcoded key mappings.

![A screenshot of the gaming key layer 4 key mappings](/static/layer-4.png)

## Contributing

Because this is my personal configuration, contributions are not accepted unless
there's a bug in something in here, which I'm unlikely to spot most of the time.
Otherwise, I encourage anyone who wants to use this as a base to fork it and
customize as much as they want.

If you use it, I would still encourage forking the repository. Any changes
I make down the road might not suit someone's taste, and I'd hate to
accidentally ruin someone's day if they had to reflash their Advantage 360 and
ended up with unexpected changes because I wanted something different.
