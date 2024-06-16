# 😎 OSX ENV

## Zsh Config



## Git Config

Replace name, email, GitHub user.

```
[user]
	name = kuga
	email = kuga@cestbon.mbp

[alias]
        pr = pull --rebase
        br = branch -avv
        ci = commit
        co = checkout
	cm = checkout master
	mg = merge
        st = status
        l = log --color --graph --pretty=format:'%Cred%h%Creset -%C(bold yellow)%d%Creset %s %Cgreen(%cd) %C(bold blue)<%an>%Creset' --abbrev-commit
        accept-ours = "!f() { files=\"$@\"; [ -z $files ] && files='.'; git checkout --ours -- $files; git add -u $files; }; f"
        accept-theirs = "!f() { files=\"$@\"; [ -z $files ] && files='.'; git checkout --theirs -- $files; git add -u $files; }; f"
        diffeol = diff --ignore-space-at-eol

[core]
        excludesfile = /Users/hairdresser/.gitignore

[color]
        branch = auto
        diff = auto
        status = auto

[GitHub]
        user = kuga

[credential]
	helper = osxkeychain

[pull]
	rebase = false// Some code
```

## Tools

* [HSTR: Easily view, navigate and search your command history.](https://github.com/dvorka/hstr)
* [kube-ps1: Kubernetes prompt for bash and zsh.](https://github.com/jonmosco/kube-ps1)

## Kubernetes

