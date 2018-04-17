# git-aliases
Useful git aliases

```
[alias]
branch-name = "!git rev-parse --abbrev-ref HEAD"
publish = "!git push -u origin $(git branch-name)"
co = checkout
cob = checkout -b
poc = "!git pull origin $(git branch-name)"
```
