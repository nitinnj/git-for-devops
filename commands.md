# Git Commands Guide

## 1. Setting Up a Git Repository

mkdir git-for-devops  # Create a new directory  
cd git-for-devops/    # Navigate into the directory  
git init              # Initialize an empty Git repository  

## 2. Checking Status and Listing Files

ls      # List files in the directory  
ls -a   # List all files including hidden ones  
ls -l   # List files with detailed information  
git status  # Check the status of the repository  

## 3. Creating and Managing Files

touch nibba.txt  # Create a new file  
touch nibbi.txt  # Create another file  
vim hello.txt    # Open a file in Vim editor  
cat hello.txt    # Display the content of a file  
rm -r hello.txt  # Remove a file  

## 4. Staging and Unstaging Files

git add nibbi.txt  # Stage a specific file  
git add nibba.txt  # Stage another file  
git rm --cached nibba.txt  # Unstage a file (remove from index)  

## 5. Committing Changes

git commit -m "adding nibba nibbi"  # Commit staged changes with a message  

## 6. Branching and Switching Branches

git branch           # List all branches  
git checkout -b dev  # Create and switch to a new branch 'dev'  
git checkout master  # Switch back to the master branch  
git checkout dev     # Switch back to the 'dev' branch  

## 7. Making Changes in a Branch

touch child.txt     # Create a new file  
git add child.txt   # Stage the new file  
git commit -m "committed new file named child"  # Commit the changes  

## 8. Viewing History

git log  # View commit history  

## 9. Restoring and Deleting Files

rm nibbi.txt      # Delete a file  
git restore nibbi.txt  # Restore a deleted file  

## 10. Clearing and Exiting

clear  # Clear the terminal screen  
history  # Show command history  
