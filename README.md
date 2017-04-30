# Resources for Git, GitHub, and Terminal Commands

## Git Basic Steps
1. Use the **`cd`** command in Terminal to navigate to the correct file on the local computer
2. Use the **`git init`** command in Terminal to initialize a Git
3. Use **`git add .`** to add all files
4. Use **`git commit -m ["Message"]`** to commit the files to your local repository
5. Create your repository on [GitHub.com](https://github.com/), and copy the URL for the repository
6. Use **`git push -u origin [URL]`** to connect to the GitHub repository -- enter username and password if necessary
7. Use **`git push -u origin master`** for additional pushes

## Terminal Commands
- **`cat`** = print the contents of a file to the Terminal screen
- **`cd [directory]`** = change Directory
- **`cd ..`** = change Directory up one level
- **`cd ../..`** = change Directory up two levels
- **`clear`** = clear the Terminal screen
- **`echo ["Text"] >> [fileName]`** = create a new file and add the Text to the bottom of the file
- **`git add [fileName]`** = adds a specific file to the repository
- **`git add .`** = adds all files and directories in the current directory to the repository
- **`git commit -m ["Message'].`** = commits the files to the staging area with a Message. 
  - *Message best practices:*
  - Start with an imperative verb
  - End with a period
  - Enclose in quotation marks
  - Written in present tense
  - 50 characters or less
- **`git init`** = initializes a Git repository
- **`git push origin master`** = pushes changes to the master branch on the remote repository
- **`git push -u origin master`** = pushes a new commit (version) upstream (**`-u`**) to the remote repository and links the local and remote repositories
- **`git remote add origin [URL]`** = adds a remote (online) repository at the given URL
- **`git remote -v`** = verify the remote directory
- **`git status`** = prints a log of the changes to the Terminal screen
- **`ls`** = lists all files in the directory
- **`mkdir [directoryName]`** = make a directory with the given Name
- **`pwd`** = print working directory to the Terminal screen
- **`touch [fileName]`** = create a new file with the given Name

## Acronyms
- **BASH** = Bourne-Again SHell
- **CLI** = Command Line Interface

## Git Directory Basics
1. **Working Directory** = make changes to files (additions, deletions, modifications)
2. **Staging Area** = bring changes into the Staging Area
3. **Repository** = save changes to the Repository as a "commit"

*Resources from [Codecademy's](https://www.codecademy.com/) course on Freelance Web Development*
