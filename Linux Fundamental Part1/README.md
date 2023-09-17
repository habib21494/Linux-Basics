
1) Q=: What year was the first release of a Linux operating system?
  A=: 1991

2) Q=: If we wanted to output the text "TryHackMe", what would our command be?
   C= echo
   A=: echo tryhackme

3) Q=: What is the username of who you're logged in as on your deployed Linux machine?
   C= whoami
   A= TryHackMe

4) Q=: On the Linux machine that you deploy, how many folders are there?
   C=: ls
   A=: 4

5) Q=: Which directory contains a file? 
   C=: cd 
   A=: Folder4

6) Q=: What is the contents of this file?
   C=: cat
   A=: Hello World

7) Q=: Use the cd command to navigate to this file and find out the new current working directory. What is the path?
   C=: pdw
   A=: /home/tryhackme/folder4

8) Q=:Use grep on "access.log" to find the flag that has a prefix of "THM". What is the flag?
   C=: grep
   A=:THM{ACCESS}

9) Q=: If we wanted to run a command in the background, what operator would we want to use?
   C=: &
   A=: &

10) Q=: If I wanted to replace the contents of a file named "passwords" with the word "password123", what would my command be?
    C=: echo > 
    A=: echo password123 > passwords

11) Q=: Now if I wanted to add "tryhackme" to this file named "passwords" but also keep "passwords123", what would my command be
    C=: echo >>
    A=: echo tryhackme >> passwords

12) Q=:What directional arrow key would we use to navigate down the manual page?
    A=: down

13) Q=:What flag would we use to display the output in a "human-readable" way?
    C=: 
    A=: -h

14) Q=: How would you create the file named "newnote"?
    C=: touch
    A=: touch newnote


15)  Q=: On the deployable machine, what is the file type of "unknown1" in "tryhackme's" home directory?
     C=: cat
     A=: ASCII text

16)  Q=: How would we move the file "myfile" to the directory "myfolder" 
     C=: mv
     A=: mv myfile myfolder


17)  Q=: What are the contents of this file?
     C=: file
     A=: THM{FILESYSTEM}


18) Q=:On the deployable machine, who is the owner of "important"?
    C=: su 
    A=: user2


19)  Q=: What would the command be to switch to the user "user2"?
     C=: su 
     A=: su user2


20)  Q=: Output the contents of "important", what is the flag?
     C=: cat
     A=: THM{SU_USER2}


21) Q=:What is the directory path that would we expect logs to be stored in?
    C=: 
    A=:/var/log


22)  Q=:What root directory is similar to how RAM on a computer works?
     A=:/tmp


23) Q=:Name the home directory of the root user 
    A=: /root




 



