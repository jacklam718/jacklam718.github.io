
### First time setup
- Install hugo

- Build and Deployment
Now check out the gh-pages branch into your public folder using git’s worktree feature. Essentially, the worktree allows you to have multiple branches of the same local repository to be checked out in different directories: `rm -rf public git worktree add -B gh-pages public upstream/gh-pages`

### Deployment
`./scripts/publish_toghpages.sh`
