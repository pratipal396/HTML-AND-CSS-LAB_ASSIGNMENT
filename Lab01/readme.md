BCS554 - HTML & CSS Development Lab
Name: Pushpendra Singh
Roll No: 24103303351
Student ID: BCS2024369 Section : D Course: B.Tech(CSE) Course: BCS554 - HTML & CSS Development Lab
University: Invertis University, Bareilly (B.Tech CSE)

Invertis University, Bareilly - B.Tech CSE, Third Year

Folder	Assignment
lab1	Starting a Git Repository
lab2	Pushing and Cloning a Repository
lab3	Your First HTML Page
lab4	Divs, Attributes and a Small Fix
lab5	Links and Images
lab6	Types of HTML Lists
lab7	About Me Page
lab8	Sign-Up Forms and Choices
lab9	Tables with Headers and Footers
lab10	CSS Fundamentals
lab11	Units and CSS Variables
lab12	Box Model, Cards and Scrolling
lab13	Flexbox Layouts
lab14	CSS Grid Layouts
lab15	Responsive Pages with Media Queries
Releases

Aim Create a Git repository, set the author identity, make two commits and read the history.

Theory

Git is a version control system. It remembers every saved version (commit) of your project, so you can go back or compare.
A repository (repo) is a project folder that Git tracks. git init creates a hidden .git folder inside it.
git config --local user.name and user.email set the author for this repo only. (--global would set it for every repo.) Running the same command without a value prints the saved value.
Git has three areas: working directory (your files) → staging area (files chosen for the next commit) → repository (saved commits).
git status tells the state of each file: untracked (new), modified, or staged.
git add moves a file to the staging area. git commit -m "message" saves a snapshot with a message.
git log --oneline shows the history, one line per commit, newest first.
Files in this folder

index.html: Final page: an h1 and an h2 (Task 2 and Task 3).
commands.txt: All Git commands for Tasks 1 to 3.
How to check Run the commands in git-practice/html-lab (outside the main lab folder). Take a screenshot of each task's terminal output.