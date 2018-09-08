# Vim Cheat Sheet

## Cursor Movement

* **`$`** Jump to the end of the line

## Manipulating Text

* **`>`** Shift text right
* **`<`** Shift text left

## Insert Mode 

* **`i`** Start insert mode at cursor
* **`I`** Insert at the beginning of the line
* **`a`** Append after the cursor
* **`A`** Append at the end of the line
* **`o`** Append blank a line below current line
* **`O`** Append blank a line above current line

## Editing

* **`u`** Undo
* **`<C-r>`** Redo
* **`s`** Delete character at cursor and substitute text
* **`S`** Delete line at cursor and substitute text (same as cc)
* **`.`** Repeat last command

## Cut and Paste

* **`yy`** yank (copy) a line
* **`C`** Delete from the cursor position to the end of the line
* **`p`** Put (paste) the clipboard after cursor
* **`P`** Put (paste) before cursor
* **`dd`** Delete current line
* **`x`** Delete character under the cursor

## Searching and Replacing

* **`f`** Look ahead for the next occurrence of the specified character and then move the cursor directly to it if a match is found
* **`;`** Scan line for next character
* **`,`** Scan line for previous character
* **`/pattern`** Search for pattern
* **`?pattern`** Search backward for pattern
* **`n`** Repeat search in same direction
* **`N`** Repeat search in opposite direction
* **`%s/old/new/g`** Replace all old with new throughout file
* **`*`** Search forward for the [count]'th occurrence of the word nearest to the cursor

