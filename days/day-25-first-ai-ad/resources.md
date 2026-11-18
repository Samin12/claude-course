# Day 25 — Make Your First AI Ad

## Tools used in the video

- **HeyGen** — [heygen.com](https://heygen.com) — AI video generation platform with avatars and the Seedance 2.0 model for ads.
- **Seedance 2.0** — [heygen.com](https://heygen.com) — HeyGen's newest video model; what actually renders the ad.
- **Composio** — [composio.dev](https://composio.dev) — the connector layer that lets Claude talk to HeyGen (and a few hundred other apps).
- **Claude** — [claude.ai](https://claude.ai) — where you send the prompt that kicks the whole thing off.

## Links referenced

- HeyGen Developers / API dashboard — inside HeyGen, sidebar → Developers → API dashboard.
- Composio Connect Apps — [app.composio.dev](https://app.composio.dev) <!-- verify URL -->
- Converti (Samin's product, used as the ad example) — https://converti.ai

## Downloads / templates for this day

Starter prompt — paste into Claude, swap in your product:

```
Hey, can you use the Composio connector and through that use HeyGen,
and from there use the Seedance model.

With the Seedance model, I want you to make an ad for [PRODUCT NAME].
[PRODUCT NAME] is basically [one-line description of what it does].

Make an ad about how [CUSTOMER TYPE] is dealing with [PAIN POINT],
and then [FRIEND / PEER] shows them [PRODUCT NAME]. After they use it,
they're really happy because now [OUTCOME].

Make the video and then send me the link or download it.
```

## Further reading

- HeyGen's Omni-reference docs — how to feed logos and brand assets into Seedance so the video actually uses your branding. <!-- verify link -->
- Facebook Ads Library — [facebook.com/ads/library](https://facebook.com/ads/library) — scroll competitors' ads to steal structure and angles before you write your own prompt.
