```
[user]
	email = ...
	name = ...
[core]
	autocrlf = input
	quotePath = false
	longpaths = true
[alias]
	st = status
	ci = commit -a
	cm = commit -m
	br = branch
	up = checkout
	glog = log --graph --decorate --all
	pl = pull origin
	ps = push origin
[color]
	ui = auto
[color "branch"]
	current = yellow
	local = yellow
	remote = green
[color "diff"]
	meta = yellow
	frag = magenta
	old = red
	new = green
[color "status"]
	added = yellow
	changed = green
	untracked = cyan
[i18n]
	commitencoding = utf-8
[filter "lfs"]
	clean = git-lfs clean -- %f
	smudge = git-lfs smudge -- %f
	process = git-lfs filter-process
	required = true
```
