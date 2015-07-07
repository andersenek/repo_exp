# repo_exp

steps to create upstream branch and reference to new local branch
git pull upstream master
	fatal: 'upstream' does not appear to be a git repository
git remote -v
	origin	https://github.com/tomBeach/pbj.git (fetch)
	origin	https://github.com/tomBeach/pbj.git (push)
git remote add upstream https://github.com/ga-dc/pbj.git
git pull upstream master
git checkout -b suggestion
Switched to a new branch 'suggestion'
