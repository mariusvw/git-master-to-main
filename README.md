# git-master-to-main

## Default branch name

### Version 2.28.0 or newer
```
git config --global init.defaultBranch main
```

### Versions older than 2.28.0
```
mkdir -p ~/.config/git/template
echo "ref: refs/heads/main" > ~/.config/git/template/HEAD
git config --global init.templateDir ~/.config/git/template
```

## Links
- https://github.com/github/renaming
- https://github.blog/2020-07-27-highlights-from-git-2-28/#introducing-init-defaultbranch
