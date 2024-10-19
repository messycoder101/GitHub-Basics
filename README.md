# Learning Git Commands :)

## 1. Setting Up a Repository
- **Create a new directory for the repository**
  ```bash
  mkdir git-for-devops
  ```

- **Change into the directory**
  ```bash
  cd git-for-devops/
  ```

- **Initialize a new Git repository**
  ```bash
  git init
  ```

## 2. File Operations
- **Create a new file**
  ```bash
  vim hello-dosto.txt
  ```

- **Create multiple files**
  ```bash
  touch nibba.txt nibbi.txt
  ```

- **Remove a file**
  ```bash
  rm nibbi.txt
  ```

- **Restore a deleted file**
  ```bash
  git restore nibbi.txt
  ```

## 3. Checking Status
- **Check current directory path**
  ```bash
  pwd
  ```

- **List files in the directory**
  ```bash
  ls
  ```

- **List files with detailed info**
  ```bash
  ls -l
  ```

- **Show hidden files**
  ```bash
  ls -la
  ```

- **Check the status of the Git repository**
  ```bash
  git status
  ```

## 4. Staging and Committing Changes
- **Add a file to the staging area**
  ```bash
  git add nibbi.txt
  ```

- **Add all changes to the staging area**
  ```bash
  git add .
  ```

- **Remove a file from the staging area**
  ```bash
  git rm --cached nibba.txt
  ```

- **Commit changes with a message**
  ```bash
  git commit -m "adding nibba nibbi"
  ```

## 5. Configuring User Information
- **Set global username**
  ```bash
  git config --global user.name "yourUSERNAME"
  ```

- **Set global email**
  ```bash
  git config --global user.email "YOUR@EMAIL"
  ```

## 6. Branching
- **Create a new branch and switch to it**
  ```bash
  git checkout -b dev
  ```

- **List all branches**
  ```bash
  git branch
  ```

- **Switch back to the master branch**
  ```bash
  git checkout master
  ```

## 7. Viewing Logs
- **View the commit log**
  ```bash
  git log
  ```

- **View a simplified log**
  ```bash
  git log --oneline
  ```

## 8. Aliases
- **Create an alias for `git status`**
  ```bash
  alias gs='git status'
  ```

## 9. Miscellaneous
- **Show remote repository URLs**
  ```bash
  git remote -v
  ```

- **View command history**
  ```bash
  history
  ```

- **Show tree structure of files (if installed)**
  ```bash
  tree
  ```
