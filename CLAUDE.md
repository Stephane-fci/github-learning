# Claude Code Configuration - GitHub CLI Learning Project

## Project Overview
This is a **beginner-friendly learning project** focused on mastering Git and GitHub CLI from the ground up.

## User Context - CRITICAL
- **Complete beginner** - NOT a developer
- Needs **detailed explanations** for every step
- Requires understanding the **WHY** before the **WHAT**
- Learning Git/GitHub concepts through hands-on practice

## Teaching Approach Required
- **Break down complex tasks** into simple steps
- **Explain technical concepts** in beginner terms
- **Always explain WHY** before showing commands
- **Show practical examples** of each command
- **Provide context** for each action
- Be **patient and thorough** with explanations
- Use **simple, non-technical language**

## Project Commands
- No build process needed (static files only)
- No automated tests configured
- Primary tools: `git`, `gh` (GitHub CLI)

## Learning Goals Progress
1. ✅ Understand what GitHub CLI is and why it's useful
2. ✅ Learn basic git concepts (repositories, commits, etc.)
3. ✅ Practice GitHub CLI commands with real examples
4. ✅ **COMPLETED: Git Branches for SaaS Development** (Critical for SaaS development)
5. ✅ **COMPLETED: Git Tags as restoration points**
6. ✅ **COMPLETED: Branch merging and cleanup workflow**
7. 🔄 **NEXT TOPIC: Simple Commit Workflow** (Exploring simplest approach for solo SaaS)
8. ⏳ Understand GitHub Issues
9. ⏳ Quick overview of Actions/Workflows and Pull Requests
10. ⏳ GitHub Project Management features
11. ⏳ Build complete confidence with Git and GitHub

## Recently Completed (Git Branches & Tags Session)
**Accomplished:**
- ✅ Understanding why branches protect SaaS production code
- ✅ Created and worked with feature branches (`add-contact-form`)
- ✅ Learned branch workflow: create → work → commit → push → merge → delete
- ✅ Mastered Git tags as restoration points (`v1.0-stable-contact-page`)
- ✅ Practiced disaster recovery using tags and `git reset --hard`
- ✅ Understood local vs GitHub repository synchronization
- ✅ Learned difference between forks and branches
- ✅ Successful merge and branch cleanup workflow
- ✅ Demonstrated sync problems when editing directly on GitHub

**Key Commands Mastered:**
- `git checkout -b branch-name` (create and switch to branch)
- `git merge branch-name` (merge branch to master)
- `git branch -d branch-name` (delete local branch)
- `git push origin --delete branch-name` (delete GitHub branch)
- `git tag tag-name` (create restoration point)
- `git push origin tag-name` (push tag to GitHub)
- `git reset --hard tag-name` (restore to tag)
- `git push --force origin master` (force update GitHub)
- `git pull` (sync local with GitHub)
- `git fetch origin` (check for updates without merging)

**Real-world scenarios practiced:**
- Safe feature development using branches
- Emergency rollback using tags
- Repository synchronization issues and solutions
- Solo vs team development workflows

## Next Learning Session - START HERE
**TOPIC: Simple Commit Workflow for Solo SaaS Development**

**Why this matters:** User wants to explore the simplest possible workflow. Since every commit creates a restoration point with its SHA, maybe branches and tags add unnecessary complexity for solo development.

**What to explore:**
1. Using commit history as restoration points (no tags needed)
2. Going back 2-3 commits using commit SHAs
3. Simple workflow: edit → commit → push (stay on master)
4. When this approach works vs when branches are still needed
5. `git log` and `git reset` for navigation
6. Compare simplicity vs safety trade-offs

**Goal:** Determine if commit-only workflow is sufficient for simple SaaS development.

**After Simple Commits, cover:**
1. **GitHub Issues** - What they are and basic usage
2. **Actions/Workflows & Pull Requests** - Quick overview
3. **GitHub Project Management** - Built-in project features
4. **Final confidence building** - Complete Git/GitHub mastery

## Project Structure
- `README.md` - Project description
- `glossary.md` - Technical terms reference (UPDATE when introducing new concepts)
- `CLAUDE.md` - This configuration file

## Important Instructions for Claude
- Always update `glossary.md` when introducing new Git/GitHub terms
- Use TodoWrite tool to track learning progress
- Explain commands before running them
- Show what each action accomplishes
- Help user understand the bigger picture of version control
- This is a **safe learning environment** - encourage questions
- Maintain beginner-friendly pace throughout sessions

## Preferences
- Focus on practical, hands-on learning
- Visual explanations when possible
- Connect new concepts to previously learned ones
- Encourage questions and exploration