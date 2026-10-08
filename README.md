# project-handoff-x20-2 cloud handoff

This public repository contains one complete, sanitized handoff archive for continuing the project on another computer.

## Download

Download the complete archive from the GitHub release:

[project-handoff-x20-2-cloud-handoff-20261008.zip](https://github.com/Jane9669/project-handoff-x20-2-cloud-handoff-20261008/releases/download/handoff-20261008/project-handoff-x20-2-cloud-handoff-20261008.zip)

Verify it in PowerShell:

```powershell
Get-FileHash -Algorithm SHA256 .\project-handoff-x20-2-cloud-handoff-20261008.zip
```

Expected SHA-256:

`e250c53495a7866b702679f4bc7d7616050740b1e630407d11ba4eaadddb9e0b`

After extraction, open `project-handoff-x20-2/PROJECT_STATE.md` first.

The archive excludes environment files, dependency folders, caches, and existing archive files.
