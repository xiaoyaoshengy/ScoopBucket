# Personal Scoop Bucket

<!-- Uncomment the following line after replacing placeholders -->
[![Tests](https://github.com/xiaoyaoshengy/ScoopBucket/actions/workflows/ci.yml/badge.svg)](https://github.com/xiaoyaoshengy/ScoopBucket/actions/workflows/ci.yml) [![Excavator](https://github.com/xiaoyaoshengy/ScoopBucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/xiaoyaoshengy/ScoopBucket/actions/workflows/excavator.yml)

Personal bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add sb https://github.com/xiaoyaoshengy/ScoopBucket
scoop install sb/<manifestname>
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
