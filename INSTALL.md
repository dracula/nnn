### [nnn](https://github.com/jarun/nnn)

#### Install

Add this to the shell startup script (eg. bashrc)

```
# DRACULA COLOR SCHEME
# Background    3B
# Current Line  3C
# Foreground    E7
# Comment       67
# Cyan          9F
# Green         78
# Orange        DE
# Pink          D4
# Purple        B7
# Red           D2
# Yellow        E5

BLK="D4" CHR="DE" DIR="B7" EXE="78" REG="E7" HARDLINK="9F" SYMLINK="9F" MISSING="67" ORPHAN="D2" FIFO="E5" SOCK="E5" OTHER="D2"
export NNN_FCOLORS="$BLK$CHR$DIR$EXE$REG$HARDLINK$SYMLINK$MISSING$ORPHAN$FIFO$SOCK$OTHER"
```

Or this for simplicity

```
export NNN_FCOLORS="D4DEB778E79F9F67D2E5E5D2"
```
