**Week 7 Lab Report**

Changing the name of the start parameter and its uses to base keybinds:

1. in Normal Mode in DocSearchServer.java, do `/start<Enter>` to search for the word "start" in the code.
2. type `ce` to delete the word start, while entering insert mode.
3. Type `base<Esc>` to replace the word start with base and then entering Normal mode again.
4. press `n` to cycle to the next 'start'.
5. Repeat steps 2 and 3 and 4 until all 'start' is switched to 'base' except for the sever.start. (note: after all 'start' has been converted to 'base', no need to do the last step 4.)
6. save and exit vim by typing `:wq` in Normal mode.

Editing in VSC: 1 minute 5 seconds


Editing in SSH: 22 seconds

Which of these two styles would you prefer using if you had to work on a program that you were running remotely, and why? **I prefer doing the edits to my code in the remote server directly because I am familiar with the vim shortcuts and I can instantly bash it there, therefore it took me less time to finish.**

What about the project or task might factor into your decision one way or another? (If nothing would affect your decision, say so and why!) **If the project or task requires me to do heavy testing and editing, I would definitely prefer to do it remotely directly due to the ease when bashing and the shortcuts in vim. In general, I think vim would be faster than vsc in any project for me. This is because: doing it in vsc might be time consuming in the editing, scp, and they dont support bash in the local workstation.**