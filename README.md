# Streamer Companion Modules

Module catalogue and independently versioned downloads by **Sethani**.

- [Browse the catalogue folder](catalog/).
- [Download individual module releases](https://github.com/Sethani/StreamerCompanion-Modules/releases).
- [Application downloads and all editable source](https://github.com/Sethani/StreamerCompanion).

This repository distributes modules, not the Companion application. Each release contains one module package and its checksum. A Spotify update does not rebuild or re-upload Video or the application. The catalogue preserves each unchanged module's existing version, URL and SHA-256.

Use Check for updates inside Companion 1.1.1 or newer to browse and install. Packages install only after confirmation. These initial modules are experimental; respect their documented external dependencies and keep backups.

## Publishing one module

Bump that module's version in the source repository, then run the Publish module workflow here with its module ID. The workflow checks out public source, builds only the selected module, creates its immutable per-module release and then commits only its catalogue entry. Publications are serialized to protect the shared index. No cross-repository write token is needed: this repository's GitHub token writes only here.

First-party modules and catalogue metadata are MIT-licensed. Third-party licences are retained separately in the source project and packages. Do not replace an existing version's package bytes; publish a new version instead.
