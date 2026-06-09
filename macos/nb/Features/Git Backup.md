---
title: Git Backup
tags: features, git, backup, sync
---

# Git Backup

Meridian committer og synkroniserer automatisk hvelvet ditt til et privat GitHub-repositorium. Hvert lagre blir et øyeblikksbilde i versjonshistorikken din.

---

## Oppsett

1. Åpne **Innstillinger → Synkronisering og GitHub** (`⌘,`)
2. Koble til GitHub-kontoen din (åpner nettleseren)
3. Åpne **Sikkerhetskopiering i skyen**-panelet (git-ikon i sidepanelet)
4. Klikk **Sett opp sikkerhetskopiering** og skriv inn repo-URL-en din
5. Ferdig — hvelvet ditt er nå sikkerhetskopiert

---

## Slik fungerer det

**Lagre øyeblikksbilde** — commit alle endringer manuelt med en melding.

**Automatisk sikkerhetskopiering** — sett et intervall (15 min, 30 min, 1 time) i panelet. Meridian committer og pusher automatisk.

**Historikk** — hver commit er et øyeblikksbilde av et bestemt tidspunkt. Bla gjennom historikken i panelet.

---

## Commit-meldinger

Meridian genererer commit-meldinger automatisk:

```
Updated: Research Note.md, Project Planning.md
Added: Daily/2026-05-22.md
```

Tilpass malen i **Innstillinger → Synkronisering → Mal for commit-melding**.

---

## Hvorfor GitHub?

- Gratis for private repositorier
- Pålitelig synkronisering på tvers av enheter
- Rene tekstfiler — ingen innlåsing

> [!NOTE]
> Aktiver utvidelsen «Git Autocommit Backups» i **Innstillinger → Kjerneutvidelser** først.

> [!TIP]
> Sett automatisk sikkerhetskopiering til 15 minutter og glem det. Notatene dine er alltid trygge.
