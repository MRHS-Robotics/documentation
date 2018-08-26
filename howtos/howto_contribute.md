# How to Contribute

This site is hosted in GitHub Pages and redirected from our team 
domain at [http://mrhsrobotics.com](http://mrhsrobotics.com).  The source material for this site is managed in our 
[GitHub repository](https://github.com/MRHS-Robotics/mrhs-robotics).   

So how do team members update this site?  

It's actually pretty easy, and doesn't require any previous experience with web development.  It does, however, require 
that you install some tools on your computer, and have a willingness to learn "markdown" which is a kind of 
text formatting shorthand.  If you've ever updated a wiki page, it should look pretty familiar to you.

In this HOWTO, we will be using a terminal window to enter some text commands into a "bash" shell.  All of the 
commands you need are provided explicitly, so you don't need to know or learn bash.  But, you may find it interesting
 to know why we are using the commands we are, and what other commands are available.  If so, have a look at this 
 [bash cheatsheet](https://courses.cs.washington.edu/courses/cse390a/14au/bash.html).

## Before You Begin

1. Create an account on [github.com](https://github.com)
2. Get a team leader to add you to the [MRHS-Robotics organization](https://github.com/MRHS-Robotics)
3. Download and install [git](https://git-scm.com/) on your computer

If installing to a PC, be sure to include the "bash" shell option.

## Clone the GitHub Repository

To update the MRHS Robotics site you will first need a copy of the source files.  You obtain this copy by "cloning" 
the GitHub repository to your own computer.  Follow these steps to clone the repository.

1. Open a command-line window:
    * linux: open terminal 
    * mac: ```⌘-space```, type "terminal", then press ``enter``
    * pc: open the "bash shell" that came with your git install
  
2. Change to your Desktop folder/directory
    ```
    cd ~/Desktop
    ```

3. Use git to clone the repository to your computer
   ```
   git clone git@github.com:MRHS-Robotics/mrhs-robotics.git 
   ```
   
4. Change to the newly created ``mrhs-robotics`` folder/directory
   ```
   cd mrhs-robotics
   ```
   
5. Verify the clone worked by listing the contents of ``mrhs-robotics``
   ```
   ls -1
   ```
   You should see something like this:
   ```
   README.md
   _config.yml
   howtos
   images
   ```
   Yay, it worked!
   