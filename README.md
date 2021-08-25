# Periodic

A periodic table in Lua

## Usage

To import everything, simply put this at the top of your Lua file:

```lua
require('periodic')
```

Now, the global table will be filled with the following tables for use:

* `periodic`, `pdt`: Periodic Table
* `numtosy`, `nts`: Atomic number to symbol converter
* `numtoname`, `ntn`: Atomic number to name converter

The periodic table has these following fields:

* `mass`: Atomic mass
* `number`: Atomic number
* `name`: Name of element

To use, simply access whichever field of an element on the periodic table like so:

```lua
periodic.Hg.mass
pdt.Hg.mass
pdt.mercury.mass
periodic.mercury.mass
```

To convert atomic number to symbol, do this:

```lua
numtosy[15]
nts[15]
```

To convert atomic number to name, do this:

```lua
numtoname[15]
ntn[15]
```

