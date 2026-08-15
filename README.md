# scoop-bucket

[Scoop](https://scoop.sh/) bucket for [kwrkb](https://github.com/kwrkb)'s tools.

```powershell
scoop bucket add kwrkb https://github.com/kwrkb/scoop-bucket
scoop install ssh-pushkey
```

## Packages

| Package | Description |
|---------|-------------|
| [ssh-pushkey](https://github.com/kwrkb/ssh-pushkey) | An `ssh-copy-id` alternative for Windows OpenSSH servers |
| [taskctl](https://github.com/kwrkb/taskctl) | Diagnoses why a Windows Task Scheduler task failed and tells you what to do next |

Manifests in this repository are generated automatically by each project's
release workflow when a package is released. Do not edit them by hand —
changes belong in the source repository.
