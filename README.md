# test-pr-release-action

The purpose of this repo:
1. to examine which github actions would be the most suitable option (for me) for generating release PRs.
1. to document working configurations 

## main.yml
this action config uses `bakunyo/git-pr-release-action` in which it calls the og `x-motemen/git-pr-release`

- the workflow [run without authentication errors](https://github.com/yongabyte/test-pr-release-action/runs/1974359644?check_suite_focus=true) from the start
- unfortunately, it's not able to find any merged prs on `dev` on many many trials
- Spent the better part of the afternoon trying to fix the config to no avail


## another.yml
this action configs is taken from `grassedge/git-pr-release-action` with little customize

- [it just works](https://github.com/yongabyte/test-pr-release-action/actions/runs/597414806)
- result: https://github.com/yongabyte/test-pr-release-action/pull/9
