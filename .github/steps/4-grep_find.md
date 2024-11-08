<!--
  <<< Author notes: Step 4 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
  TBD-step-4-notes.
-->

# Week 4

The goal of this week is:
- searching and editing files
- creating aliases
- learn about environmental variables

## 1. :book: Week 3 review
If you would like to read more from Software Carpentry to review week 3:
- [Loops](https://swcarpentry.github.io/shell-novice/05-loop.html)
- [Shell Scripts](https://swcarpentry.github.io/shell-novice/06-script.html)


## 2. :book: Searching and editing files
- Read from [Software Carpentry to learn about `grep` and `find` commands](https://swcarpentry.github.io/shell-novice/07-find.html)
- Read from [How-To Geek website about `sed` command](https://www.howtogeek.com/666395/how-to-use-the-sed-command-on-linux/)

## 3. :keyboard: :white_check_mark: Exercise 1: Explore repository content

Open Codespace and start using `find` command to explore content of the repository. You should check all the files and directories. You might notice that there are many files that you haven't seen before because they were inside "hidden" files and directories that starts with dot, `.`. They are part of the repository, but they are not meant to be edited by the user.

In the new branch that was created for this week, `week4`, you will find a new directory, `week4`, that will be used as a working directory for this week. In this directory create a new file `output_find.txt` that will contain all the files of the repository that have `txt` extension.  


## 4. :keyboard: :white_check_mark: Exercise 2: Creating a script to search files

In the new branch that was created for this week, `week4`, you will find a new directory, `week4`, that will be used as a working directory for this week. In the directory you will find `massachusetts_cities.csv` file.
Create a script that finds all cities that have "North" in the name and save it to the new file `output_cities.txt`, but instead of using format "<City>, <Population>" use a syntax "<City> has population of <Population>".

## 5. :book: Environmental Variables

An addditional topic that might be worth exploring is Environmental Variables. 
You could read more from [Geeks for Geeks about the topic](https://www.geeksforgeeks.org/environment-variables-in-linux-unix/).

## 6. :keyboard: Practice using Environmental Variable

Explore the environment variables in the Codespace. Check your current working directory, home directory, and print all environmental variables using `printenv`. Try to set a new variable.
If your local computer has UNIX or OSX system, compare the variables with your local system.

> [!TIP]
> If you don't remember how to open Codespace, create a new file and add to the repository, you can review instruction from the previous week [here](./week1/Readme.md)

##

> [!IMPORTANT]
> Update the repository in  order to move to the next week/part of the course:
>  - Create a Pull Request to the `main` branch
>  - Check the status of tests
>  - If all tests pass, merge the Pull Request, this should update a new `README.md` on the main page of the repository (you can reload the page after 30-60s if you don't see the new content)

