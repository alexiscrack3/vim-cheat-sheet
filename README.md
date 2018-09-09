# Vim Cheat Sheet

## Cursor Movement

* **`h`** Cursor left
* **`j`** Cursor down
* **`k`** Cursor up
* **`l`** Cursor right
* **`w`** Next word
* **`b`** Start of word
* **`e`** End of word
* **`0`** Beginning of line
* **`$`** End of line
* **`gg`** Start of file
* **`G`** End of file
* **`:n`** nth line of file
* **`f{char}`** Forward to char
* **`F{char}`** Back to char
* **`;`** Scan line for next character
* **`,`** Scan line for previous character
* **`H`** Top of screen
* **`M`** Middle of screen
* **`L`** Bottom of screen
* **`<C-b>`** Page up
* **`<C-f>`** Page down

## Inserting Text

* **`i`** Start insert mode at cursor
* **`I`** Insert at the beginning of the line
* **`a`** Append after the cursor
* **`A`** Append at the end of the line
* **`o`** Append blank a line below current line
* **`O`** Append blank a line above current line
* **`C`** Delete from the cursor position to the end of the line
* **`<C-[>`** Exit insert mode
* **`<Esc>`** Exit insert mode

## Editing Text

* **`u`** Undo
* **`<C-r>`** Redo
* **`s`** Delete character at cursor and substitute text
* **`S`** Delete line at cursor and substitute text (same as cc)
* **`.`** Repeat last command
* **`<C-h>`** Delete back one character (same as backspace)
* **`<C-w>`** Delete back one word
* **`<C-u>`** Delete back to start of line

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

* **`/pattern`** Search for pattern
* **`?pattern`** Search backward for pattern
* **`n`** Repeat search in same direction
* **`N`** Repeat search in opposite direction
* **`*`** Search for next instance of current word
* **`#`** Search for last instance of current word

## Replacing

* **`%s/old/new/g`** Replace all old with new throughout file

## Other

* **`K`** Looks up the man page for the word under the cursor
* **`zz`** Redraws the screen with the current line in the middle of the window
* **`<C-o>`** Switch to insert normal mode. Fire off a single command, after which we'll be returned to insert mode immediately

