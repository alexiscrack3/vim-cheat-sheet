# Vim Cheat Sheet

## Navigating

* **`h`** Cursor left
* **`j`** Cursor down
* **`k`** Cursor up
* **`l`** Cursor right

### Words

* **`w`** Next word
* **`b`** Start of word
* **`e`** End of word

### Line

* **`0`** Start of line
* **`$`** End of line

### Character

* **`f{char}`** Go forward to char
* **`F{char}`** Go backward to char
* **`;`** Scan line for next character
* **`,`** Scan line for previous character
* **`t{char}`** The cursor is placed on the character left of {char}

### Document

* **`gg`** Start of file
* **`G`** End of file
* **`:n`** Go to line n

### Window

* **`zz`** Redraws the screen with the current line in the middle of the window
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

## Visual Mode

* **`v`** Enter visual mode
* **`V`** Enter visual line mode
* **`>`** Shift text right
* **`<`** Shift text left
* **`y`** Yank selection (copy)
* **`d`** Delete selection
* **`s`** Replace selection

## Clipboard

* **`x`** Delete character under the cursor
* **`dd`** Delete current line (cut)
* **`yy`** Yank a line (copy)
* **`p`** Put after cursor (paste)
* **`P`** Put  before cursor (paste)
* **`<C-r>0`** Paste the text that was just yanked at cursor

## Searching

* **`/pattern`** Search for pattern
* **`?pattern`** Search backward for pattern
* **`n`** Repeat search in same direction
* **`N`** Repeat search in opposite direction
* **`*`** Search for next instance of current word
* **`#`** Search for last instance of current word

## Replacing

* **`%s/old/new/g`** Replace all old with new throughout file

## Register

* **`<C-r>=`** Opens prompt at the bottom of the screen where a expression can be evaluated. When done, hit <CR>

## Other

* **`K`** Looks up the man page for the word under the cursor
* **`<C-o>`** Switch to insert normal mode. Fire off a single command, after which we'll be returned to insert mode immediately
* **`:help key-notation`** Show all key notations
* **`<C-v>{code}`** Insert character by decimal code
* **`ga`** Print the ascii value of the character under the  cursor in decimal, hexadecimal and octal.
* **`<C-k>{char1}{char2}`** Insert unusual characters by digraph.

