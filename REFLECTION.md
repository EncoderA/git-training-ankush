# Reflection - Git Training Assignment

## What I Learned

I learned how Git history becomes easier to understand when each commit has one clear purpose. Creating the home page, styling it, and then adding separate pages on feature branches made the workflow feel organized.

I also learned why pull requests are useful even on a solo project. A pull request creates a review step before code reaches `main`, and it keeps a visible record of what changed and why.

The merge conflict exercise showed me that a conflict is not an error to panic about. Git marks the competing changes, and the developer chooses the final version, stages the file, and commits the resolution.

## What Confused Me

The most confusing part was understanding the difference between `git fetch`, `git pull`, and `git merge`. I now understand that `git pull` downloads remote changes and immediately tries to merge them into the current branch.

Another confusing point was branch cleanup. Deleting a local branch does not delete the remote branch unless I explicitly push the deletion to GitHub.

## One Command to Explore Further

```bash
git log --oneline --graph --all --decorate
```

I want to explore this command further because it shows branches, merges, and commit history in a visual way.
