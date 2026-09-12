# poker-shalmanim

Source of truth for Potter / הדילרAI poker state for the WhatsApp group שלמנים ב50.

Agents read and write these files. Do not invent missing fields, player names, phones, or a match date.

| File | Role |
| --- | --- |
| `introduction.md` | First lines of every WhatsApp message. Do not skip. |
| `next-match.yaml` | Next match date, time, host, location, and status. |
| `approvers.yaml` | Coming / Out / TBD from the poll for that match date. |
| `unapproved-responses.yaml` | Per-player nudge/roast state machine for anyone not on Coming. |
