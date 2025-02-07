- unzip
- move to Applications
- to use hust call open Spotlight (for me `CMD+Space`) and find `clean deriveddata` (for me just fine to write `cle`)

Application from apple Automator inside script:
```
rm -rf ~/Library/Developer/Xcode/DerivedData/*
osascript -e 'display notification "Derived Data cleaned!"'
```
