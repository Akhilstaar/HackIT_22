# Repository for HackIT'22 Summer Project

This repo would be used to document mentees' writeups for the provided Assignments.  
Check your standings [here](https://ba-13.github.io/HackIT_22)

---

## Assignment 0

Make a writeup about what you understood about `UNIX filesystem` and `vim`.  
Document the shortcuts and concepts you learnt, more comprehensive, better score (relatively scored throughout the project :). Just don't copy from somewhere (if you found it on the internet, so would we)  
Please fork this repository, clone it locally, put your writeup names as
`2XXXXX_YourName.md` in the corresponding [assignment folder](./Assignment_0). Commit with meaningful message, push to your remote origin, and make a pull request(PR) to this repo's `main` branch.  
You may work on a new branch on your fork, but PR on this main only.  
Note that the upcoming Assignments won't be submitted in this manner. This is
done to help you understand a basic workflow of git.

Submit a PR **by Sunday, May 29th 2022**, no deadline extension. You can of
course submit before!

---

## Assignment 1

You're given a [file](./Assignment_1/i_am_hiding_stuff.txt). It's too long for you to go through. But there are a few pieces of information lying in midst that string that you need to find.

1. The word "HACK"
2. A 10 consecutive digit Number
3. A link based on File Transfer Protocol at Port 8080
4. A substring of the form "hackIT{...}"

It's guaranteed that the formats would be like this, with no other such substrings in that file

The problem is you're only provided the access of `/bin/bash` or `/usr/bin/python3` (i.e. you can use bash or python as languages, with these being included in the she-bang line), with no other string search binaries or libraries. It means you **can't** use tools like `grep`, `awk`, `tr`, `sed`, `re`, etc. Only i/o tools or libraries and pure scripting.  
So create 4 scripts of name `1.sh`, `2.sh`, `3.sh`, and `4.sh` for the corresponding problems, mark them as executables, such that running them directly outputs the needed strings.

> Bonus : Apart from returning/echo-ing values, return/echo their line numbers as well.

You've to submit a directory of name `XXXXXX_Your_Name` with `XXXXXX` being your roll number. Keep all 4 scripts and any bonus related writeup inside that directory. Commit this folder **inside [Assignment_1](./Assignment_1/)** and make a PR on this repo's `main` branch ONLY.

I'm giving a choice between `bash` or `python`, because this will decide how comfortable you get in either. You'll eventually find that mostly all languages can replace each other, so it comes down to convenience and speed.

Do remember that judgement is on you using BASH/Python3 with no pre-built string manipulation commands. Inefficient but working code **is acceptable** for this assignment. Use any amount of nesting you want! (Just that it should run within 5 seconds).

Submit a PR **by Sunday, June 5th 2022**, no deadline extension. You can of course submit before!

---
