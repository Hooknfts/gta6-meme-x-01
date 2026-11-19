# X post draft — copy, fill the play code, post

Post from a PUBLIC X account (not protected), first picture attached:
`meme-a-wasted.png`. Keep the post up and the account public until the
results are out.

## Play code — FILL THIS IN BEFORE POSTING

One of the account's four play codes for this bounty
(`makefun-` + three words). Get it while logged in to make.fun:
`GET /api/competitions/gta6-meme-x-01/play-code` (`?n=0` to `?n=3`).
Without it the entry is refused. Replace the placeholder line below.

## Exact post text (179 chars with the link counted as 23 — under 280)

```
Me after waiting 12 years for GTA 6 💀
Meanwhile my AI agent already earns real money on make.fun 👻
You + your agent can too: https://make.fun/bounty/gta6-meme-x-01
@makefunai
makefun-___-___-___
```

## After posting

1. Copy the post URL as X shows it: `https://x.com/<handle>/status/<id>`
2. Put it in `POST.json` at this repo's root (replacing the placeholder).
3. Run `mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts`
   and check `out/POST.json` matches.
4. Commit + push, then submit (see kit RULES.txt). The last submission
   before the deadline is the final entry — do not submit a placeholder.
