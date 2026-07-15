
# Assignment: Incremental PR / Dependent Branch

## Goal
Learn how to synchronize a dependent branch with its base branch.

## Instructions
1. This branch (`feature/dependent-feature`) was created from `feature/base-feature`.
2. After this branch was created, a crucial bug fix was merged into `feature/base-feature` (a commit fixing a connection leak).
3. Your task is to bring those new changes from `feature/base-feature` into your current branch so you have the bug fix!


# Assignment: Rebase with Conflicts

## Goal
Learn how to rebase a branch and resolve conflicts that occur in the middle of the rebase process.

## Instructions
1. This branch is behind `main`, and both this branch and `main` have modified `utils.sh`.
2. Run `git rebase main`.
3. The rebase will pause because of a conflict in `utils.sh`.
4. Resolve the conflict by keeping both the new `multiply` function (from this branch) and the new `divide` function (from main), and combining the changes to `calculate_sum`.
5. Add the resolved file and run `git rebase --continue` to finish.

# Assignment: Squash Commits

## Goal
Learn how to use interactive rebase (`git rebase -i`) to clean up a messy commit history.

## Instructions
1. This branch has 7 messy commits that were made during development.
2. One of the commits adds unnecessary debug logs (commit message: "add unnecessary debug logs"). You must **drop** this commit entirely during the rebase.
3. **Squash** the remaining commits into a single, clean commit.
4. The final commit message should be: "feat: update config settings for production".


