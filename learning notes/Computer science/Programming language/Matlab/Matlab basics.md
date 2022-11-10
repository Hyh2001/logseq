# window structure
Current folder.    Command window.      Workspace
# path 
List of folders through which a program searches for a file. 
## set path
Use set path button

# command window
## clc
Clean the command window
## clean variable name
Clean all the variables if there is no name provided
## prompt
A symbol used by matlab while it is running to request an action from the user.
## quit environment
	quit()
## regain control 
Ctrl-c
## suppressing printing 
use Colons

	X = 5
## saving variables
Save all the variables in a .mat file
	
	save
### loading variables


## continue a command
Add … at the end
## repeating a command
Use up-arrow key 
# semantics
## [[Matlab Naming rules]]
## get help for commands
### help
	help command name
### lookfor 
	lookfor xyz
will search *xyz* through command summaries
# write command into a file
## Create .m file
1. Create new script
2. Type edit in the command window 
3. Save the file
## execute .m file 
Type the name of the .m file without .m in the command line.
## comments
Starting the line with a percent sign (%)
### block comments 
Ctrl + r for comment the whole block 
Ctrl + t for uncomment the whole block
# plot figures 
```matlab
plot(x,y)
%x and y are ordered lists 
```
## close figures
```matlab
close
```
## plot a picture
```matlab
a = imread(‘name’)
image(a)
truesize     %each color in the array to be displayed by exactly one pixel
```
# basic commands:
1
4. format
5. rand(0-1 with no parameters)
6. tab(completion )
7. load (load .mat file)
8. semi-colon(;) : a semi-colon in the end will prevent echo and it can also allow multiple commands in one line 
9. ... continue one statement in the next line
