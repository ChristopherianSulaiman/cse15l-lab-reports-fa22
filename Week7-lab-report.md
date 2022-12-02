**Week 7 Lab Report**

Changing the name of the start parameter and its uses to base keybinds:

1. in Normal Mode in DocSearchServer.java, do `/start<Enter>` to search for the word "start" in the code.
2. type `ce` to delete the word start, while entering insert mode.
3. Type `base<Esc>` to replace the word start with base and then entering Normal mode again.
4. press `n` to cycle to the next 'start'.
5. Repeat steps 2 and 3 and 4 until all 'start' is switched to 'base' except for the sever.start. (note: after all 'start' has been converted to 'base', no need to do the last step 4.)
6. save and exit vim by typing `:wq` in Normal mode.




**Sequence of keys pressed (as mentioned by the comment on my early submission of the reason why I got 1/2):**

1.    "`/`"

2.  "`s`" 

3.  "`t`" 

4.  "`a`" 

5.  "`r`"

6.  "`t`"

7. "`<Enter>`"

8. "`c`"

9.  "`e`"

10. "`b`"

11. "`a`"

12. "`s`"

13. "`e`"

14. "`<Esc>`"

15. "`n`"

16. "`c`"

17. "`e`"

18. "`b`"

19. "`a`"

20. "`s`"

21. "`e`"

22. "`<Esc>`"

23. "`n`"

24. "`c`"

25. "`e`"

26. "`b`"

27. "`a`"

28. "`s`"

29. "`e`"

30. "`<Esc>`"

31. "`:`"

32. "`!`"

33. "`w`"

34. "`q`"

**I have made edits based on the feedback given to me :)**


Editing in VSC: 1 minute 5 seconds


Editing in SSH: 22 seconds

Which of these two styles would you prefer using if you had to work on a program that you were running remotely, and why? **I prefer doing the edits to my code in the remote server directly because I am familiar with the vim shortcuts and I can instantly bash it there, therefore it took me less time to finish.**

What about the project or task might factor into your decision one way or another? (If nothing would affect your decision, say so and why!) **If the project or task requires me to do heavy testing and editing, I would definitely prefer to do it remotely directly due to the ease when bashing and the shortcuts in vim. In general, I think vim would be faster than vsc in any project for me. This is because: doing it in vsc might be time consuming in the editing, scp, and they dont support bash in the local workstation.**