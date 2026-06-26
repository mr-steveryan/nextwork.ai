<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Set Up Claude Code's Status Line

**Project Link:** [View Project](http://nextwork.ai/projects/claude-code-statusline)

**Author:** mrsteve  
**Email:** mr_ryann@icloud.com

---

![Image](http://nextwork.ai/gleeful_rose_silly_kaka/uploads/claude-code-statusline_vu9c3f7m)

---

## Introducing Today's Project!

In this project, I'm going to build a status line for my Claude Code. 
This will help me manage my Claude Code Sessions a bit easier.

### Key tools and concepts

The key tools I used:
Terminal Emulator (Ghostty)
Claude Code
 Key concepts I learnt include
Agentic Workflow (tell Claude what you want, review its plan and execute it) learnt it by setting my statusline.

### Challenges and wins

I did this project today to learn how to use Claude Code's Agentic Workflow to build my custom statusline accoprding to my workflow. 
Another skill I want to learn is how to think in terms of system architecture and product design.

---

## Installing and Verifying Claude Code

In this step, I am verifying that Claude Code is installed and running a test prompt to confirm its working

![Image](http://nextwork.ai/gleeful_rose_silly_kaka/uploads/claude-code-statusline_w4nt8q6j)

### Confirming the installation

I verified Claude Code is working by using claude -v. I'm running Claude Code version 2.1.193

---

## Generating a Live Status Line

In this step, I'm setting up a live status bar in my Claude Code Setup, so that I can view the important information like Token usgae, context window, etc.. in real-tiome without typing in their respective codes.

![Image](http://nextwork.ai/gleeful_rose_silly_kaka/uploads/claude-code-statusline_vu3j8d6f)

### Understanding the status line data

I learned that the four fields are.
-> Model: Shows the current model in use
-> Context: Shows the percentage of the used context window
-> Cost: Shows the cost of tokens used
-> Branch: Shows the current branch used in the git intialized cwd

---

## Configuring the Status Line Settings

The prompt told Claude Code to display
the word STATUS
current git branch
model name
context
cost of tokens used

![Image](http://nextwork.ai/gleeful_rose_silly_kaka/uploads/claude-code-statusline_vu7n4p2x)

---

## Customizing the Status Line With a Progress Bar

In this step, I'm customizing the status line to match my workflow. I going to:
add a powerline branch icon near the current git branch
add a percentage to track my 5 hour subscription usage 

change some of the colors to match my taste & terminal theme

![Image](http://nextwork.ai/gleeful_rose_silly_kaka/uploads/claude-code-statusline_vu8b1g4p)

### Making it my own

I customized my status line by 
removing the boxes around context bar.
adding clear labels before the metrics
added a usage meter of my current 5h session and the time left for the next session to begin
 I chose this because this suits my workflow.

---

## Adding Color-Coded Context Warnings

In this project extension, I'm going to add context warnings that tells me what happened in a nutshell

### ANSI escape codes and context thresholds

In this project extension, I prompted Claude to use ANSI escape codes to tell me when my context rots by a simple rule based system. 
green when the context is less than 50%. displays OK
yellow when the context is around 60% displays "/compact"
red when the context is around 90% displays "/clear"

![Image](http://nextwork.ai/gleeful_rose_silly_kaka/uploads/claude-code-statusline_p4w8n1v6)

### Context usage and rate limits

In this project extension, I learned that context fills up as the conversation goes on
 Rate limits differ because the more context claude reference from its context windows, the more tokens are used which is reflected on the weekly rate limits

---

## Wrapping Up

This project took me approximately an hour and half. 
The most challenging part was to find the simple words for what I actually want to express to Claude, so that I don't redo any tasks

---

---
