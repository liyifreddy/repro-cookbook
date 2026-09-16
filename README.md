# repro-cookbook

Reproduction reports, dataset cards and working demos for robot learning and
vision. Each entry answers what the paper and the official README skip: what
it takes to set up, what it costs, whether the numbers match, and where the
method stops working.

Use it to decide in ten minutes whether something is worth your week.

## Papers

| Paper | Claim | Status | Hardware | Report |
|---|---|---|---|---|
| | | | | |

## Datasets

| Dataset | Used by | License | Size | Status | Card |
|---|---|---|---|---|---|
| | | | | | |

## Demos and experiments

| What | Built on | Result | Dir |
|---|---|---|---|
| | | | |

**Status** — ✅ runs / available · ⚠️ partial · ❌ blocked (with the exact blocker)

## How entries are written

- Every entry was run. Failures are entries too, with the blocker named.
- Numbers come from the recorded run, with hardware and config. Where they
  differ from the paper, the entry says so.
- Upstream code is not vendored. `code/<slug>/setup.sh` clones the original
  at a pinned commit and applies `patches/`. Data files are never committed;
  dataset cards say where to get them and what the license allows.
- Each entry has a time box. If it does not run inside it, the blocker is
  recorded and the entry stops there.

## Contributing

Ran something that is not here, or got a different number? Open a PR using
`entries/_TEMPLATE.md`, or an issue with your hardware and the blocker.
Corrections to existing entries are the most useful kind of contribution.
See `CONTRIBUTING.md`.

## Cite

If an entry saved you time, cite the repository (`CITATION.cff`) or link
back to the entry.
