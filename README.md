# corners
Patch 4 corner glyphs into a font.

## Dependencies
- `python3`
- `fontforge`

## Patching
`./patch <input-font> <output-file-name>`

## The glyphs
- `e4c5` `` full-top-left
- `e4c6` `` full-top-right
- `e4c7` `` full-bottom-right
- `e4c8` `` full-bottom-left
- `e4c9` `` half-top-left
- `e4ca` `` half-top-right
- `e4cb` `` half-bottom-right
- `e4cc` `` half-bottom-left

## Neovim borders

### Full height
```lua
border = { "", "█", "", "█", "", "█", "", "█" }
```

### Half height
```lua
border = { "", "▄", "", "█", "", "▀", "", "█" }
```
