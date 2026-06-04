# Week 4 Git & GitHub Advanced Challenge

## Repository

90DaysOfDevOps

---

## Task 1: Fork and Clone Repository

Commands Used:

```bash
git clone https://github.com/csriramganesh/90DaysOfDevOps.git
cd 90DaysOfDevOps
```

---

## Task 2: Initialize Local Repository

Commands Used:

```bash
mkdir week-4-challenge
cd week-4-challenge
git init
```

---

## Task 3: Create File and Commit

Commands Used:

```bash
vim info.txt
git add info.txt
git commit -m "Initial commit: Add info.txt with introductory content"
```

Commit Hash:

```text
df037ba15eabe889c1965196c5bf3c2e216f3444
```

---

## Task 4: Configure Remote and Push

Commands Used:

```bash
git remote add origin https://github.com/csriramganesh/90DaysOfDevOps.git
git push -u origin main
```

---

## Task 5: Explore Commit History

Commands Used:

```bash
git log
git log --oneline
git show
```

---

## Task 6: Branching and Feature Development

Commands Used:

```bash
git checkout -b feature-update
git switch feature-update

git add info.txt
git commit -m "Feature update: Enhance info.txt with additional details"

git push -u origin feature-update
```

Feature Branch Commit Hash:

```text
6bf12ca3ee059369e9369046625ff57a534581e6
```

---

## Why Branching Strategies Are Important

Branching strategies are important in collaborative software development because they allow developers to work independently without affecting the main codebase.

Benefits include:

1. Isolating Features and Bug Fixes

   * Developers can work on features separately.
   * Bugs can be fixed without impacting ongoing development.

2. Facilitating Parallel Development

   * Multiple team members can work simultaneously.
   * Development becomes faster and more organized.

3. Reducing Merge Conflicts

   * Changes are isolated and reviewed before merging.
   * Conflicts become easier to identify and resolve.

4. Enabling Effective Code Reviews

   * Pull Requests provide a structured review process.
   * Teams can maintain code quality standards.

Branching is one of the core practices used in modern DevOps and software engineering workflows.

