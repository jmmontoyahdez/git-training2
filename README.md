# git-training2

EJERCICIO 1
-----------------------------------------------------
-----------------------------------------------------

prueba de montoya


EJERCICIO 2
-----------------------------------------------------
-----------------------------------------------------

para commit: 

git add pasa del workspace al staging
git commit -m TEXTo

git push origin master <-

EJERCICIO 3
-----------------------------------------------------
-----------------------------------------------------

git branch features/exercice3
git checkout features/exercice3


EJERCICIO 4
-----------------------------------------------------
-----------------------------------------------------

C:\cmder\git-training2 (master -> montoya)
? git checkout -b features/featureGFT
Switched to a new branch 'features/featureGFT'

C:\cmder\git-training2 (features/featureGFT -> origin)
? git status
On branch features/featureGFT
nothing to commit, working tree clean

C:\cmder\git-training2 (features/featureGFT -> origin)
? git push montoya features/featureGFT
Username for 'https://github.com': jmmontoyahdez
Password for 'https://jmmontoyahdez@github.com':
Total 0 (delta 0), reused 0 (delta 0)
remote:
remote: Create a pull request for 'features/featureGFT' on GitHub by visiting:
remote:      https://github.com/jmmontoyahdez/git-training2/pull/new/features/featureGFT
remote:
To https://github.com/jmmontoyahdez/git-training2.git
 * [new branch]      features/featureGFT -> features/featureGFT


C:\cmder\git-training2 (features/featureGFT -> origin)
? git add .

C:\cmder\git-training2 (features/featureGFT -> origin)
? git commit -m **
[features/featureGFT 7093833] **
 1 file changed, 8 insertions(+), 1 deletion(-)

C:\cmder\git-training2 (features/featureGFT -> origin)
? git status
On branch features/featureGFT
nothing to commit, working tree clean

C:\cmder\git-training2 (features/featureGFT -> origin)
? git checkout master
Switched to branch 'master'
Your branch is up to date with 'montoya/master'.

C:\cmder\git-training2 (master -> montoya)
? git status
On branch master
Your branch is up to date with 'montoya/master'.

nothing to commit, working tree clean

C:\cmder\git-training2 (master -> montoya)
? git merge --ff features/featureGFT
Updating 0123cc9..7093833
Fast-forward
 README.md | 9 ++++++++-
 1 file changed, 8 insertions(+), 1 deletion(-)


EJERCICIO 5
-----------------------------------------------------
-----------------------------------------------------
cambiar a la rama master, y haces commit
cambias a la rama features/featureGFT y haces otro commit
al mergear da conflicto

C:\cmder\git-training2 (master -> montoya)
? git checkout master
Already on 'master'
Your branch is ahead of 'montoya/master' by 1 commit.
  (use "git push" to publish your local commits)

C:\cmder\git-training2 (master -> montoya)
? git add .

C:\cmder\git-training2 (master -> montoya)
? git commit -m **
[master c3e28e5] **
 1 file changed, 80 insertions(+), 2 deletions(-)

C:\cmder\git-training2 (master -> montoya)
? git checkout features/featureGFT
Switched to branch 'features/featureGFT'

C:\cmder\git-training2 (features/featureGFT -> origin)
? git add .

C:\cmder\git-training2 (features/featureGFT -> origin)
? git commit -m **
[features/featureGFT a537d7a] **
 1 file changed, 80 insertions(+), 2 deletions(-)

C:\cmder\git-training2 (features/featureGFT -> origin)
? git merge --no-ff features/featureGFT
Already up to date.

C:\cmder\git-training2 (features/featureGFT -> origin)
? git merge --no-ff master
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
Automatic merge failed; fix conflicts and then commit the result.


EJERCICIO 6
-----------------------------------------------------
-----------------------------------------------------
Merge with conflicts!!

PDTE



EJERCICIO 7
-----------------------------------------------------
-----------------------------------------------------
aaaaa


