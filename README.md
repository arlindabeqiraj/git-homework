# Git Homework

## Custom Git Alias for Visual History

This repository uses a custom Git alias to display commit history in a clear, graphical format.

### Alias Configuration & Usage

To configure the alias on your local machine, run:

```bash
git config --global alias.visual "log --graph --pretty=format:'%C(auto)%h %C(blue)%an%C(auto)%d %C(black)%s %C(green)(%cr)' --all"


After configuration, use the alias with:

git visual


