In Master Branch I implemented Addition feature/functionality.
I created branch called feature and implemented subtraction functionality in the same file.
I switched to master branch and merged using cherry-pick.
Again I created a branch called mergeFeature and implemented multiplication functionality.
I switched to master and add a test line.
Then again I created a branch called rebaseFeature and implemented percentage functionality.
Then go to master branch and I ran a merge command ie git merge mergeFeature.
The flow will be like M1 -> F1 -> MF1 -> testline ->extra merge commit.
Then I ran git rebase rebaseFeature.
The flow will be like M1 -> F1 -> MF1 -> testline -> RF1.

M1 -> Master Branch
F1 -> Feature Branch
MF1 -> MergeFeature Branch
RF1 -> RebaseFeature Branch

Note: I have used rebase command in master branch just for a practice purpose but in real world senario rebase command should not be used in master branch.
