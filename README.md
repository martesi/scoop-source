# Martesi Scoop bucket

Scoop manifests for portable Windows tools used by the Martesi Helldivers 2
tooling workflow, plus Argus.

## Install

```powershell
scoop bucket add martesi https://github.com/martesi/scoop-source
scoop install martesi/argus
scoop install martesi/hd2-mod-quick-deploy
scoop install martesi/hd2-mod-setting-gui
scoop install martesi/hd2-mod-migrator
scoop install martesi/hd2-audio-modder
```

The bucket's scheduled Excavator workflow checks upstream GitHub releases every
four hours and commits manifest updates when versions or asset hashes change.
