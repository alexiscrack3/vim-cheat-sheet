# Vim Cheat Sheet

## Cursor Movement

* **`w`** Next word
* **`0`** Beginning of line
* **`$`** End of line
* **`gg`** Start of file
* **`G`** End of file
* **`H`** Top of screen
* **`M`** Middle of screen
* **`L`** Bottom of screen

## Inserting Text

* **`i`** Start insert mode at cursor
* **`I`** Insert at the beginning of the line
* **`a`** Append after the cursor
* **`A`** Append at the end of the line
* **`o`** Append blank a line below current line
* **`O`** Append blank a line above current line
* **`C`** Delete from the cursor position to the end of the line

## Editing Text

* **`u`** Undo
* **`<C-r>`** Redo
* **`s`** Delete character at cursor and substitute text
* **`S`** Delete line at cursor and substitute text (same as cc)
* **`.`** Repeat last command

## Visual Commands

* **`>`** Shift text right
* **`<`** Shift text left

## Cut and Paste

* **`yy`** yank (copy) a line
* **`p`** Put (paste) the clipboard after cursor
* **`P`** Put (paste) before cursor
* **`dd`** Delete current line
* **`x`** Delete character under the cursor

## Searching

* **`f`** Look ahead for the next occurrence of the specified character and then move the cursor directly to it if a match is found
* **`;`** Scan line for next character
* **`,`** Scan line for previous character
* **`/pattern`** Search for pattern
* **`?pattern`** Search backward for pattern
* **`n`** Repeat search in same direction
* **`N`** Repeat search in opposite direction
* **`*`** Search forward for the [count]'th occurrence of the word nearest to the cursor

## Replacing

* **`%s/old/new/g`** Replace all old with new throughout file

