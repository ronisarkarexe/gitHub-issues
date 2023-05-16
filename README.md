# Solve GitHub Issues

## Change Git User Name and Gmail, Open your terminal or command prompt.

### Before change, check it by this command

```sh
git config --global --list
```

### After see command, If you think it should need to change Enter the following command

1. user.name:-
```sh
git config --global user.name "Your Name"
```
2. user.email:-
```sh
git config --global user.email "your email"
```

### Check for confirmation

```sh
git config --global --list
```


# Change SSR Key

## Open your terminal or command prompt.

### Enter the following command to start the key generation process:

1. Enter the following command
```sh
ssh-keygen -t ed25519 -C "your_email@example.com"
```
2. Enter 
3. Next, you will be prompted to enter a passphrase. A passphrase adds an extra layer of security to your SSH key, but it's optional. You can press Enter to leave it blank, or enter a passphrase if you prefer.
4. Open id_ed25519.pub
5. Copy all text.
6. GitHub, go to "Settings" → "SSH and GPG keys" → "New SSH key" and paste the public key there.
7. Done


# Here are some common Git commands:

1. `git init` - Initializes an empty Git repository in the current directory.
2. `git clone` - Copies an existing Git repository to a new directory.
3. `git add` - Adds changes to the staging area in preparation for committing.
4. `git commit` - Records changes to the repository.
5. `git status` - Shows the current status of the repository, including changes that have not been committed.
6. `git log` - Shows a list of all commits in the repository.
7. `git branch` - Lists all branches in the repository, and indicates which one is currently active.
8. `git checkout` - Switches to a different branch in the repository.
9. `git merge` - Merges changes from one branch into another.
10. `git push` - Uploads local changes to a remote repository.
11. `git pull` - Downloads changes from a remote repository and incorporates them into the local repository.
12. `git fetch` - Downloads changes from a remote repository, but does not incorporate them into the local repository.
13. `git remote` - Shows a list of remote repositories associated with the local repository.
14. `git tag` - Marks a specific commit with a label or tag.
15. `git diff` - Shows the difference between two commits, or between the working directory and the last commit.
16. `git reset` - Resets the repository to a previous commit.
17. `git revert` - Undoes a previous commit by creating a new commit that reverses the changes.
18. `git stash` - Temporarily saves changes that are not ready to be committed.
19. `git submodule` - Manages submodules, which are separate Git repositories that are embedded within another repository.
20. `git config` - Configures Git settings, such as username and email.


