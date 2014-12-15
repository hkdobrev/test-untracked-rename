This is a test Git repo.

I want to test when I have a folder with ignored files inside, but a single tracked `.gitkeep` file,
and then if I rename the folder (Git will track the rename in the path to the `.gitkeep` file)
will it keep the untracked files and if yes - where.


---

Result: Git keeps the old ignored folder and the untracked files and does not delete anything. In the renamed folder, only the tracked files are moved.
