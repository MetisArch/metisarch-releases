# MetisArch — Releases

Official distribution repository for **MetisArch** desktop installers and automatic updates.

🌐 **Website & Documentation:** [metisarch.github.io/metisarch-site](https://metisarch.github.io/metisarch-site/)  
📦 **Latest Release:** [Download Latest Version](https://github.com/metisarch/metisarch-releases/releases/latest)

---

## What is MetisArch?

**MetisArch** is a local-first business and technical knowledge management workspace with native **Model Context Protocol (MCP)** integration. It gives AI coding assistants (GitHub Copilot, Cursor, Claude, VS Code) deterministic, surgical access to your domain rules, architecture decisions, and technical documentation — without sending your entire knowledge base to external servers.

### Core Capabilities

- **Local-First & Private:** Your documents, indexes, and embeddings stay on your machine or your own infrastructure.
- **Hybrid Context-Preserving Search:** Combines lexical search (FTS5/BM25), local ONNX vector embeddings, AST structural chunking, and neural re-ranking to deliver accurate, low-noise context.
- **Rich Format Support:** Native support for Markdown (`.md`), Word documents (`.docx`), Mermaid diagrams, and structured configs.
- **Native MCP Server:** Connects directly to your IDE or AI client to query official business rules and submit proposed updates for human review.

---

## Download & Installation

Download the installer for your operating system from the [Latest Release](https://github.com/metisarch/metisarch-releases/releases/latest) page:

| Platform                  | Package              | Notes                                                                     |
| :------------------------ | :------------------- | :------------------------------------------------------------------------ |
| **Windows**               | `.exe`               | Standard Windows installer (supports automatic updates)                   |
| **macOS (Apple Silicon)** | `.dmg`               | Drag to Applications (automatic updates handled via `.zip` in background) |
| **Linux**                 | `.AppImage` / `.deb` | `.AppImage` supports automatic updates; `.deb` for Debian/Ubuntu          |

> **Note on release assets:** Files ending in `.yml`, `.blockmap`, and `-mac.zip` are used exclusively by the built-in auto-updater. You do not need to download them manually.

### Self-Hosted (Docker)

MetisArch is also available as a self-hosted container image via GitHub Container Registry (GHCR). Check the [official website](https://metisarch.github.io/metisarch-site/) for setup instructions.

---

## Feedback & Support

This repository is dedicated exclusively to binary releases and changelogs.  
For licensing, documentation, or support, visit [metisarch.github.io/metisarch-site](https://metisarch.github.io/metisarch-site/).
