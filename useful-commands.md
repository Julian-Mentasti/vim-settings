`set spell!` toggles spelling on and off

`sh` lets you into the terminal

I use Backspace in Normal mode to go back a pane, and Tab to go forward. 

`nnoremap <Tab> <c-w>w`

`nnoremap <bs> <c-w>W`

shift l to go to the left tab and shift H to go to the right one

`:vsplit [filename]` open a file in new vertical pane

`:tabnew [filename]` open a file in a new tab

I think you wanted to save the file with CTRL-s. That's a screen-lock. Use CTRL-q to unlock and save with :w.

What you want is to use is the a command instead of the i command to enter insert mode. Or if you want to jump to the end of the line and start insert mode, use A. Note that I will jump to the beginning of the line and enter insert mode.
