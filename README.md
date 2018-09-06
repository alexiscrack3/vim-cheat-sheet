# Vim Cheat Sheet

## Cursor Movement

* **`$`** Jump to the end of the line

## Manipulating Text

* **`>`** Shift text right
* **`<`** Shift text left

## Editing Text

* **`u`** Undo last change 

## Inserting Text

* **`C`** Delete from the cursor position to the end of the line
* **`i`** Insert before the cursor
* **`I`** Insert at the beginning of the line
* **`a`** Insert (append) after the cursor
* **`A`** Insert (append) at the end of the line
* **`o`** Append (open) a new line below the current line
* **`O`** Append (open) a new line above the current line

## Deleting Text

Almost all deletion commands are performed by typing d followed by a motion. A few other deletes are:

* **`x`** Delete character under the cursor
* **`dd`** Delete current line

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

