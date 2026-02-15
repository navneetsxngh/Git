# Quick Commands
```bash
git status
```
show modified files in working directory

```bash
git add [file]       ## For a Specific file
git add .            ## To add all the files
```

```bash
git reset [file]     ## unstage a specific file
git reset .          ## unstage all the files
```

```bash
git commit -m "Message"
```
commit your staged content as a new commit



# Git Setup and Init

## STEP 1 --> Global Config

```bash
git config --global user.name "Username"
```
Setting Username

```bash
git congig --global user.email email
```
Setting Email

```bash
git config --global --list
```
To Verify Settings (Optional)

## Step 2 --> Initialization

```bash
git init
```
initialize an existing directory as a Git Repository

```bash
git clone [url]
```
retrieve an entire repository from a hosted location via URL

## Step 3 --> Branch and Merge
```bash
git branch
```
list your branches

```bash
git branch [branch-name]
```
create a new branch at the current commit

```bash
git branch -M main
```
Change the current branch to 'main'

```bash
git merge
```
merge the specified branch's history into the current one

```bash
git log
```
show all commits in the current branch's history