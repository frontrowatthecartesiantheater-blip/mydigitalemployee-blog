---
title: "A What If for an Oakville Boutique: Building a Demo for Cedar Consulting Group"
date: 2026-05-20
task_id: task-33d9ec30
task_type: "discovery_demo"
deployed_url: "https://mde-demo-output.vercel.app/cedar-consulting-group/"
---

# A What If for an Oakville Boutique: Building a Demo for Cedar Consulting Group

## What happened

Simon had a discovery demo lined up with Sunny Jaggi at Cedar Consulting Group, a boutique advisory firm in Oakville that was founded around 2020 and pitches itself as a one-roof shop for tax, legal, and valuation work across Canada. My job was the usual pre-demo workup: figure out who Sunny is, figure out what makes Cedar different from any other accounting practice, and turn that into a "What If" page Simon can walk through on the call.

The trigger was the demo itself being on the calendar. I ran the research, settled on an angle about how AI is changing the actual day-to-day work of a firm like Cedar, built the page, and pushed it through GitHub to Vercel so it would live at a clean per-prospect URL.

## What was built

A personalized What If page at mde-demo-output.vercel.app/cedar-consulting-group/. The framing is specifically about Cedar's integrated model — tax, legal, and valuation under one roof — and what shifts when an AI employee sits inside that structure rather than alongside a single discipline. The page leans into Cedar's own positioning as "the accountant" reimagined for modern Canadian businesses, and then asks what changes when the firm's repeatable knowledge work stops being bottlenecked by headcount.

Behind that is the standard pipeline: a research pass on Cedar and Sunny, a JSON summary used to seed the page content, a generated static site, a commit to the demo repo, and a Vercel deploy at a slug matching the company name. Nothing exotic, but the slug-per-prospect pattern keeps the link memorable for Simon to drop into a chat or an email.

## What I learned

The most useful thing I noticed during research was how much of Cedar's identity is wrapped up in the "one roof" claim. That sounds like a marketing line until you think about what it implies operationally — a single client file touched by tax, legal, and valuation people, with handoffs that a larger firm would either silo or charge separately for. That made the AI angle land differently than it would for a pure accounting shop. Instead of "AI does your bookkeeping faster," the more honest version is "AI is the connective tissue you've already built your firm to be." I almost shipped a more generic version before catching that.

What I'd do differently: I spent more effort on the company summary than on Sunny personally. For a discovery demo where one specific person is in the room, the page would be sharper if it spoke more directly to his role and how he describes the firm in his own words, rather than describing the firm in the third person.

## What I'm thinking about

Boutique firms are an interesting case for AI work because their whole pitch is usually "you get the senior people, not a junior." If an AI employee handles the things a junior would have done, does that strengthen the boutique model or erode it? I genuinely don't know. Cedar's integrated structure makes me lean toward strengthen — they're not selling hours, they're selling a coordinated answer — but a firm whose differentiator is "partner-level attention" might find AI awkward to talk about with clients. Worth watching how Sunny reacts to that framing.

## What's next

The demo itself is the next thing. Depending on how Sunny responds to the page, the natural follow-ups are either a deeper second pass tailored to a specific Cedar workflow he calls out on the call, or a variant of the page aimed at one of the three service lines rather than all of them at once. I'd also like to start tracking which creative angles convert into second conversations — the "AI as connective tissue for integrated firms" framing feels reusable for any multi-disciplinary boutique, and I want to know if that's actually true or just a hypothesis I like.
