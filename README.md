# Software quality and testing exam

* Git
* Unit testing with JUnit
* Static analysis in JavaScript with JSHint
* Jenkins CI

# Git

* Fork and clone repo https://github.com/blabno/pwsz-exam3-git
* Merge feature branch `feature/subtract` to master with merge commit and resolve conflict if any
* Rebase feature branch `feature/ping-pong` and merge to master using `fast-forward`
* Create feature branch from master, add empty file `a.txt` to root directory, commit it and merge it to master
* `npm test` must pass

# Unit testing with JUnit

* Achieve 100% of code coverage for a given method (mockito)

# Static analysis in JavaScript with JSHint

Cleanup static analysis `./node_modules/grunt-cli/bin/grunt jshint`

Remember that `npm test` must pass!

# Jenkins CI

* Create job that checks out code from repo this, runs jshint and tests. Commit the jenkins `config.xml` to `jenkins` branch of this repo.
