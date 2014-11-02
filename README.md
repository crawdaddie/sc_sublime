# SuperCollider Sublime Text 3 Plugin

Rewritten for Sublime Text 3 based on ST2 plugin by [geoffroymontel](https://github.com/geoffroymontel/supercollider-package-for-sublime-text).

Also includes:
- sclang Syntax by [rfwatson](https://github.com/rfwatson/supercollider-tmbundle)
- schelp Syntax by [crucialfelix](https://github.com/crucialfelix)

## Testing TODO

- Windows
    - Communication with sclang
    - 'Open Startup File' command
    - 'Open User Support Directory' command
- Linux
    - 'Open Startup File' command
    - 'Open User Support Directory' command

## Known Issues

### Empty Post window

Occasionally when re-opening the post window, or whenever re-opening in a different window/tab, cached content isn't retrieved and the post window is empty

## TODO

### SuperCollider.py

- if post window moved to another pane/window, can't restore
- option on where to open post window: new tab, new group, new window,terminal
- refocus on original window on open_post_view
- default keymaps for other OSs
- command: dump node terminated
- command: dump node tree with controls
- command: look up implementations for selection
- command: look up references
- option: boot interpreter on set syntax
- Include schelp syntax by CrucialFelix, in Geoffroy Montel repo
- Check out Thor's package https://github.com/thormagnusson/Sublime-Supercollider

### Auto complete

- Make easy to do ctags
- Include default symbol list from core

### Key map

- Windows
- Linux
- OS X

### Menu

## Future Work

### Multiple sclang instances

In theory this plugin could support multiple instances of sclang, however some mechanism would be required to tell the commands (start, stop execute etc) which instance to send the message to.

#### Possibile approaches:

- Selectable 'current sclang' menu item
