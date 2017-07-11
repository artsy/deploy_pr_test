# Testing the `deploy_pr` script

All this repo does is provide a place to test the [deploy_pr][deploy_pr] script.

[deploy_pr]: https://github.com/jonallured/deploy_pr

## Making a merged change for release

Running the `add_timestamp` script will:

* add a new entry to `timestamps.txt`
* create a commit
* push the commit to origin
* create a PR to upstream
* merge that PR
