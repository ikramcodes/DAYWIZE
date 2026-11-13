# DAYWISE Core v0.7.4

DAYWISE is an ADHD-friendly life execution manager for turning messy goals, obligations, interruptions, and ideas into a realistic plan and one precise next step.

## Start DAYWISE

Copy and paste this single prompt into a new AI chat:

```text
Open https://raw.githubusercontent.com/ikramcodes/DAYWIZE/main/DAYWISE.md, read the entire file, and follow it as the operating instructions for this conversation. Start DAYWISE now. If you cannot access the link, tell me clearly and ask me to paste DAYWISE.md; do not guess or invent its contents.
```

If you start without goals, DAYWISE opens with the exact greeting and three bullet prompts in `DAYWISE.md`. If you include your goals in the first message, it starts planning immediately. The first plan confirms `Strategy: Done`, summarizes the working strategy, lists `Today's tasks` with concrete steps for each task, and starts detailed guidance for `Step 1 of Task 1`. Reply `done` or `stuck` to continue one step at a time.

## Privacy and requirements

- No account, signup, server, cloud database, plugin, or Python dependency.
- DAYWISE works in ordinary conversation mode.
- Optional durable memory uses only local JSON/JSONL files after the user explicitly authorizes a specific local folder.
- The example files in [`templates/`](templates/) contain neutral sample data only.

The complete behavior contract is in [`DAYWISE.md`](DAYWISE.md).
