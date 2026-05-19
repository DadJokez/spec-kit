<div align="center">
    <img src="./media/logo_large.webp" alt="Spec Kit Logo" width="200" height="200"/>
    <h1>🌱 Spec Kit</h1>
    <h3><em>Build high-quality software faster.</em></h3>
</div>

<p align="center">
    <strong>An open source toolkit that allows you to focus on product scenarios and predictable outcomes instead of vibe coding every piece from scratch.</strong>
</p>

<p align="center">
    <a href="https://github.com/github/spec-kit/releases/latest"><img src="https://img.shields.io/github/v/release/github/spec-kit" alt="Latest Release"/></a>
    <a href="https://github.com/github/spec-kit/stargazers"><img src="https://img.shields.io/github/stars/github/spec-kit?style=social" alt="GitHub stars"/></a>
    <a href="https://github.com/github/spec-kit/blob/main/LICENSE"><img src="https://img.shields.io/github/license/github/spec-kit" alt="License"/></a>
    <a href="https://github.github.io/spec-kit/"><img src="https://img.shields.io/badge/docs-GitHub_Pages-blue" alt="Documentation"/></a>
</p>

> **Mirror of [github/spec-kit](https://github.com/github/spec-kit)** — personal copy for exploration.

---

## ⚡ Get Started

### 1. Install Specify CLI

Requires **[uv](https://docs.astral.sh/uv/)** ([install uv](./docs/install/uv.md)). Replace `vX.Y.Z` with the latest tag from [Releases](https://github.com/github/spec-kit/releases):

```bash
uv tool install specify-cli --from git+https://github.com/github/spec-kit.git@vX.Y.Z
```

See the [Installation Guide](./docs/installation.md) for alternative methods, verification, upgrade, and troubleshooting.

### 2. Initialize a project

```bash
specify init my-project --integration copilot
cd my-project
```

### 3. Run the workflow

```bash
/speckit.constitution Create principles focused on code quality and testing standards
/speckit.specify Build [describe what you want to build]
/speckit.plan Use [your tech stack]
/speckit.tasks
/speckit.implement
```

For the full guide, see [spec-driven.md](./spec-driven.md) or the [upstream README](https://github.com/github/spec-kit).

## 📄 License

MIT — see [LICENSE](./LICENSE). Original project by GitHub, Inc.
