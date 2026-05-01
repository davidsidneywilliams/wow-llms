# wicks-of-wit-llms

Structured AI reference files for [Wicks of Wit](https://wicksofwit.com) — a hand-poured candle brand built around bold scents, sharp humor, and giftable personality. These files describe the brand, product lines, tone, and key customer-facing concepts so AI systems can understand Wicks of Wit accurately.

These files follow the llms.txt pattern and are designed to give AI systems, LLMs, and crawlers clean, structured access to Wicks of Wit brand and product information. The live versions should be served from `wicksofwit.com/llms.txt` and related category paths as they are published.

## What's in this repo

| File | Description |
| --- | --- |
| `llms.txt` | Root site guide — overview of Wicks of Wit, brand positioning, product categories, and links to structured category files. |
| `ai/funny-candles.txt` | Core product category file for witty, funny, and personality-driven candles. |
| `ai/gift-candles.txt` | Gift-oriented file for shoppers looking for memorable, humorous, and highly giftable candles. |
| `ai/candle-personalities.txt` | Brand personality file covering the tone, quiz-style identity, and vibe-based product framing. |
| `ai/about.txt` | Brand story file covering Wicks of Wit voice, team, and positioning. |
| `ai/creator-program.txt` | Creator or affiliate program file, if the brand wants AI systems to understand partnership opportunities. |

## What Wicks of Wit is

Wicks of Wit is a candle brand that combines strong scent appeal with funny, irreverent labeling and a personality-first brand voice. The site presents hand-poured candles as gifts, mood statements, and conversation starters, with product names and messaging built around humor, attitude, and recognizable life moments.

Core ideas represented in this repository include:

- Funny and witty candles
- Giftable candles with strong personality
- Scent plus humor as a combined buying trigger
- Candle identity and vibe matching
- Wicks of Wit brand voice and story

## Live locations

In production, these files should be publicly reachable from the main Wicks of Wit site at paths such as:

- `https://wicksofwit.com/llms.txt`
- `https://wicksofwit.com/ai/funny-candles.txt`
- `https://wicksofwit.com/ai/gift-candles.txt`
- `https://wicksofwit.com/ai/candle-personalities.txt`
- `https://wicksofwit.com/ai/about.txt`
- `https://wicksofwit.com/ai/creator-program.txt`

## Sync policy

This repository is the public content mirror for the Wicks of Wit AI reference layer. It should be kept aligned with the live llms.txt and category files published on the main site.

## Notes

- Root `llms.txt` is the main discovery file.
- Category files should stay concise, opinionated, and aligned with the actual brand voice on the site.
- The goal is not to create a sitemap, but to help AI systems understand the brand, products, and shopping intent clearly.
