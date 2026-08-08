echo # git-mastery >> README.md
git init
git add README.md
git commit -m first commit
git branch -M main
git remote add origin git@github.com:HITESHDALVI/git-mastery.git
git push -u origin main

# We add above commads to register the first branch in git history

# switch uses -c unlike branch command which uses the -b for creating a new branch

# git do not track empty folder
