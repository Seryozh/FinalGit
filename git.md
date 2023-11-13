# Git Commands and Their Relationships

## 1. `git init`
**Purpose:** 
Initializes a new Git repository. It's the starting point for any Git project.

**Relation to Others:** 
It's the first command you use. Once a repository is initialized, you can start adding files to it with `git add`.

---

## 2. `git add`
**Purpose:** 
Stages changes for the next commit. It tells Git which changes you want to include in the next snapshot of the project.

**Relation to Others:** 
It connects the changes in your working directory (like new or modified files) to the staging area, preparing them for a `git commit`. You can check which changes are staged using `git status`.

---

## 3. `git commit`
**Purpose:** 
Takes a snapshot of the staged changes. This is how you record the history of your project in Git.

**Relation to Others:** 
It follows `git add`. Once changes are staged, they are committed to the repository's history. You can view these commits using `git log`. Also, you can use `git status` to see if there are any more changes to commit.

---

## 4. `git status`
**Purpose:** 
Shows the status of changes as untracked, modified, or staged.

**Relation to Others:** 
It's a diagnostic tool. Use it after `git add` to see if all changes are staged and after `git commit` to check if all changes are committed. It doesn’t directly affect the repository but provides information on its state.

---

## 5. `git log`
**Purpose:** 
Displays the committed history of the project.

**Relation to Others:** 
It's used after `git commit` to review the history of the project. It shows the sequence of commits and is essential for understanding the evolution of the project.
