# Practical Unix: Mastering the shell and command line tools

This is an introduction to the Unix command line and some of the most important Unix tools a developer needs to know.

In addition to the specific command line tools covered, we will also have a crash course on C and learn two different ways to program the Unix system:

- Scripting (Bash)
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
- [*Practical C Programming: Solutions for modern C developers to create efficient and well-structured programs*](https://www.amazon.com/Practical-Programming-Solutions-developers-well-structured/dp/1838641106), by B. M. Harwani
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
    - Or, for Virtualbox: *SSST*, ch. 2
      - Michigan lecture 1 ([slides](https://c4cs.github.io/lectures/w18/week1.pdf)) ([video](http://leccap.engin.umich.edu/leccap/viewer/r/ZhLp2f)) ([homework](https://c4cs.github.io/static/w18/hw/c4cs-wk1-homework.pdf))
2. Introduction to Unix
    - Using the shell
      - *TLCL*, Introduction and ch. 1
      - *SSST*, ch. 1
      - *PG*, ch. 1-2, 5
      - Do: [Berkeley assignment 1.1](https://selfpaced.bitbucket.io/#/unix/assignment/unix-basics)
      - Do: [Cornell homework 1](https://www.cs.cornell.edu/courses/cs2043/2014sp/assignments/hw1.pdf)
      - [MIT session 1](https://missing.csail.mit.edu/2020/course-shell/) (do exercises)
    - Files, permissions, and the file system
      - [Penn lecture 1 slides](https://www.cis.upenn.edu/~cis191/lectures/lec1.pdf)
      - [Cornell lecture 1 slides](https://www.cs.cornell.edu/courses/cs2043/2014sp/lectures/lecture01.pdf)
      - [Cornell lecture 3 slides](https://www.cs.cornell.edu/courses/cs2043/2014sp/lectures/lecture03.pdf)
      - [Cornell lecture 2 slides](https://www.cs.cornell.edu/courses/cs2043/2014sp/lectures/lecture02.pdf)
      - *SSST*, ch. 3-4
      - *TLCL*, ch. 2-5, 9
      - *PG*, ch. 3-4
    - Working with text files
      - [Penn lecture 2 slides](https://www.cis.upenn.edu/~cis191/lectures/lec2.pdf)
      - [Cornell lecture 6 slides](https://www.cs.cornell.edu/courses/cs2043/2014sp/lectures/lecture06.pdf)
    - Pipes and redirecting
      - [Cornell lecture 5 slides](https://www.cs.cornell.edu/courses/cs2043/2014sp/lectures/lecture05.pdf)
      - *TLCL*, ch. 6
    - Completion and history
      - [Cornell lecture 4 slides](https://www.cs.cornell.edu/courses/cs2043/2014sp/lectures/lecture04.pdf)
      - *TLCL*, ch. 7-8
    - Searching for things
      - *TLCL*, ch. 17
      - Do: [Stanford week 3](https://practicalunix.org/content/week-3-pipelines)
3. Advanced basics
    - The shell environment
      - Michigan week 3 ([slides](https://c4cs.github.io/lectures/w18/week3.pdf)) ([video](http://leccap.engin.umich.edu/leccap/viewer/r/m4fzZv))
      - *SSST*, ch. 6, 10
      - *TLCL*, ch. 11
      - *PG*, ch. 8
      - Do: [Berkeley assignment 1.2](https://selfpaced.bitbucket.io/#/unix/assignment/the-shell-and-simple-filters)
      - Do: [Michigan homework 3](https://c4cs.github.io/static/w18/hw/c4cs-wk3-homework.pdf) ([advanced](https://c4cs.github.io/static/w18/advanced/c4cs-wk3-advanced.pdf))
    - Storage media
      - *TLCL*, ch. 15
    - Packages and the package manager
      - *TLCL*, ch. 14
      - Michigan week 12 ([slides](https://c4cs.github.io/lectures/w18/week12.pdf)) ([video](http://leccap.engin.umich.edu/leccap/viewer/r/BSVUAF)) ([homework](https://c4cs.github.io/static/w18/hw/c4cs-wk12-homework.pdf)) ([advanced](https://c4cs.github.io/static/w18/advanced/c4cs-wk12-advanced.pdf))
    - Archiving and backup
      - *TLCL*, ch. 18
      - *PG*, ch. 16
    - Compiling programs from source
      - *TLCL*, ch. 23
    - Automating tasks
      - *SSST*, ch. 9
4. Streams, processes, and jobs
    - [Cornell lecture 7 slides](https://www.cs.cornell.edu/courses/cs2043/2014sp/lectures/lecture07.pdf)
    - *SSST*, ch. 7
    - *TLCL*, ch. 10
    - [Penn lecture 3 slides](https://www.cis.upenn.edu/~cis191/lectures/lec3.pdf)
    - Do: [Berkeley assignment 1.3](https://selfpaced.bitbucket.io/#/unix/assignment/process-management)
    - [MIT session 5](https://missing.csail.mit.edu/2020/command-line/) (do exercises)
5. Text processing, awk, and sed
    - [Cornell lecture 8 slides](https://www.cs.cornell.edu/courses/cs2043/2014sp/lectures/lecture08.pdf)
    - [Cornell lecture 9 slides](https://www.cs.cornell.edu/courses/cs2043/2014sp/lectures/lecture09.pdf)
    - [Cornell lecture 10 slides](https://www.cs.cornell.edu/courses/cs2043/2014sp/lectures/lecture10.pdf)
    - [Cornell lecture 11 slides](https://www.cs.cornell.edu/courses/cs2043/2014sp/lectures/lecture11.pdf)
    - [Cornell lecture 12 slides](https://www.cs.cornell.edu/courses/cs2043/2014sp/lectures/lecture13.pdf)
    - [Penn lecture 4 slides](https://www.cis.upenn.edu/~cis191/lectures/lec4.pdf)
    - *SSST*, ch. 5
    - *TLCL*, ch. 19-21
    - *PG*, ch. 14-15
    - *Grep pocket reference*
    - *Sed & Awk*
    - Do: [Stanford week 4](https://practicalunix.org/content/week-4-grep)
    - Do: [Berkeley assignment 3](https://selfpaced.bitbucket.io/#/unix/assignment/grep-and-sed)
    - Michigan week 6 ([slides](https://c4cs.github.io/lectures/w18/week6.pdf)) ([video](http://leccap.engin.umich.edu/leccap/viewer/r/13kIeV)) ([homework](https://c4cs.github.io/static/w18/hw/c4cs-wk6-homework.pdf)) ([advanced](https://c4cs.github.io/static/w18/advanced/c4cs-wk6-advanced.pdf))
    - Do: [Penn homework 2](https://www.cis.upenn.edu/~cis191/hw/hw2.html)
    - [MIT session 4](https://missing.csail.mit.edu/2020/data-wrangling/) (do exercises)
6. Storage media
    - *TLCL*, ch. 15
7. Vim
    - [07-131 week 2](https://www.cs.cmu.edu/~07131/f19/topics/readings/week-2/)
    - [07-131 week 2 lecture](https://www.cs.cmu.edu/~07131/f19/topics/vim/)
    - [07-131 week 3](https://www.cs.cmu.edu/~07131/f19/topics/readings/week-3/)
    - [07-131 week 3 lectures](https://www.cs.cmu.edu/~07131/f19/topics/vim/)
    - *TLCL*, ch. 12
    - *PG*, ch. 6
    - *Modern Vim*
    - [MIT session 3](https://missing.csail.mit.edu/2020/course-shell/) (do exercises)
8. Basic networking
    - *PG*, ch. 17
    - *SSST*, ch. 8
    - *TLCL*, ch. 16
    - Do: [Berkeley assignment 2](https://selfpaced.bitbucket.io/#/unix/assignment/remote-process-execution) (except Subversion)
    - Do: [Stanford week 7](https://practicalunix.org/content/week-7-web)
    - Do: Compile Nginx web server from source
    - Do: [Penn homework 1](https://www.cis.upenn.edu/~cis191/hw/hw1.html) (use Nginx instead of Apache)
9. Bash shell scripting
    - [Penn lecture 6 slides](https://www.cis.upenn.edu/~cis191/lectures/lec6.pdf)
    - [Penn lecture 7 slides](https://www.cis.upenn.edu/~cis191/lectures/lec7.pdf)
    - [MIT session 2](https://missing.csail.mit.edu/2020/shell-tools/) (do exercises)
    - [07-131 weeks 7-10](https://www.cs.cmu.edu/~07131/f19/)
    - *PG*, ch. 10
    - *TLCL*, ch. 24-36
    - *Advanced Bash-Scripting Guide*
    - Do: [Berkeley assignment 4.1](https://selfpaced.bitbucket.io/#/unix/assignment/bash-calculator)
    - Do: [Berkeley assignment 4.2](https://selfpaced.bitbucket.io/#/unix/assignment/cat-and-mouse)
    - Do: [Stanford week 5](https://practicalunix.org/content/week-5-scripting) (use Bash instead of Python)
    - Do: [Penn homework 3](https://www.cis.upenn.edu/~cis191/hw/hw3.html)
10. Git and GitHub
    - [Penn lecture 10 slides](https://www.cis.upenn.edu/~cis191/lectures/lec10.pdf)
    - [07-131 week 5](https://www.cs.cmu.edu/~07131/f19/topics/readings/week-5/)
    - [07-131 week 5 lecture](https://www.cs.cmu.edu/~07131/f19/topics/git/)
    - [07-131 week 6](https://www.cs.cmu.edu/~07131/f19/topics/readings/week-6/)
    - [07-131 week 6 lecture](https://www.cs.cmu.edu/~07131/f19/topics/git/)
    - *Beginning Git and GitHub*
    - *Pro Git*
    - [MIT session 6](https://missing.csail.mit.edu/2020/version-control/) (do exercises)
    - Do: Michigan week 2 ([slides](https://c4cs.github.io/lectures/w18/week2.pdf)) ([video](http://leccap.engin.umich.edu/leccap/viewer/r/ZX1FDy)) ([homework](https://c4cs.github.io/static/w18/hw/c4cs-wk2-homework.pdf)) ([advanced](https://c4cs.github.io/static/w18/advanced/c4cs-wk2-advanced.pdf))
    - Do: Michigan week 5 ([video](http://leccap.engin.umich.edu/leccap/viewer/r/GHzTl6)) ([homework](https://c4cs.github.io/static/w18/hw/c4cs-wk5-homework.pdf)) ([advanced](https://c4cs.github.io/static/w18/advanced/c4cs-wk5-advanced.pdf))
    - [Building tools with GitHub](https://buildingtoolswithgithub.teddyhyde.io/)
11. Terminal multiplexing with tmux
    - *Tmux 2: Productive Mouse-Free Development*
12. C programming
    - [CS 50 lectures 1-5](https://www.youtube.com/playlist?list=PLhQjrBD2T381L3iZyDTxRwOBuUt6m1FnW)
    - *Head First C*
    - [Essential C](http://cslibrary.stanford.edu/101/)
    - [Pointers and Memory](http://cslibrary.stanford.edu/102/)
    - [Miami course slides](http://www.cs.miami.edu/~schulz/CSC322.pdf)
    - [15-123 lectures 1-19](https://www.cs.cmu.edu/~guna/15-123S11/) (do all homeworks, labs, and skills labs)
    - *Practical C Programming*
    - Do: [Berkeley C projects and quizzes](https://selfpaced.bitbucket.io/#/c/calendar)
    - Do: [Miami assignments 1-5](https://www.cs.miami.edu/home/schulz/CSC322/assignments.html)
13. Make and Unix build tools
    - [Penn lecture 11 slides](https://www.cis.upenn.edu/~cis191/lectures/lec11.pdf)
    - *The GNU Make Book*
    - [Miami course slides](http://www.cs.miami.edu/~schulz/CSC322.pdf)
    - [*Unix Programming Tools*](http://cslibrary.stanford.edu/107/)
    - [MIT session 7](https://missing.csail.mit.edu/2020/debugging-profiling/) (do exercises)
    - Michigan week 10 ([slides](https://c4cs.github.io/lectures/w18/week10.pdf)) ([video](http://leccap.engin.umich.edu/leccap/viewer/r/KzVqJL)) ([homework](https://c4cs.github.io/static/w18/hw/c4cs-wk10-homework.pdf)) ([advanced](https://c4cs.github.io/static/w18/advanced/c4cs-wk10-advanced.pdf))
    - Michigan week 11 ([slides](https://c4cs.github.io/lectures/w18/week11.pdf)) ([video](http://leccap.engin.umich.edu/leccap/viewer/r/qYiAbb)) ([homework](https://c4cs.github.io/static/w18/hw/c4cs-wk11-homework.pdf)) ([advanced](https://c4cs.github.io/static/w18/advanced/c4cs-wk11-advanced.pdf))
    - Michigan week 14 ([slides](https://c4cs.github.io/lectures/w18/week14.pdf)) ([video](http://leccap.engin.umich.edu/leccap/viewer/r/vZTLSa)) ([homework](https://c4cs.github.io/static/w18/hw/c4cs-wk14-homework.pdf)) ([advanced](https://c4cs.github.io/static/w18/advanced/c4cs-wk14-advanced.pdf))
    - Do: [Miami assignment 6](https://www.cs.miami.edu/home/schulz/CSC322/06.html)
14. Basic systems programming with C
    - [Penn lecture 12 slides](https://www.cis.upenn.edu/~cis191/lectures/lec12.pdf)
    - [Penn lecture 13 slides](https://www.cis.upenn.edu/~cis191/lectures/lec13.pdf)
    - [15-123 lectures 24-28](https://www.cs.cmu.edu/~guna/15-123S11/) (do all homeworks, labs, and skills labs)
    - [Miami course slides](http://www.cs.miami.edu/~schulz/CSC322.pdf)
    - [*Introduction to Systems Programming: a Hands-on Approach*](https://www.cs.purdue.edu/homes/grr/SystemsProgrammingBook/)
    - [Unix System Calls and Subroutines using C](https://users.cs.cf.ac.uk/Dave.Marshall/C/)
    - Do: [Miami assignments 7-8](https://www.cs.miami.edu/home/schulz/CSC322/assignments.html)

### Projects

- [Penn final project](https://www.cis.upenn.edu/~cis191/hw/project.html) ([proposal](https://www.cis.upenn.edu/~cis191/hw/proposal.html))
- Project 2: Recreate a Unix CLI utility from scratch in Bash
- Project 3: Recreate a Unix CLI utility from scratch in C
- Project 4: Design and build your own major CLI tool in C (e.g. a shell or text editor), using Make and other Unix build tools as appropriate
- Project 5: Build a network server (e.g. HTTP)

## License

All materials created by me are released under the MIT license. Other materials are &copy; to their respective authors and creators.
