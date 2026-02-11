# Technology

## Git

- Remote: `git@github.com:alum/lumi.git`
- Default branch: `master`

## Committing and Pushing

GitHub has email privacy restrictions enabled. When committing and pushing, use the noreply email for both author and committer:

```bash
GIT_COMMITTER_NAME="alum" \
GIT_COMMITTER_EMAIL="122738+alum@users.noreply.github.com" \
git commit --author="alum <122738+alum@users.noreply.github.com>" -m "your message"
```

Then push:

```bash
git push origin master
```
