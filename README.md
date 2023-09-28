# dependabot-paths-bug

This repository reproduces a bug with Dependabot and GitHub Actions where the `paths` filter is ignored.
To verify, see https://github.com/ctbur/dependabot-paths-bug/pull/1 and check the workflow file of the workflow execution on the Dependabot commit.
It should not have been executed.
