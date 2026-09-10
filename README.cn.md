# proot-rs

[English version](./README.md)

Rust implementation of PRoot, a ptrace-based sandbox

![proot-rs](https://repo.x-cmd.io/proot-rs.svg?lang=zh)

## 安装

```sh
x install proot-rs
```

## 代码规模

合计: **403** 行代码（覆盖前 5 种语言、共 **12** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| C | 147 | 40 | 28 | 3 |
| Toml | 119 | 2 | 21 | 5 |
| Sh | 49 | 7 | 15 | 1 |
| Dockerfile | 39 | 7 | 12 | 2 |
| Bash | 29 | 13 | 10 | 1 |

## 源代码

- **上游仓库**: <https://github.com/proot-me/proot-rs>
- **许可证**: GPL-3.0

## 发布

- **最新版本**: `v0.1.0` (2021-08-20)
- **最近提交**: 2026-06-08
- **Release 含资产**: 12 个

## 流行度

- **Star**: 160 · **Fork**: 27 · **开放 issue**: 36 · **贡献者**: 6

## 累计统计

- **发布数**: 1 · **已合并 PR**: 30 · **开放 PR**: 0 · **已关闭 issue**: 23 · **开放 issue**: 13 · **提交数**: 225

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 0 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-12 | 0 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-06-12 | 0 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-03-14 | 0 | 1 | 0 | 0 | 0 | 2 |
| 360d | 2025-09-15 | 0 | 1 | 0 | 0 | 0 | 2 |
| last720d | 2024-09-20 | 0 | 1 | 0 | 0 | 2 | 2 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
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

## 发行版状态

在 [repology.org](https://repology.org/project/proot-rs) 上共有 **61** 个发行版报告此项目。**1** 个 ✅ 已是最新上游版本，**56** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Debian unstable | `5.4.0` | ⚠️ outdated |
| Debian 14 | `5.4.0` | ⚠️ outdated |
| Debian 13 | `5.1.0` | ⚠️ outdated |
| Ubuntu 26.04 LTS | `5.4.0` | ⚠️ outdated |
| Ubuntu 24.04 LTS | `5.1.0` | ⚠️ outdated |
| Nix unstable | `5.4.0` | ⚠️ outdated |
| Void | `5.2.0` | ⚠️ outdated |
| Alpine edge | `5.4.0` | ⚠️ outdated |

## 改进这些数据

proot-rs 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `proot-rs` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/proot-rs.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260910.yml` · 2026-09-10T21:48:12Z._
