This is a simple number guessing game

Branches:
Feature1 – Adding ability to quit, play again and feedback on guesses.
Feature2 – Added encouraging messages for players and max attempts logic
Feature3- Gave the player a hint during the guessing game, added logic for the hint.
Hotfix – Fixes a randomint error to include the max number in the range
Main – The initial number guessing branch
Dev – The main development branch where testing is done before release.

Learning:
I learned that the difference between merge, rebase, squash, and cherry-pick is how they handle the commit history and the integration of changes from one branch to a different branch. They have their own uses depending on what you want for the project's history and how the team collaborates.
The difference in git history for feature1 vs feature2 vs feature3 is that feature1 has a linear history with clear and simple commits for each change that was done, feature2 is a bit more complex and varies the history with multiple branches that are merged in and out, and feature3 has a cleaner history because we were squashing commits before merging them back in.
I would use merge when I want to keep clean history and have multiple people working on different branches so that their changes can be integrated without me losing any work. I would use rebase when I want to keep a linear history and avoid clutter or unnecessary merge commits. I would use squash when I want to combine multiple small commits into a single commit so that they history is cleaner and easier to read to understand what is going on. I would use cheery-pick when I want to take a specific commit from one branch and put it into another branch without merging in the entire branch into the current branch.
