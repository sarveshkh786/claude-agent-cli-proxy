# Claude Agent CLI Proxy & Toolchain

A lightweight CLI automation toolchain, local API proxy router, and modular agent skill runner built for developer environments using Python (`uv`), Node.js, and PowerShell.

## Features
- **Zero-Friction API Routing:** Local proxy middleware for managing rate limits, retries, and context window payloads across LLM endpoints.
- **Cross-Platform CLI Automation:** Native integration with Windows PowerShell and POSIX shells for terminal-native agent workflows.
- **Modular Agent Skills:** Extensible schema for defining and executing local data pipeline and environment management tasks.

## Quick Start (uv / Python)
```bash
uv venv
uv pip install -r requirements.txt
python proxy_router.py --port 8080 --model claude-3-7-sonnet
