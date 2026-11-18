# Day 7 — Put Work on a Schedule

> **Today's pain:** Even with a one-click button, you still have to remember to click it every week.
>
> **Today's action:** Schedule your workflow so it runs on its own — every Monday at 7am, no input from you.
>
> **Time:** ~15–20 minutes (watch + do)

---

## Watch

Video: `00:45:01` → `00:54:00` (see `video-section.md` for the transcript slice).

## Why this matters

So far you've gathered context, processed it into a deck, and packaged it into a one-click skill. That's huge. But you're still the trigger. Every Monday you'd have to open your laptop, open Cowork, type the slash command, and wait. The work is automated — starting the work isn't. Today we fix that. Scheduled tasks are the last step that pulls you out of the loop entirely.

## Step-by-step

1. **Open the Schedule section.** In the Claude app, click Schedule in the sidebar. You'll see a panel for scheduled tasks. One thing you need to know up front — these only run when your computer is awake. That's why a lot of people are buying Mac minis and just leaving them on 24/7.
2. **Hit new task and name it.** Something like "Run weekly marketing brief." Be a bit descriptive — future you will thank you.
3. **Write the prompt the task will run.** Type a slash and your skill will show up — pick `/weekly marketing report`. Add the follow-up: "Then send the output as an email to the CEO, his email is ceo@yourcompany.com." Because your Gmail is already connected from Day 5, Claude can actually send it.
4. **Pick frequency and folder.** Hourly, daily, weekdays, weekly — pick one. Weekly, Monday, 9am is the Alex default. And a big one: match the task to the right project folder. If you've got multiple clients, each one gets its own schedule. Hit save. Done — runs every Monday at 9am from now on.
5. **(Alternative) Schedule from inside Cowork with `/schedule`.** Go back to any Cowork chat, type `/schedule`, and say in plain English: "Run the weekly marketing report skill every Monday at 1pm EST." Hit go. Claude is smart enough to find the skill in your database, wire it up, and create the scheduled task without you having to click through the form.
6. **Check the schedule panel to confirm.** Go back to Schedule, you'll see the new task, next run time, the instructions it's going to fire. You can edit, pause, or delete any of it from there.

## Try it yourself

Pick one skill you built yesterday and put it on a weekly schedule. Match it to the right project folder. Make sure your laptop will be awake when it runs (or budget for a Mac mini if you want this to be bulletproof).

## Common stuck points

- **Computer asleep when the task fires.** Scheduled tasks do not run if the machine is off. This is the number one reason people think "it didn't work" — it did, you just weren't listening.
- **Wrong folder attached.** If you've got multiple projects and your schedule isn't matched to the right one, Claude pulls the wrong context. Always double-check the folder dropdown.
- **Too-vague prompt.** "Run the report" isn't enough. The scheduled task has to be as specific as the manual prompt — what skill, what output, where it goes. Treat it like leaving instructions for a new hire.

## Key takeaways

- Scheduled tasks are the layer that removes you as the trigger. You built the skill. Now it runs itself.
- Two ways to schedule: the Schedule panel (form-based, easiest for first-timers) or `/schedule` inside any Cowork chat (faster once you know what you want).
- Your computer must be awake when the task fires. Mac mini parked on a shelf is the most common setup for people who take this seriously.
- Always match each scheduled task to a project folder — that's how Claude keeps context clean across multiple clients or businesses.
- This is where Alex stops thinking about Monday reports. Every Monday at 9am, the deck is just done.

## Resources

See `resources.md`.

## What you'll build

`artifact/` should hold a screenshot of your first scheduled task in the Schedule panel — name, frequency, prompt, folder. When it runs the first time, drop a second screenshot in there of the output it produced. That's proof the loop closed without you touching it.

## Next up

Day 8 →
