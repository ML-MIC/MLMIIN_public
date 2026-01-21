
# MLMIIN – How Weekly Assignments Work

This course uses **GitHub Classroom** to distribute and collect weekly assignments.
Each assignment lives in its **own GitHub repository**, created automatically for you.

## 1. What happens each week

1. You receive a GitHub Classroom assignment link.
2. You click the link and accept the assignment.
3. GitHub creates a **private repository** for you inside the course organization.
4. You clone that repository to your laptop.
5. You work locally (using Docker or a native environment).
6. You commit and push your work.

That’s it. There is **no syncing with previous weeks**.

---

## 2. Repository structure

Each assignment repository contains only the material for that week.

Typical structure:

```
week_07/
├── theory.ipynb
├── exercises.ipynb
├── data/
└── README.md
```

You should **only modify files inside your assignment repository**.

---

## 3. How to work on the assignment

1. Clone your assignment repository:
   ```bash
   git clone https://github.com/<org>/<assignment-repo>.git
   ```

2. Open the folder in VS Code.

3. Run notebooks:
   - Using the provided Docker setup **or**
   - Using a native conda environment (if instructed)

4. Save notebooks **with outputs** before submission unless instructed otherwise.

---

## 4. Submitting your work

Submission is automatic:

- Your **latest pushed commit before the deadline** is your submission.
- You do not need to upload anything separately.

You may push multiple times before the deadline.

---

## 5. Feedback and grading

- You will receive feedback through a **Feedback Pull Request** in your repository.
- Comments may be:
  - Inline on code or notebook cells
  - General comments on structure, clarity, or results

Grades will be based on the rubric published for the course.

---

## 6. Common mistakes to avoid

- ❌ Editing files outside your assignment repo
- ❌ Forgetting to push commits
- ❌ Working in the wrong repository or week
- ❌ Assuming Docker/conda issues excuse missing work (ask early!)

---

## 7. If something goes wrong

- Check that you accepted the correct assignment link.
- Verify you pushed your changes.
- Ask questions early on the course forum or in class.
