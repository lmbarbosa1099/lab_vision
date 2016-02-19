# Warmup Questions

1.  What is the clone url of this repository?
    >  https://github.com/lmbarbosa1099/lab_vision

2.  What is the output of the ``cal`` command?

    > It is used to display the calendar. The format output is: 
    > Month Year 
    > Su Mo Tu We Th Fr Sa 
    > 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30

# Homework Questions

1.  What is the ``grep``command?
    > It is a command used to search given strings or words in a given file. It displays the matching lines.

2.  What is a *makefile*?
    >   This file contains type of commands that will be executed using "make" in terminal. 

4.  What does the ``-prune`` option of ``find`` do? Give an example
    >  This  command is used to limit the file searching process. It establishes in which directories the search should not be done. 
5.  Where is the ``grub.cfg``  file
    >   It is located in /boot/grub/grub.cfg

6.  How many files with ``gnu`` in its name are in ``/usr/src`` 
    > ubuntu-gnome@ubuntu-gnome:~/Documents/tutorial$ find /usr/src -name gnu |wc -l : 0

7.  How many files contain the word ``gpl`` inside in ``/usr/src``
    > ubuntu-gnome@ubuntu-gnome:~/Documents/tutorial$ grep -irm 1 gpl /usr/src | wc -l : 824

8.  What does the ``cut`` command do?
    >   This command is used to extract portion of text from a file by specifying columns. 

9.  What does the ``wget`` command do?
    >  This command is used to download files from the web. It supports HTTP, HTTPS and FTP protocols.

9.  What does the ``rsync`` command do?
    >   This command is used for coying and synchronizing files and directories remotively and locally too. 

10.  What does the ``diff`` command do?
    >   This command is used to analyze the differences between two lines. The output of this command is a set of instructions indicating how to change one file in order to make it identical to the other file. 

10.  What does the ``tail`` command do?
    >  This command outputs the last part of files. As standard output it print the last 10 lines of the file. 

10.  What does the ``tail -f`` command do?
    >   This command follow the ten last line sof the file and the new ones added. 

10.  What does the ``link`` command do?
    >   This command is used to link two files. It creates a hard link between both files which is named FILE2

11.  How many users exist in the course server?
    >  vision@ing-542:~$ users
       vision vision vision vision vision vision vision vision vision
       vision@ing-542:~$ users | wc -w
       9

12. What command will produce a table of Users and Shells sorted by shell (tip: using ``cut`` and ``sort``)
    >   answer

13. What command will produce the number of users with shell ``/sbin/nologin`` (tip: using ``grep`` and ``wc``)
    >   answer

15. Create a script for finding duplicate images based on their content (tip: hash or checksum)
    You may look in the internet for ideas, but please indicate the source of any code you use
    Save this script as ``find_duplicates.sh`` in this directory and commit your changes to github

16. What is the meaning of ``#! /bin/bash`` at the start of scripts?
    >  It calls the shell bash. #! is used to make the file execute where it is suposed. 

17. How many unique images are in the ``sipi_images`` database?
    >   answer
    
