# kanata_extend.kbd

(The full `kanata.kbd` file contains more features: home-row mods, symbol layer, mouse control, ...)  

An implementation of [DreymaR's Extend layer](https://dreymar.colemak.org/layers-extend.html) using [Kanata](https://github.com/jtroo/kanata).  
Extend turns Caps Lock into a modifier that enables navigation/editing without moving your hands.  
(See [DreymaR's Extend page](https://dreymar.colemak.org/layers-extend.html) for color-coded diagrams and the full concept.)  

## Activation

Hold **Caps Lock** to access the Extend layer.  
Or replace `spc` in base layer with `@spext` to use dual-function **Space** key (tap for space, hold for extend).  

## Layout

### Base

```
+--------+
|  Esc   |
+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+
|   `    |   1    |   2    |   3    |   4    |   5    |   6    |   7    |   8    |   9    |   0    |   -    |   =    | BkSpc  |
+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+
|  Tab   |   Q    |   W    |   E    |   R    |   T    |   Y    |   U    |   I    |   O    |   P    |   [    |   ]    |   \    |
+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+
| Extend |   A    |   S    |   D    |   F    |   G    |   H    |   J    |   K    |   L    |   ;    |   '    | Enter  |
+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+
| Shift  |   Z    |   X    |   C    |   V    |   B    |   N    |   M    |   ,    |   .    |   /    | Shift  |
+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+
|  Ctrl  |  Win   |  Alt   |                        Space                        |  Alt   |  Win   |  Ctrl  |
+--------+--------+--------+-----------------------------------------------------+--------+--------+--------+
```

### Extend — hold Caps Lock (or Space if config changed)

```
+--------+
| CapLck |
+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+
| Ctrl ` |   F1   |   F2   |   F3   |   F4   |   F5   |   F6   |   F7   |   F8   |   F9   |  F10   |  F11   |  F12   | BkSpc  |
+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+
|  Tab   |        | ScrlUp | Enter  |        |        | PageUp |  Home  |   Up   |  End   | Delete |        |        |        |
+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+
| Extend |  Alt   | ScrlDn | Shift  |  Ctrl  | MLeft  | PageDn |  Left  |  Down  | Right  | BkSpc  |        | PrtScr |
+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+
| Shift  |  Undo  |  Cut   |  Copy  | Paste  |        |        | Escape |        |        |        | Shift  |
+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+
|  Ctrl  |        |  Alt   |                        Enter                        |  Alt   |        | Reload |
+--------+--------+--------+-----------------------------------------------------+--------+--------+--------+
```

**Navigation cluster** `I J K L` become Up / Left / Down / Right, `U O` become Home / End, `Y H` become Page Up / Down. `P` becomes Delete, `;` becomes Backspace, and `M` becomes Escape.  

**Modifier cluster** `A D F` become Alt / Shift / Ctrl. Use alongside right-hand navigation for text selection and shortcuts.  
`W S` scroll up / down, `E` and `Space` become Enter, and `G` acts as left mouse button.  

**Shortcuts** `Z X C V` are Undo / Cut / Copy / Paste.

**Number/Function row** `1 2 3 4 5 6 7 8 9 0 - =` become F1–F12. The backtick becomes Ctrl+\`.  

**Right Ctrl** reloads the Kanata config file.
