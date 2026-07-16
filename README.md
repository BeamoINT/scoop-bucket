# BeamoINT Scoop bucket

Install [Claudex](https://github.com/BeamoINT/Claudex) on Windows with:

```powershell
scoop bucket add beamoint https://github.com/BeamoINT/scoop-bucket
scoop install beamoint/claudex
claudex --login
```

Claudex's automatic first-run setup installs Codex and Claude Code when they
are missing. Scoop installs the Node.js and jq runtime dependencies used by
that setup.

## Beamo Flasher CLI

Install [Beamo Flasher](https://github.com/BeamoINT/beamo-flasher) on Windows with:

```powershell
scoop bucket add beamoint https://github.com/BeamoINT/scoop-bucket
scoop install beamoint/beamo-flasher
bflash --help
```
