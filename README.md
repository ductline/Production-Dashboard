# Ductline production board

Fabrication planning board for Ductline Manufacturing, Hyderabad.

Open `index.html` in any browser. No build step, no dependencies, no server.

## What it does

Tracks every live fabrication job through five stages:

| Stage | Ball is with |
|---|---|
| Part list to prepare | Our drawing office |
| With client for approval | The client |
| Cleared to make | The shop floor |
| In production | The shop floor |
| Ready to dispatch | Dispatch |

Each job shows how many days it has sat at its current stage. Anything over
five days is flagged. Set a target date and the row turns red once it passes.

Sq m, gauge, target date and shop notes are editable. Stage totals add up the
sq m you enter.

## Entering sq m

Sq m and gauge start blank by design. Those figures live in the part-list and
PO attachments, not in the email text the job list was built from. Fill them
from the part list once per job.

## Where the data lives

Everything typed into the board is saved in that browser's local storage only.
It does not sync between people or devices. Two people opening the board keep
separate figures.

To make it a shared board the whole shop updates, the job data needs to move to
a hosted store.

## Job list

Seeded from the info@ductline.in mailbox on 13 October 2026 — 20 jobs across
TAP Engineering, KNND Associates, Star Airwell, Comfonomics, Sobha, Magnacool,
Airwell Engineering, Tootmnetech and Hanuman Enterprises.

To refresh the list against current mail, ask Claude to rebuild the `JOBS`
array in `index.html`.

## Note on visibility

This repository contains client names, project names and PO numbers. Keep it
private.
