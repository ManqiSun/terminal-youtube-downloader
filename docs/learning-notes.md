# Learning Notes

## Project Overview

This project started with a simple goal:

Create a command-line tool that can download YouTube videos with a short command.

Although the final functionality is relatively simple, the development process taught me much more than I expected.

---

## What I Thought Before Starting

Before building this project, I believed that learning Python mainly meant:

* learning syntax
* writing functions
* understanding variables and loops

I thought that once I knew enough Python, building a tool would be straightforward.

This project changed that perspective.

---

## Lesson 1 — Writing Code Is Only Part of Development

The Python code itself was only a small part of the project.

Most of the challenges came from:

* environment setup
* terminal configuration
* file paths
* command execution
* tool integration

This helped me understand that software development is not just programming.

It is also about making different tools work together.

---

## Lesson 2 — Understanding PATH

One of the first problems I encountered was:

```text
yt-dlp is not recognized
```

At first I thought something was wrong with the installation.

Later I learned about Windows PATH.

### My Understanding Now

PATH is a list of locations that Windows searches when a command is entered.

If a tool is installed but not included in PATH, the terminal cannot find it.

This was my first practical experience with environment configuration.

---

## Lesson 3 — PowerShell and CMD Are Different

Before this project, I treated all terminals as the same thing.

During development I discovered that:

* PowerShell behaves differently from CMD
* Commands may work in one environment and fail in another

This taught me that execution environments matter.

Understanding the environment is just as important as understanding the code.

---

## Lesson 4 — File Paths Matter

Several issues were caused by file paths rather than Python logic.

Examples included:

* script execution location
* relative paths
* Chinese folder names

I learned that path management is an important part of building reliable tools.

---

## Lesson 5 — Batch Files Are Useful

Before this project, I rarely used batch files.

By creating:

```text
yt-basic.bat
yt-hd.bat
```

I learned how batch files can simplify command-line workflows.

Instead of running Python manually every time, I could create commands that felt like real tools.

---

## Lesson 6 — Debugging Is a Skill

The biggest surprise was how much time was spent debugging.

Examples:

* command not recognized
* wrong execution path
* terminal differences
* encoding issues

At first these errors felt frustrating.

Over time I realized that debugging is not something separate from development.

Debugging is development.

---

## Lesson 7 — AI Is a Development Assistant

This project was built with AI assistance.

AI helped me:

* understand error messages
* compare possible solutions
* explain unfamiliar concepts
* organize my development process

However, I still needed to:

* test solutions
* verify results
* adjust configurations
* solve environment-specific problems

This helped me understand the difference between:

```text
Getting a suggestion
```

and

```text
Making something actually work
```

---

## Lesson 8 — Real Projects Feel Different

Compared with learning exercises, this project felt different because it solved a real problem.

I was not writing code simply to complete a lesson.

I was building something I intended to use.

That made the debugging process more meaningful and helped me stay motivated.

---

## Biggest Takeaway

The most important thing I learned is that building software is not only about code.

A working tool requires:

```text
Idea
↓
Research
↓
Development
↓
Environment Setup
↓
Testing
↓
Debugging
↓
Iteration
↓
Usable Result
```

This project was my first experience completing that full cycle.

---

## Looking Back

The downloader itself is a small utility.

But for me, the value of the project is not the final command.

The value is learning how a real tool comes together.

This project helped me move from:

```text
Following tutorials
```

to:

```text
Building something for myself
```

And that is the most meaningful result of this project.
