# Lab 4: Git & GitHub

**Question 1:** `--global` saves your name and email for every repo on this computer; without it, the setting applies only to the current repo.

**Question 2:** `ls -a` reveals the hidden `.git` folder, which holds the repo's entire history and settings.

**Question 3:** Git offered about [N] files and folders, and the `.venv/` entries were not written by me; they are other people's installed code.

**Question 4:** The `.venv/` and `__pycache__/` entries disappeared from the untracked list, leaving only my own files and `.gitignore`.

**Question 5:** `.gitignore` should be committed so the ignore rules are saved in the history and travel to GitHub and anyone who clones the repo.

**Question 6:** `README.md` moved from "Untracked files" to "Changes to be committed", meaning it went from the working folder to the staging area.

**Question 7:** Git printed the branch, a short commit ID and the message, then "[N] files changed", which is the number of files saved in that commit.

**Question 8:** It is the short commit hash, a unique ID used to refer to that exact commit (for example in `git show`).

**Question 9:** The loop is edit files, check with `git status`, stage with `git add`, then save with `git commit`.

**Question 10:** `README.md` is the standard name and sits in the repo root because GitHub looks for it there and shows it as the project's front page guide.

**Question 11:** It stores a login token on my computer that Git uses automatically, so pushes do not ask for a password.

**Question 12:** The README is shown (rendered as formatted text) because GitHub automatically displays the `README.md` in the repo root.

**Question 13:** No, pushing only copies my commits to GitHub and leaves my local history unchanged.

**Question 14:** A private repo exists on GitHub but only I and invited people can see it, while a repo that does not exist has nothing on GitHub at all to share or see.
