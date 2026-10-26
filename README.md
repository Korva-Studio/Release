# Korva Releases

Public release and distribution information for **Korva**, a Windows desktop
application for DAW project organisation.

This repository is an information surface only. It does not host binaries and
it is not the release authority.

## Current release

| | |
|---|---|
| Version | **0.4.367** |
| Channel | `release` |
| Platform | Windows x64 |
| Installer | [Korva-0.4.367-windows-x64-setup.exe](https://releases.korva.studio/releases/v0.4.367/Korva-0.4.367-windows-x64-setup.exe) |
| Installer size | 179,677,599 bytes |

## Download and update

Download the installer from the link above, or from
[korva.studio/download](https://korva.studio/download/).

Korva checks for updates by reading the signed release manifest for its
channel:

- Manifest: <https://releases.korva.studio/releases/v0.4.367/latest.json>
- Signature: RS256, key `release-2026-01`
- Software bill of materials: <https://releases.korva.studio/releases/v0.4.367/Korva.cdx.json>

Release artifacts are served from `releases.korva.studio`, backed by Cloudflare
R2. **GitHub Releases are not used for distribution.** The versioned URL for a
release is immutable; a new build is published under a new version rather than
overwriting an existing one.

## Release notes

Release notes and the current download are published at
<https://korva.studio/download/>. Changelog announcements are posted in the
Korva Discord.

## Source code

Korva's source lives in private repositories under
[github.com/Korva-Studio](https://github.com/Korva-Studio). This repository is a
public release-information surface, not a source mirror.

## Reporting a problem

Use the support channels linked from <https://korva.studio/>. Please do not
include credentials, license keys, or personal data in a public issue.
