01.0.0 ╠═1 [branch](01_git/01_branch/01_git_branch.md)  
02.0.0 ╠═2 [checkout](01_git/02_checkout/01_git_checkout.md)  
03.0.0 ╠═3 [clone](01_git/03_clone/01_git_clone.md)  
04.0.0 ╠═4 config --global  
04.1.0 ║ ╠═4.1 alias  
04.1.1 ║ ║ ╠═4.1.1 [alias.dt : git difftool](01_git/04_config/01_alias/01_alias.dt.md)  
04.1.2 ║ ║ ╠═4.1.2 [alias.dtg : git difftool --gui](01_git/04_config/01_alias/02_alias.dtg.md)  
04.1.3 ║ ║ ╠═4.1.3 [alias.lg : git log --graph --decorate](01_git/04_config/01_alias/03_alias.lg.md)  
04.1.4 ║ ║ ╚═4.1.4 [alias.sync : git fetch -p && git pull](01_git/04_config/01_alias/04_alias.sync.md)  
04.2.0 ║ ╠═4.2 core  
04.2.1 ║ ║ ╠═4.2.1 [core.commentChar : # -> ;](01_git/04_config/02_core/01_core.commentChar_semicolon.md)  
04.2.2 ║ ║ ╠═4.2.2 [core.editor : vim](01_git/04_config/02_core/02_core.editor_vim.md)  
04.2.3 ║ ║ ╚═4.2.3 [core.pager : cat, less or pager.cmd](01_git/04_config/02_core/03_core.pager_cat.md)  
04.3.0 ║ ╚═4.3 diff  
04.3.1 ║ - ╠═4.3.1 [diff.guitool : p4merge](01_git/04_config/03_diff/01_diff.guitool_p4merge.md)  
04.3.2 ║ - ╚═4.3.2 [diff.tool : vimdiff](01_git/04_config/03_diff/02_diff.tool_vimdiff.md)  
05.0.0 ╠═5 [diff : diff HEAD vs WorkingDirectory, Branch vs Branch, Commit vs Commit](01_git/05_diff/01_git_diff.md)  
06.0.0 ╠═6 [fetch](01_git/06_fetch/01_git_fetch.md)  
07.0.0 ╠═7 [merge](01_git/07_merge/01_git_merge.md)  
08.0.0 ╠═8 [pull](01_git/08_pull/01_git_pull.md)  
09.0.0 ╠═9 [remote](01_git/09_remote/01_git_remote.md)  
10.0.0 ╠═10 [stash](01_git/10_stash/01_git_stash.md)  
11.0.0 ╠═11 [status](01_git/11_status/01_git_status.md)  
12.0.0 ╠═12 [tag](01_git/12_tag/01_git_tag.md)  

# [git commit](02_git_command/10_git_commit.md)
```{bash}
$ git commit
```

# [git reset](02_git_command/11_git_reset_soft.md)
```{bash}
$ git reset --soft HEAD~2
$ git reset --mixed HEAD~
$ git reset --hard HEAD^
```

# [git squash commit](02_git_command/12_git_squash_commit.md)
```{bash}
$ git reset --soft HEAD~9 && git commit
```

# [git push](02_git_command/13_git_push.md)
```{bash}
$ git push origin localBranch:remoteBranch
$ git push origin :remoteBranch
```

# [git log](02_git_command/14_git_log.md)
```{bash}
$ git log
```

# [git revert](02_git_command/15_git_revert.md)
```{bash}
$ git revert
```

