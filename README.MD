# Anvil Unlocker

Disables the ‘Too Expensive!’ message and allows using anvils past the normal level cap of 40. No permissions.

The new level cap is configurable. Any integer from 41 to 32,767 is valid.

**[ProtocolLib](https://github.com/dmulloy2/ProtocolLib/releases) is required.**

![Screenshot showing an anvil with ‘Enchantment Cost: 55’ in green.](https://cdn.modrinth.com/data/N4CZEMrg/images/2b745ef9e906c21c566d91d1ae95049e938cb655.png)

## Caveats

Due to Vanilla client limitations:

* Anvil costs above 40 levels cannot be displayed in red if the client lacks the required
  experience. For simplicity and consistency, the mechanic of the cost turning red is disabled entirely.
* Costs greater than 32,767 levels cannot be rendered correctly and are therefore not supported.
