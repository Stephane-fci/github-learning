# Git & GitHub Glossary

## Core Concepts

**Repository (repo)**
- A project folder that tracks all changes to your files over time
- Contains your project files + a hidden `.git` folder with version history
- Like a "magic folder" that remembers every version of every file

**Git**
- The software that tracks changes to files on your computer
- Works locally (on your computer only)
- The "engine" that powers version control

**GitHub**
- An online platform where people store and share git repositories
- Like "Google Drive for code projects"
- Provides web interface, collaboration tools, and cloud storage for git repos

**Local Repository**
- The git repository on your computer
- Changes here are private to you until you share them
- Located in your project folder (contains the `.git` folder)

**Remote Repository**
- The copy of your repository stored online (usually on GitHub)
- Other people can see and contribute to it
- The "published" version of your project

## Actions & Commands

**git init**
- Creates a new git repository in your current folder
- Adds the hidden `.git` folder that tracks everything
- Turns a regular folder into a git repository

**Commit**
- A "snapshot" of your project at a specific moment in time
- Like saving your progress in a video game
- Contains: what files changed, when, who made the changes, and why

**Snapshot**
- Another word for commit
- A saved state of all your files at one point in time
- You can go back to any snapshot later

**Staging Area**
- A temporary holding area for files before you commit them
- Like a "shopping cart" - you add files you want to include in your next commit
- Command: `git add filename`

**git add**
- Puts files into the staging area
- You're saying "I want these files in my next commit"
- Must be done before committing

**git status**
- Shows you what's happening in your repository right now
- Lists: untracked files, staged files, modified files
- Like asking "what's the current situation?"

**git commit**
- Creates a snapshot (commit) of all files in the staging area
- Requires a message explaining what you changed
- Saves the snapshot to your local repository

## File Storage & Organization

**.git folder**
- Hidden folder created by `git init`
- Stores all your commits, branches, and git configuration
- The "brain" of your repository - don't delete this!

**objects folder**
- Inside `.git` folder
- Where git stores the actual file snapshots/commits
- Think of it as git's "storage warehouse"

**refs folder**
- Inside `.git` folder
- Contains pointers to different commits and branches
- Like "bookmarks" pointing to specific snapshots

**Untracked files**
- Files that exist in your folder but git isn't watching them yet
- Git knows they exist but ignores changes to them
- Use `git add` to start tracking them

**Tracked files**
- Files that git is monitoring for changes
- Git will notice when these files are modified
- Started tracking when you first used `git add` on them

## GitHub CLI Specific

**GitHub CLI (gh)**
- Command-line tool for interacting with GitHub
- Lets you create repos, issues, pull requests without using the website
- Connects your local git commands with GitHub's online features

**Authentication**
- Process of proving you are who you say you are to GitHub
- Required before you can create or modify repositories on GitHub
- Usually done once and then remembered

## Workflow Terms

**Branch**
- A separate "timeline" of your project where you can make changes
- Like making a copy to experiment without affecting the main version
- Main branch is usually called "main" or "master"

**Push**
- Uploading your local commits to the remote repository (GitHub)
- Sharing your changes with the online version
- Command: `git push`

**Pull**
- Downloading changes from the remote repository to your local one
- Getting updates that others have made
- Command: `git pull`

**Clone**
- Making a complete copy of a GitHub repository on your computer
- Downloads the entire project and its history
- Command: `git clone [url]`

## Quick Reference

**The Basic Workflow:**
1. Make changes to your files
2. `git add` (stage the changes)
3. `git commit` (save a snapshot)
4. `git push` (upload to GitHub)

**File States:**
- **Untracked**: Git doesn't know about the file
- **Staged**: File is ready to be committed
- **Committed**: File snapshot is saved in git history
- **Pushed**: File snapshot is uploaded to GitHub