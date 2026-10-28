# AssetHub

An asset manager for individuals, studios and small teams: preview, search, annotate and drag assets while keeping your existing folder structure.

[中文](README.md) · [Download Alpha](https://github.com/Airkria/AssetHub-Releases/releases/tag/v2.0.0-alpha.5) · [Illustrated quick start (Chinese)](docs/QUICK_START.md) · [Report an issue](https://github.com/Airkria/AssetHub-Releases/issues/new/choose)

> **Current release: 2.0.0-alpha.5.** This release improves NAS browsing, huge PNG previews, loading feedback and consistent covers across layouts. Setup is covered in the [Chinese illustrated guide](docs/QUICK_START.md). Screenshots come from an isolated instance of the actual desktop app.

## Getting started

**Public release: 2.0.0-alpha.5 — Windows 10/11 x64.** Download the setup executable from Releases, install it, then choose your work preset and connect a small existing asset folder in the setup wizard. Existing users keep their settings. The installer includes the model converter. WebView2 may require an Internet connection on first installation. See the [illustrated guide (Chinese)](docs/QUICK_START.md).

## Features

- Configurable boards, scan scopes, categories, search and tags.
- Masonry, grid, tree, detail and adaptive detail views.
- Folder packages, version groups, multiple previews and native drag-out.
- Responsive image detail previews, video/GIF hover scrubbing and video play/stop controls.
- Configurable video size limit (1024 MiB by default); larger files open externally. Files below the limit may still fail to preview.
- 3D previews with texture provenance and file location.
- Metadata save status, retry and backup recovery.
- Board icons, third-party notices and signed Alpha updates.

## Updates and Alpha limitations

Use **Settings → About → Check for updates**, or enable automatic checks at startup. Download an update, then choose to install and restart. Pending saves, scans and model conversions must finish first.

This is an early test build. Try copies or non-critical assets first. Concurrent metadata editing across machines is not supported yet. Failed edits are retained only for the current session; reconnect and retry before quitting. Package size represents indexed assets rather than total folder size. Huge non-interlaced PNG previews are limited to 2048px in detail; other huge images may still require an external viewer. Custom icons are local to the machine. Model/material compatibility varies. macOS/Linux and in-app screenshot submission are not included.

The updater verifies signed artifacts. The installer does not currently have a Windows publisher certificate signature, so Windows may show an unknown publisher warning.

## Feedback and author

Public feedback: [GitHub Issues](https://github.com/Airkria/AssetHub-Releases/issues/new/choose). Include the version, steps, expected and actual results; remove private content before attaching screenshots.

Author: **Airkria** · Private contact: **airkria.assethub@gmail.com**.

This repository contains downloads, update manifests and documentation. The source project is maintained separately. Licenses and third-party notices are included with the installer.
