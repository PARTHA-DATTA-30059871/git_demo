# git_demo
This is for demonstrating Git Merge Conflict 

## Steps to  recreate:
1. Git Clone or Add remote head

```sh
git clone URL
# OR
git remote add origin URL
```

2. Checkout to new branch to work on:
```
git checkout -b feature/partha
```

3. Update any file and do the necessary steps to push back as feature branch
```
git add .
git commit -am "Updating the script"
git push --set-upstream origin feature/partha