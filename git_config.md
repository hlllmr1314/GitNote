1. 配置UserName
$ git config --global user.name "Huang Lei"
2. 配置Email
$ git config --global user.email leihuang@example.com
3. 配置编辑器
$ git config --global core.editor vim
4. 配置模板
$ git config --global commit.template ~/.gitmessage.txt
$ git commit
5. 配置分页
$ git config --global core.pager ''
6. 配置GPG签署密匙
$ git config --global user.signingkey <gpg-key-id>
7. 配置无需纳入GIt管理的文件(类似.gitignore)
$ git config --global core.excludesfile ~/.gitignore_global
8. 配置颜色相关开关（color.*,color.branch，color.diff，color.interactive，color.status）
$ git config --global color.* false
9. 配置合并工具
$ git config --global merge.tool kdiff3
10. 配置差异工具
$ git config --global diff.tool bc3
11. 配置别名
$ git config --global alias.co checkout  



备注：
$ git mergetool --tool-help
'git mergetool --tool=<tool>' may be set to one of the following:
        emerge
        gvimdiff
        gvimdiff2
        opendiff
        p4merge
        vimdiff
        vimdiff2

The following tools are valid, but not currently available:
        araxis
        bc3
        codecompare
        deltawalker
        diffmerge
        diffuse
        ecmerge
        kdiff3
        meld
        tkdiff
        tortoisemerge
        xxdiff
