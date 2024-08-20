# Part 1
- cd into Eolian caves and use `tree` command to see the list of all folders and files or use `find -name "parchment.txt"` to get the exact location of the file
- cat parchement.txt allows you to read the file
- code: **aHR0cHM6Ly9naXRo**

# Part 2
I could find herbs that were either holy or good. But had a hard time finding herbs which were both holy and good. Also I wasted a lot of time, just to realize that the folder Eolian caves has space in its name so my command was not being executed properly. 
Then used `grep -lrZ "holy" * | xargs -0 grep -lr "good"` to find the good and holy herbs where
- -l List only the filenames instead of the the actual lines
- -r: Searches through all the directories.
- -Z: This is crucial when dealing with files or directories that contain spaces in their names.
When MoonbloomMistveil is decoded it gives **LnnmknnlLhrsdhk**
 
From Celestial Veil Amulet, the code **CSigVmaroAn** is known

# Part 3
codes obtained from files in different branches are as follows
- Lightbook.txt - **dWIuY29tL2FtYW5ze**
- DarkbookI.txt - **GNhbGlidXIvVGVyb**
- DarkBookII.txt - **WluYWwtQ2hhb3MtR29kU3VpdGU**=

# Part 4
Combining all the four codes, results in a Base-64 encoded URL that leads to the [Godsuite](https://github.com/amansxcalibur/Terminal-Chaos-GodSuite)  repository

# Part 5
The command `git log -p` shows the differences between each commit
From there another base-64 encoded code led to the final [github repo](https://github.com/angrezichatterbox/To-the-stars-and-realms-unseen).


