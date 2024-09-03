# ZAFT's Godot Project Template

How to use:

### 1) init submodules

```bat
git submodule update --init --recursive --remote --rebase
```

### 2) Configure your itch username/project name

```bat
:: bat\setup.bat

:: these can be the full path to the files in case they are not in your PATH
set GODOT_BINARY=Godot_v4.3-stable_win64_console.exe
set BUTLER_BINARY=butler.exe

:: this assumes your project is at zafteer.itch.io/sink, substitute accordingly
set ITCH_USERNAME=zafteer
set ITCH_PROJECT=sink
```
