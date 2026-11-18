# Day 7 — Put Work on a Schedule

## Tools used in the video

- **Claude Scheduled Tasks** — runs any prompt or skill on a cron schedule (hourly, daily, weekdays, weekly). Found in the Schedule section of the Claude app. https://claude.ai <!-- verify URL -->
- **Claude Dispatch** — lets you send tasks from the Claude mobile app to your desktop so the heavy lifting runs on your main machine. Accessed via the Claude iOS/Android app. https://claude.ai/dispatch <!-- verify URL -->
- **Claude mobile app** — iOS and Android. Needed for Dispatch. App Store / Google Play.
- **Gmail connector** — already wired up from Day 5, used here to send scheduled report emails.

## Links referenced

- Schedule section — sidebar inside the Claude app, look for "Schedule."
- `/schedule` command — works inside any Cowork chat as an alternative to the form.
- Claude iOS app — https://apps.apple.com <!-- verify URL -->
- Claude Android app — https://play.google.com <!-- verify URL -->

## Downloads / templates for this day

Quick scheduled-task setup (paste in the prompt field when creating a new task):

```
Run /weekly marketing report, then send the final deck as an email to the CEO
at ceo@yourcompany.com with a one-paragraph summary of the highlights.
```

Schedule-from-Cowork prompt (works inside any chat with `/schedule`):

```
Can you make it so you're running the weekly marketing report skill every
Monday at 1pm EST. Send the output by email to the CEO.
```

## Further reading

- Why people use Mac minis for always-on automation — any "headless Mac mini server" writeup. Samin mentions this on camera as the reason scheduled tasks become bulletproof.
- Dispatch deep-dive — Samin's YouTube video on Cloudbot / Claude on phone covers the full mobile flow if you want to go deeper before Day 8.
