# Obsidian synchronization test

- Test ID: orchestration-roundtrip-2026-10-07
- Repository: auric007/orchestration
- Branch: main
- Created on the GPU server: 2026-10-07, 18:12 IST.
- Purpose: check Markdown synchronization only; do not run an experiment.

## Server to laptop

This note was created in `/sfs/end_to_end/experiments/sync-test.md`.
After your laptop pulls it, open `Projects/orchestration/experiments/sync-test`
in Obsidian.

## Laptop to server

Laptop response: Hello from Obsidian — saved on my laptop.

On your laptop, replace the line above with:

> Laptop response: Hello from Obsidian — saved on my laptop.

Save the note and let the laptop automation commit and push it. Once that
commit reaches GitHub main, the server service should pull it on its next
successful cycle (approximately one minute). The return trip is not verified
until the edited line appears on the server.

## Mac background sync verification

- Verification edit saved on the Mac at 2026-10-07 18:33:37 IST.
- Purpose: verify that the scheduled company notes job uploads this saved Markdown without a manual Git command.
- No experiment was launched.


