# Pycraft (Termcraft)

A console based 2D Minecraft, runs best on *nix with Python 3.3+. Built by [grit96](https://github.com/grit96) and [olls](https://github.com/olls).

Usage: `python3 main.py`

![Pycraft gameplay image](https://cdn.dvbris.com/pycraft-2.gif)

## Controls

For the best control, you should set your keyboard repeat time to around 200-300ms.

```
Menus:
   Move up                    - W or UP
   Move down                  - S or DOWN
   Select                     - SPACE or RETURN
   Pause                      - SPACE or RETURN
Blocks:
   Break/place block          - K
   Move cursor clockwise      - L
   Move cursor anti-clockwise - J
Inventory:
   Cycle inventory down       - O
   Cycle inventory up         - U
   Toggle crafting menu       - C
   Craft selected item        - I
Movement:
   Move left                  - A
   Move right                 - D
   Jump                       - W
```

## Crafting

A number of items are only obtainable through crafting them using the crafting system.
Items that you can craft with the items in your inventory will automatically show up in the crafting grid.
Press <kbd>C</kbd> to toggle your selection between inventory and crafting grid, press <kbd>I</kbd> to craft the currently selected item.

#### Recipes:

- 6 sticks:
   - 1 wood
- 4 torches:
   - 1 stick
   - 1 coal
- ladder:
   - 3 sticks
- wooden pickaxe:
   - 2 sticks
   - 3 wood
- stone pickaxe:
   - 2 sticks
   - 3 stone
- iron pickaxe:
   - 2 sticks
   - 3 iron
- diamond pickaxe:
   - 2 sticks
   - 3 diamonds

####  Tools:

Certain blocks require you to craft the right tool before being able to mine it.
The tool has to be selected in your inventory to be able to use it.
Each tier of pickaxe allows you to break more blocks than the previous tier.

- fist (i.e. don't need a tool):
   - grass
   - tall grass
   - wood
   - leaves
   - torch
   - ladder
- wooden pickaxe:
   - stone
- stone pickaxe:
   - coal
   - iron
- iron pickaxe:
   - redstone
   - gold
   - diamond
- diamond pickaxe:
   - emerald

## Using the C Renderer

The C renderer is likely to be faster than the Python renderer, but to use it you must compile it first. To do this run the command: `python3 setup.py build` in the root of the repository. Then run the game as normal, and go in to the settings to swich the renderer.

Please report any bugs in the C renderer, or differences between the Python renderer and the C renderer, in the issues.

## Contributing

We welcome pull requests or issues for bug reports/fixes or new feature ideas! Help us make the game more fun :D
