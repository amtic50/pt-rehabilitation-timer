# PT Rehabilitation Timer

A single-file exercise timer for physiotherapy rehabilitation — hold/rest
countdowns with voice announcements and beeps, adjustable sets, reps, holds
and cycles.

**Live:** https://amtic50.github.io/pt-rehabilitation-timer/

## v2 features

- **Saves everything locally** (localStorage): timer settings, routine edits,
  reminders and history. Last-used values are restored on load; defaults only
  on first run. No account, no cloud.
- **Day-wise log + streak:** finishing a routine logs the date, exercises and
  time; last 7 days and last 30 days are shown, with a consecutive-days streak.
- **Export / Import:** local JSON backup download and restore.
- **Installable (PWA):** manifest + service worker, works offline after the
  first visit.
- **Accurate timer:** deadline-based countdown (stays right when the tab is
  throttled) + screen Wake Lock while a routine runs.
- **How-to cues** under each exercise name, plus a stop-if-sharp-pain note.
- **Edit routine:** rename, reorder, remove and add exercises without
  touching code.
- **Time estimate** shown before starting.
- **Morning/evening reminders** (07:00 / 18:00 by default, toggleable).
  Reminders fire while the app is open; true background reminders need a
  server and are not included.

## Default routine

Standing Lumbar Extension (1×10, 3s) · Prone Press-Up (1×10, 5s) ·
Glute Bridges (2×10, 5s) · Seated Chin Tucks (1×10, 5s) ·
Shoulder Blade Squeezes (1×10, 5s).

## Privacy

Everything stays on the phone (localStorage). Nothing is uploaded anywhere.
