# proot-rs

[中文版本](./README.cn.md)

Rust implementation of PRoot, a ptrace-based sandbox

![proot-rs](https://repo.x-cmd.io/proot-rs.svg)

## Install

```sh
x install proot-rs
```

## Code insight

Total: **403** lines of code across **12** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| C | 147 | 40 | 28 | 3 |
| Toml | 119 | 2 | 21 | 5 |
| Sh | 49 | 7 | 15 | 1 |
| Dockerfile | 39 | 7 | 12 | 2 |
| Bash | 29 | 13 | 10 | 1 |

## Source

- **Upstream**: <https://github.com/proot-me/proot-rs>
- **License**: GPL-3.0

## Release

- **Latest**: `v0.1.0` (2021-08-20)
- **Last commit**: 2026-06-08
- **Assets in release**: 12

## Popularity

- **Stars**: 160 · **Forks**: 27 · **Open issues**: 36 · **Contributors**: 6

## Totals (cumulative)

- **Releases**: 1 · **Merged PRs**: 30 · **Open PRs**: 0 · **Closed issues**: 23 · **Open issues**: 13 · **Commits**: 225

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-12 | 0 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-13 | 0 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-06-13 | 0 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-03-15 | 0 | 1 | 0 | 0 | 0 | 2 |
| 360d | 2025-09-16 | 0 | 1 | 0 | 0 | 0 | 2 |
| last720d | 2024-09-21 | 0 | 1 | 0 | 0 | 2 | 2 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [proot-rs-v0.1.0-aarch64-linux-android.tar.gz](https://github.com/proot-me/proot-rs/releases/download/v0.1.0/proot-rs-v0.1.0-aarch64-linux-android.tar.gz) | 619.0 KiB | `native/linux/arm64` |
| [proot-rs-v0.1.0-aarch64-unknown-linux-gnu.tar.gz](https://github.com/proot-me/proot-rs/releases/download/v0.1.0/proot-rs-v0.1.0-aarch64-unknown-linux-gnu.tar.gz) | 611.3 KiB | `native/linux/arm64/glibc` |
| [proot-rs-v0.1.0-aarch64-unknown-linux-musl.tar.gz](https://github.com/proot-me/proot-rs/releases/download/v0.1.0/proot-rs-v0.1.0-aarch64-unknown-linux-musl.tar.gz) | 647.0 KiB | `native/linux/arm64/musl` |
| [proot-rs-v0.1.0-arm-linux-androideabi.tar.gz](https://github.com/proot-me/proot-rs/releases/download/v0.1.0/proot-rs-v0.1.0-arm-linux-androideabi.tar.gz) | 627.4 KiB | `native/linux/arm` |
| [proot-rs-v0.1.0-armv7-unknown-linux-gnueabihf.tar.gz](https://github.com/proot-me/proot-rs/releases/download/v0.1.0/proot-rs-v0.1.0-armv7-unknown-linux-gnueabihf.tar.gz) | 621.0 KiB | `native/linux/arm/glibc` |
| [proot-rs-v0.1.0-armv7-unknown-linux-musleabihf.tar.gz](https://github.com/proot-me/proot-rs/releases/download/v0.1.0/proot-rs-v0.1.0-armv7-unknown-linux-musleabihf.tar.gz) | 639.4 KiB | `native/linux/arm/musl` |
| [proot-rs-v0.1.0-i686-linux-android.tar.gz](https://github.com/proot-me/proot-rs/releases/download/v0.1.0/proot-rs-v0.1.0-i686-linux-android.tar.gz) | 750.2 KiB | `native/linux/x86` |
| [proot-rs-v0.1.0-i686-unknown-linux-gnu.tar.gz](https://github.com/proot-me/proot-rs/releases/download/v0.1.0/proot-rs-v0.1.0-i686-unknown-linux-gnu.tar.gz) | 748.2 KiB | `native/linux/x86/glibc` |
| [proot-rs-v0.1.0-i686-unknown-linux-musl.tar.gz](https://github.com/proot-me/proot-rs/releases/download/v0.1.0/proot-rs-v0.1.0-i686-unknown-linux-musl.tar.gz) | 742.0 KiB | `native/linux/x86/musl` |
| [proot-rs-v0.1.0-x86_64-linux-android.tar.gz](https://github.com/proot-me/proot-rs/releases/download/v0.1.0/proot-rs-v0.1.0-x86_64-linux-android.tar.gz) | 720.4 KiB | `native/linux/x64` |
| [proot-rs-v0.1.0-x86_64-unknown-linux-gnu.tar.gz](https://github.com/proot-me/proot-rs/releases/download/v0.1.0/proot-rs-v0.1.0-x86_64-unknown-linux-gnu.tar.gz) | 733.1 KiB | `native/linux/x64/glibc` |
| [proot-rs-v0.1.0-x86_64-unknown-linux-musl.tar.gz](https://github.com/proot-me/proot-rs/releases/download/v0.1.0/proot-rs-v0.1.0-x86_64-unknown-linux-musl.tar.gz) | 736.7 KiB | `native/linux/x64/musl` |

## Distribution status

Reported by **61** distros on [repology.org](https://repology.org/project/proot-rs). **1** are ✅ on the latest upstream release, **56** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Debian unstable | `5.4.0` | ⚠️ outdated |
| Debian 14 | `5.4.0` | ⚠️ outdated |
| Debian 13 | `5.1.0` | ⚠️ outdated |
| Ubuntu 26.04 LTS | `5.4.0` | ⚠️ outdated |
| Ubuntu 24.04 LTS | `5.1.0` | ⚠️ outdated |
| Nix unstable | `5.4.0` | ⚠️ outdated |
| Void | `5.2.0` | ⚠️ outdated |
| Alpine edge | `5.4.0` | ⚠️ outdated |

## Improve this data

Install metadata for proot-rs lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `proot-rs` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/proot-rs.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260911.yml` · 2026-09-11T04:57:36Z._
