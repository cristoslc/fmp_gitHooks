# fmp_gitHooks
Hooks to simplify working with FileMaker in git repositories. See the [git hooks documentation](https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks) for more information on how to install and use git hooks.

##Done
### pre-commit
 * quit FileMaker Pro Advanced
 * re-stage any files that have already been staged (to make sure they get committed from a closed state)

##TODO

### post-commit
 * (optional) re-open any files that were added
