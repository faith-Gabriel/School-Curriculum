# Contributing to the School Curriculum

Thank you for helping maintain The Coding Clubhouse curriculum. This guide explains exactly how to make changes — whether you are fixing a typo, updating a lesson, or adding new content.

Please read this fully before making your first edit.

---

## 📋 Table of contents

1. [Before you start](#1-before-you-start)
2. [Fork the repository](#2-fork-the-repository)
3. [Set up your working environment](#3-set-up-your-working-environment)
4. [Create a branch for your changes](#4-create-a-branch-for-your-changes)
5. [Make your changes](#5-make-your-changes)
6. [Write a good commit message](#6-write-a-good-commit-message)
7. [Open a Pull Request](#7-open-a-pull-request)
8. [The review process](#8-the-review-process)
9. [Commit message reference](#9-commit-message-reference)

---

## 1. Before you start

- Make sure you have a [GitHub account](https://github.com)
- Check the [Issues tab](https://github.com/The-Coding-Clubhouse/School-Curriculum/issues) to see if someone is already working on the same thing
- If you are making a significant change, open an Issue first to discuss it before you start editing

> ⚠️ **Never edit the `main` branch directly.** The `main` branch is the live curriculum. All changes must go through a Pull Request so they can be reviewed before going live.

---

## 2. Fork the repository

Forking creates your own personal copy of the curriculum under your GitHub account.

1. Go to [https://github.com/The-Coding-Clubhouse/School-Curriculum](https://github.com/The-Coding-Clubhouse/School-Curriculum)
2. Click the **Fork** button (top-right of the page)
3. Keep all default settings and click **Create fork**
4. You now have your own copy at `https://github.com/YOUR-USERNAME/School-Curriculum`

---

## 3. Set up your working environment

Choose one of the following options:

### Option A — GitHub Codespaces (browser, no install needed)

1. Go to your forked repository
2. Click the green **Code** button → **Codespaces** tab
3. Click **Create codespace on main**
4. Wait ~30 seconds — VS Code opens in your browser
5. You can now edit files directly

### Option B — VS Code on your computer

1. Install [VS Code](https://code.visualstudio.com) if you have not already
2. Install [Git](https://git-scm.com/downloads) if you have not already
3. On your fork page, click the green **Code** button → copy the **HTTPS** link
4. In VS Code: **View → Command Palette → Git: Clone**
5. Paste the link and choose a folder on your computer
6. Click **Open** — the curriculum files appear in VS Code

---

## 4. Create a branch for your changes

A branch is a safe copy of the curriculum where you can make edits without affecting the live version.

**In GitHub Codespaces or VS Code:**

1. Open the Source Control panel (the branch icon in the left sidebar)
2. Click the branch name at the bottom-left (it says `main`)
3. Click **Create new branch**
4. Name your branch using this format:

```
fix/week-02-typo-lesson
update/term-1-week-05-objectives
add/term-2-week-03-new-lesson
```

**Branch naming rules:**

| Type of change | Prefix to use | Example |
|----------------|--------------|---------|
| Fixing an error | `fix/` | `fix/term1-week3-broken-link` |
| Updating existing content | `update/` | `update/term2-week1-objectives` |
| Adding new content | `add/` | `add/term2-week6-new-lesson` |
| Removing outdated content | `remove/` | `remove/term1-week4-old-exercise` |

---

## 5. Make your changes

- All lesson files are written in **Markdown** (`.md` files)
- Every new lesson must use the [`LESSON_TEMPLATE.md`](./LESSON_TEMPLATE.md) structure
- Keep language clear, simple, and appropriate for the age group
- Do not delete sections from a lesson file — if content is no longer needed, replace it rather than leaving a blank section
- Images and worksheets go in the `assets/` folder:
  - Images → `assets/images/your-image-name.png`
  - Worksheets → `assets/worksheets/your-worksheet-name.pdf`
- Reference images in lesson files like this:
  ```markdown
  ![Description of image](../../assets/images/your-image-name.png)
  ```

---

## 6. Write a good commit message

A commit message is the short note you write every time you save a change. It must be clear enough for someone to understand what changed without opening the file.

### Format

```
type: short description of what changed

Optional longer explanation if needed.
Reference issue number if applicable: closes #42
```

### Good examples

```
fix: corrected typo in Term 1 Week 2 lesson intro
update: revised learning objectives in Term 2 Week 5
add: new debugging exercise to Term 1 Week 7 exercises
remove: deleted outdated Scratch 2.0 instructions from Term 1 Week 3
fix: replaced broken YouTube link in Term 2 Week 1 lesson
update: clarified assessment criteria in Term 3 Week 2
```

### Bad examples — avoid these

```
update          ← too vague
changes         ← meaningless
fixed stuff     ← not specific enough
asdfg           ← never acceptable
```

**Rule:** If someone reads your commit message 6 months from now, they should know exactly what file was changed and why.

---

## 7. Open a Pull Request

Once your changes are ready:

1. Push your branch to GitHub (VS Code will prompt you, or click **Publish Branch**)
2. Go to your fork on GitHub — you will see a banner saying your branch was recently pushed
3. Click **Compare & pull request**
4. Fill in the Pull Request form:
   - **Title:** Use the same format as your commit message (e.g. `fix: typo in Term 1 Week 3 lesson`)
   - **Description:** Explain what you changed and why. Link to the Issue it relates to if applicable (type `closes #` followed by the issue number)
5. Click **Create pull request**

A curriculum maintainer will be notified and will review your changes.

---

## 8. The review process

After you open a Pull Request:

| Stage | What happens |
|-------|-------------|
| **Submitted** | A maintainer is notified and will review within a few days |
| **Changes requested** | The maintainer leaves comments — address each one and push your updates |
| **Approved** | The maintainer approves the PR |
| **Merged** | Your changes go live on the `main` branch |
| **Closed** | If the change is not accepted, the PR is closed with an explanation |

**If changes are requested:**
1. Read each comment carefully
2. Make the requested edits in the same branch
3. Commit and push — the PR updates automatically
4. Reply to each comment to confirm you have addressed it

---

## 9. Commit message reference

| Prefix | Use for |
|--------|---------|
| `fix:` | Correcting errors, typos, broken links |
| `update:` | Revising or improving existing content |
| `add:` | Adding new lessons, exercises, or assets |
| `remove:` | Removing outdated or incorrect content |
| `reorder:` | Moving content to a different week or term |
| `format:` | Fixing formatting without changing content |

---

## Questions?

If you are unsure about anything, open an Issue with the label `question` and a maintainer will help you.

Thank you for contributing to The Coding Clubhouse curriculum. 🎉
