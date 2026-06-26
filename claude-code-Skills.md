<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Claude Code Skills Basics

**Project Link:** [View Project](http://nextwork.ai/projects/ai-claude-code-skills)

**Author:** mrsteve  
**Email:** mr_ryann@icloud.com

---

![Image](http://nextwork.ai/gleeful_rose_silly_kaka/uploads/ai-claude-code-skills_n2t8w6j4)

---

## Introducing Today's Project!

In this project, I'm going to build a set of skills that scans my local git history to generate changelogs and structured commits. This will help me in automating my git work.

### Key tools and concepts

The key tools I used includes Claude Code in Terminal. Key concepts I learned include
Defining and using Skills
Defining Orchestrator skill that creates a dev-pipeline of multiple skills
Defining Hooks in Claude Code

### How long this project took

This project took me approximately
50 minutes across three days.
The most challenging part was staying focused to learn about the most basic fundamentals in a different way.

### Project reflection

I did this project today to learn how to use Claude Code effectively using Skills.
Another skill I want to learn is to use Claude Code as my co-foudner in my SaaS idea.

---

## Setting Up Claude Code and Git

In this step, I'm going to
Confirm the Installation of Claude Code
Create a Directory and initialize git using git init
Create started code and make my first commit

![Image](http://nextwork.ai/gleeful_rose_silly_kaka/uploads/ai-claude-code-skills_c5r2w8j3)

### Setting up the Git repository

---

## Building a Changelog Generator Skill

In this step, I'm going to create and verify the CHANGELOG skill by:
creating the necessary directories
define the purpose, inputs, outputs, step-by-step instructions
invoke and verify it

![Image](http://nextwork.ai/gleeful_rose_silly_kaka/uploads/ai-claude-code-skills_g6q3l5c7)

### What Claude did when I invoked the skill

When I ran /changelog, Claude execute git log and read my commit history. 
The CHANGELOG.md showed my existing commits and the exact commit was written to CHANGELOG.md

---

## Configuring Skill Frontmatter

In this step, I'm going to add a YAML Frontmatter to. your skill
Specifically, I'm going to
Set the name, description and allowed-tools fields
Verify it by running it after a second commit

![Image](http://nextwork.ai/gleeful_rose_silly_kaka/uploads/ai-claude-code-skills_k7v9x3m1)

### How allowed-tools works as a security boundary

The allowed-tools field manages the access of tools to skills. This matters because the only tools mentioned here, in this field is allowed by the skill to use.

---

## Building a Dev Pipeline with Smart Commit

In this step, I'm going to build a skill that smart commits based on conventional messages. 
Then, I create a dev-pipeline orchestration that chains changelog and smart commit

![Image](http://nextwork.ai/gleeful_rose_silly_kaka/uploads/ai-claude-code-skills_n2t8w6j4)

### How the orchestrator coordinates skills

My dev-pipeline first runs /smart-commit which starts with checking for git diff to learn about the edits done. From the edits done, the skill analyzes for the major feature and uses it for a conventional commit message  then runs /changelog which uses git log to identify all the commits done so far, then note it down in CHANGELOG.md

---

## Adding Hook Triggers

In this project extension, I configured a hook by...

![Image](http://nextwork.ai/gleeful_rose_silly_kaka/uploads/ai-claude-code-skills_q3f7y2m5)

---

---
