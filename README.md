/// Junk-File-Organiser

-Arranging files on your computer is just like arranging anything else in your daily life like for example your bookshelf.
-You might arrange each genre of book into separate stacks or you could throw everything into one place and hope you can find the right book when you need the most. 
-Isn't that how we typically treat our files: we save files randomly to our Desktop and Documents folders, then waste time searching for files every day.
-It is a very boring and monotonous task to manually arrange all the files into one folder.
-So this is a python program to organise everything in a blink of an eye.


/// Requirements:
- usage of os module
- usage of time module
- usage of tkinter module
- File handling in python
- recursion


///prerequisites
- python 3.9 (Install this from the  official website https://www.python.org/)
- Basic knowledge of how to use command prompt, how to copy and paste files .


/// How to run
- There are 3 ways by which you can organise your files via this code.

 1- run the command_line_interface.py file- Give the desired location where you want to 
    organise the folders along with the type in which you want to organise your files.

 2- run the gui_run_file.py- If you are not familiar with command line parsing and what an interactive experience.
    Just paste the path and select the option for organizing and leave the rest to us.

 3- run the File_Organiser.exe file and simply do the exact same steps as mentioned above.
    Advantage of this is basically you don't need the code files , just keep this exe file like any other app and run whenever you wanna organise your stuff. 

/// command for command line parsing method
    1) python command_line_interface.py --p [Path] --o keyword [Type]

    2) python command_line_interface.py --p [Path] --o keyword [Size]

    3) python command_line_interface.py  --p[Path] --o keyword [Date-Modified]
    
    4) python command_line_interface.py --p [Path] --o keyword [Recently-Used]
    
    5) python command_line_interface.py  [ default Path None] [ default keyword None]

    - way to execute this code via command line parsing is select the command_line _interface.py in terminal then space --p [Path] --o [Method]



/// Approach:
1. Create different folders based on type of files according to size/date-modified/type/recently-used.

2. Create the map of file types/file sizes/last accessed time into their respective folders to initiate check and create folders accordingly.

3. Create a function to filter file types into their respective folders.

4. Use os module of python to recursively list out all the files that are present in the folders with their relative path. 
 
5. Move all the files into newly created folders depending on the user's choice.

6. Recursively call the same function to check for folders present within the path specified by user and perform the same organising method on them.

7. After running the above code in the required destination, the user will have their files sorted according to their needs.

 
/// Premium Features:
1. This script can organize the files according to given specific extension in the command line

2. This script can organize the files of according to the substring of the file name.

3. The .exe file can be used by anyone easily.


/// Built using:
1. Python language

2. The code is built according to the standard pep8/flake8 rules and regulations.
