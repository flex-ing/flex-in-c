# ~~~

Thoughts on how it shall work.

## Minimal needs

- Edit
- Navigate
- Utilize mouse (both edit and navigate)

## Edit

- Insert
- Delete
- Replace

## Navigate

- Scroll
- Move
-

It needs to work with the mouse (!) to edit and navigate the blocks of code

In the future: cscope, ncurses, dart, or even pure node, which would grab all the input keys and deal with them
Also, we shouldn't depend on Xorg in this project, but we may need to use that in flex-in-dart or something like that

Also, you're limited on shortcuts, because terminal doesn't differentiate between Ctrl+a and Ctrl+Shift+a (A there should be uppercase)

So, maybe curses give a workaround, gathering all the input. Or, I should watch for keycodes, like xmodmap does
