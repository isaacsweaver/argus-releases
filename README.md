# Argus releases

**Argus** is a graph-based control plane for building software with AI: you
draw your project's structure, standards and decisions once, and Claude Code
works inside them. It runs **entirely on your computer** — your projects, your
Claude Code login and your keys never leave it.

This repository holds the built apps and release notes only.

## Download

Pick the latest release on the [Releases page](../../releases/latest):

| You have | Download |
|---|---|
| a Mac with Apple silicon (M1 or later) | `Argus-<version>-arm64.dmg` |
| an Intel Mac | `Argus-<version>-x64.dmg` |
| Windows 10 or 11 (64-bit) | `Argus-Setup-<version>.exe` |

Open the download and follow the installer (on a Mac, drag Argus to
Applications). The first time you open Argus it walks you through connecting
Claude Code. Argus tells you when a new release is out and updates only when
you say so.

## Windows: "Windows protected your PC"

The Windows installer is not code-signed yet, so SmartScreen shows a blue
warning the first time. Choose **More info**, then **Run anyway**. The
installer only installs for your own user.

## What it needs

- [Claude Code](https://claude.ai/code), signed in with your own account —
  Argus' setup screen checks this and shows how to install it.
- Optional: a Tripo API key and the Artlist connector, for the 3D and media
  tools. Argus' setup screen explains both.

## Privacy

Argus has no account service and no server of ours. Projects, history and keys
stay on your machine; Argus talks to GitHub only if you connect an account to
share a workspace, and to this repository to look for updates.
