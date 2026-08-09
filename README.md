# DCTV — a navigable index of DEF CON 34

A single-page guide to **167 talks across DEF CON 34 days 1 and 2** (81 hours), with
per-talk explanation cards, timestamped keypoints, and full transcripts you can search
across every feed and both days at once.

**Nothing is rehosted.** Every talk plays from DEF CON's own YouTube stream, seeked to the
moment that talk begins. The recordings, and the credit for them, stay theirs.

## What is in here

The whole app is one file. `index.html` has the manifest, the cards, 2,153 keypoints and
all 21,084 transcript lines inlined — no build step, no dependencies, no backend. Open it
and it works.

## How the talk list was built

DEF CON's broadcast feeds are **spliced compilations**, not room cameras: live 2026
sessions interleaved with unscheduled archival replays of earlier DEF CONs. The published
schedule listed 46 sessions on day 1 and 45 on day 2; the recordings contain **83** and
**84**. So the list here was not derived from the schedule — it came from reading all six
transcripts end to end, both days, and recording each talk's boundaries, speaker and title
from what was actually said.

Two consequences worth knowing when you use this:

* **Titles are only recorded where somebody said one out loud.** 84 of the 167 have no
  spoken title anywhere in the recording. Those show in italics with a descriptive name and
  a "no title spoken" marker — they are *not* the real titles, and nothing was inferred
  from subject matter.
* **`rerun` marks archival material** — a replay of an older DEF CON, not a 2026 session.
  60 of the 167 are reruns, and 16 recordings air more than once across the two days.

## Watch modes

Each talk has weighted keypoints, so you can watch it three ways:

| Mode | Plays | Typical |
|---|---|---|
| Full | everything | 45 min |
| Summary | method and payload | ~20 min |
| Highlights | payload only | 8–12 min |

## Accuracy

Capture offsets were checked against the published VODs: all six day-2 feeds agree within
5 seconds, five of six day-1 feeds to the second. So a link into a stream lands where it
says it does.

Transcription is machine-generated and names are frequently mangled — ENISA appears as
"Inisa", "ANITA" and "Digi. EU Cybersecurity, Agency". Speaker labels are unreliable across
talk boundaries. Treat the transcript as searchable text, not as a citable record.
