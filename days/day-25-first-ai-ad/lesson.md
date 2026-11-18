# Day 25 — Make Your First AI Ad

> **Today's pain:** You've got something to sell, but nobody's seeing it.
>
> **Today's action:** Generate your first AI ad creative (image + copy) end-to-end.
>
> **Time:** ~15–20 minutes (watch + do)

---

## Watch

Video: `03:56:46` → `04:00:00` (see `video-section.md` for the transcript slice).

## Why this matters

Content and video ads used to cost thousands and take weeks. Now you can spin up a real video ad — script, voiceover, visuals — in a few minutes by wiring HeyGen into Claude through Composio. This is where all the setup from the last few weeks pays off: you describe the ad, Claude builds it.

## Step-by-step

1. **Sign up for HeyGen.** Head to [heygen.com](https://heygen.com) and make an account. HeyGen just released Seedance 2.0 and the results are honestly pretty crazy.
2. **Grab your HeyGen API key.** Inside HeyGen, click **Developers** in the sidebar, then **API dashboard** on the bottom left. Hit **Create API key**. Name it something obvious like "for creating video ads" and mark that it's for an agent so they know what's up.
3. **Connect HeyGen to Composio.** Go back to Composio, hit **Connect apps**, find HeyGen, paste the API key, and click connect. Composio is already wired into Claude as a connector from earlier in the course, so you're good.
4. **Open Claude and write your ad prompt in plain English.** Something like: "Can you use the Composio connector, and through that use HeyGen, and with the Seedance model make an ad for [your product]." Describe the scenario you want — the pain, the fix, the happy ending. Samin's example: an HVAC company missing calls, a friend shows them Converti, and now AI handles every call.
5. **Tell it how to deliver the result.** End the prompt with "send me the link or download the video." Hit go and wait.
6. **Watch the output and note what's off.** Samin's first ad mispronounced the product name because he didn't say it clearly — and it didn't use his logos. That's fine. You iterate.

## Try it yourself

Write a 3-sentence scenario for an ad for your own product or a client's — pain, fix, happy ending. Drop it into Claude with the Composio + HeyGen prompt above. Render one video today. Don't polish it. Just ship one.

## Common stuck points

- **HeyGen API key not connecting in Composio.** Double-check you copied the full key and that it's the API key, not the organization token. Reconnect HeyGen from Composio if it still won't take.
- **Pronunciation errors in the voiceover** (like a product name said wrong). Spell your brand phonetically in the prompt, or add a line that tells Seedance exactly how to say it.
- **No logos or brand assets in the video.** Seedance with Omni-reference can pull your brand context in, but you have to feed it the logo. Attach your logo file or link to your brand page in the prompt.

## Key takeaways

- Claude + Composio + HeyGen = one prompt turns into a finished video ad.
- Describe the pain, the fix, and the happy ending in plain English. That's the script.
- First output won't be perfect. Mispronounced brand names and missing logos are normal — you iterate.
- Once the pipeline works for one ad, you can put it on a schedule and crank out variations.
- The skill isn't video editing anymore. It's writing a clear prompt and wiring the right tools together.

## Resources

See `resources.md`.

## What you'll build

Drop the rendered video (or a link to it) plus your prompt into `artifact/` so you can remix it next week.

## Next up

Day 26 →
