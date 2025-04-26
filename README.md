# git_assignment_HeroVired
##{
Q1: CalculatorPlus Application
Objective: Implement a simple Python calculator with an additional square root feature.

Steps Performed:
Created the repository git_assignment_HeroVired.

Created a branch dev and added the base Python code for CalculatorPlus.

Implemented the square_root() function:

python
Copy
Edit
def square_root(self, x):
    return math.sqrt(x)
Uncommented and tested the square root feature in __main__.

Merged the dev branch into the main branch.

Created a GitHub release: Version 1.0.

Added classmates as collaborators for code review access.

Created a new branch feature/sqrt for the square root feature separately.

While working, fixed a bug in the divide() function to handle division by zero:

python
Copy
Edit
def divide(self, a, b):
    if b == 0:
        raise ValueError("Cannot divide by zero.")
    return a / b
Completed the square root feature and created a pull request.

Requested a code review, made changes based on feedback.

Merged feature/sqrt into dev.

After testing in dev, merged into main.

Created GitHub release: Version 2.0.

Q2: Git LFS Integration
Objective: Manage large files (>200MB) using Git LFS.

Steps Performed:
Installed Git LFS:

bash
Copy
Edit
git lfs install
Created a new branch lfs.

Tracked large files:

bash
Copy
Edit
git lfs track "*.zip"
Added a large file (over 200MB) to the repository.

Committed and pushed the file to GitHub.

Verified that the file is correctly uploaded via Git LFS.

Cloned the repository on a different machine to confirm that the large file was properly downloaded using Git LFS.

Q3: Geometry Calculator with Git Stash
Objective: Use Git Stash to manage multiple features simultaneously without committing incomplete changes.

Steps Performed:
Created a branch geometry-calculator.

Created a new feature branch feature/circle-area.

Started implementing the circle area feature.

Stashed the incomplete changes:

bash
Copy
Edit
git stash push -m "Circle area WIP"
Created another branch feature/rectangle-area.

Started implementing rectangle area feature.

Stashed the incomplete changes:

bash
Copy
Edit
git stash push -m "Rectangle area WIP"
Switched back to feature/circle-area.

Applied stashed changes:

bash
Copy
Edit
git stash pop stash@{0}
Completed and committed the circle area feature.

Switched to feature/rectangle-area.

Applied the stashed changes.

Completed and committed the rectangle area feature.

Pushed both feature branches to GitHub.

Created separate pull requests for both features targeting dev branch.

Got the pull requests reviewed by teammates.

After approval, merged both features into dev, then merged dev into main.
}
