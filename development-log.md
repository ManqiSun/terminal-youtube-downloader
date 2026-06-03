# Development Log

## Project Goal

The original goal was very simple:

I wanted to download YouTube videos from the terminal with a short command.

Instead of opening multiple folders and typing long commands every time, I wanted a workflow like:

```bash
yt-basic
```

or

```bash
yt-hd
```

Then paste a YouTube URL and start downloading.

This project was created as an independent command-line tool.

It is not part of my YouTube Auto Downloader project and does not include RSS monitoring, channel tracking or other automation features.

---

## Why I Built It

As a Python beginner, I wanted to build something I could actually use.

Most learning exercises focus on syntax.

This project gave me a chance to connect Python with real tools and solve practical problems.

---

## Development Process

### Step 1 — Finding a Download Tool

I started by researching how YouTube videos are commonly downloaded.

Eventually I chose:

```text
yt-dlp
```

because it is actively maintained and supports high-quality downloads.

At this stage, I thought the project would be very easy.

I quickly learned that getting a tool to work is often harder than writing the code itself.

---

### Step 2 — First Problem: yt-dlp Not Recognized

After installing yt-dlp, the terminal could not recognize the command.

Example:

```text
'yt-dlp' is not recognized as an internal or external command
```

#### Cause

The executable location was not available through Windows PATH.

#### What I Learned

Installing a tool is not enough.

The operating system also needs to know where to find it.

This was my first practical experience with PATH configuration.

---

### Step 3 — Understanding Windows PATH

To solve the previous issue, I had to learn how PATH works.

Before this project, PATH was just a word I had seen in tutorials.

Now I understood that:

```text
PATH
=
A list of folders Windows searches when I type a command.
```

This helped me understand why some commands work globally while others do not.

---

### Step 4 — PowerShell vs CMD

During testing, I discovered that PowerShell and CMD sometimes behaved differently.

Commands that worked in one environment could fail in another.

#### What I Learned

Windows has multiple terminal environments.

Understanding the execution environment is important when building command-line tools.

---

### Step 5 — Python Execution Path Issues

At one point the Python script could not find the files it needed.

The problem was not the code itself.

The problem was where the script was being executed from.

#### What I Learned

Relative paths depend on the current working directory.

File paths are often a bigger source of bugs than Python syntax.

---

### Step 6 — Chinese Path Problems

Some folders contained Chinese characters.

This created unexpected issues during testing.

#### What I Learned

Path naming and encoding can affect command-line tools.

This made me more aware of creating stable and predictable project structures.

---

### Step 7 — Batch File Integration

After getting Python and yt-dlp working, I wanted a simpler user experience.

Instead of running Python manually, I created:

```text
yt-basic.bat
```

and

```text
yt-hd.bat
```

#### Initial Result

The batch files failed.

#### What I Learned

A batch file is not simply a shortcut.

It still depends on correct paths, commands and execution context.

---

### Step 8 — Organizing Download Output

The final challenge was making sure videos and thumbnails were saved to the correct directory.

#### What I Learned

A usable tool needs predictable output.

Good folder organization is part of the user experience.

---

## Final Result

The final workflow became:

```bash
yt-basic
```

or

```bash
yt-hd
```

Paste a YouTube URL.

Wait for the download to finish.

The video and thumbnail are automatically saved to the target directory.

---

## Biggest Takeaway

Before this project, I thought software development was mostly about writing code.

After this project, I realized that a working tool also requires:

* environment configuration
* debugging
* file paths
* terminal knowledge
* tool integration

The code itself was only one part of the process.

---

## Personal Reflection

This is not a large project.

The code is relatively simple.

However, it is the first tool I built that solves a real problem in my daily workflow.

More importantly, it helped me experience a complete development cycle:

```text
Need
↓
Idea
↓
AI-Assisted Development
↓
Errors
↓
Debugging
↓
Working Tool
```

For me, that is the most valuable outcome of this project.
