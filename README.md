# Scoop Bucket

[![Tests](https://github.com/sergehas/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/sergehas/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/sergehas/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/sergehas/scoop-bucket/actions/workflows/excavator.yml)

Bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

## How do I use this template?

1. Create new manifests by copying `bucket/app-name.json.template` to
`bucket/<app-name>.json`.
2. Commit and push changes.

## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add personal https://github.com/sergehas/scoop-bucket
scoop install personal/<manifestname>
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.

## Apps

<!-- <apps> -->
<!-- The following table was inserted by makeindex.ps1 -->
<!-- Your edits will be lost the next time makeindex.ps1 is run -->
|Name|Version|Description|
|----|-------|-----------|
|[checkov](https://www.checkov.io/)|[3.2.524](https://www.checkov.io/)|A static code analysis tool for infrastructure as code (IaC) and also a software composition analysis (SCA) tool for images and open source packages.|
