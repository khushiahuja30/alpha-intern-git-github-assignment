Git and GitHub Workshop Assignment
<br>
Command Used :- git --version
<br>
Output :- git version 2.54.0.windows.1
<br>
Command Used :- git config --global user.name"Khushi"
<br>
Command Used :- git config --global user.email"ahujarekha09@gmail.com"
<br>
Output :- Khushi
<br>
Output :- ahujarekha09@gmail.com
<br>
Git Log Output :-
<br>
e562059 (HEAD -> main, feature/day-1-final) Add branch practice file
<br>
a2a4c85 Add day1 practice file
<br>
d67c29e (origin/main, origin/HEAD) Update ASSIGNMENT.md
<br>
e93d7cb Create ASSIGNMENT.md
<br>
420cefa Update README.md
<br>
512329a Initial commit
<br>
Branch Rename Command
<br>
Command Used:
<br>
git branch -m feature/day-1-practice feature/day-1-final
<br>
Purpose:
<br>
This command renames an existing branch from feature/day-1-practice to feature/day-1-final.
<br>
Merge Conflict Explanation
<br>
A merge conflict occurs when the same part of a file is modified differently in two branches and Git cannot automatically decide which version to keep.
<br>
Resolution Steps:
<br>
Open the conflicted file.
<br>
Review both versions of the changes.
<br>
Keep the correct content.
<br>
Remove conflict markers.
<br>
Save the file.
<br>
Run git add .
<br>
Commit the resolved file.