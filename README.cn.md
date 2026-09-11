# capstone

[English version](./README.md)

Capstone disassembly/disassembler framework for ARM, ARM64 (ARMv8), Alpha, BPF, Ethereum VM, HPPA, LoongArch, M68K, M680X, Mips, MOS65XX, PPC, RISC-V(rv32G/rv64G), SH, Sparc, SystemZ, TMS320C64X, TriCore, Webassembly, XCore and X86.

![capstone](https://repo.x-cmd.io/capstone.svg?lang=zh)

## 安装

```sh
x install capstone
```

## 代码洞察

合计: **2,668,153** 行代码（覆盖前 5 种语言、共 **3550** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Bitbake | 1,522,492 | 123,605 | 61,866 | 201 |
| Yaml | 851,425 | 525 | 65,312 | 1856 |
| C | 81,226 | 4,942 | 10,015 | 201 |
| CSharp | 65,902 | 98 | 327 | 1090 |
| CHeader | 50,839 | 3,838 | 3,481 | 202 |

## 源代码

- **上游仓库**: <https://github.com/capstone-engine/capstone>
- **官网**: <http://www.capstone-engine.org>
- **许可证**: NOASSERTION

## 发布

- **最新版本**: `6.0.0-Alpha10` (2026-07-21)
- **最近提交**: 2026-09-10
- **Release 含资产**: 5 个

## 流行度

- **Star**: 9,010 · **Fork**: 1,726 · **开放 issue**: 1,437 · **贡献者**: 319

## 累计统计

- **发布数**: 48 · **已合并 PR**: 1329 · **开放 PR**: 16 · **已关闭 issue**: 1096 · **开放 issue**: 341 · **提交数**: 5477

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-12 | 0 | 24 | 3 | 6 | 5 | 21 |
| last60d | 2026-07-13 | 1 | 47 | 3 | 11 | 11 | 44 |
| 90d | 2026-06-13 | 1 | 68 | 5 | 14 | 13 | 62 |
| last180d | 2026-03-15 | 5 | 125 | 10 | 25 | 16 | 109 |
| 360d | 2025-09-16 | 8 | 173 | 13 | 49 | 29 | 159 |
| last720d | 2024-09-21 | 16 | 326 | 16 | 116 | 78 | 302 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [capstone-6.0.0-Alpha10-Windows-x64.exe](https://github.com/capstone-engine/capstone/releases/download/6.0.0-Alpha10/capstone-6.0.0-Alpha10-Windows-x64.exe) | 5.7 MiB | `native/win/x64` |
| [capstone-6.0.0-Alpha10.tar.xz](https://github.com/capstone-engine/capstone/releases/download/6.0.0-Alpha10/capstone-6.0.0-Alpha10.tar.xz) | 5.4 MiB | `other` |
| [capstone-6.0.0-Alpha10.tar.xz.sha256](https://github.com/capstone-engine/capstone/releases/download/6.0.0-Alpha10/capstone-6.0.0-Alpha10.tar.xz.sha256) | 96 B | `other` |
| [capstone-devel-6.0.0-Alpha10.x86_64.rpm](https://github.com/capstone-engine/capstone/releases/download/6.0.0-Alpha10/capstone-devel-6.0.0-Alpha10.x86_64.rpm) | 6.3 MiB | `runtime/rpm/x86_64` |
| [libcapstone-dev_6.0.0-Alpha10_amd64.deb](https://github.com/capstone-engine/capstone/releases/download/6.0.0-Alpha10/libcapstone-dev_6.0.0-Alpha10_amd64.deb) | 6.5 MiB | `runtime/deb/amd64` |

## 发行版状态

在 [repology.org](https://repology.org/project/capstone) 上共有 **239** 个发行版报告此项目。**64** 个 ✅ 已是最新上游版本，**147** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Debian unstable | `5.0.7` | 🪦 legacy |
| Debian 14 | `5.0.9` | ✅ latest |
| Debian 13 | `5.0.7` | ⚠️ outdated |
| Ubuntu 26.04 LTS | `5.0.7` | ⚠️ outdated |
| Ubuntu 24.04 LTS | `4.0.2` | ⚠️ outdated |
| Arch | `5.0.9` | ✅ latest |
| Homebrew | `5.0.9` | ✅ latest |
| Fedora rawhide | `5.0.6` | ⚠️ outdated |
| Nix unstable | `5.0.9` | ✅ latest |
| Void | `5.0.9` | ✅ latest |
| Alpine edge | `5.0.9` | ✅ latest |
| openSUSE Tumbleweed | `5.0.6` | ⚠️ outdated |

## 改进这些数据

capstone 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `capstone` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/capstone.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260911.yml` · 2026-09-11T20:21:05Z._
