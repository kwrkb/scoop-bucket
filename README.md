# scoop-bucket

[Scoop](https://scoop.sh/) bucket for [kwrkb](https://github.com/kwrkb)'s tools.

```powershell
scoop bucket add kwrkb https://github.com/kwrkb/scoop-bucket
scoop install ssh-pushkey
```

## Packages

| Package | Description |
|---------|-------------|
| [rdp-host-info](https://github.com/kwrkb/rdp-host-info) | Shows Remote Desktop connection info and host readiness at a glance |
| [ssh-pushkey](https://github.com/kwrkb/ssh-pushkey) | An `ssh-copy-id` alternative for Windows OpenSSH servers |
| [taskctl](https://github.com/kwrkb/taskctl) | Diagnoses why a Windows Task Scheduler task failed and tells you what to do next |

Manifests live in `bucket/`, and are generated automatically by each project's
release workflow when a package is released. Do not edit them by hand —
changes belong in the source repository.

Scoop only counts manifests under `bucket/` (`scoop bucket list` reports 0 for a
repository that keeps them at the root), and once `bucket/` exists it is the only
directory Scoop reads. So every manifest has to stay in there — a release
workflow that writes to the repository root would be silently ignored.
