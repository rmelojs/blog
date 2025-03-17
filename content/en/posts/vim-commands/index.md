---
author: Hugo Authors
title: Vim Commands
date: 2025-03-16
description: Vim's Commands
toc: false
---


# Vim Editing Commands Tutorial

## Introduction
Vim is a powerful text editor used by developers and system administrators. This tutorial covers essential editing commands to enhance your efficiency.

## Basic Editing Commands

### Insert Mode
To enter insert mode:

```vim
i   # Insert before the cursor
a   # Insert after the cursor
o   # Insert on a new line below
O   # Insert on a new line above
```

### Deleting Text
To delete characters, words, or lines:

```vim
dd   # Delete the current line
dw   # Delete a word
d$   # Delete from cursor to end of line
d0   # Delete from cursor to beginning of line
```

### Copy and Paste
Copy (yank) and paste:

```vim
yy   # Yank (copy) the current line
yw   # Yank a word
p    # Paste after the cursor
P    # Paste before the cursor
```

### Undo and Redo
Undo and redo changes:

```vim
u    # Undo last change
Ctrl+r   # Redo last undone change
```

### Save and Exit
To save and exit Vim:

```vim
:w    # Save file
:q    # Quit (only if no changes were made)
:wq   # Save and quit
:q!   # Quit without saving
```
