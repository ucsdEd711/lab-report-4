# lab report 4
# first part
The one I'm doing is: In DocSearchServer.java, change the name of the start parameter of getFiles, and all of its uses, to instead be called base.<br>
`cd week6-skill-demo1
vim DocSearchServer.java
/start <enter> ce base <escape> n . n . n . n :wq <enter>`

Step by step:
1. After typing `cd week6-skill-demo1
vim DocSearchServer.java /start` <br>
/start means that we will search the word start in the file.
![Image](lab4r_1.png)
2. Aftrer typing `ce`<br>
`c` stands for change and `e` stand for moving to the end of a word. And since we are changing the file, we are in insert mode. 
![Image](lab4r_ce.png)
3. Aftrer typing `base`<br>
we type in "base" to switch off start and change it to "base".
![Image](lab4r_base.png)
4. Aftrer typing `<esc>`<br>
we exit the insert mode and back to the normal mode.
![Image](lab4r_esc.png)
5. After type in `n`<br>
`n` stand for repeating the last search from the cursor's position.
![Image](lab4r_n1.png)
6. After typeing `.`<br>
`.` will repeat the last change.
![Image](lab4r_dot1.png)
7. After type in second `n`<br>
`n` stand for repeating the last search from the cursor's position. Which will take us to the next "start".
![Image](lab4r_n2.png)
8. After typeing the second `.`<br>
`.` will repeat the last change. Which will change the start to base.
![Image](lab4r_dot2.png)
9. After type in the third `n`<br>
`n` stand for repeating the last search from the cursor's position. Which will take us to the next "start".
![Image](lab4r_n3.png)
10.  After typeing the third `.`<br>
`.` will repeat the last change. Which will change the start to base.
![Image](lab4r_dot3.png)
11. After type in the fourth `n`<br>
`n` stand for repeating the last search from the cursor's position. Which will take us to the next "start". And since we don't hhave another "start". It shows "Pattern not found: start"
![Image](lab4r_n4.png)
12. After type in `:wq <enter>` <br>
`:` bring us to the command line and `w`help us save the file and we use `q` to quit the file.
13. The screenshot after we quit the file.
![Image](lab4r_aftersave.png)

# second part
For the method with editting in the local, scp and run on the remote, I took around 53.2 seconds to get the result.
However, for the method with on the remote first and edit in vim, I spent around 42.6 seconds to get the result.<br>

Which of these two styles would you prefer using if you had to work on a program that you were running remotely, and why?<br>
<br>
In my opinion, if I get used to how to use vim and know a lot of method to edit a file in vim, I would choose the second method. Because for this method, It is more convenient and faster even though I haven't get used to vim yet. The first method is a decent method too, but it is slower and the scp running time may sometimes be long.

What about the project or task might factor into your decision one way or another? (If nothing would affect your decision, say so and why!)
<br>
<br>
I think when we only need to change small part of a file the time difference between two methods might not be that much. However, when the file we need to change is long and we need to change lots of part in the file, or we need to use some method to change it, such as searching, copy and paste... it will make the second method way faster than the first one. Therefore, when the file we need to change is long and thare are a lot of part we need to change, I will fastor my decision to prefer the vim method, but when we don't need to change too much stuff in the file, both methods are fine for me.
