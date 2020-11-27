# Code navigation in Vim

Learn to navigating in the code efficiently is a crucial part of being a developer. Before I use Vim, I'm was panic whenever someone approach my computer and watch me write the code, evenwhen it was a pair programming session. The most painful part is code navigation, it took me awhile to navigate to the position I want to edit the code, searching things, find and replace... After all I still can perform all those actions, but it was painful and unconfident.

Then I learn to use Vim.

## The most obvious way
The most obvious way to navigate is using mouse, or `j` `k` to navigate up/down. It even worse when I use arrow keys to mo up/down some time. This is not efficient, let's avoid this.

## Jumping by line number
By showing the relative number I now esier move to the line I want, e.g., 
- Move up 10 lines: `10k`
- Move down 15 lines `15j`

Then jump to the expected work by `f` and `t`, jump backward by `F` and `T`. For example, assume the cursor is at the begin of this line, I want to jump to second character `j` I press `fj;`

It still not so efficient but I'm good with it for a year.

## Jumping by `incsearch`
Jumping by line number is still painful, I have to look at the line number and perform the jump, its distracting. To jump by `incsearch` setting this in the config file.
```
set incsearch
set cursorline
```

## Combine them all
So far jumping by `incsearch` is the most efficient way to navigate, I use it everyday and feel better everyday. Now I'm code with confidence evenwhen the whole team whatch me coding. 

But I'm not stricted to any of the methods above, I use it all.

