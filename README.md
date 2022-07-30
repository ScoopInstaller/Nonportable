# Scoop Nonportable Bucket [![Tests](https://github.com/ScoopInstaller/Nonportable/actions/workflows/ci.yml/badge.svg)](https://github.com/ScoopInstaller/Nonportable/actions/workflows/ci.yml) [![Excavator](https://github.com/ScoopInstaller/Nonportable/actions/workflows/excavator.yml/badge.svg)](https://github.com/ScoopInstaller/Nonportable/actions/workflows/excavator.yml)

[Scoop](https://scoop.sh/) bucket for non-portable applications.

```
scoop bucket add nonportable
```

How do I install these packages?
---------------------------------

To add this bucket, run `scoop bucket add nonportable`.

To install, run `scoop install <package>`.

Most of the packages in this bucket requires **admin rights** to install. To install them, you should either:

**(1)** Run *windows command line* (cmd) or *Powershell* as admin.

or, **(2)** install *sudo*(`scoop install sudo`) or *gsudo* (`scoop install gsudo`), and run `sudo scoop install <package>`


How do I contribute new packages?
----------------------------------

To make a new package contribution, please read the [Contributing Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md).
