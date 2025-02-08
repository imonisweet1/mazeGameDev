# Maze project
## Background Context
The goal of this project is to create a game in 3D using raycasting !

You don’t have to do the tasks in order, except for the first one (obviously), or if a task depends on a previous one

You have a link to a very good and very long tutorial about raycasting in the Tips and links section below, so read it very carefully, and practice !

Please have a lot of fun doing this project !<br>
![game](mazeGameDev/img/a.gif)
## Requirements
### General
- All your files will be compiled on Ubuntu 14.04 LTS, using gcc (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4
- We will use the gcc flags ```-Wall -Werror -Wextra``` and ```-pedantic```
- All your functions must be commented
- Your functions should be maximum 40 lines long (one statement per line)
- Your functions should be maximum 80 columns long
- No more than 5 functions per file
### Betty
- Your entire repository will be checked using Betty
- Don’t push any object files ```.o ```or temporary files ```*~```, or any unused source file if you don’t want to lose points !
- It is advised to always keep a clear organisation in your repository. For example, store all your sources in a ```src``` directory, and all your headers in a ```inc, headers``` or ```dependencies``` folder
## More Info
### Tips and links
- SDL2 - Get 
[started.pdf](sdl2.pdf)
- [SDL2 tutorials](https://lazyfoo.net/tutorials/SDL/index.php)
- Be careful with tutorials/help online: We are using [SDL2](), and not [SDL-1.2]() !
- [RAYCASTING !!!](https://permadi.com/1996/05/ray-casting-tutorial-table-of-contents/)
- [Alternative Raycasting Tutorial](https://lodev.org/cgtutor/raycasting.html)
### Important
- Don’t forget to install SDL2 [SDL2 tutorials](https://lazyfoo.net/tutorials/SDL/index.php)
- There are no forbidden functions for this project. You are allowed to use any system call and/or standard library function.
- You are allowed to use [all the functions provided by SDL2](https://wiki.libsdl.org/SDL3/CategoryAPI)
## Tasks
### 0. Walls !
In this first part, you’ll have to:

- Create a window with SDL2
- Use raycasting to draw walls on your window !
- You don’t need to be able to rotate the camera during the execution in this part, but you must provide a way to change the angle of the camera in your code to see if it works after recompiling it
- The color of the walls must be different from the color of the ground/ceil
- The map doesn’t need to be parsed from a file, but you must provide a way to modify it in your code to see if it works after recompiling it. (e.g. using an array of arrays of integers or characters).<br>
Example:![img](mazeGameDev/img/b.png)
In the following image, the camera is the red square, and the visible area is painted in green:


