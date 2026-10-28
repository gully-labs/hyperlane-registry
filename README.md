<!-- gully-header:start -->
<p align="center">
  <a href="https://gullychain.xyz">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset=".github/assets/gullychain-wordmark-for-dark-bg.png">
      <img alt="Gully Chain" src=".github/assets/gullychain-wordmark-for-light-bg.png" width="360">
    </picture>
  </a>
</p>

<p align="center"><b>The social chain where your profile is your wallet. Arbitrum Orbit L3, testnet chain 485590.</b></p>

<p align="center">Hyperlane chain and warp route configs, including Gully Chain.</p>

<p align="center">
  <a href="https://gullychain.xyz"><img src="https://img.shields.io/badge/gullychain.xyz-01D9FA?style=for-the-badge&labelColor=000000&logo=googlechrome&logoColor=000000" alt="Website"></a>
  <a href="https://docs.gullychain.xyz"><img src="https://img.shields.io/badge/Docs-0A0F1A?style=for-the-badge&labelColor=000000&logo=readthedocs&logoColor=01D9FA" alt="Docs"></a>
  <a href="https://t.me/GullyChain"><img src="https://img.shields.io/badge/Telegram-0A0F1A?style=for-the-badge&labelColor=000000&logo=telegram&logoColor=26A5E4" alt="Telegram"></a>
  <a href="https://discord.com/invite/tY2ErsNNBp"><img src="https://img.shields.io/badge/Discord-0A0F1A?style=for-the-badge&labelColor=000000&logo=discord&logoColor=5865F2" alt="Discord"></a>
  <a href="https://x.com/Gully_Labs"><img src="https://img.shields.io/badge/@Gully__Labs-0A0F1A?style=for-the-badge&labelColor=000000&logo=x&logoColor=white" alt="X"></a>
</p>

<p align="center"><sub>A Gully Chain fork of <a href="https://github.com/hyperlane-xyz/hyperlane-registry">hyperlane-xyz/hyperlane-registry</a>, maintained by <a href="https://gullylabs.xyz">Gully Labs</a>. It is used under its MIT licence; the upstream LICENSE, copyright and attribution notices are kept unchanged. The upstream README follows below as published. Not affiliated with or endorsed by hyperlane-xyz.</sub></p>

---
<!-- gully-header:end -->

# Hyperlane Registry

A collection of configs, artifacts, and schemas for Hyperlane. See the [documentation](https://docs.hyperlane.xyz/docs/reference/registries) for more information.

## Contents

### Chains

A list of chains and the relevant information that Hyperlane utilities and apps will require to interact with chains.
Structured as a folder for each chain. Each folder should contain a `metadata.yaml`, `addresses.yaml`, and a `logo.svg` file.

### Deployments

#### Core

Configs and artifacts for [Hyperlane Core Contract](https://docs.hyperlane.xyz/docs/guides/chains/deploy-hyperlane) deployments.

#### Warp

Address artifacts for [Warp Route](https://docs.hyperlane.xyz/docs/applications/warp-routes/overview) token deployments.

#### Install `gitleaks`

You need `gitleaks` installed on your machine. You can download it from [official page](https://github.com/gitleaks/gitleaks) or use a package manager of your choice.

## Contributing

This registry is maintained by the core Hyperlane team but community members are encouraged to add chain and deployment information here! See the [Contribution Guide](./CONTRIBUTING.md) for more information.


<!-- gully-footer:start -->
---

<p align="center">
  <a href="https://gullylabs.xyz">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset=".github/assets/powered-by-gully-labs-dark-2x.png">
      <img alt="Powered by Gully Labs" src=".github/assets/powered-by-gully-labs-light-2x.png" width="254" height="64">
    </picture>
  </a>
</p>
<!-- gully-footer:end -->
