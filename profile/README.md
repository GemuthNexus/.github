# <img src="../logo.svg" width="48" height="48" align="center" /> GemuthNexus

A self-hosted server management platform with a browser-based desktop interface.
Full control over your Linux server. **Designed for LAN & VPN deployments.**

[**Documentation**](https://github.com/GemuthNexus/doc) • [**Overview**](https://github.com/GemuthNexus/doc/blob/main/architecture/project-overview.md) • [**Description**](https://github.com/GemuthNexus/doc/blob/main/architecture/project-description.md) • [**Tech Stack**](https://github.com/GemuthNexus/doc/blob/main/architecture/tech-stack.md)

---

## 🧬 Core Philosophy

We believe that managing your own server should feel as **natural** as using a desktop — without giving up control to third-party platforms. GemuthNexus is built on the principle that the **Linux kernel** already provides everything you need for security, identity, and isolation. The platform's job is to make that power **accessible** through a modern interface — not to replace it.

### 🛡️ The Pillars

*   **Native Identity** — Your web session is your Linux session. Users authenticate with real system credentials, and every permission is enforced by the kernel.
*   **Process Isolation** — Every application runs as a dedicated process under the user's own UID. No shared runtimes, no containers, no trust boundaries to configure.
*   **Lean & Efficient** — The entire platform idles at ~30 MB RAM. Plugins are spawned on demand and released when idle. No background bloat, no wasted resources.
*   **Extensibility** — The platform ships with zero built-in apps. Everything is a plugin — installed, updated, and removed independently.

---

*No external accounts. No third-party cloud. Your server, your users, your rules.*

*Built with ❤️ for the self-hosted future.*