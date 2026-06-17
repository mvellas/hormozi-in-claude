# Hormozi in Claude

I built this because I am a genuine fan of Alex Hormozi's work.

Not because I want another folder full of clever marketing theory.

Because I wanted a practical Claude skill that could take the ideas behind `$100M Offers` and `$100M Leads` and turn them into assets I can actually use: offers, sales pages, VSLs, emails, lead magnets, ads, outreach, launch campaigns, and acquisition plans.

## The Promise

This skill helps Claude build marketing assets around one simple standard:

Make the offer so clear, valuable, and believable that the right buyer feels the cost of waiting more than the cost of buying.

It is designed to help with:

- Grand Slam Offers
- Sales page copy
- VSL scripts
- Email sequences
- Lead magnets
- Paid ads
- Warm and cold outreach
- Content hooks and stories
- Referral and affiliate campaigns
- Launch campaigns
- Offer audits and acquisition roadmaps

## Why I Made It

I like Hormozi's frameworks because they force the hard questions.

Not "how do I make this sound better?"

But:

- Is the market hungry?
- Is the avatar specific?
- Is the dream outcome obvious?
- Is the proof strong enough?
- Is the risk low enough?
- Is the first win fast enough?
- Is the offer valuable enough to charge more?
- Is there a real reason to act now?

That is the useful stuff.

That is what this skill is built to do inside Claude.

## Commands

Use these commands directly:

- `/hormozi:diagnose` - audit an offer, funnel, page, script, or campaign.
- `/hormozi:offer` - create a Grand Slam Offer with bonuses, guarantee, scarcity, urgency, and naming.
- `/hormozi:lead-magnet` - create a lead magnet that solves a narrow problem and points to the core offer.
- `/hormozi:sales-page` - write a sales page from hook to final CTA.
- `/hormozi:vsl` - write a VSL script, slide outline, and CTA sequence.
- `/hormozi:emails` - write nurture, launch, follow-up, onboarding, or sales emails.
- `/hormozi:ads` - create paid ad angles, hooks, copy, CTAs, and testing plans.
- `/hormozi:outbound` - create warm/cold outreach scripts and follow-ups.
- `/hormozi:content` - create content hooks, stories, posts, and CTAs.
- `/hormozi:affiliate` - create referral, partner, or affiliate offers and launch assets.
- `/hormozi:launch` - create launch campaigns using whisper, announce, shout, and integrate phases.
- `/hormozi:roadmap` - create a practical implementation roadmap.

## Example Prompts

```text
Use $hormozi-in-claude /hormozi:offer to create a premium offer for a B2B SaaS that helps agencies reduce client churn.
```

```text
Use $hormozi-in-claude /hormozi:sales-page to write a high-converting page for my consulting offer. Ask only for missing details that change the copy.
```

```text
Use $hormozi-in-claude /hormozi:vsl to create a 12-minute VSL for a paid workshop.
```

```text
Use $hormozi-in-claude /hormozi:emails to write a 7-email launch sequence with proof, objections, bonuses, and deadline urgency.
```

## What It Will Not Do

This is not a shortcut for fake proof, fake scarcity, fake guarantees, or fake expertise.

The skill is built to use placeholders when facts are missing. It should not invent:

- Revenue numbers
- Testimonials
- Case studies
- Credentials
- Scarcity
- Legal, medical, or financial claims

The goal is better strategy and sharper copy, not hype with a costume on.

## How It Works

The skill uses a small `SKILL.md` file as the operating layer, then loads specific reference playbooks only when needed:

- `references/offer-engine.md`
- `references/sales-page-copy.md`
- `references/vsl-framework.md`
- `references/email-sequences.md`
- `references/acquisition-copy.md`
- `references/diagnostics-and-output.md`

That keeps the skill fast, focused, and useful without dumping every framework into context every time.

## My Standard

If the output does not make the offer clearer, more valuable, more believable, or easier to act on, it is not good enough.

That is the bar.

