# Thaumcraft 4.2.2.0 Research Helper

A research helper for Thaumcraft 4.2.2.0. Based on [glowredman/tcresearch](https://github.com/glowredman/tcresearch) (itself a fork of [ythri/tcresearch](https://github.com/ythri/tcresearch)), modified to target only Thaumcraft 4.2.2.0 with all addon aspects included by default.

## Changes from the original

- Version selection removed — the aspect data is fixed to Thaumcraft 4.2.2.0
- All addon aspects (Forbidden Magic, Magic Bees, Gregtech, Avaritia, Thaumic Boots, GTNH 2.1.3.0+) are always included; the addon checkboxes are gone
- Obsolete aspects and images from other Thaumcraft versions removed

## Using

Choose **`From`** and **`To`** Aspects from your research note and minimum number of steps between those aspects. Then click **`Find Connection`** and the script will search for the shortest path (well, with at least the minimum length) that connects the two aspects.

## Note

Sometimes the length of any path is longer than the given minimum, but this should not be a problem for your research note.

## Disabling aspects

If you are unhappy with the path you got, because you do not have access to those aspects yet or they are quite rare, simply disable those aspects from Available Aspects:. The script will then try to find paths without these. Note that this may cause the path to grow longer. If too many aspects are disabled and there are no paths left without any of those, the script will try to find the shortest path using the minimal number of disabled aspects.

If you don't have a particular addon installed, disable its aspects the same way.
