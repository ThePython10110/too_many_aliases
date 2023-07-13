# Too Many Aliases

[ContentDB](https://content.minetest.net/packages/ThePython/too_many_aliases)

[GitHub](https://github.com/ThePython10110/too_many_aliases)

[Direct Download](https://content.minetest.net/packages/ThePython/too_many_aliases/releases/18461)

This mod "fixes" MineClone's inconsistent itemstrings.
Instead of typing `/giveme mesecons_torch:redstoneblock`, you can just type `/giveme mineclone:redstone_block`.
Registers aliases for all MineClone items (as of MineClone 2 0.83.0). All aliases follow MineCraft Java edition's item ID's. The aliases can have a custom prefix or none at all. The default prefix is "" (an empty string).
If the prefix (found in the Minetest settings) is set to nothing, no prefix is required (you could just type `/giveme redstone_block`).

The `mineclone:` prefix is always available, regardless of the setting. This is so mods can depend on this one.
After doing all this work, I realized that MineClone already does this... I just never knew before because I never had "Item ID debug" turned on.