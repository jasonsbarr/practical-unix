# Practical Unix: Mastering the shell and command line tools

This is an introduction to the Unix command line and some of the most important Unix tools a developer needs to know.

In addition to the specific command line tools covered, we will also have a crash course on C and learn two different ways to program the Unix system:

- Scripting (Bash, Python)
- Using system APIs (C)

Fluency in Unix is an indispensible skill for a software engineer. Unix is everywhere: servers, development environments, virtual machines, containers... the reality is if you're not comfortable in a Unix environment you'll be at a serious disadvantage relative to other developers who are.

## Course purpose and goals

The purpose of this course is to teach the Unix system from a developer's perspective (i.e. it is *not* a systems administration course).

The course covers general usage of the Bash shell, plus several important command line tools including Git, tmux, Sed, and Awk. It also covers tools used in the developer's toolchain, including GCC and Make. You will learn how to program the system using Bash scripts that connect operations using CLI tools and commands and how to program the Unix system itself using C.

The main goal is to learn how to manage your software projects and day-to-day development tasks by gaining mastery over the Unix system.

## Operating systems and software

This course will focus on the latest LTS version of Ubuntu (20.04), but the skills you develop will be applicable to other Linux distros and non-Linux systems like FreeBSD.

## Topics covered

- Installing Linux on a virtual machine
- Introduction to Unix
- Navigating the file system
- Using the package manager
- Working with files and text
- Grep and regular expressions
- Streams, processes and jobs
- Text manipulation with Awk and Sed
- Vim
- Bash shell scripting
- Python shell scripting
- Version control (Git and GitHub)
- Automation and timing (cron, etc.)
- Terminal multiplexing (tmux)
- C programming
- Make and build systems
- Basic systems programming
- Building your own Unix tools

## Sources

### University courses

- [Cornell CS 2043 (Spring 2014) - Unix Tools & Scripting](https://www.cs.cornell.edu/courses/cs2043/2014sp/)
- [Stanford CS 1U - Practical Unix](https://practicalunix.org/)
- [Berkeley CS 9E - Productive Use of the Unix Environment](https://selfpaced.bitbucket.io/#/unix/calendar)
- [Penn CIS 191 - Linux and Unix](https://www.cis.upenn.edu/~cis191/)
- [MIT - The Missing Semester of Your CS Education](https://missing.csail.mit.edu/)
- [Michigan - Computing for Computer Scientists](https://c4cs.github.io/archive/w18/)
- [Carnegie Mellon 07-131 - Great Practical Ideas in CS](https://www.cs.cmu.edu/~07131/f19/)
- [Carnegie Mellon 15-123 (Spring 2011) - Effective Programming in C and Unix](https://www.cs.cmu.edu/~guna/15-123S11/)
- [Miami CSC 322 (2002) - C Programming and Unix](https://www.cs.miami.edu/home/schulz/CSC322.html)
- [Harvard CS 50](https://www.youtube.com/playlist?list=PLhQjrBD2T381L3iZyDTxRwOBuUt6m1FnW) (lectures 1-5)

### Books, study notes, etc.

- [*GNU Coreutils*](https://www.gnu.org/software/coreutils/manual/html_node/index.html) (freely available)
- [*Small, Sharp Software Tools: Harness the Combinatoric Power of Command-Line Tools and Utilities*](https://pragprog.com/book/bhcldev/small-sharp-software-tools), by Brian P. Hogan
- [*The Linux Command Line: A Complete Introduction*](http://linuxcommand.org/tlcl.php), by William Shotts (freely available)
- [*A Practical Guide to Linux Commands, Editors, and Shell Programming*, 4th ed.](https://www.amazon.com/Practical-Guide-Commands-Editors-Programming/dp/013308504X), by Mark G. Sobell & Matthew Helmke
- [*grep Pocket Reference: A Quick Pocket Reference for a Utility Every Unix User Needs*](https://www.amazon.com/grep-Pocket-Reference-Utility-OReilly/dp/0596153600), by John Bambenek & Agnieszka Klus
- [*Learning Regular Expressions*](https://www.amazon.com/Learning-Regular-Expressions-Ben-Forta/dp/0134757068), by Ben Forta
- [*sed & awk*, 2nd ed.](https://www.amazon.com/sed-awk-Dale-Dougherty/dp/1565922255), by Dale Dougherty & Arnold Robbins
- [*Modern Vim: Craft Your Development Environment with Vim 8 and Neovim*](https://pragprog.com/book/modvim/modern-vim), by Drew Neil
- [*Advanced Bash-Scripting Guide*](https://tldp.org/LDP/abs/html/), by Mendel Cooper (freely available)
- [*Beginning Git and GitHub: A Comprehensive Guide to Version Control, Project Management, and Teamwork for the New Developer*](https://www.amazon.com/Beginning-Git-GitHub-Comprehensive-Management/dp/1484253124), by Mariot Tsitoara
- [*Pro Git*, 2nd ed.](https://git-scm.com/book/en/v2), by Scott Chacon & Ben Straub (freely available)
- [*Tmux 2: Productive Mouse-Free Development*](https://pragprog.com/book/bhtmux2/tmux-2), by Brian P. Hogan
- [*Head First C*](https://www.amazon.com/Head-First-C-Brain-Friendly-Guide/dp/1449399916), by David Griffiths & Dawn Griffiths
- [*Learn C Programming Tutorial*](https://fresh2refresh.com/c-programming/) (freely available)
- [*Essential C*](http://cslibrary.stanford.edu/101/), by Nick Parlante (freely available)
- [*Pointers and Memory*](http://cslibrary.stanford.edu/102/), by Nick Parlante (freely available)
- [*Unix Programming Tools*](http://cslibrary.stanford.edu/107/), by Stanford Faculty (freely available)
- [*The GNU Make Book*](https://nostarch.com/gnumake), by John Graham-Cumming
- [*GNU Make Manual*](https://www.gnu.org/software/make/manual/make.html) (freely available)
- [*Introduction to Systems Programming: a Hands-on Approach*](https://www.cs.purdue.edu/homes/grr/SystemsProgrammingBook/), by Gustavo A. Junipero Rodriguez-Rivera & Justin Ennen (freely available)

## Assessment and best practices for learning

There is no formal assessment for this course. Projects will be chosen from the various materials used to cover course topics. You win if you can get them all to work properly.

Doing as many practice exercises and programming projects as possible is far more important than consuming additional information (e.g. reading more books or tutorials) for getting the material to stick in your brain. You should also take notes on the readings and other materials, and quiz yourself regularly. Give yourself as many chances to practice your recall of the material as possible.

Close the book or turn off the computer screen, turn over your notes so you can't look at them, then ask yourself the question, and then say aloud or write down the answer. Then go back to the material to check if you were right. If you were wrong, make notes! Don't just be wrong; make a note of the correct answer and give yourself additional opportunities to get it right.

Practice "[holistic learning](https://www.scotthyoung.com/blog/Programs/HolisticLearningEBook.pdf)."

Keep a "Feynman notebook" of the course materials as you go. Write as much of the material as you can from memory. If you can do this, you've got it down. ([information about the Feynman technique](https://collegeinfogeek.com/feynman-technique/))

It will feel like a real struggle and you *will* get frustrated. That's ok, though&ndash;when you're struggling the most is the time when your brain is really working to learn the material! The struggle bus is the only path to true mastery.

## Course materials

1. Installing Linux on a virtual machine
    - [Vagrant documentation](https://www.vagrantup.com/docs/)
    - [Official Ubuntu 20.04 Vagrant box](https://app.vagrantup.com/ubuntu/boxes/focal64)
2. Introduction to Unix
    - Files and the file system
    - Basic CLI utilities
    - Permissions
    - Working with text files
    - Pipes and redirecting
    - Packages and the package manager
    - Completion and history
3. Advanced basics
    - The environment
    - Grep and regular expressions
    - Storage media
    - Searching for things
    - Formatting output
    - Archiving and backup
    - Compiling from source
4. Streams, processes, and jobs
5. Text processing, awk, and sed
6. Vim
7. Basic networking
8. Bash shell scripting
9. Python scripting
10. Git and GitHub
11. Automation and timing
12. Terminal multiplexing with tmux
13. C programming
14. Make and Unix build tools
15. Basic systems programming with C
16. Building your own Unix tools

## License

All materials created by me are released under the MIT license. Other materials are &copy; to their respective authors and creators.
