# Scribe

A Mac app for reading: articles, essays, PDFs and EPUB books in one place,
with highlights and notes that work the same way across all of them.

**Needs macOS 26 (Tahoe) or later.**

## Download

**[Download Scribe](https://github.com/AdamDWalker/scribe-releases/releases/latest/download/Scribe.dmg)**
(the latest version, as a disk image)

## Install

1. Open **Scribe.dmg** and drag **Scribe** onto the **Applications** folder.
2. Open Scribe from Applications. The first time, macOS says it can't check
   Scribe for malicious software. Click **Done**. (Scribe isn't registered
   with Apple yet, so this is expected.)
3. Open **System Settings › Privacy & Security**, scroll down to **Security**,
   and click **Open Anyway** next to the line about Scribe. Enter your Mac's
   password.
4. Click **Open** in the box that follows.

You only do this once. Scribe updates itself after that: when a new version
is out, it installs the next time you quit Scribe.

Keep Scribe in Applications. Run from the disk image or from Downloads, it
can't update itself.

## Your library

Everything you save stays on your Mac, in Scribe's own folder (Settings ›
Library › Show in Finder). Scribe keeps a weekly copy of its database there,
and Time Machine backs it all up.

## Problems

Help › Report a Bug… in Scribe starts an email with the details that help
fix it. Or write to [scribe@possibilitytwo.com](mailto:scribe@possibilitytwo.com).

---

## About this repository

Scribe's source is private; this repository is its public update feed.
`appcast.xml` is the Sparkle feed the app checks, and each GitHub Release
holds that version's signed zip (for updates) and DMG (for first installs).
Everything except this README is published by `scripts/release.sh` in the
source repository, so don't edit it by hand.
