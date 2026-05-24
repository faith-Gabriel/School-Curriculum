# 📚 The Coding Clubhouse — School Curriculum

Welcome to the official curriculum repository for **The Coding Clubhouse**.

This is where all lesson content, exercises, and teaching materials are stored, maintained, and updated. Every change is tracked, every contributor is credited, and nothing is ever permanently lost.

---

## 🗂️ What is in this repository?

This repository contains the full school curriculum organised by class, term and week. Each class folder holds a term file, a week file and a lesson file and an exercises file. Shared assets like images and worksheets are stored in the `assets/` folder.

```
School-Curriculum/
├── README.md                        ← You are here
├── CONTRIBUTING.md                  ← How to make changes
├── LESSON_TEMPLATE.md               ← Template for new lessons
│-- Primary one
├── Term-1/
│   ├── Week-01/
│   │   ├── lesson.md                ← Lesson plan and content
│   │   └── exercises.md             ← Student exercises
│   ├── Week-02/
│   │   ├── lesson.md
│   │   └── exercises.md
│   ├── Week-03/
│   ├── Week-04/
│   ├── Week-05/
│   ├── Week-06/
│   ├── Week-07/
│   ├── Week-08/
│   ├── Week-09/
│   └── Week-10/
│
├── Term-2/
│   ├── Week-01/
│   │   ├── lesson.md
│   │   └── exercises.md
│   └── ... (same structure as Term 1)
│
├── Term-3/
│   └── ... (same structure as Term 1)
│
└── assets/
    ├── images/                      ← Diagrams, screenshots, illustrations
    └── worksheets/                  ← Printable PDFs and extra materials
```

> **File path to create the assets folder:**
> `School-Curriculum/assets/images/` and `School-Curriculum/assets/worksheets/`
> GitHub does not store empty folders, so create a placeholder file inside each:
> `School-Curriculum/assets/images/.gitkeep`
> `School-Curriculum/assets/worksheets/.gitkeep`

---

## 🏫 About The Coding Clubhouse

The Coding Clubhouse is a non-profit organisation that teaches technology and coding skills to school students. This curriculum is used by instructors across our partner schools.

Our curriculum covers:
- Computational thinking and problem solving
- Block-based and text-based programming
- Digital literacy and online safety
- Real-world project-based learning

---

## 📖 How the curriculum is organised

Each **term** runs for approximately 10 weeks. Each **week** contains:

| File | What it contains |
|------|-----------------|
| `lesson.md` | Learning objectives, key concepts, teaching notes, and step-by-step lesson plan |
| `exercises.md` | Student-facing tasks, activities, and challenges for that week |

All lesson files follow the same structure defined in [`LESSON_TEMPLATE.md`](./LESSON_TEMPLATE.md).

---

## ✏️ How to contribute

All curriculum managers, instructors, and contributors must follow the process described in [`CONTRIBUTING.md`](./CONTRIBUTING.md) before making any changes.

**Quick summary:**
1. Fork this repository to your own GitHub account
2. Make your changes in your fork
3. Open a Pull Request for review
4. A maintainer will review and merge it

> ⚠️ **Do not edit files directly on the `main` branch.** All changes must come through a Pull Request.

---

## 🐛 Reporting problems

Found a mistake? Something out of date? Need a new lesson?

Go to the [Issues tab](https://github.com/The-Coding-Clubhouse/School-Curriculum/issues) and open a new Issue. Choose from the available templates:

- **🐛 Content Error** — typos, wrong information, broken links
- **✨ New Lesson Request** — suggest a topic or activity to add
- **📅 Outdated Content** — flag content that needs refreshing

---

## 👥 Who maintains this repository?

This repository is maintained by the curriculum team at The Coding Clubhouse.

| Role | Responsibility |
|------|---------------|
| Curriculum Lead | Reviews and approves all Pull Requests |
| Curriculum Managers | Write, edit, and maintain lesson content |
| Instructors | Report issues and suggest improvements |

---

## 📄 Licence

Curriculum content © The Coding Clubhouse, licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

You are free to use, share, and adapt this material for any purpose, as long as you give appropriate credit to The Coding Clubhouse.

Code examples and starter files are licensed under the [MIT License](./LICENSE).
