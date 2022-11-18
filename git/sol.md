# Git

1. null
2. git log --graph
   git log README.md
   git blame _config.yml && git show a88b4eac_config.yml
3. bfg --delete-files FILE
   add .gitignore
4. git stash: 保存当前进度
   git log --all --oneline: 一列带有message和id的commit
   git stash pop 恢复进度到当前工作区
   scenario: 切换到其他工作区工作时
5. .gitconfig: graph = log --all --graph --decorate --oneline
6. git config --global core.excludesfile ~/.gitignore_global
7. after fixing the problem
   git commit
