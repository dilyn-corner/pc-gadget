# The Gadget Snap

This gadget snap provides the boot assets required to boot a generic AMD64
machine.

Further, it provides some initial interface connection information and a
Landscape configuration in the `gadget.yaml`.

However, this gadget is quirky in that it specifically targets creating Core
**Desktop** images, not standard Ubuntu Core images. If you are looking for non
Core Desktop gadgets, check the other branches.


## Usage

The gadget should be generic enough to be useful out-of-the-box. It should work
regardless of if you have your own Store or if you purely side-load your snaps.
However, note the Landscape configuration; if you install the landscape-client
snap, you'll have to manually configure it or modify the defaults provided in
the `gadget.yaml`.


## Building

To build the gadget snap locally please use `snapcraft`.
