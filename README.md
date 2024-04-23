# Gym-Git-Exercise-Solutions

## Bundle 1

### Exercise 1

1. git branch
2. git add .
3. git commit -m "Created file01"
4. git push
5. git switch -b dev
6. git switch -c dev
7. git switch -c test
8. git switch dev
9. git branch -d test
10. git push
11. git switch main
12. git switch dev
13. git commit -a -m "dev branch"
14. git push
15. git push --set-upstream origin dev

## Exercise 2

1.  git switch dev
2.  git branch
3.  git stash list
4.  git add .
5.  git stash save "Made a stash save on dev"
6.  git stash save "Stached about.html on dev"
7.  git add .
8.  git stash save "Stached about.html on dev"
9.  git add .
10. git stash save "Stached team.html on dev"
11. git stash list
12. git stash pop@{1}
13. git stash pop stash@{1}
14. git stash pop stash{2}
15. git stash pop stash@{2}
16. git stash list
17. git stash pop stash@{1}
18. git merge --continue
19. git add home.html
20. git add .
21. git commit -m "Pushed the first 2 changes for about.html and home.html
    I did the stash and then recovered them"
22. git stash pop stash@{0}
23. git reset HEAD^
24. git status
25. git add .
26. git commit -m "Finished exercise 2"

## Bundle 2

### Exercise 2

1.  git status 2. git switch main 3. git branch 4. git switch dev 5. git switch 'ft/bundle-2' 6. git switch main 7. git pull 8. git commit -a -m "Made new changes in services.html on main branch" 9. git push
2.  git switch -c 'ft/service-redesign'
3.  git branch
4.  git switch ft/service-redesign
5.  git pull
6.  git switch main
7.  git branch -d ft/service-redesign
8.  git branch
9.  git switch -c ft/service-redesign
10. git commit -a -m "new changes in services.html on ft/service-redesign branch"
11. git push
12. git push --set-upstream origin ft/service-redesign
13. git branch
14. git switch main
15. git commit -a -m "New changes on services.html on main branch but affecting the same line as the previous one"
16. git push
17. git switch ft/service-redesign
18. git diff main ft/service-redesign
19. git merge main
20. git commit -m "Fixed the merge merging main into ft/service-redesign"
21. git add .
22. git commit -m "Fixed merge conflicts from main to ft/service-redesign"
23. git push
24. git switch main

