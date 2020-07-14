# Terminal Walk Through
​
## Lesson Objectives
​
After this workshop, participants will be able to
​
* Use Terminal to navigate files and folders
* Change preferences
* Create files and folders on the command line
* Build and open and use a file structure

## Terminal
​
**Open Terminal**
​
- `⌘ (Command) + Space`, or open Spotlight
- "Terminal"
- `Enter`
​
- Keep it locked in your dock. Right click on the icon, highlight options, check "Keep in Dock".
​

**Terminal Preferences**
​
You can change the color of your Terminal and the font size. It is recommended to make your Terminal output easier to read, rather than the tiny default output.
​
> Terminal > Preferences > Pro
​
<br>
<hr>
​

- Before this code along type this in the terminal `brew intsall tree`
- `ls` command just shows the directories while `tree` shows that and the files within
- This makes it easy to see the file structure in your current working directory
- Very powerful command so be careful where your at when you run the `tree` command

<br>
<hr>
​

## MAKING DIRECTORIES AND FILES
​
`mkdir` - makes a directory

<br>
​
Example:
​
- `mkdir directory_name`
​
	> makes a directory called 'directory_name'`
​
<br>
​
`touch` - creates an empty file. A file typically will have a **file extension** like `.html` whereas a directory will not.
​
​
Example:
​
- `touch index.html`
​
	> makes a .html file
​
<br>

​
## Success tip: staying organized throughout the class
​
* Be obsessive, starting today
* Inside your home folder, create a folder where everything from the class will live, and always put everything from class in there:
​
Example:
​
- `mkdir SEA`
​
	> makes a SEA folder


* In that folder, make a new folder for each topic we will be going over in class. Suggestion below:
​
- `mkdir web_dev_fundamentals`
- `cd web_dev_fundamentals`
​
* In that folder make a new folder for each lesson or lab or homework and give that folder a nice descriptive name, for example:
​
- `mkdir practice_terminal`
- `cd practice_terminal`
- `pwd`
- typing in pwd just to make sure we are in the right directory

​
​
<br>
​<hr>

## Activity
​
​
**Build, Navigate a Directory**<br>
​
​
Using what you know about navigating directories and creating files and folders, construct a 'hello_world' in today's folder.

<br>

​
**Precision** is important. There are a few layers to this exercise. Be patient.
​
- Make sure you are in the correct directory when you go to create another directory or file.
- Be sure to always check this by the command `pwd`
- Make sure you use `touch` to make files, and `mkdir` to make directories. **files** and **directories** are two different things.
​
* Create today's folder structure
- `mkdir hello_world`
- `cd hello_world`​
- `touch index.html`
- `mkdir css`
- `mkdir js`

​
**css** and **js** are child directories of the hello_world directory.<br>
​
​
**index.html** is a file inside the the hello_world directory which is also the root directory.<br>
​
​
If you make a mistake, don't worry, just keep adding the right stuff to the right place.
​
​
<br>
<hr>
​

## Navigation: RELATIVE PATHS
​
Chain more directories to the current path with the `/` separator
​
- Go down the chain into child directories
	- `cd parent_directory`
	- `cd parent_directory/child_directory`
	- `cd parent_directory/child_directory/grandchild_directory`
​
- Go up the chain into parent directories
	- `cd ..`
	- `cd ../..`
	- `cd ../../..`
​
- Go sideways into a sibling directory by first going up, then down
	- `cd ../sibling_directory`
​
- Go into an aunt or uncle directory by first going up to the parent, then the grandparent, then down again on another branch:
​
	- `cd ../../auntie_directory`
​
<br>

​
## Navigation: ABSOLUTE PATH
​
Move anywhere relative to the home directory: 
​
`cd ~/` - the path starts in home directory

<br>
​
Example:
​
- `cd ~/hello_world/js`
​
Navigates to the js folder no matter where you are currently located in your filesystem
​
> NOTE: You can combine absolute and relative pathing when copying or moving files from one location to another with `cp` and `mv`.
​
#### Jump back
​
- `cd -` if you cd to a (far-away) absolute path you can go to the previous directory this way
​

<br>
​

**Code along**<br>
​
​
**Navigate the hello_world**<br>
​
​
* Navigate to the hello_world root directory
* From the hello_world root directory, navigate to the `js`
* From the `js`, navigate to the `css`
* From the `css`, navigate to the root directory
​
<br>
​

**Activity**<br>
​

​
**Create file structure**<br>
​
​
For each of these, write your command on one line
​
* Navigate to the root directory
* check where your at with the `pwd` to make sure your in the right folder
* From the root directory, navigate to the `css`
* From the `css` create a file `style.css`
* From the `css`, navigate back up the root directory
* From the root directory, navigate to the `js`
* From the `js`, create a file `app.js`
* From the `js`, navigate to the root
* From the root directory type in the `tree` command
* You should be able to see your file structure now

​
<br>
<hr>

​
## Take aways

- Should now be able to navagate through your computer

- Be able to create folders and files



