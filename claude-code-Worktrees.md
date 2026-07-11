<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Claude Code with Git Worktrees

**Project Link:** [View Project](http://nextwork.ai/projects/ai-git-worktrees)

**Author:** mrsteve  
**Email:** mr_ryann@icloud.com

---

![Image](http://nextwork.ai/gleeful_rose_silly_kaka/uploads/ai-git-worktrees_bj6f2k8w)

---

## Introducing Today's Project!

In this project, I'm going to. learn how to use git worktrees with AI Coding Agents. This will help me execute AI Agents to work on my project in parallel isolation. I'm interested in this because it will help me build a project with AI faster.

### Key tools and concepts

Git is a tool that enables version control in a project directory. We need it for this project because git enables worktrees, which will be used for parallel execution of AI.

### Challenges and wins

A commit is a save point for directory. It is useful because through it, I can revert or restore the changes done, if any features are not working or if any files are accidentally deleted.

---

## Installing Claude Code and Git

In this step, I am setting up:
Claude Code CLI
Git

![Image](http://nextwork.ai/gleeful_rose_silly_kaka/uploads/ai-git-worktrees_qn3v8f5w)

---

## Scaffolding the Budget Tracker with AI

In this step, I am creating creating a git-intialized directory for my project and use Claude Code to scaffold it. I'll also learn about key git concepts like branches, commits and worktrees.

![Image](http://nextwork.ai/gleeful_rose_silly_kaka/uploads/ai-git-worktrees_v2b1np3q)

### Understanding the project structure

Claude Code created three files: 
index.html
styles.css
app.js
The empty main element is where the features are added

---

## Launching the First Worktree Session

In this step, I'm going to do:
Launch a worktree session with Claude Code
Verify my worktree & branch setup by building an "add transaction" feat. 

![Image](http://nextwork.ai/gleeful_rose_silly_kaka/uploads/ai-git-worktrees_m3r8j5w1)

### How worktree isolation works

I used worktrees because. it allowed me to assign files to multiple agents and keep them isolated. The worktree created a new branch called add-transactions and a folder at ~/.claude/worktrees/add-transactions

![Image](http://nextwork.ai/gleeful_rose_silly_kaka/uploads/ai-git-worktrees_h5k9c3n7)

---

## Running Parallel Claude Code Sessions

In this step, I am launching 2 more claude code sessions, assign them different worktrees and execute them in parallel.

![Image](http://nextwork.ai/gleeful_rose_silly_kaka/uploads/ai-git-worktrees_w2p5t9a6)

### Why worktrees stay independent

Just like in Step 3, this worktree creates a separate directory in ~/.claude/worktrees/ and keep all the files separate from the root directory, which is easier during merge

![Image](http://nextwork.ai/gleeful_rose_silly_kaka/uploads/ai-git-worktrees_b5r2x7k9)

### Managing multiple feature branches

The three feature branches I see are:
add-transactions
category-breakdown
monthly-summary

---

## Merging Three Features into One App

I'm merging the worktrees into my master branch because I want a single product with all the developed features.

![Image](http://nextwork.ai/gleeful_rose_silly_kaka/uploads/ai-git-worktrees_q9t3k7m1)

### Resolving merge conflicts with AI

A merge conflict happens when there are 2 versions of the same file with differen edits in each of them. Claude resolved it by merging these 2 versions into a single one

![Image](http://nextwork.ai/gleeful_rose_silly_kaka/uploads/ai-git-worktrees_h5c9w1f3)

---

## Automating Feature Development with Subagents

Subagent are the agents spawned by Claude Code automatically to build a new feature. A Subagent with worktree isolation is the automated process of what I did above.

![Image](http://nextwork.ai/gleeful_rose_silly_kaka/uploads/ai-git-worktrees_vn4t7r9q)

---

---
