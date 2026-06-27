# launch-strategy

> Shipping is not launching. A product launched into a cold space is a tree falling in an empty forest. Launch is a campaign — strategy, sequencing, and an honest read of where your first users actually are.

Part of the [go-to-market](https://github.com/ohanatais/go-to-market) skill set, within the [build-from-zero](https://github.com/ohanatais/build-from-zero) ecosystem.

---

## What this skill does

Plans a product launch that generates real traction, not just a day-one spike — for a solo builder with no audience yet. It treats launch as a campaign across phases: find the channel that actually works, warm the space before launch day, run a coordinated launch, and measure whether it moved anything real.

It's grounded in go-to-market evidence rather than launch-day folklore: Weinberg & Mares' Bullseye channel framework and the 50% rule, the three-phase launch model, and build-in-public as pre-launch infrastructure.

The skill is **universal by design**: a developer tool, a local consumer app, and a B2B product launch in completely different places. The channels and the plan are derived from *this* product, *this* persona, and *this* market — never from a generic "Product Hunt + LinkedIn" checklist.

---

## The thesis: a campaign, not a day

```
1. Foundation   →  Who is it for, what's the "only," and where do those people gather?
2. Channels     →  Find the one channel that works (Bullseye: brainstorm → test → focus)
3. Pre-launch   →  Warm the space before launch day (waitlist, build-in-public)
4. Launch day   →  The coordinated push (sequenced checklist; Product Hunt if it fits)
5. Post-launch  →  Sustain and measure (did it work? what now?)
```

Pre-launch is where launches are won — the best launch day is the visible tip of weeks of quiet warming. And traction is *returning users*, not applause.

---

## Three modes, one interface

| Mode | When to use | Output |
|---|---|---|
| **guided** | Planning a launch for the first time | Walk the five phases, explaining the why |
| **playbook** | Has the pieces, wants the plan + day-of checklist | A sequenced launch plan with metrics |
| **review** | Has a plan, or already launched | Pressure-test or honest post-mortem + next moves |

---

## What every output includes

- **The foundation** — who it's for, the onliness line, and the specific places they gather
- **A channel plan** — the few to test, the cheap test for each, and the metric that picks a winner
- **A pre-launch plan** — waitlist + build-in-public, with a timeline
- **A launch-day checklist** — sequenced, with timing
- **Success metrics** — what "it worked" means in returning-user terms
- **Next step** — usually `/first-users` and `/product-copy`

---

## How to install

```bash
cp -r launch-strategy /your-project/.claude/skills/
```

---

## How to trigger

```
/launch-strategy
```

It also triggers on natural phrasing — "how do I launch", "should I do Product Hunt", "build a waitlist", "launch day checklist", "how do I get traction", "I launched and nothing happened" — even without the word "launch."

---

## The relationship to the rest

Launch-strategy plans the *campaign and channels*. Its companion [`first-users`](../first-users) works the *manual, unscalable* acquisition of the earliest handful of users underneath it. Write the launch assets with [`product-copy`](https://github.com/ohanatais/brand-and-copy), and aim the whole thing using your [`positioning`](https://github.com/ohanatais/product-thinking).

---

Made by [Ohana Taís](https://github.com/ohanatais) · part of [build-from-zero](https://github.com/ohanatais/build-from-zero)
