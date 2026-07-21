GIT BASIC COMMANDS

1. Check Git version
git --version

2. Configure Git user name
git config --global user.name "Your Name"

3. Configure Git email
git config --global user.email "your@email.com"

4. Create a new Git repository
git init

5. Clone an existing repository
git clone <repository-url>


CHECK STATUS

6. Check repository status
git status


ADDING FILES (STAGING)

7. Add one file to staging area
git add filename

Example:
git add file.txt

8. Add all files to staging area
git add .


COMMIT

9. Commit staged files
git commit -m "commit message"

Example:
git commit -m "Added login feature"


VIEW HISTORY

10. View commit history
git log

11. View short commit history
git log --oneline


VIEW CHANGES

12. Show unstaged changes
git diff

13. Show staged changes
git diff --staged


BRANCHES

14. List branches
git branch

15. Create a new branch
git branch branch-name

Example:
git branch feature-login

16. Create and switch to a new branch
git switch -c branch-name

Example:
git switch -c feature-login

17. Switch branch
git switch branch-name

Example:
git switch main

18. Delete a branch
git branch -d branch-name


REMOTE REPOSITORY (GITHUB)

19. Check remote repository
git remote -v

20. Add remote repository
git remote add origin <url>

Example:
git remote add origin https://github.com/user/project.git

21. Upload code to remote repository
git push origin branch-name

Example:
git push origin main

22. Download latest changes
git pull origin branch-name

Example:
git pull origin main

23. Download changes without merging
git fetch


REMOVE FILES

24. Remove file from Git and computer
git rm filename

Example:
git rm file.txt

25. Remove file from Git but keep it on computer
git rm --cached filename

Example:
git rm --cached file.txt


UNDO CHANGES

26. Remove file from staging area
git restore --staged filename

27. Discard changes in a file
git restore filename


STASH

28. Temporarily save unfinished work
git stash

29. Bring back saved work
git stash pop


COMMON DAILY WORKFLOW

1. Get latest code:
git switch main
git pull origin main

2. Create your feature branch:
git switch -c feature-name

3. Work on files

4. Add changes:
git add .

5. Commit:
git commit -m "Description of changes"

6. Push:
git push origin feature-name

7. Create Pull Request on GitHub
feature-name ---> main
