# new-project manual

```sh
mkdir new-project
cd new-project
touch README.md
git add README.md
git commit -m "init"
git branch development
git checkout development
vim README.md
#//edit file as needed
#//don't forget :wq to exit saving changes:)
git add README.md
git commit -m "Add step-by-step instructions to README.md"
git checkout main
git merge defelopment
git status
git commit -m "Merge development with main"
```

That's it folks.

