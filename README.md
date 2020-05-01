# field and button descriptions

directory: the root directory that you want to select files from

depth: how far down from the root directory that you want to choose files from. (must be >= 1)
       
if your directory looks like this:
       
      root
      ├── dir1
      |   ├── file1
      ├── dir2
      |   ├── dir2-1
      |   |   ├── file2
      ├── dir3
      
      depth = 1 would choose from [dir1, dir2, dir3]
      depth = 2 would choose from [file1, dir2-1]
      depth = 3 would choose from [file2]

allow repeats: check this if you don't mind being able to randomly select the same file(s) multiple times

do not allow repeats: check this if you don't want to randomly select the same file more than once

reset repeats: allows the program to re-select files again

random: selects a file with the above parameters and displays the file location in the text box below

open: opens the file or directory with the default windows program

# note

the program makes no attempt to check that what you're trying to do is correct and is prone to crashing and logic errors. so don't go setting depth to -1 or opening files that windows doesn't know how to open.
