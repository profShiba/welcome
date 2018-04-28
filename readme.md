# Hello and welcome to year one IBCS!

Here is your user documentation for the first lesson. This guide will take you through the steps of setting up a developers environment. Make sure your are familiar with the following terms:

- [what is user documentation](http://www.teach-ict.com/as_a2_ict_new/ocr/A2_G063/331_systems_cycle/slc_stages/miniweb/pg20.htm)
- [what is a developers environment](https://en.wikipedia.org/wiki/Deployment_environment)
- [IDE](https://computersciencewiki.org/index.php/IDE)
- [package manager](https://en.wikipedia.org/wiki/Package_manager)
- [version control](https://whatis.techtarget.com/definition/version-control)
- [object-oriented programming](https://computersciencewiki.org/index.php/Object-Oriented_Programming)
- [terminal](https://www.quora.com/In-coding-terms-what-is-a-terminal-and-what-is-it-used-for)
- slack
- gitlab


## Slack: Sign up for and download slack. 

This is how you will get class notes and todos. Slack is basically taking all the good parts of email and leaving the bad parts behind

- [slack](https://slack.com/signin)

our team name is ibcs2018

## Download sublime text 3:

This will be your IDE for the course. The terminal is where you will run your code.

- [sublime](https://www.sublimetext.com/3)

To really make sublime your own, check out what plugins it has
- [make sublime great](https://packagecontrol.io/)
- [wow my life is so easy now](https://www.sitepoint.com/10-essential-sublime-text-plugins-full-stack-developer/)
 

## Download homebrew:
This is your package manager. Basically, it is an easy way to download software, stay updated, and manage dependencies.
- [brew](https://brew.sh/)

## Install Oh-my-zsh:
- [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)

### For advanced users only:
If you are new to the terminal, skip this part. You can seriously damage your computer if you mess up these steps!

- enable st . as a hotkey for sublime
- [Here is the documentation](https://github.com/robbyrussell/oh-my-zsh/tree/master/plugins/sublime)

## Install python3 with brew
``` bash
brew install python
```

## Make sure ruby is up to date
```bash
brew install ruby
```

## Create a GitHub account
Make sure you keep it professional. This is how the whole programming world will know you
- [github](https://github.com/)


# Project Initium
What is IBCS? Well, it is meant to teach you about hardware, software, networks, programming, the design cycle, version control, etc. There is a ton of material. So, being organized is key. 


The first goal of this lesson is to ensure organization. The second goal is to acquaint you with a project-based class. The final goal is to introduce you to managing ambiguity, meaning often times, you will feel lost, confused, and overwhelmed. This is completely normal. All you need to do is accept that this is normal and try your best!

Please email me with any questions or if you get stuck! I will be around campus until August.

## Course Norms:
Every time you write a program, the follow will be expected:

- All programs must have comments
- After each program, I will ask you to explain your work in a short paragraph (3-5 sentences)

## Exams
You will only have two tests this year. A midterm and a final. Both of which are old IB exams. If you give this your all, you will ace the course and IB exam!

This means you will have to do work outside of class in order to pass the exams.


## Part One: Terminal Commands
Create the following file structure in a root dir on your desktop called year_one_ibcs. Complete this task using the terminal. If you don't know what a terminal is our any terminal commands, no worries. That is the goal of this project!

[learn terminal](https://www.learnenough.com/command-line-tutorial)
In order to create part one, you'll need to know how to:

- navigate in the terminal
- create folders
- create files
- remove folders/files
- run a ruby and python program
- what a file path is

### Directories at the root level:
Once you have learned enough terminal to be dangerous, make the following file structure:
- unit_0
- unit_1
- unit_2
- unit_3
- unit_4
- oop
- adt
- api
- networks
- control
- extras

These are all the topics covered in year one

### Directories within each unit
All directories need the following three folders inside of them
- programming
- projects
- notes


## Part Two: User Documentation

Learn to use [markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) and create a bio in unit_0. You can fill with any information you like. Just make sure to include:

- what you want out of the class
- experience level
- some sort of picture
- a snippet of code that stands out to you (not too long!)

## Part Three: Hello World
On the first day of class, you will be asked to run your hello_world program as your introduction to the class. Hello world is a programming tradition when learning a new language. For your hello world, you will print out a few strings from your bio.

A string is a form of datatype in programming, which is composed of a sequence of characters.

#### How-to
In unit_0/programming create a file called hello_world. If you want to use ruby add .rb to the end of the file, and if you want to use python use .py at the end of the file. The extension lets the computer know what language to expect.

Example:

ruby: unit_0/programming/hello_world.rb
```ruby
puts "Hello, I'm Mr. James and I'm from Chicago and loves dogs"
puts "Machine learning is my hobby, and I one day want to live on Mars"
```

python: unit_0/programming/hello_world.py
```python3
print("Hello, I'm Mr. James and I'm from Chicago and loves dogs")
print("Machine learning is my hobby, and I one day want to live on Mars")
```

To run the program, navigate your terminal to the same dir level. Type ls in the terminal. You should see your program.

```bash
ls
hello_world.py hello_world.rb
```

If using ruby

```ruby
ruby hello_world.rb
```

If using python

```python3
python3 hello_world.rb
```

Your terminal should now show the strings you have programmed. Congrats!!!

#### Debug
The terminal will give you clues as to why your program isn't working. For this program, if you are having trouble, check to make sure

- you saved the program
- you have the right file path when running the program

## Policies 

- Life happens, if you are going to turn work in late I need an email 48 hours before the work is due asking for an extension. 

- Office hours are a real thing! Many students will need to take advantage of this during the year

- If you need a letter of reference, allow at least seven days for completion 

