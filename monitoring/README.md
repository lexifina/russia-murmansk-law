<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Murmansk Oblast only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-26 05:43 UTC, Murmansk Oblast: Official Internet Portal of Legal Information (region51): 8 addresses read; 0 added, 0 changed, 0 removed; no change; 0 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Murmansk Oblast: Official Internet Portal of Legal Information (region51)](http://publication.pravo.gov.ru/documents/block/region51) | `zakony-<year>/` | daily | 2026-11-26 05:43 UTC | no change | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-26 05:43](checks/2026-11.md#ru-pravo-murmansk-20261126t054312z) | pravo-murmansk | 8 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-25 06:17](checks/2026-11.md#ru-pravo-murmansk-20261125t061710z) | pravo-murmansk | 8 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-24 14:13](checks/2026-11.md#ru-pravo-murmansk-20261124t141327z) | pravo-murmansk | 8 | 9 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-murmansk-law/compare/4f38f8a3fa89...d455269c257b) |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
