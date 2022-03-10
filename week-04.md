## Week 4

### Context

This week we read two stories by Philip K. Dick. The first one was called, Pay for the Printer which follows the life of Allen Fergesson and charlotte in Detroit. They are living in a future world devastated by war and falling apart. They seem to rely on these alien machines called Biltongs that build and replicate things. It seems the world has fallen apart because people stopped doing things for themselves and just relied on something else to do everything for them. One quote that was striking from the story was from right after Charlotte apartment building was falling down and they realized even the Biltongs were dying, “She was silent. They all knew. The Biltong had become sterile in their struggle to keep the human race alive. Dead eggs, progeny hatched without life…” The second story was titled, The Preserving Machine, and was another science fiction tale all about someone named Doctor Labyrinth who imagines a preserving machine to preserve music in the form of animals. It creates some funky things like a Beethoven beetle. One follow up question I have from this story is what would the world be like if cultures and history were perfectly preserved? What would change if we knew everything about the past? Lastly, I watched part 2 of All Watched over by machines of loving grace. This episode called, the Use and Abuse of Vegetational Concepts, talks all about how we perceive the natural world and how it’s based on misconceptions about ecology and evolution.  

### Chapter 3 - Operating System, Recipes and outcomes:

#### 3.0. Introduction
- Much of 3.1-3.4 is covered in learn-computing/slides/command-line.html 
#### 3.1. Browsing Files Graphically
1. Demonstrate how to use the RPi Desktop
- file manager that is very similar to finder on MAC
- you can change directories and move files around
#### 3.2. Copying Files onto a USB Flash Drive
- [x] Use a USB flash drive with an RPi
#### 3.3. Starting a Terminal Session
- [x] Open the Terminal application on the RPi Desktop
#### 3.4. Navigating the Filesystem Using a Terminal
1. Explain essential UNIX CLI concepts: prompt, path, root, home, ~ (tilde) 
- prompt: pi@raspberrypi: ~ $
- path: is made up of words separated by a /, can be absolute and relative
- root: of the file system = /
- home: your home directory (/home/pi)
- ~ (tilde):shorthand for your home directory

2. Demonstrate basic UNIX filesystem command(s): cd, ls, pwd, man

![Screen Shot 2022-03-09 at 8 32 08 PM](https://user-images.githubusercontent.com/70282901/157569475-34ab329f-f86f-4b4e-b8d8-39367ef151d7.png)

3. Demonstrate intermediate shell usage: tab, * (wildcards), listing hidden files

![Screen Shot 2022-03-09 at 8 36 23 PM](https://user-images.githubusercontent.com/70282901/157569925-f54254ab-ceab-4db3-89aa-d0e050ae988b.png)

#### 3.5. Copying a File or Folder
1. Demonstrate command(s): cp 
 
![Screen Shot 2022-03-09 at 8 39 11 PM](https://user-images.githubusercontent.com/70282901/157570183-a12925f6-4438-4dd7-bbeb-9252021020cf.png)

#### 3.6. Renaming a File or Folder
1. Demonstrate command(s): mv 

![Screen Shot 2022-03-09 at 8 40 13 PM](https://user-images.githubusercontent.com/70282901/157570291-a33c7079-cc9a-4a0c-a20d-43419157ebae.png)

#### 3.7. Editing a File
1. Demonstrate how to use nano text editor to open, edit, save, close a file
- nano filename.txt is ot open and create file, ^o is save, then hit enter, then ^x to exit

![Screen Shot 2022-03-09 at 8 41 52 PM](https://user-images.githubusercontent.com/70282901/157570474-35a821d8-e473-4c23-a370-8d9e1e5bc487.png)

#### 3.8. Viewing the Contents of a File
1. Demonstrate command(s): cat, more

![Screen Shot 2022-03-09 at 8 43 32 PM](https://user-images.githubusercontent.com/70282901/157570641-de4bc889-42b6-457c-91c0-3ababa2c323d.png)

#### 3.9. Creating a File Without Using an Editor
1. Demonstrate how to use echo with the ">" character to export a string to a file

![Screen Shot 2022-03-09 at 8 45 10 PM](https://user-images.githubusercontent.com/70282901/157570826-62ac499c-83db-4615-82db-c856d2831957.png)

#### 3.10. Creating a Directory
1. Demonstrate command(s): mkdir

![Screen Shot 2022-03-09 at 8 46 09 PM](https://user-images.githubusercontent.com/70282901/157570947-52f24243-2d39-415e-a119-9d917d0bca06.png)

#### 3.11. Deleting a File or Directory
- Be careful when removing files and directories!
1. Demonstrate command(s): rm

![Screen Shot 2022-03-09 at 8 47 23 PM](https://user-images.githubusercontent.com/70282901/157571451-d78c58e8-91ae-4469-83c7-9e3cb46e4337.png)

#### 3.12. Performing Tasks with Superuser Privileges
1. Demonstrate how to reboot the RPi from the CLI
- $ sudo reboot
- $ sudo sh 

#### 3.13. Understanding File Permissions
1. Demonstrate how to view permissions for files in a directory

![Screen Shot 2022-03-09 at 8 49 07 PM](https://user-images.githubusercontent.com/70282901/157572177-39744bc6-471c-4657-a3eb-f14d3242984a.png)

3. Explain the three types of owners, and the three types of permissions they might have for each file.
- owner types: user is the one who created the file and can create, modify or deleter file, group can contain multiple users who all have the same access and other is anyone else who has access to the file. 
- permission types: read (r) allows you to open and read the file, write (w) allows you to edit, rename, and remove, execute(x)aloows you to run and execute a file
#### 3.14. Changing File Permissions
1. Explain why you might use chmod
- allows you to add or remove permissions for a file
- first parameter is the change to make, and the second is the file or folder to which it should apply
#### 3.16. Making a Screen Capture
1. Recall which command to use for making a screenshot: **scrot**
#### 3.18. Removing Software Installed with apt-get
1. Demonstrate how to install and remove packages with apt
- $ sudo apt-get install abiword
- $ sudo apt-get remove abiword
#### 3.19. Installing Python Packages with Pip
1. Demonstrate how to install and remove Python libraries with PIP

![Screen Shot 2022-03-09 at 9 01 34 PM](https://user-images.githubusercontent.com/70282901/157573574-f6539c8f-42c3-40dc-8bc7-a344b6d9a006.png)

#### 3.20. Fetching Files from the Command Line
1. Demonstrate how to use wget
- use the wget command to fetch a file from the internet
- $ wget http:// ...
#### 3.21. Fetching Source Code with Git
1. Demonstrate how to use Git to clone a repository with source code 
- https://github.com/omundy/dig333-raspberry-pi 

![Screen Shot 2022-03-09 at 8 49 07 PM](https://user-images.githubusercontent.com/70282901/157574064-dd523fb2-b17c-488b-be63-dc0ac938c399.png)

2. Demonstrate how to use Python to execute the script inside ^ topics/introduction/01-hello/hello.py 

![Screen Shot 2022-03-09 at 9 15 14 PM](https://user-images.githubusercontent.com/70282901/157574999-5991d055-55ed-4b78-ba7f-2772ed53b6d7.png)

4. Demonstrate how to clone your own (DevLog) repository, edit files, stage, commit, and push the code back to Github.

![Screen Shot 2022-03-09 at 9 26 12 PM](https://user-images.githubusercontent.com/70282901/157576186-aaf1dc79-e6ea-4447-b358-eb33e4127f1d.png)

![Screen Shot 2022-03-09 at 9 25 39 PM](https://user-images.githubusercontent.com/70282901/157576101-0d139981-365a-4812-bf7b-5402f09a818f.png)


#### 3.22. Fetching This Book’s Accompanying Code
- https://github.com/simonmonk/raspberrypi_cookbook_ed3 
#### 3.23 to 3.240
- Skim or return to the following sections when needed.


### Chapter 5 - Python Basics, Notes:
- use python3 until you need to use python 2
- you can edit programs withn Mu it is preinstalled
- you can use python console in terminal: $ python3 then $ exit() when done
- to run a python3 program: $ python3 myfile.py
- assign a value a name using =
- use print to see the value of a varibale: print(a)
- in order to ask for user input use input() command
- Use the +, -, *, and / operators to perform arithmetic
- use quotes to create a string
- use + to join strings
- use str to convert numbers into strings
- use int or float to convert string into number
- use len to fins the length of a string
- use find to find the position of one string in abother string
- use .upper() adn .lower() to convert the case of a string
- use the if/else/elif command to run something conditionally
- to compare two values use <, >, <=, >=, ==, or !=
- a for loop is used to do something a certain number of times
- to repeat something until something else happens you cn use a while loop
- to break out of either loop use the break command
- defining a function: def function():
- then to run the function: function()

