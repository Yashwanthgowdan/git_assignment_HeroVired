# git_assignment_HeroVired

Q1: CalculatorPlus Application
Implementing a simple Python calculator.

##Steps Performed:
1. Created the repository git_assignment_HeroVired.
2.Created a branch dev and added the base Python code for CalculatorPlus.
3. Tested the code and Merged the dev branch into the main branch.
4. Created a GitHub release: Version1.0.
5. Created a new branch feature/sqrt for the square root feature separately
6. Fixed a bug in the divide() function to handle division by zero:
7. Added collaborators for code review and requested a to Approve the pull request.
8. Merged feature/sqrt into dev and tested code again in dev, them merged to main.
9. Created GitHub release: Version 2.0.

Q2: Git LFS Integration

##Steps Performed:
1. Installed Git LFS using git lfs install
2. Created a new branch lfs.
3. Tracked large file using git lfs track "*.mpeg"
4. Added a large file (over 200MB) to the repository.
5. Committed and pushed the file to GitHub.
6. Cloned the repository on a different machine to confirm that the large file was properly downloaded using Git LFS.

Q3: Geometry Calculator

##Steps Performed:
1. Created a new feature branch feature/circle-area.
2. Started implementing the circle area feature.
3. Stashed the incomplete changes using git stash push -m "Work in progress - Circle area feature"
4. Created another branch feature/rectangle-area and started implementing rectangle area feature.
5. Stashed the incomplete changes using git stash push -m "Work in progress - Rectangle area feature"
6. Switched back to feature/circle-area and stashed changes:git stash apply
7. Committed and Pushed code to the feature/circle-area branch.
8. Switched to feature/rectangle-area and stashed changes.
9. Committed and Pushed code to the feature/rectangle-area branch.
10. Created separate pull requests for both features targeting dev branch.
11. Got the pull requests reviewed by teammates.
12. After approval, merged both features into dev, then merged dev into main.
