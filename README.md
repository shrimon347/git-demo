# Git Demo Project

This is a simple Git demo project to practice version control with Git and GitHub.

## ✨ Git Workflow

Follow these steps to create a new branch, modify files, and merge changes into the main branch.

### ✅ 1. Create a New Branch Named `feature-branch`
```sh
git branch feature-branch
```

### ✅ 2. Switch to the New Branch
```sh
git checkout feature-branch
```
Or, for Git 2.23+:
```sh
git switch feature-branch
```

### ✅ 3. Modify `README.md` (e.g., Add More Details)
Edit the `README.md` file and save your changes.

### ✅ 4. Add and Commit the Changes
```sh
git add README.md
git commit -m "chore(docs): update README with additional details"
```

### ✅ 5. Push the Branch to GitHub
```sh
git push -u origin feature-branch
```

### ✅ 6. Merge `feature-branch` into `main`
Switch back to the `main` branch:
```sh
git checkout main
```
Then, merge the changes:
```sh
git merge feature-branch
```

### ✅ 7. Delete the `feature-branch` (Optional)
After merging, you can delete the branch locally:
```sh
git branch -d feature-branch
```
And remove it from GitHub (if no longer needed):
```sh
git push origin --delete feature-branch
```

---

Now you have a structured workflow for creating branches, modifying files, and merging changes in Git! 🚀

