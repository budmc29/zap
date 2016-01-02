# Simple Bash Bookmarking

  Originally Written By "getmizanur" From StackOverflow

## Install:
```
cp zap.bash ~/zap.bash
```
Add this line to your bash.rc
```
# zap bookmark manager
if [ -f ~/.zap.bash ]; then
    source ~/zap.bash
fi
```
## Usage:
```
$ cd ~/test && zap remember test # save bookmark
$ zap to test # go to bookmark
$ zap locations # show all bookmarks
$ zap forget test # delete bookmark
```

