---
name: launch-strategy
description: >
  Plan a product launch that generates real traction, not just a spike on day one — grounded
  in go-to-market evidence (Weinberg & Mares' Bullseye channel framework and the 50% rule,
  the three-phase launch model, and build-in-public as pre-launch infrastructure). Treats
  launch as a campaign with sequencing, not a single day: find the one channel that works,
  warm the space before launch day, run a coordinated launch, and measure whether it actually
  worked.

  Make sure to use this skill whenever the user invokes /launch-strategy or is planning how to
  put a product in front of people — "how do I launch", "plan my launch", "I'm about to go
  live", "should I do Product Hunt", "how do I build a waitlist", "launch day checklist",
  "how do I build in public", "which channel should I use to grow", "how do I get traction",
  or "I launched and nothing happened, what now". Also trigger right after the product is
  nearly ready and the question shifts from building to distribution.

  Do NOT use for: getting the first handful of users by hand, the manual unscalable
  recruiting and the user conversations (use /first-users — it's the companion to this);
  writing the launch copy, landing page, or emails (use /product-copy); or strategic
  positioning (use /positioning). This skill plans the campaign and the channels; first-users
  works the early manual acquisition underneath it.
---

# Launch Strategy

Shipping is not launching. Most solo builders treat launch as a moment — the day the product
goes live. They post on LinkedIn, get a hundred likes from friends who will never become
users, and wonder why nothing happened. A product launched into a cold space is a tree
falling in an empty forest.

Launch is a **campaign**: strategy, sequencing, and an honest read of where your first real
users are and what it takes to reach them. This skill helps a solo builder plan that campaign
— find the channel that actually works, warm the space before launch day, run a coordinated
launch, and measure whether it moved anything.

## Language rule

**Always respond in the user's language.** If the user writes in Portuguese (including
Brazilian Portuguese), plan the launch in Portuguese — channels, examples, and copy
directions in the language their market actually uses. Where users gather, what counts as
spam, and which platforms matter are all culture- and language-specific; a launch plan in the
wrong language is planning for the wrong market.

## The thesis: a campaign, not a day

Two ideas reframe everything (from Weinberg & Mares' *Traction*):

- **The 50% rule.** Spend roughly half your effort on the product and half on traction — from
  early on, not after launch. Builders who spend 100% on product and 0% on distribution arrive
  at launch day with a great product and no one to show it to.
- **Traction is evidence of demand**, measurable (sign-ups, users, sales) — not applause. The
  goal of a launch isn't attention; it's evidence that people want this and will come back.

A launch has three phases, and the most-skipped one is the first:

```
1. Foundation   →  Who is it for, what's the "only," and where do those people gather?
2. Channels     →  Find the one channel that works (Bullseye: brainstorm → test → focus)
3. Pre-launch   →  Warm the space before launch day (waitlist, build-in-public)
4. Launch day   →  The coordinated push (sequenced checklist; Product Hunt if it fits)
5. Post-launch  →  Sustain and measure (did it work? what now?)
```

Why the order: you can't pick channels without knowing who you're reaching (foundation), you
can't run a launch day into a cold audience (pre-launch), and a launch you don't measure
teaches you nothing for the next one. **Pre-launch is where launches are won** — the best
launch day is the visible tip of weeks of quiet warming.

Load `references/core-principles.md` every session (the evidence base and the "campaign not a
day" stance). Load `references/components.md` for the per-phase method and the Bullseye
channel process.

## Entry point: where is the user?

**Signal 1 — how close is launch?** Months out (start pre-launch now), weeks out (build the
plan and the launch-day checklist), or already launched (measure and decide what's next).

**Signal 2 — do they have a foundation?** Positioning and a sense of the persona and where
they gather? Reuse it. If not, name the gap — a launch with no idea who it's for has no
channel to aim at.

**Signal 3 — any audience yet?** A waitlist, a build-in-public following, an email list, a
community presence? This decides whether launch day has anywhere to land.

Route:

| Mode | When | Reference |
|---|---|---|
| **guided** | Planning a launch for the first time, wants to understand the campaign | `references/mode-guided.md` |
| **playbook** | Has the pieces, wants the concrete launch plan + day-of checklist produced | `references/mode-playbook.md` |
| **review** | Has a plan or has launched; wants it pressure-tested or a post-mortem | `references/mode-review.md` |

If unsure, ask: "How far from launch are you — months, weeks, or already live and wondering
what's next?"

## How each phase works (the short version)

**1. Foundation.** Reuse positioning: who it's for, the onliness line ("the only ___ that
___"), and — the launch-specific part — *where those specific people already gather* (which
communities, platforms, search terms, newsletters). Generic "post on social media" is not a
plan; specific places are.

**2. Channels (Bullseye).** Don't guess one channel and pour everything in. Brainstorm a
tactic across the channel types, **test a few cheaply**, find the one that actually moves the
metric, then focus there. Most growth comes from one channel at a time — finding *which* is
the work.

**3. Pre-launch.** Build the audience before there's a product to show: a **waitlist** that
captures interest, and **build-in-public** content that turns your building process into
pre-launch infrastructure (an audience that's already warm on launch day), not just personal
branding.

**4. Launch day.** A coordinated, sequenced push to the warm audience and chosen channels — a
checklist with an order, not a frantic scramble. Product Hunt and similar are *optional
amplifiers* that only pay off with preparation and an existing base; decide if they fit rather
than defaulting to them.

**5. Post-launch.** Launch day is the start, not the finish. Sustain the momentum, and
**measure honestly**: did real users sign up and come back, or was it a vanity spike? Decide
the next move from the evidence.

## Universal by design — fit the product and the market

The frameworks are fixed; the plan is not. A developer tool launches in completely different
places (technical communities, Show HN, content) than a local consumer app (regional groups,
word of mouth, local press) or a B2B product (direct outreach, LinkedIn, partnerships). Derive
the channels and the plan from *this* product, *this* persona, and *this* market and language —
never from a generic launch checklist. If the plan starts to look like "do a Product Hunt and
post on LinkedIn" regardless of the product, stop and re-derive from where the real users
actually are.

## Output always includes

1. **The foundation** — who it's for, the onliness line, and the specific places they gather.
2. **A channel plan** — the few channels to test, the cheap test for each, and how you'll know
   which one is working (the metric).
3. **A pre-launch plan** — waitlist and build-in-public approach, with a rough timeline.
4. **A launch-day checklist** — sequenced, with owners and timing.
5. **Success metrics** — what "it worked" means in real terms (not likes), and the measure.
6. **Next step** — usually `/first-users` for the manual early-acquisition work that runs
   underneath the campaign, and `/product-copy` for the launch assets.

## The early-stage reality

Most first launches are quiet, and that's normal — the value is the *evidence* and the
*channel learning*, not a viral moment. Plan for a launch that teaches you which channel works
and gives you your first real, returning users, then launch again (relaunches are
underrated). Pre-launch started early beats a clever launch day every time.
