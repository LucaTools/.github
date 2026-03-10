<div align="center">
  <img src="https://luca.tools/images/luca-logo-alt.svg" alt="Luca" height="80">

  <h3>A minimalistic, lightweight, decentralized tool manager<br>for macOS and Linux</h3>

  [![License](https://img.shields.io/badge/License-Apache%202.0-green.svg)](https://github.com/LucaTools/Luca/blob/main/LICENSE)
  [![Swift](https://img.shields.io/badge/Swift-5.7+-orange.svg)](https://swift.org)
  [![Platforms](https://img.shields.io/badge/Platforms-macOS%20%7C%20Linux-blue.svg)](https://github.com/LucaTools/Luca)
  [![Marketplace](https://img.shields.io/badge/Marketplace-setup--luca-blue?logo=github)](https://github.com/marketplace/actions/setup-luca)
</div>

---

Luca helps developers install, manage, and activate specific versions of CLI tools inside their projects — without polluting the global PATH. There is no central registry: tools are installed directly from GitHub Releases or any URL, pinned in a simple YAML file (`Lucafile`), and symlinked into `.luca/tools/` inside your project.

## Install

```bash
curl -fsSL https://luca.tools/install.sh | bash
```

## Repositories

| Repository | Description |
|------------|-------------|
| [**Luca**](https://github.com/LucaTools/Luca) | Core CLI — installs, manages, and links versioned tools in your project |
| [**setup-luca**](https://github.com/LucaTools/setup-luca) | GitHub Action to install Luca and your project tools in CI workflows ([Marketplace](https://github.com/marketplace/actions/setup-luca)) |
| [**LucaWorkflows**](https://github.com/LucaTools/LucaWorkflows) | Copy-paste CI workflow templates to publish Luca-compatible releases for Swift, Go, Rust, Python, C#, and Zig |
| [**LucaScripts**](https://github.com/LucaTools/LucaScripts) | Shell scripts: installer, uninstaller, shell PATH hook, and git post-checkout hook |

## Resources

- **Website**: [luca.tools](https://luca.tools)
- **Documentation**: [luca.tools/Luca/documentation/lucacore](https://luca.tools/Luca/documentation/lucacore/)
- **Tutorial**: [luca.tools/Luca/tutorials/luca](https://luca.tools/Luca/tutorials/luca)

## License

All repositories are licensed under [Apache 2.0](https://github.com/LucaTools/Luca/blob/main/LICENSE).

---

<div align="center">
  Made by <a href="https://x.com/albertodebo">@albertodebo</a> · <a href="https://bsky.app/profile/albertodebo.bsky.social">Bluesky</a> · <a href="https://albertodebortoli.com">Website / Blog</a>
</div>
