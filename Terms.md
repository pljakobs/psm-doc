#a few terms
###repo / repository 
a collection of files (represented by the content of a directory) that is managed together by git
###commit
when you commit changes to a repo, you tell git to treat the change between the last and the current commit as one change set. 
###branch
A version of the repository that diverges from the main working project. Branches can be a new version of a repository, experimental changes, or personal forks of a repository for users to alter and test changes.
###master (or main)
The primary branch of all repositories. All committed and accepted changes should be on the master branch. You can work directly from the master branch, or create other branches.
###merge
Taking the changes from one branch and adding them into another (traditionally master) branch. These commits are usually first requested via pull request before being merged by a project maintainer.
###pull/pull request
If someone has changed code on a separate branch of a project and wants it to be reviewed to add to the master branch, that someone can put in a pull request. Pull requests ask the repo maintainers to review the commits made, and then, if acceptable, merge the changes upstream. A pull happens when adding the changes to the master branch.
###rebase
When rebasing a git commit, you can split the commit, move it, squash it if unwanted, or effectively combine two branches that have diverged from one another.
