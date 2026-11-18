# Day 8 — Let Claude Scrape the Web for You

> **Today's pain:** Some of the sites your job depends on have no Claude connector — and Claude can't visit them raw.
>
> **Today's action:** Give Claude a safe browser it can use, so it can scrape hotel prices, product listings, anything — and put it on a schedule.
>
> **Time:** ~15–20 minutes (watch + do)

---

## Watch

Video: `00:54:00` → `01:04:00` (see `video-section.md` for the transcript slice).

## Why this matters

You've now got Dispatch on your phone, scheduled tasks running weekly, and skills wired up. But one of Converti's clients — a travel agency — needs hotel prices scraped from Booking.com, Expedia, and Hotels.com every morning. Those sites don't have connectors. There's no Booking.com toggle. And if Claude tries to visit them raw, CAPTCHAs and bot detectors shut it down. Today's about giving Claude a safe, isolated browser so it can scrape anything on the internet — then scheduling it so the data just shows up.

## Step-by-step

1. **Install the Claude Chrome extension (quick option).** Google "Chrome Web Store," search Claude, install the extension. Log in, pin it to your toolbar. Click the icon, hit "I understand" through the walkthrough, and turn on **Act without asking** + **Enable fast mode**. Now Claude can drive your browser. Prompt it: "Open Google Flights and Booking.com." It works, but heads up — it's slow, eats tokens, and it's touching your real browser with all your logged-in accounts. Not ideal for anything serious.
2. **Or turn on Claude in Chrome as a connector.** Inside Cowork, hit the plus button, go to Connectors, flip on **Claude in Chrome**. Same powers, wired into your Cowork project.
3. **Understand why we're switching to FireCrawl.** Giving Claude your real browser is like handing an AI agent the keys to your car — Gmail, banking, passwords, everything. We want Claude to have its own car. FireCrawl is a sandboxed, dedicated browser that's isolated, private, and controlled. It stays logged in to services on its own, so sessions persist without touching yours.
4. **Sign up for FireCrawl.** Go to firecrawl.dev. The free plan works for most people starting out. Grab your API key from the dashboard.
5. **Install the FireCrawl MCP in Claude.** Google "FireCrawl MCP" and copy the install string. Back in Claude, go to Customize, hit the plus button, pick **Add custom connector**, name it "firecrawl," paste the install string, and paste your API key. Hit add. Flip it to **always allowed** so you don't get prompted every time.
6. **Run your first scrape.** New task in Cowork, pick the right project, then prompt: "Use FireCrawl to scrape hotel listings near the LA Convention Center on Booking.com for April 20th to 24th. Pull names, star ratings, room types, prices, any discounts. Organize into a clean table."
7. **Layer scheduling on top.** Switch to Opus (the request is compound). Ask: "Schedule this to run every morning at 6am. Save the log as LA-Hotel-Tracker.csv in my Drive. Compare today's price to yesterday's — if anything drops more than $30, flag it." Now every morning, the data just shows up.

## Try it yourself

Pick one website you refresh manually (a competitor's pricing page, a jobs board, a product page). Set up FireCrawl, write one scraping prompt, and schedule it daily. Goal: never manually check that URL again.

## Common stuck points

- **Using the Chrome extension for real work.** It works, but it's slow, token-heavy, and shares your real browser session. Fine for one-off testing. Bad for recurring jobs. Move to FireCrawl.
- **Pasting the wrong API key or skipping the "always allowed" toggle.** If FireCrawl doesn't show up as usable in connectors, it's almost always one of these two. Re-paste the key, confirm the toggle.
- **Scheduling without specifying output.** "Scrape hotels every morning" leaves Claude guessing. Tell it the file name, the folder, the comparison logic, what counts as a flag. The scheduler only runs what you wrote.

## Key takeaways

- Browser-access mode (extension or Claude in Chrome connector) is fine for exploring. It's not how you run production work — too slow, too token-heavy, too much exposure to your personal accounts.
- FireCrawl gives Claude its own sandboxed browser. Isolated from your Gmail, your banking, your passwords. Sessions persist so authenticated scraping keeps working.
- Adding a custom MCP connector is a 5-minute setup: install string, API key, always-allowed toggle. Same pattern works for any MCP in the ecosystem, not just FireCrawl.
- For compound requests (scrape + schedule + save + compare + alert), switch to Opus. Sonnet will try and miss steps.
- Once FireCrawl is wired in, Claude can read basically any public site on the internet on a schedule. That's the last piece — now nothing on the web is off-limits.

## Resources

See `resources.md`.

## What you'll build

`artifact/` should hold the first CSV or spreadsheet FireCrawl produced (hotel prices, competitor listings, whatever you chose) plus a screenshot of the scheduled task that fires it every morning. That's your proof you've got daily data flowing in without touching the machine.

## Next up

Day 9 →
