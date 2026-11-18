# Day 4 — Make Claude Feel Like a Teammate

## Tools used in the video

- **Claude Desktop app (Cowork)** — https://claude.ai (download from bottom-left icon when logged in) — required for Cowork. Top toggle switches between Chat and Cowork.
- **Claude Pro or Max plan** — https://claude.ai/upgrade — Cowork is Pro/Max only. Minimum $20/month Pro plan.
- **Connectors** — in-app: `+ button → Connectors → Manage Connectors → + → Browse connectors`. Hundreds of official Anthropic partners. Secure, standard integrations via MCP.
- **MCP (Model Context Protocol)** — the protocol connectors are built on. You don't need to learn it — just know it's how Claude talks to external apps securely. You'll hear "connectors" and "MCPs" used interchangeably.
- **Google Drive connector** — pulls files, folders, receipts, invoices. The easiest first connector.
- **PostHog connector** — https://posthog.com — website + product analytics. Used for web traffic and conversion data.
- **HubSpot connector** — https://hubspot.com — CRM. Leads, funnel position, conversions.
- **Virtual machine (Cowork sandbox)** — a sandboxed mini-computer inside your computer that Cowork runs on. Has its own temporary file system. Can interact with external services and, in a limited way, your desktop.

## Links referenced

- `claude.ai/upgrade` — plan comparison for Pro vs. Max.
- Samin references `converti.ai` (fictional SaaS Alex works at) for the HubSpot connector authentication.

## Downloads / templates for this day

**GCPS framework — memorize this. Every Cowork workflow uses it:**

```
G — Gather        → Connectors pull context from Gmail, Drive, HubSpot, PostHog, etc.
C — Contextualize → Projects give Claude the system prompt, memory, files.
P — Process       → Cowork plans and executes the workflow autonomously.
S — Standardize   → Skills package the output. Schedules run it. Dispatch controls from phone.
```

**Connector setup checklist (do at least one today):**

```
[ ] Google Drive       — team files, invoices, receipts
[ ] Gmail              — email, notifications
[ ] HubSpot / CRM      — leads, funnel, conversions
[ ] PostHog / analytics — website + product data
[ ] Slack              — team messages
[ ] Notion / Linear    — docs, tickets
```

Screenshot your Cowork session after the connector is authenticated and drop it in `artifact/day-04-first-connector.png`.

## Further reading

- **MCP spec** — https://modelcontextprotocol.io — if you actually want to understand what's under the hood. Not required for this course.
- **Anthropic's connector directory** — browse the full list inside the app under Browse Connectors. Hundreds of options, more added regularly.
