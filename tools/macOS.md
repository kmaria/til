# Useful Tips for MacOS

## Package Manager - brew.sh

To install open the terminal and paste:
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Then getting ant is like
```
brew install ant
```

## Creating a Happy Git Environment

Get happy Git colors. Paste the following into your ~/.gitconfig file:
```
[color]
	branch = auto
	diff = auto
	status = auto
[color "branch"]
	current = yellow reverse
	local = yellow
	remote = green
[color "diff"]
	meta = yellow bold
	frag = magenta bold
	old = red bold
	new = green bold
[color "status"]
	added = yellow
	changed = green
	untracked = cyan
```
