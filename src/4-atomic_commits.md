# Atomic Commits

## Demos

### Why are non-atomic commits problematic?

When a commit contains multiple unrelated changes, it becomes difficult to understand the purpose of each individual difference. Reviewers (and even your future self) have to spend extra time untangling which change was meant to fix a bug, which was a refactor, and which was just a formatting tweak. This slows down code review, increases the chance of mistakes slipping through, and makes it harder to revert or isolate a single change later.

TODO: Add in explanation that ties in with the demo

![diff of non-atomic commit](demos/atomic-commits/git-diff-not-atomic.gif)

### Why atomic commits are important for revert errant changes?

TODO: Add in explanation that ties in with the demo

![reverting a commit](demos/atomic-commits/git-revert.gif)

### How do I use `git add -p` to select specific changes?

TODO: Add in explanation that ties in with the demo

![using git add -p](demos/atomic-commits/git-add-p.gif)
