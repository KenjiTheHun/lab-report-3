# Lab Report 3 - Terminal Command Lines (Week 5)
For this lab report, I chose to use the "find" command to demonstrate the variety of ways that it can be utilized to navigate your directories and files.

## "find -name" Usage
The first variation of "find" is "-name", which finds the file or directory that has the matching string of characters. I found the options for this commands through asking ChatGPT, and it gave out several options.

```
[cs15lwi23aog@ieng6-202]:written_2:317$ find . -name "Cuba*.*"
./travel_guides/berlitz2/Cuba-History.txt
./travel_guides/berlitz2/Cuba-WhatToDo.txt
./travel_guides/berlitz2/Cuba-WhereToGo.txt
```

![Image](FIND-CUBA.png)

Here I used the "find -name" command to find all files that contained the pretext "Cuba", using * to account for different aftertext or types of file.

```
[cs15lwi23aog@ieng6-202]:written_2:318$ find . -name "*n.txt"
./travel_guides/berlitz1/HandRLisbon.txt
./travel_guides/berlitz1/HistoryDublin.txt
./travel_guides/berlitz1/HistoryJapan.txt
./travel_guides/berlitz1/IntroDublin.txt
./travel_guides/berlitz1/IntroJapan.txt
./travel_guides/berlitz1/WhatToDublin.txt
./travel_guides/berlitz1/WhatToJapan.txt
./travel_guides/berlitz1/WhereToDublin.txt
./travel_guides/berlitz1/WhereToJapan.txt
```

![Image](FIND-N.png)

Here I modified the command to find all .txt files that ended with a lowercase "n".

## "find -size" Usage
The second variation of "find" is "-size", which finds files of specific sizes. I found this option from search on Google and on this website https://www.tecmint.com/35-practical-examples-of-linux-find-command/
