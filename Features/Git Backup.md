---
title: Git Backup
tags: features, git, backup, sync
---

# Git Backup

Meridian automatically commits and syncs your vault to a private GitHub repository. Every save becomes a snapshot in your version history.

---

## Setting up

1. Open **Settings → Sync & GitHub** (`⌘,`)
2. Connect your GitHub account (opens browser)
3. Open the **Cloud Backup** panel (git icon in sidebar)
4. Click **Set up backup** and enter your repo URL
5. Done — your vault is now backed up

---

## How it works

**Save Snapshot** — manually commit all changes with a message.

**Auto-backup** — set an interval (15 min, 30 min, 1 hour) in the panel. Meridian commits and pushes automatically.

**History** — every commit is a point-in-time snapshot. Browse history in the panel.

---

## Commit messages

Meridian generates commit messages automatically:

```
Updated: Research Note.md, Project Planning.md
Added: Daily/2026-05-22.md
```

Customize the template in **Settings → Sync → Commit message template**.

---

## Why GitHub?

- Free for private repos
- Reliable, cross-device sync
- Plain text files — no lock-in

> [!NOTE]
> Enable the "Git Autocommit Backups" plugin in **Settings → Core Plugins** first.

> [!TIP]
> Set auto-backup to 15 minutes and forget about it. Your notes are always safe.
