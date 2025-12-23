Level 1

In this level, I learned that a commit is used to save changes in Git. Each commit creates a new version of the project, and by making multiple commits, Git builds the complete history of the project over time.<img width="1915" height="908" alt="image" src="https://github.com/user-attachments/assets/e371c505-016f-451e-b3ff-fc8bb3abafa8" />
git commit

Level 2<br>
In this level, I learned that a branch allows developers to work on a new feature separately without affecting the main code. I created a new branch named bugFix and switched to it to work independently.
<img width="1897" height="910" alt="image" src="https://github.com/user-attachments/assets/09f7b207-87d0-4b01-b155-070f3d444c9d" />
git branch bugFix<br>
git checkout bugFix<br>
Level 3 <br>
In this level, I learned how to merge changes from one branch into another. I first made a commit in the bugFix branch, then made a commit in the main branch, and finally merged the bugFix branch into main, which created a merge commit.
<img width="1898" height="911" alt="image" src="https://github.com/user-attachments/assets/9cde06b7-dd68-49c4-95a5-7f0503dd5a4e" />
git checkout -b bugFix<br>
git commit<br>
git checkout main<br>
git commit<br>
git merge bugFix
