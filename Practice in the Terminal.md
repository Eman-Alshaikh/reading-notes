
 ##  :red_square: The Command Line!
 A terminal, is a text based interface to the system. Where you can enter the commands to do multiple tasks  .
  i will present some of these commands and how i applied them on mt system : 
 
 ##  :red_square: Basic Navigation 
 :small_blue_diamond:  pwd:  It tells you what is your current working directory .

  :small_blue_diamond:ls [options] [location]: 
 these square brackets ( [ ] ) mean that the items inside them are optional. 

:small_blue_diamond:ls list the contents of the current directory.

:small_blue_diamond: cd : to  move into another directory.
![1](https://user-images.githubusercontent.com/97835837/155716178-050ef99d-5f1e-4864-bb82-9a099d25f01c.PNG)

 ![2](https://user-images.githubusercontent.com/97835837/155717183-1de0a84b-7349-4338-a266-2947cae3539a.PNG)

 ##  :red_square: More About Files 
 Linux is Case Sensitive , so i got this error when i write ASAC in small case :
 
 ![3](https://user-images.githubusercontent.com/97835837/155719009-1903c4f4-62ea-4f19-9fe4-fba4ee294fee.PNG)

:small_blue_diamond: file :
tell you what is the  type of file or directory.

:small_blue_diamond: ls -a : List all the contents of a directory, including hidden files inside it .

![4](https://user-images.githubusercontent.com/97835837/155724444-e31f2ffd-230f-4cc6-9c0a-453ec6deff1d.PNG)


 ##  :red_square: Manual Pages 
 The manual pages are a set of pages that explain every command available on the system including what they do.
 
:small_blue_diamond: man ls :
Look up the manual page for the ( ls )command.

![5](https://user-images.githubusercontent.com/97835837/155726277-fef6a5eb-0658-4658-a17c-4873eb6e7de8.PNG)

##  :red_square: File Manipulation 
:small_blue_diamond: mkdir : Create a new directory.

![6](https://user-images.githubusercontent.com/97835837/155728925-d03a4620-58f4-4188-9025-39d0b05eab6d.PNG)

:small_blue_diamond:rmdir: Delete a directory.

![7](https://user-images.githubusercontent.com/97835837/155729914-c4547341-576d-4012-890a-fa7ded62dccd.PNG)

:small_blue_diamond:touch:Create a blank file.

![image](https://user-images.githubusercontent.com/97835837/155730232-2e13200f-33b0-4392-a412-14c6ff15b2c6.png)

:small_blue_diamond: cp:Copy a file or directory.

![image](https://user-images.githubusercontent.com/97835837/155730597-46c5d4e8-7529-4165-ac7c-ae998e1ee839.png)

:small_blue_diamond:mv:Move a file or directory (can also be used to rename).

![image](https://user-images.githubusercontent.com/97835837/155731993-9a48af9d-fd77-442e-9d13-53b48091ceca.png)


:small_blue_diamond:rm : Delete a file.

![image](https://user-images.githubusercontent.com/97835837/155732952-32779792-3e51-482a-ab0d-ede61da86986.png)

##  :red_square: Cheat Sheet 
 

:small_blue_diamond: du -sh ./* :
Find the size of every directory in your current directory.
![image](https://user-images.githubusercontent.com/97835837/155734316-2bfc1e61-f7d4-404f-a929-cd9b8f6854d7.png)

:small_blue_diamond:df -h
Display how much disk space is used and also free.
![image](https://user-images.githubusercontent.com/97835837/155734685-be40a4f8-f3ef-46a5-bb80-956299716d37.png)
