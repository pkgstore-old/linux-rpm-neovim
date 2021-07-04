# Neovim

**Neovim** is a project that seeks to aggressively refactor Vim in order to:

- Simplify maintenance and encourage contributions.
- Split the work between multiple developers.
- Enable advanced UIs without modifications to the core.
- Maximize extensibility.

## Install

### Fedora COPR

```
$ dnf copr enable pkgstore/neovim
$ dnf install -y neovim
```

### Open Build Service (OBS)

```
# Work in Progress
```

## Update

```
$ dnf upgrade -y neovim
```

## How to Build

1. Get source from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/neovim).
2. Write last commit SHA from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/neovim) to [CHANGELOG](CHANGELOG).
3. Modify & update source (and `*.spec`).
4. Build SRPM & RPM.
