# learning-vim
Notes and cheatsheets while for learning VIM

# VIM Cheatsheet

## Open VIM

To open a file in VIM use `vim filename.file_extension`
To open a folder in VIM use `vim folder_name`
To open the current folder use `vim .`

## Create or edit a file
**e**
To create or edit a file open vim and enter command mode and then use `e filename.file_extension`

To edit a new or existing file in a new tab enter command mode and then use `tabe filename`

## Modes

**ESC**
Normal: This is the default mode which is readonly. Pressing escape will return to normal mode.

**i**
Insert: This mode allows you to modify text.

**v**
Visual: This mode allows you to visually select text

**SHIFT**+**:**

Command

You can bring up the VIM command line by returning to normal mode **ESC* and then pressing **SHIFT**+**:*. This command line allows you to execute commands in VIM and commands you would normally run in the terminal.

## Saving

**ESC** **SHIFT** + **:w**
Return to Normal mode **ESC* and press **SHIFT*+**:** to enter command mode, next type **w* to write the file. **wq** is commonly used to write and quit vim for quick edits to files. You can force commands with the **!**...so you can force write to a file using **!w** for example.

## Exiting

**ESC** **SHIFT** + **:q**

## Navigationg

`h`left 
`j`down
`k`up
`l`right


### KEEP LEARNING

**https://thoughtbot.com/upcase/onramp-to-vim**



