.%%...%%...%%%%...%%%%%...%%%%%%...%%%%.......%%%%%%..%%..%%........%%..%%..%%%%%%..%%...%%..
.%%%.%%%..%%..%%..%%..%%..%%......%%............%%....%%%.%%........%%..%%....%%....%%%.%%%..
.%%.%.%%..%%..%%..%%..%%..%%%%.....%%%%.........%%....%%.%%%........%%..%%....%%....%%.%.%%..
.%%...%%..%%..%%..%%..%%..%%..........%%........%%....%%..%%.........%%%%.....%%....%%...%%.. 
.%%...%%...%%%%...%%%%%...%%%%%%...%%%%.......%%%%%%..%%..%%..........%%....%%%%%%..%%...%%..
.............................................................................................
                                                
# There's 3 modes in VIM

1.	Normal Mode: For navigation and commands (e.g., delete, copy, paste).
2.	Insert Mode: For typing and editing text.
3.	Visual Mode: For selecting blocks of text.

> Vim flips the typical text editor work flow upside down.
> Google docs, etc.. - Insert mode by default
> In VIM, you're in Normal mode by default

## Why are there modes?

- They eliminate ambiguity.
  - You don't need to hold down special keys like control, alt, command to perform commands.
  - Each mode has a specific purpose, making workflows more efficient.

### Examples:

#### Normal

> Task: Delete the first line of a file

`ggdd`

1. `gg` Moves cursor to the first line
2. `dd` Deletes the line

#### Insert

> Task add a new paragraph

`o`

1. `o` Creates a new line below the current one and switches to insert mode

#### Visual mode

> Task: Select this 'word and' copy it.

`yi'`

- Stands for "yank inside quote"

`p` - paste
