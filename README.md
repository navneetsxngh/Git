# Quick Commands

show modified files in working directory
```bash
git status
```

```bash
git add [file]       ## For a Specific file
git add .            ## To add all the files
```

```bash
git reset [file]     ## unstage a specific file
git reset .          ## unstage all the files
```

commit your staged content as a new commit
```bash
git commit -m "Message"
```


# Git Setup and Init

## STEP 1 --> Global Config

Setting Username
```bash
git config --global user.name "Username"
```

Setting Email
```bash
git congig --global user.email email
```

To Verify Settings (Optional)
```bash
git config --global --list
```

## Step 2 --> Initialization

Initialize an existing directory as a Git Repository
```bash
git init
```

retrieve an entire repository from a hosted location via URL
```bash
git clone [url]
```


## Step 3 --> Branch and Merge
list your branches
```bash
git branch
```

create a new branch at the current commit
```bash
git branch [branch-name]
```

Change the current branch to 'main'
```bash
git branch -M main
```

merge the specified branch's history into the current one
```bash
git merge
```

show all commits in the current branch's history
```bash
git log
```


## Step by Step pushing the files
```bash
git add .                                    ## Add all the files
git commit -m "message"                      ## Stages the files to push
git remote add origin [RepositoryURL]        ## Repositiory URL
git branch -M main                           ## Changing branch to main
git push -u origin main                      ## Pushing to Repositiory