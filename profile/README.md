# ArtCraft by storytold — Unofficial Fork Collection

### Seven creative tools. One preservation home.

This is an **unofficial personal fork collection** maintained by [@builtbyjasim](https://github.com/builtbyjasim). Original development, authorship, and credit belong to the **ArtCraft Team and contributors at [@storytold](https://github.com/storytold)**. This collection is not the official ArtCraft project and is not endorsed by its developers.

[Original organization](https://github.com/storytold) · [Official ArtCraft website](https://getartcraft.com) · [All collection repositories](https://github.com/orgs/storytold-artcraft-forks/repositories)

## Explore the collection

| Application | What it does | Original project |
| --- | --- | --- |
| [PhotoCraft](https://github.com/storytold-artcraft-forks/photocraft) | Image editing with layers, masks, text, and PSD files. | [storytold/photocraft](https://github.com/storytold/photocraft) |
| [VectorCraft](https://github.com/storytold-artcraft-forks/vectorcraft) | Vector illustration and artwork. | [storytold/vectorcraft](https://github.com/storytold/vectorcraft) |
| [FilmCraft](https://github.com/storytold-artcraft-forks/filmcraft) | Nonlinear video editing, color, and sound. | [storytold/filmcraft](https://github.com/storytold/filmcraft) |
| [LightCraft](https://github.com/storytold-artcraft-forks/lightcraft) | Photo library management and raw development. | [storytold/lightcraft](https://github.com/storytold/lightcraft) |
| [PdfCraft](https://github.com/storytold-artcraft-forks/pdfcraft) | Reading, editing, organizing, and protecting PDFs. | [storytold/pdfcraft](https://github.com/storytold/pdfcraft) |
| [EffectCraft](https://github.com/storytold-artcraft-forks/effectcraft) | Motion graphics, visual effects, and compositing. | [storytold/effectcraft](https://github.com/storytold/effectcraft) |
| [DesignCraft](https://github.com/storytold-artcraft-forks/designcraft) | Page layout and publishing. | [storytold/designcraft](https://github.com/storytold/designcraft) |

## Preservation and synchronization

All seven projects were created using GitHub native forks, with the main-only option disabled. Original commit history, authorship, license files, and notices remain in their respective repositories. No application source code was edited. Each project retains its original license and asset/trademark terms; no additional rights are granted here.

**Last verified: 16 October 2026.** All seven public repositories exist in this organization. Daily workflows are configured for the default branch at **02:23 UTC (07:53 India time)**. All seven initial manual verification runs were submitted and were **queued** at last inspection; successful execution is not yet verified. This date is an existence/configuration check, not a successful scheduled synchronization. Check the live run links below for current results.

Preservation policy: create a backup reference before updating; never force-push, delete repositories or branches, or discard independent changes. Stop on merge conflicts. An unavailable upstream must leave existing forks intact.

| Project | Initial verification run |
| --- | --- |
| photocraft | [Run #1](https://github.com/storytold-artcraft-forks/photocraft/actions/runs/38897769978) — queued at last check |
| vectorcraft | [Run #1](https://github.com/storytold-artcraft-forks/vectorcraft/actions/runs/38897930980) — queued at last check |
| filmcraft | [Run #1](https://github.com/storytold-artcraft-forks/filmcraft/actions/runs/38897940521) — queued at last check |
| lightcraft | [Run #1](https://github.com/storytold-artcraft-forks/lightcraft/actions/runs/38897976063) — queued at last check |
| pdfcraft | [Run #1](https://github.com/storytold-artcraft-forks/pdfcraft/actions/runs/38897985998) — queued at last check |
| effectcraft | [Run #1](https://github.com/storytold-artcraft-forks/effectcraft/actions/runs/38898008636) — queued at last check |
| designcraft | [Run #1](https://github.com/storytold-artcraft-forks/designcraft/actions/runs/38898030544) — queued at last check |

### How synchronization works

The workflow calls GitHub’s API directly; it does not check out, build, or download the application. It requests only repository contents write permission through the built-in GITHUB_TOKEN; no personal access token is stored. It confirms the original parent, checks for missing upstream commits, creates a unique `preservation/backup-*` branch before any merge, and uses GitHub’s non-forced upstream merge. Independent commits remain in history. If a conflict occurs, `preservation/sync-paused` is created and future runs stop until the owner resolves the conflict and manually removes that marker. No automated branch or repository deletion exists.

All branches were included in the original fork; daily updates target only the default branch. Backup branches are retained indefinitely. Organization and repository Actions settings currently allow execution; the default token permission stays read-only and the sync workflow explicitly requests `contents: write`. Upstream workflow-file changes or branch protection may require owner intervention if GitHub refuses the built-in token; failures leave the backup intact. Public repository schedules can be disabled by GitHub after 60 days without repository activity; check Actions and re-enable the workflow when needed. Scheduled start times may be delayed by GitHub.
