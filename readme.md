Батуринский Владислав Андреевич

git filter-branch --tree-filter 'rm -rf refs’ HEAD
git reflog expire --expire=now --all && git gc --prune=now --aggressive
git push origin --force --all
git push origin --force –tags
git push
