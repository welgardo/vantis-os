<div align="center">

# VANTIS

### Security-first Linux, built from the ground up.

*An Arch-based distribution engineered for penetration testing, reconnaissance, and offensive security research.*

[![Status](https://img.shields.io/badge/status-in%20development-orange)]()
[![Base](https://img.shields.io/badge/base-Arch%20Linux-1793D1)]()
[![License](https://img.shields.io/badge/license-GPLv3-blue)]()
[![Target Release](https://img.shields.io/badge/v0.1-New%20Year-critical)]()

</div>

---

## What is Vantis?

Vantis is not a fork with a new wallpaper. It's a security-focused Linux distribution built on Arch, designed from the ground up to be the daily driver of a security researcher — fast, minimal, and armed.

Where most security distros bundle the same public tools everyone already has, Vantis is built around a growing set of **original, unreleased tooling** — written specifically for this system and not available anywhere else. The public toolkit (Nmap, Wireshark, Metasploit, Burp Suite, and the usual suspects) is included too, but it's the foundation, not the point.

This is a long-term build. Vantis is not a weekend project — it's a system intended to be developed, broken, rebuilt, and shipped updates to for years.

---

## Why Arch?

- **Rolling release** — no waiting for the next major version to get the newest kernel, tools, or CVE database
- **Minimal base** — no bloat, no assumptions about what you need pre-installed
- **AUR access** — the largest community package repository in the Linux world, from day one
- **Full control** — every part of the system is understood and configured on purpose, not inherited

---

## Roadmap

### v0.1 — Target: New Year
- [ ] Custom Arch ISO via `archiso`
- [ ] Base install with security-hardened defaults
- [ ] Branding: boot splash, terminal theme, wallpaper set
- [ ] Core toolkit pre-installed (recon, scanning, exploitation basics)
- [ ] First original Vantis-exclusive tool shipped

### v0.2+
- [ ] Custom package repository (Vantis repo, `pacman`-compatible)
- [ ] Expanded original toolkit — recon automation, custom scanners
- [ ] Hardened kernel configuration
- [ ] Live-boot + persistent install modes

### Long-term
- [ ] Full documentation site
- [ ] Community-contributed packages
- [ ] Regular CVE/tooling update cycle
- [ ] Dedicated hardware compatibility list

*This roadmap will evolve. Vantis is built in the open, in public commits, over time — not in one sprint.*

---

## What makes Vantis different

| | Standard security distros | Vantis |
|---|---|---|
| Toolset | Public tools only | Public tools + original, exclusive tooling |
| Release model | Point releases | Rolling, Arch-based |
| Development | Team-maintained | Solo-built, actively maintained long-term |
| Branding | Inherited | Built from scratch |

---

## Status

Vantis is currently **in active early development**. There is no installable image yet. Progress is tracked through commits in this repository — every commit is a real step, not a placeholder.

Follow the repo to watch it grow from an empty roadmap to a bootable ISO.

---

## Philosophy

A distro is a statement about how you think a system should work. Vantis is built on the belief that a security professional's OS should:

1. **Do nothing you didn't ask it to do** — no bloat, no telemetry, no guesswork
2. **Give you the newest tools, always** — rolling release, no stale packages
3. **Include tools nobody else has** — original tooling built specifically for this system
4. **Be understood, not just used** — every component is documented and intentional

---

## License

Vantis is licensed under the [GNU General Public License v3.0](LICENSE) — free to use, study, modify, and share.

---

<div align="center">

**Built solo. Built to last.**

*Star ⭐ this repo to follow the build.*

</div>
