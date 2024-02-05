## git / github
### tag
- Add tag (local)
  - `git tag tagname`
- Add tag (Remote)
  - `git push origin tagname`
- Remove tag (local)
  - `git tag —delete tagname`
- Remove tag (Remote)
  - `git push —delete origin tagname`
### Clean
- Clean all files and check out again
  - `git checkout . && git clean -f -x .`

## General
### File access
- Change permission
  - ex) `sudo chmod 754 PATHtofile`
  - read = 4, write = 2, execute = 1
  - left= owner, middle = owner group, right = other

### process
- Kill process
  - ex) `killall java`

### Android
- log
  - `adb logcat`
- log with filter
  - ex) `adb logcat -s Unity`
- Install apk
  - `adb install PATHtoapk`

### Change prompt(zshrc) look
- `PROMPT="%K{cyan} %n %D %* %~ %# %k "`
