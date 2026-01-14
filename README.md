# LiteRT Studio

LiteRT Studio is a powerful, completely offline AI chat application built for Linux. It provides a seamless, self-contained environment to run Large Language Models (LLMs) and Vision-Language Models locally on your machine without an internet connection.

## Key Features

- **100% Offline**: No internet required once models are downloaded. Your privacy is guaranteed.
- **Built-in Model Store**: Browse, download, and manage LiteRT-optimized models directly within the application.
- **Universal Hardware Support**: Optimized for CPU inference, allowing it to run on almost any hardware (including older Laptops/Desktops).
- **Zero Configuration**: No need to worry about Python environments, CUDA, or complex dependencies. It just works out of the box.
- **Vision Model Support**: View and interact with images using vision-language models.
- **Resource Control**: Dedicated CPU thread allocation settings to balance performance and system usage.
- **Modern UI**: A premium, responsive interface featuring glassmorphism aesthetics and animated transitions.

## Installation (Linux)

Currently, LiteRT Studio is distributed as a `.deb` package for Debian-based distributions (Ubuntu, Linux Mint, etc.).

1. Download the latest `.deb` package from the [Releases](https://github.com/DjagbleyEmmanuel/LiteRT-Studio/releases) page.
2. Install it using `dpkg` or your favorite package manager:
   ```bash
   sudo dpkg -i litert_studio_1.0.0_amd64.deb
   ```
3. Launch "LiteRT Studio" from your application menu.

## How it Works

LiteRT Studio uses the LiteRT-LM runtime to execute models efficiently on CPUs. It packages all necessary shared libraries and binaries, ensuring a standalone experience regardless of your system's global environment.

---
*Note: This repository currently hosts the binary releases. Source code integration is planned for a future update.*




- **PS: Check new releases for for fixes and feature updates**
