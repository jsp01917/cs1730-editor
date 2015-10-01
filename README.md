# cs1730-editor

This repository contains the skeleton code for the Editor project assigned to
the students in the Fall 2015 CSCI 1730 class at the University of Georgia. 

**Please read the entirety of this file before beginning your project.**

## Due Date

This project is due on Friday 2015-10-16 @ 11:55 PM.

## Academic Honesty

You implicitly agree to Academic Honesty policy as outlined in the course 
syllabus and course website.

In accordance with the notice above, I must caution you **not** to fork this
repository on GitHub if you have an account. Doing so will more than likely make
your copy of the project publicly visible. Please follow the instructions 
contained in the Resources section below in order to do your development on
<code>nike</code>.

## Project Description

Your goal is to implement a basic text editor in C++ using system calls for 
low-level file I/O and the <code>ncurses</code> library for the Text User 
Interface (TUI). This will require you to lookup things related to 
<code>ncurses</code> and apply your knowledge of object oriented programming.

Part of software development is being given a goal but not necessarily being 
given instruction on all of the details needed to accomplish that goal. For 
example, even though the <code>ncurses</code> library hasn't been covered in 
class, in order to complete this project you are going to need to lookup how to 
create TUIs using <code>ncurses</code>. Furthermore, since <code>ncurses</code>
is a C library (and not a C++ library), you're going to need to take special
care that you are still using C++ best practices and exercising concepts related
to object oriented programming. For example, you may wish to create multiple
classes in order to better organize your code base.

## Functional Requirements

Your submission needs to satisfy the following functional requirements:

 * ()

## Non-Functional Requirements

Your submission needs to satisfy the following non-functional requirements:

 * **(5 points) Documentation:** Your source code should be documented using
   comments. Inline comments may be used inside of functions. Functions 
   themselves should be documented using Javadoc-style comments. You don't need
   to go overboard when commenting your code. Simply include comments so that
   someone else could potentially figure out what is going on with your code.

 * **(5 points) Compiling & Linking:** You need to make sure that your 
   submission compiles each <code>.cpp</code> file into its own <code>.o</code>
   file. Furthermore, your <code>.o</code> files need to link into an
   executable called <code>editor</code>. This can be streamlined by a
   properly implemented <code>Makefile</code>.

 * **(5 points) Makefile:** Your <code>Makefile</code> should include an 
   <code>all</code> target and a <code>clean</code> target in addition to any
   other targets it might need. Furthermore, your <code>Makefile</code> should
   be written in such a way that is satisfies the "Compiling & Linking"
   requirement mentioned above.

 * **(5 points) Compiler Warnings & Memory Leaks:** Your submission should not
   issue any compiler warnings or errors when compiled and linked. Furthermore,
   when your submission is run, the <code>valgrind</code> utility should
   indicate that there are NO memory leaks (in the first three leak reports).

**NOTE:** The expectation is that the grader should be able to type in the 
following to clean, compile, link, and run your submission:

```
$ make clean
$ make
$ ./editor somefile
```

## Extra Credit Opportunity

You may gain some extra credit points if your submission includes the following:

 * **(5 points) File Menu:** test

 * **(5 points) Line Numbers:** test 

## Skeleton Code

The files for this project are hosted Github using <code>git</code>. They can be
retrieved by cloning the repository found at 
<code>git://github.com/uga-csci-1730-cotterell/cs1730-editor.git</code>. 
For example, you can issue the following command to clone the repository:

```
$ git clone git://github.com/uga-csci-1730-cotterell/cs1730-editor.git LastName-FirstName-p1
```

If the above command issues you any errors or warnings, then you might try the
following command instead:

```
$ git clone https://github.com/uga-csci-1730-cotterell/cs1730-editor.git LastName-FirstName-p1
```

**NOTE:** There really isn't any skeleton code for this project. Creating your
files is completely up to you so long as you fullfill the project requirements.
The above command simply creates a directory for this project that includes this
<code>README.md</code> file as well as a stub for your <code>Makefile</code>.

**NOTE:** As always, I suggest developing directly on 
<code>nike.cs.uga.edu</code>because this is where your project will be run and 
tested. Since <code>git</code> is already installed on <code>nike</code>, you 
can clone the project directly into your <code>nike</code> home directory using
the command provided above.

**NOTE:** If any changes are made to the project description or skeleton code, 
they will be announced in class. In order to incorporate such changes into your 
code, you need only do a <code>git pull</code>.

**NOTE:** Also, since <code>git</code> is a decentralized version control 
system, you will have your own local copy of the repository. This means that you
can log your changes using commits and even revert to a previous revision if
necessary.

## Submission Instructions

You will be submitting your project via <code>nike</code>. Make sure your work 
is on <code>nike.cs.uga.edu</code> in a directory called 
<code>LastName-FirstName-p1</code>, and, from within the parent directory, 
execute the following command:

    $ submit LastName-FirstName-p1 cs1730a

It is also a good idea to email a copy to yourself. To do this, simply execute 
the following command, replacing the email address with your email address:

    $ tar zcvf LastName-FirstName-p1.tar.gz LastName-FirstName-p1
    $ mutt -s "[cs1302] p1" -a LastName-FirstName-p1.tar.gz -- your@email.com < /dev/null

## Questions

If you have any questions, please post them on Piazza.

