<!-- gully-header:start -->
<a href="https://gullychain.xyz"><img src="https://gullychain.xyz/brand/repos/hyperlane-registry.svg" alt="GullyChain · Hyperlane Registry" width="100%"></a>

<p align="center">
  <a href="https://gullychain.xyz"><img src="https://img.shields.io/badge/gullychain.xyz-01D9FA?style=for-the-badge&labelColor=000000&logo=googlechrome&logoColor=000000" alt="Website"></a>
  <a href="https://app.gullychain.xyz"><img src="https://img.shields.io/badge/App-0A0F1A?style=for-the-badge&labelColor=000000&logo=googlechrome&logoColor=01D9FA" alt="App"></a>
  <a href="https://docs.gullychain.xyz"><img src="https://img.shields.io/badge/Docs-0A0F1A?style=for-the-badge&labelColor=000000&logo=readthedocs&logoColor=01D9FA" alt="Docs"></a>
  <a href="https://x.com/Gully_Labs"><img src="https://img.shields.io/badge/@Gully__Labs-0A0F1A?style=for-the-badge&labelColor=000000&logo=x&logoColor=white" alt="X"></a>
  <a href="https://t.me/GullyChain"><img src="https://img.shields.io/badge/Telegram-0A0F1A?style=for-the-badge&labelColor=000000&logo=telegram&logoColor=26A5E4" alt="Telegram"></a>
  <a href="https://discord.com/invite/tY2ErsNNBp"><img src="https://img.shields.io/badge/Discord-0A0F1A?style=for-the-badge&labelColor=000000&logo=discord&logoColor=5865F2" alt="Discord"></a>
  <a href="https://github.com/gully-labs"><img src="https://img.shields.io/badge/GitHub-0A0F1A?style=for-the-badge&labelColor=000000&logo=github&logoColor=white" alt="GitHub"></a>
</p>

<p align="center"><b>Hyperlane Registry: Chain and warp route configs, including GullyChain.</b></p>

<p align="center"><sub>Maintained by <a href="https://gullylabs.xyz">Gully Labs</a> as part of <a href="https://gullychain.xyz">GullyChain</a>. Fork of <a href="https://github.com/hyperlane-xyz/hyperlane-registry">hyperlane-xyz/hyperlane-registry</a>, used under its MIT licence. Not affiliated with or endorsed by Abacus Works.</sub></p>

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
