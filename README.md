# scoop-bucket

[Scoop](https://scoop.sh) manifests for tools I maintain.

## Usage

```powershell
scoop bucket add angeltonio https://github.com/angeltonio/scoop-bucket
scoop install <app>
```

## Apps

| App | Description |
| --- | --- |
| _(none published yet)_ | |

## About the contents of this repository

Everything under `bucket/` is generated. [GoReleaser](https://goreleaser.com)
writes each manifest during a release, with the download URLs and checksums for
that exact version, and commits it here.

Editing a manifest by hand will work until the next release overwrites it. Fix
the source project's release configuration instead.
