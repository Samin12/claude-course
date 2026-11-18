# Day 3 — Your First Project: Make Claude Do Real Work

> **Today's pain:** You're staring at a pile of data and a deadline, and Claude feels like just a chat box.
>
> **Today's action:** Create a Claude Project, drop in your files, write a system prompt, and build a branded deck + interactive widget.
>
> **Time:** ~15–20 minutes (watch + do)

---

## Watch

Video: `00:09:57` → `00:23:04` (see `video-section.md` for the transcript slice).

## Why this matters

This is where Claude stops feeling like a chatbot and starts feeling like a workstation. Alex's CEO just said: "we're spending too much on paid ads. Pull the P&L, figure out where to reallocate, present tomorrow morning." Data is scattered across credit card statements, ad platforms, CRM, five revenue sources. Instead of doing it by hand, Alex sets up a Project — system prompt, files, memory — and Claude does the reading, the math, the charts, the deck. This is Level 1 of the course, and it already replaces hours of work.

## Step-by-step

1. **Create a new Project.** Open the sidebar in the Claude Desktop app, hit **Projects**, then **New Project**. Name it something concrete — Alex named his `PL for boss`. Give it a short description ("create a P&L and see where we should allocate budget for next quarter").
2. **Write a system prompt in the Instructions field.** This is the text that gets inserted before every message in this project. Set the role, the tone, the rules. Alex's was:
   > "Hey, I'm the marketing manager at a B2B SaaS company. I need sharp, data-first answers. Lead with the number of findings, then the reasoning. Use bullet points, not long paragraphs. When you give me recommendations, give me the one you actually believe, and do not hedge. Make visualizations as much as you can. Match our brand voice — be direct, confident, no fluff."
   
   Write one once, it shapes every conversation in this project.
3. **Drag all your files in.** Credit card statements, ad platform receipts, revenue data, CRM exports — drag them into the Project files area. Claude ingests each one. Now it has the context it needs without you pasting anything.
4. **Ask for the P&L and charts.** In a new chat inside the project, type something like:
   > "Hey, I just uploaded all our credit card statements, ad platform receipts, revenue data. Break down the P&L for me. Show me two pie charts — one for revenue by source, one for expenses by channel."
   
   Switch the model from Opus to **Sonnet** — you don't need Opus for this. Hit go. Claude reads the files, builds interactive pie charts right in the chat. That's the new chart artifact feature — use it for anything you need to visualize.
5. **Ask the follow-up that actually matters.** Once you can see the data, the next question almost always writes itself:
   > "Based on this data, where are we right now? Which channels per marketing spend are bringing in the most leads so we can double down? Build me visualizations for that."
   
   In Alex's case, meta ads burned $27k for $1,200 back. YouTube spent $1,350 and pulled $9,600. Blog and Instagram same shape. The answer: cut meta, double down on organic.
6. **Build the deck.** Once the insights are there, ask Claude to package it:
   > "With all this data, build me a presentation artifact based on our brand guidelines (look it up from converti.ai). Cover the P&L, key findings, recommendations, and where to shift the budget. Make it clean — this is going to the CEO tomorrow."
   
   Claude builds a branded slide deck. Export it to Google Slides with one click from the artifact menu — now you can edit it in your browser.
7. **Level it up — build an interactive widget.** Instead of a static deck, ask for something the CEO can play with:
   > "Build me an interactive budget reallocation tool I can share with my CEO. Show Q1 spending by channel vs. recommended reallocation. Let the user drag sliders to adjust the paid-vs-organic split, with real-time projected changes in leads, conversions, and CPA based on our Q1 data. Match our brand guidelines."
   
   For a build this big, flip on **Extended Thinking** so Claude actually reasons step by step. Hit go, wait.
8. **Save and publish the artifact.** Top-right of the artifact → **Save as artifact** → **Publish artifact** → choose "share with team" or "publish to web." You get a public link anyone can open and interact with. This is how you ship interactive tools without writing a single line of code.

## Try it yourself

Pick one recurring task from your own work — a report, a spreadsheet breakdown, a summary you build every month. Create a Project for it today. Write the system prompt. Drag in whatever files you have. Ask Claude for the output you'd normally build by hand. Screenshot the result and drop it in `artifact/`.

## Common stuck points

- **Skipping the system prompt.** This is where most people miss the leverage. Without it, Claude hedges and gives you mushy answers. Tell it who you are, what voice to match, and how to format output. Every conversation in the project inherits this.
- **Leaving the model on Opus by default.** For chart building and analysis, Sonnet is fast enough and way cheaper on your rate limits. Only bump to Opus (or turn on Extended Thinking) for big reasoning tasks like building the interactive widget.
- **Treating every conversation as one-shot.** Projects exist because the same task repeats. If you're rebuilding the system prompt each time, you're doing it wrong.
- **Forgetting about artifacts for sharing.** Published artifacts give you a shareable URL for interactive tools. Most people don't realize they can ship polished widgets to non-technical teammates with no code.

## Key takeaways

- Projects = system prompt + files + memory. Write the prompt once, shape every conversation automatically.
- Drag files in instead of copy-pasting. Claude reads them directly in context.
- Sonnet for most work. Flip on Extended Thinking for big reasoning or coding tasks like interactive widgets.
- Artifacts aren't just text — they're charts, decks, interactive tools. Publish them to share a live link with your team or boss.
- Chat is still Level 1. It hits a ceiling the moment work starts repeating — that's Day 4.

## Resources

See `resources.md`.

## What you'll build

By end of today you'll have: a working Project with a system prompt, files ingested, a P&L with pie charts, a branded slide deck (exported to Google Slides), and an interactive reallocation widget with a public share link. Drop screenshots and the published artifact URL into `artifact/`.

## Next up

Day 4 →
