# unfuck-my-git
___
**unfuck-my-git** is a practical Git guide. It’s designed to teach you how to use Git effectively, fix common screw-ups, and understand what’s actually going on behind the scenes.

Whether you're a beginner or someone who just screamed at a merge conflict for the third time today — this is for you.

## Structure
This repository is structured into **three progressive sections**, each living on its own branch:

| Section    | Branch     | Time       | Focus                            |
|------------|------------|------------|----------------------------------|
| **foreplay** | `foreplay` | ~10 minutes | Git basics & local workflow      |
| **quicky**   | `quicky`   | ~30 minutes | Branching, merging, undoing      |
| **go-deep**  | `go-deep`  | ~120 minutes | Advanced workflows & recovery    |

Scroll to the bottom to learn how to start.

---

## 🔹 foreplay (`foreplay` branch)
**Estimated Time: 10 minutes**

Start here if you're completely new or want a quick brush-up.

### Learn how to:
- Create a local repository (`git init`)
- Clone a remote repository (`git clone`)
- Check the current status (`git status`)
- Stage changes (`git add`)
- Commit changes (`git commit`)
- View commit history (`git log`)
- Push to a remote repository (`git push`)
- Set up your identity (`git config`)

### Concepts:
- What Git actually *is*
- Working directory vs. staging area vs. repository
- Local vs. remote (basic overview)

---

## 🔸 quicky (`quicky` branch)
**Estimated Time: 30 minutes**

Ready to do more than just commit? This section adds collaboration, version control, and basic damage control.

### Includes everything from **foreplay**, plus:
- Create and manage branches (`git branch`, `git checkout -b`)
- Switch between branches (`git switch`)
- Merge branches (`git merge`)
- View and resolve merge conflicts
- View changes (`git diff`)
- Remove or move tracked files (`git rm`, `git mv`)
- Undo changes:
    - Unstage files (`git reset`)
    - Revert commits (`git revert`)
    - Discard changes (`git checkout -- <file>`)
- Pull latest changes (`git pull`)
- Add a remote (`git remote add`)
- Fetch without merging (`git fetch`)

### Concepts:
- Branching model
- Fast-forward vs recursive merge
- Conflict basics
- Reset vs revert vs checkout (simplified)

---

## 🔻 go-deep (`go-deep` branch)
**Estimated Time: 120 minutes**

This is the advanced section. Learn how to **recover**, **rebase**, and **refactor** like a pro.

### Includes everything from **quicky**, plus:
- Rewrite history safely:
    - Rebase (`git rebase`)
    - Interactive rebase (`git rebase -i`)
    - Amend last commit (`git commit --amend`)
- Inspect the past:
    - Blame (`git blame`)
    - Show file history (`git log -p`, `git show`)
    - Find who broke it (`git bisect`)
- Stash work-in-progress (`git stash`, `git stash pop`)
- Tag important commits (`git tag`)
- Cherry-pick specific commits (`git cherry-pick`)
- Clean untracked files (`git clean`)
- Recover lost commits (`git reflog`)

### Concepts:
- Rewriting vs reverting history
- When to rebase vs when to merge
- Cleaning up your commit history
- Collaboration workflows: GitHub flow, Git flow, trunk-based development
- Best practices: commit hygiene, atomic commits, meaningful messages

---

## Getting Started
To explore a branch and its documentation **on GitHub**:

1. Click the **branch selector dropdown** at the top left of the file list (it says `main`).
2. Search for or select one of the learning branches:
  - `foreplay`
  - `quicky`
  - `go-deep`
3. GitHub will reload the page with the contents of that branch.

---

To explore a branch **locally**, run:

```bash
git clone https://github.com/your-username/unfuck-my-git.git
cd unfuck-my-git
git checkout foreplay   # or quicky / go-deep