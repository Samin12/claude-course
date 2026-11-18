# Day 3 — Your First Project: Make Claude Do Real Work

## Tools used in the video

- **Claude Projects** — https://claude.ai (sidebar → Projects → New Project) — a scoped workspace with its own system prompt, uploaded files, and memory. Every chat inside the project inherits the context.
- **System prompt / Custom Instructions** — the Instructions field on every project. Inserted before every message Claude sees. Sets role, tone, format rules.
- **Claude Artifacts** — the side-panel where Claude builds documents, charts, diagrams, and interactive tools. Make sure this is toggled on in Settings → Capabilities (from Day 2).
- **Interactive chart artifacts** — new Claude Chat feature. Pie charts, bar charts, and other visualizations rendered directly in the chat from your data.
- **Google Slides export** — one-click button on deck artifacts. Opens the deck in your browser, fully editable in Google Slides.
- **Publish artifact** — top-right of an artifact → Publish → share with team or publish to web. Gives you a public URL anyone can open and interact with.
- **Extended Thinking toggle** — flip on for big reasoning or coding tasks (like building the interactive widget). More expensive, slower, but noticeably better for heavy work.

## Links referenced

- `converti.ai` — Alex works at this (fictional) B2B SaaS. Used as the brand-voice reference Claude looks up when building the deck. Substitute your own brand URL.
- Samin's community classroom — referenced as a place he drops interactive Claude artifacts as guides for members. Uses the exact same publish-artifact flow.

## Downloads / templates for this day

**System prompt template (copy, edit, paste into your Project Instructions):**

```
Hey, I'm the [your role] at [your company / team].

I need sharp, data-first answers.

- Lead with the number of findings, then the reasoning.
- Use bullet points, not long paragraphs.
- When you give me recommendations, give me the one you actually believe. Do not hedge.
- Make visualizations as much as you can to explain what you mean.
- Match our brand voice — [describe it in 3–5 words].
- Be direct, confident, no fluff.
```

**Prompts Alex used (copy, adapt for your own data):**

```
Prompt 1 — P&L breakdown:
Hey, I just uploaded all of our credit card statements, ad platform receipts, 
and revenue data. Break down the profit and loss for me, please. Show me two 
pie charts — one for revenue by source, one for expenses by channel.
```

```
Prompt 2 — What's actually working:
Based on all this data, where are we right now? What's actually working and 
what's not? I want to know which channels per marketing spend are bringing 
in the most leads so we can double down on that channel. Build me some 
visualizations.
```

```
Prompt 3 — Build the deck:
With all this data, build me a presentation (an artifact) based on our brand 
guidelines — you can look it up from [your brand URL]. Cover the P&L, key 
findings, recommendations, and where to shift our budget to. Make it clean — 
this is going to the CEO tomorrow.
```

```
Prompt 4 — Interactive widget (turn on Extended Thinking):
Build me an interactive budget reallocation tool I can share with my CEO. 
Show our Q1 spending by channel versus the recommended reallocation. Let the 
user drag sliders to adjust the budget split between paid ads and organic, 
and show real-time the projected changes in leads, conversions, and cost per 
acquisition based on our Q1 performance data. Match our brand guidelines, 
and the CEO should be able to play with these numbers on the widget.
```

## Further reading

- **Anthropic docs on Projects** — search "Claude Projects" in Anthropic's help center for the official feature overview.
- **Publish artifact gallery** — scroll through Claude's public artifact gallery (accessible from the publish flow) to see what other people have built as interactive tools.
