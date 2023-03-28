## create a new repository on the command line

```
echo "# playing-around-with-git" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:vivmagarwal/playing-around-with-git.git
git push -u origin main
```

## push an existing repository from the command line

```
git remote add origin git@github.com:vivmagarwal/playing-around-with-git.git
git branch -M main
git push -u origin main
```