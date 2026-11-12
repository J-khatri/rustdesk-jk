# HelpLink

HelpLink is a self-hosted remote-support platform for computer and software
dealers, built around a self-hosted ID/relay server (`helplink.in`).

HelpLink is based on [RustDesk](https://github.com/rustdesk/rustdesk) and
therefore continues to be free software: this fork publishes its full source
code and is licensed under the **GNU Affero General Public License v3.0**
(see [LICENSE](LICENSE)), with all copyright notices retained. We thank the
RustDesk project and contributors.

## What is changed vs upstream

- Rebranded client (name, icons, installer metadata) for the HelpLink service.
- Server defaults point clients to the HelpLink-hosted ID/relay servers.
- Windows-first build pipeline producing signed/unsigned client installers.

## Build

See upstream [docs](https://rustdesk.com/docs) and `build.py`; CI lives in
`.github/workflows/`.
