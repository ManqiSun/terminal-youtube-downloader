# Terminal YouTube Downloader

My first real-world Python utility project.

A simple command-line YouTube downloader built with Python, yt-dlp, PowerShell and Windows batch files.

The purpose of this project is not to build a complex downloader, but to document how I turned a personal need into a working tool through AI-assisted development, debugging and environment setup.

---

## Project Background

I am currently learning Python.

Instead of following tutorials only, I wanted to build a small tool that I could actually use in daily life.

The goal was simple:

Open terminal → Enter a command → Paste a YouTube URL → Download the video.

After several rounds of debugging and environment configuration, I successfully built a working terminal-based YouTube downloader.

---

## Features

### yt-basic

Download:

* YouTube video
* Video thumbnail

Output:

* Save files to a specified directory

Quality:

* Up to 1080P

Usage:

```bash
yt-basic
```

---

### yt-hd

Download:

* YouTube video
* Video thumbnail

Output:

* Save files to a specified directory

Quality:

* Highest available quality

Usage:

```bash
yt-hd
```

---

## Tech Stack

* Python
* yt-dlp
* PowerShell
* Windows PATH
* Batch files (.bat)

---

## Development Process

This project was built through a complete learning workflow:

```text
Personal Need
      ↓
AI-Assisted Development
      ↓
Environment Setup
      ↓
Debugging
      ↓
Problem Solving
      ↓
Working Tool
```

Rather than focusing on writing a large amount of code, most of the effort went into understanding how different tools work together.

---

## Challenges Encountered

During development, I encountered several real-world issues:

### yt-dlp command not recognized

Understanding how Windows PATH works and why commands cannot be found.

### PATH environment configuration

Learning how command-line tools become globally available.

### PowerShell vs CMD differences

Understanding that different terminal environments may execute commands differently.

### Python execution path issues

Learning how working directories affect script execution.

### Chinese path encoding issues

Encountering and troubleshooting path-related problems.

### Batch file calling Python

Understanding how batch files launch Python scripts and pass execution control.

### Download directory management

Organizing file outputs and creating a more usable workflow.

---

## What I Learned

This project taught me that building a usable tool involves much more than Python syntax.

I learned about:

* Command-line workflows
* Windows PATH
* Terminal environments
* PowerShell
* Batch scripting
* File paths
* Debugging techniques
* Tool integration

Most importantly, I learned that debugging is a normal part of development.

---

## Project Value

This repository is primarily a learning record.

The value of the project is not the downloader itself.

The value is documenting the process of:

* identifying a real need
* using AI as a development assistant
* troubleshooting errors
* understanding development environments
* turning an idea into a working utility

As a Python beginner, this project represents an important step from copying commands to building my own tools.

---

## Current Commands

Download video + thumbnail (up to 1080P)
```bash
yt-basic
```

Download video + thumbnail (highest available quality)
```bash
yt-hd
```

---

## Documentation

Additional notes are available in:

* Development Log
* Learning Notes
* Roadmap

---

## Future Improvements

Possible future improvements:

- Improve error handling
- Improve terminal prompts
- Refactor code structure
- Learn more about command-line tools

This project is intentionally kept small.

The primary goal is to document my learning process rather than build a full-featured downloader.

---

## Author's Note

This repository reflects my experience as a Python beginner building a real-world utility.

The code may be simple, but the learning process behind it was valuable.

Every problem solved in this project helped me better understand how software tools, operating systems and development environments work together.
