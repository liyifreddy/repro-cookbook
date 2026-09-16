# Contributing

Three kinds of contribution, in order of usefulness:

1. **A correction.** You ran an existing entry and got a different number,
   or found the blocker was wrong. Open an issue with your hardware, the
   commit you used and what you saw. Or edit the entry directly in a PR.
2. **A new entry.** Copy `entries/_TEMPLATE.md` (or the dataset / demo
   template), fill in only what you actually ran, leave the rest blank.
   Add a row to the README table. Put your changes under `code/<slug>/`
   as patches; do not vendor upstream code.
3. **A dataset card.** Read the license file, not the README badge, before
   filling in the license table.

Rules that keep the repository useful:

- Every number must come from a run you did. Blank beats estimated.
- One entry per paper or dataset. If you re-ran something, add a section
  to the existing entry with your hardware and date.
- Keep it short. The two starred sections are the point.
- Add yourself as `Contributor:` in the entry header.
