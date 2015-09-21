commit 0
- git init
- git add README.md
- git commit -m "commit 0: git init"
- git remote add origin https://github.com/rpcrimi/HW2.git
- git push -u origin master

commit 1
- git add .
- git commit -m "commit 1"
- git push origin master

commit 2
- git add .
- git commit -m "commit 2"
- git push origin master

commit 3
- git checkout 7559f2090c50a955515e67f1b811b0eb2f262ba0
- git checkout -b bug-fix
- git add .
- git commit -m "commit 3"
- git push origin bug-fix

commit 4
- git add .
- git commit -m "commit 4"
- git push origin bug-fix

commit 5
- git merge master
- FIXED MERGE CONFLICTS
- git add .
- git commit -m "commit 5"
- git merge master

commit 6
- git add .
- git commit -m "commit 6"
- git push origin bug-fix