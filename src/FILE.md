git init
cd src

0. git add FILE.md <br>
0. git commit -m "Commit 0" <br>

BUG-FIX BRANCH
0. git branch bug-fix <br>

1. git commit -a -m "Commit 1" <br>

2. git commit -a -m "Commit 2" <br>

SWITCH TO BUG-FIX
3. git checkout bug-fix <br>
3. git commit -a -m "Commit 3" <br>

4. git commit -a -m "Commit 4" <br>

NEW BRANCH
4. git branch bug-fix-experimental

MERGE BUG-FIX INTO MASTER
5. git merge --no-ff master
5. git commit -a -m "Commit 5" <br>

6. git add FILE.md <br>
6. git commit -m "Commit 6" <br>