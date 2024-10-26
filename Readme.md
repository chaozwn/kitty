## How to mouse draggable window on macos

```shell
defaults write -g NSWindowShouldDragOnGesture YES
```

then `ctrl` + `cmd` to drag

### use kitty diff in .gitconfig

```
[core]
	autocrlf = input
[pull]
	rebase = true

[diff]
    tool = kitty
    guitool = kitty.gui

[difftool]
    prompt = false
    trustExitCode = true

[difftool "kitty"]
    cmd = kitty +kitten diff $LOCAL $REMOTE

[difftool "kitty.gui"]
    cmd = kitty kitty +kitten diff $LOCAL $REMOTE
```
