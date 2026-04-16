# am i cooked? 🔥

> a 5-question reality check for founders in denial

[![Built with Claude](https://img.shields.io/badge/built%20with-claude-D97706)](https://claude.ai)
[![Next.js](https://img.shields.io/badge/next.js-15-black)](https://nextjs.org)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

**[amicooked.web-skyline.com](https://amicooked.web-skyline.com)**

answer 5 honest questions. get your status. share the pain.

- 🥩 **RAW** — you haven't even started
- 🔥 **MEDIUM** — you're cooking, don't stop
- 🍖 **WELL DONE** — you're doing real shit
- 💀 **BURNT** — take a walk. maybe delete twitter.

## why this exists

built in one evening with claude as my co-founder.
part of my "ship something every day with ai" experiment.

it's a meme. it's also kinda true.

## how it works

1. 5 questions about your startup (users, runway, last ship, sleep)
2. score 0-15 maps to one of 4 statuses
3. satori generates a shareable 1200x1200 badge as og:image
4. share link in X → followers see the badge → click → their own quiz → viral loop

## stack

- next.js 15 (app router)
- typescript + tailwind
- satori for og image generation
- zero dependencies, zero api calls, zero cost

infra cost: €0/month. runs on a shared hetzner vps.

## run locally

\`\`\`bash
npm install
npm run dev
\`\`\`

open http://localhost:3005

## deploy

see instructions in the source. runs on any node host.

## built by

[@fursov_v](https://x.com/fursov_v) — solo founder building ai saas from germany.

follow for the unfiltered version of building with ai.

## license

MIT. fork it, clone it, make your own meme tool. just tag me if it blows up.
