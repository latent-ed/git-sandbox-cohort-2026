# Git Sandbox — Cohort 2026
 
A practice repo. Nothing here matters. Break it, fix it, break it again.
 
## Two ways to change a file
 
**In the browser** — click a file, hit the pencil, edit, commit.
Good for typos, README tweaks, quick fixes.
 
**On your machine** — clone, edit in your editor, commit, push.
Necessary for anything you need to run or test first.
 
Both create commits. Both are real. Use whichever fits the job.
 
## Drill 1 — Your first pull request
 
1. Create a branch called `yourname/intro`
2. Add a file at `team/yourname.md`
3. Write three lines about yourself
4. Commit, push, open a pull request
5. Wait for approval, then merge
6. Delete your branch, then run `git pull` on main
 
Everyone edits a different file, so nobody conflicts.
 
## Drill 2 — The merge conflict
 
Two people edit **the same line** of `team-notes.md` on separate
branches. The first to merge succeeds. The second gets a conflict
— and resolves it.
 
This is deliberate. Better to meet your first conflict here than at
midnight in a real pipeline.
 
## House rules
 
- Never push straight to `main` — always branch
- Branch names: `yourname/what-it-does`
- Commit messages say what changed and why
- Delete your branch once it is merged
