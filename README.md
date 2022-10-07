# rime-apl

[Rime](https://rime.im/) (weasel) schemata for APL (primarily Dyalog)

`apl.schema.yaml` lets you input APL glyphs by their names. You can open file `apl.dict.yaml` to see and edit the names to each glyph. 

To use the schema, you need to put `apl.schema.yaml`, `alpahbet.dict.yaml`, `apl_boot.schema.yaml` and `apl.dict.yaml` in your Rime user folder, and select both `APL` and `APL Boot` in Rime setting.

When using the `APL` schema:
- you can type the letters normally. (This is a hack using `alpahbet.dict.yaml`. The output is **NOT** real direct keyboard output.)
- When you want to type APL glyphs, type `` ` `` + name.
Tab and Return confirm the highlighted candidate text. Number keys confirm the candidate text labeled that number. Space commits the raw input.

Shift (customizable in the schema) changes the mode (APL or ascii). 
It works like the Caps Lock.
