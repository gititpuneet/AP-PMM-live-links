# Alternative Payments — Instantly.ai Cold Outreach Master Framework

**Version:** 1.1 | **Date:** March 25, 2026 | **Owner:** ABM Team
**Verticals:** MSP/IT Services + Accounting/CAS Firms
**Goal:** Reply → Conversation → Demo (genuine, curious, concerned — never pushy)

---

## Table of Contents

1. [Milestone 1: Infrastructure & Deliverability (COMPLETED)](#milestone-1-infrastructure--deliverability-completed)
2. [Milestone 2: Lead List Quality (COMPLETED)](#milestone-2-lead-list-quality-completed)
3. [Milestone 3: Email Sequence Framework](#milestone-3-email-sequence-framework)
4. [Milestone 4: Deliverability & Sending Health Checklist](#milestone-4-deliverability--sending-health-checklist)
5. [Milestone 5–6: Sales Team Activity Cadences](#milestone-5-6-sales-team-activity-cadences)
6. [Milestone 7: Metabase Tracking & Attribution](#milestone-7-metabase-tracking--attribution)

---

# MILESTONE 1: INFRASTRUCTURE & DELIVERABILITY (COMPLETED) ✅

**Status:** Complete — all requirements met.

## What Was Done

Sending domains and mailboxes are fully warmed up and operational. The infrastructure has been validated against best-practice standards:

| Requirement | Standard | Status |
|---|---|---|
| SPF records configured on all sending domains | Pass authentication checks | ✅ Done |
| DKIM signing enabled on all sending domains | 2048-bit key minimum | ✅ Done |
| DMARC policy published on all sending domains | p=quarantine or p=reject | ✅ Done |
| Sending domains separate from primary business domain | Never cold-email from alternativepayments.io | ✅ Done |
| Mailbox warm-up completed (14-21 day ramp) | Start at 5/day, ramp to 30-40/day | ✅ Done |
| Inbox placement rate validated | 95%+ inbox (not spam/promotions) | ✅ Done |
| Google Postmaster Tools connected | Domain reputation visible and monitored | ✅ Done |
| Blacklist monitoring active | All sending IPs/domains checked weekly | ✅ Done |

## Maintenance Requirements

Infrastructure is never "set and forget." See Milestone 4 for the ongoing daily/weekly/monthly checklist that keeps deliverability healthy.

---

# MILESTONE 2: LEAD LIST QUALITY (COMPLETED) ✅

**Status:** Complete — verified and segmented lists ready for sequencing.

## What Was Done

Lead lists have been built, verified, and segmented for both verticals:

| Requirement | Standard | Status |
|---|---|---|
| Email verification run on all lists | Bounce rate < 2% | ✅ Done |
| Lists segmented by vertical | MSP and Accounting separated | ✅ Done |
| Lists segmented by persona (title matching) | P1/P2/P3/P4 buckets per vertical | ✅ Done |
| Enrichment applied where available | ~20% have incumbent processor/tech stack data | ✅ Done |
| Suppression list applied | Existing customers, current pipeline, opted-out contacts excluded | ✅ Done |
| Duplicate removal | No contact appears in multiple active sequences | ✅ Done |
| ICP validation | MSP: 10+ employees, 1+ managed service offering. Accounting: 11-100 employees, CAS/bookkeeping/general accounting | ✅ Done |
| List source quality tracked | Source tagged on every lead for downstream performance analysis | ✅ Done |

## Ongoing Requirements

List quality degrades over time (people change jobs, emails go stale). See Milestone 4 for the weekly list hygiene and monthly list source quality audits.

---

# MILESTONE 3: EMAIL SEQUENCE FRAMEWORK

## 3.1 — Framework Architecture

### Core Principles

This framework follows three non-negotiable rules derived from 551 closed-won deals and deep knowledge-base analysis:

1. **Lead with pain, not product.** The top two pain points across all closed deals are pricing/fee opacity (1,304 mentions) and manual reconciliation (902 mentions). Every first email must surface a specific, vertical-relevant pain.
2. **Branch on behavior, not just time.** Sequences adapt based on opens, replies, and sentiment — not just "wait 3 days, send next email."
3. **Sound like a human who gives a damn.** Tone is genuine curiosity and concern. No "just checking in," no "circling back," no corporate filler.
4. **Ascending length arc.** Email 1 is a tap on the shoulder. Each email earns the right to be slightly longer. The breakup is the shortest of all.

### Email Length Guidelines (10% Tighter Than Industry Best Practice)

Every email in every sequence must respect these limits. No exceptions.

| Email Stage | Max Word Count | Max Characters (~) | Purpose | Tone Style |
|---|---|---|---|---|
| **Email 1 — Pain Opener** | **45 words** | ~270 chars | One pain. One question. Get a reply. | Tap on the shoulder — curiosity |
| **Email 2A — Social Proof** (opened) | **65 words** | ~390 chars | Prove the pain is solvable with one proof point. | "Here's why I tapped" |
| **Email 2B — New Subject** (not opened) | **55 words** | ~330 chars | Same angle, new hook. Shorter than 2A. | Second attempt — tighter |
| **Email 3A — New Angle** (opened) | **60 words** | ~360 chars | Pivot to secondary pain. Fresh perspective. | Different door, same curiosity |
| **Email 3B — Reframe** (not opened) | **40 words** | ~240 chars | Strip to core value prop. 2-3 sentences max. | Direct and simple |
| **Email 4A — Value Drop** (opened) | **90 words** | ~540 chars | The one email that earns length. Stat, insight, or resource. | Standalone value — not a follow-up |
| **Email 4B — Hail Mary** (not opened) | **30 words** | ~180 chars | Last shot. Curiosity-driven one-liner. | Ultra-crisp |
| **Email 5 — Breakup** | **35 words** | ~210 chars | Graceful exit. Leave door open. Name-drop customers. | Withdrawal creates urgency |

**Why these limits matter:** Cold email is not content marketing. Every word that doesn't earn a reply is a word that pushes the reader toward "delete." The #1 predictor of reply rate on Email 1 is brevity + relevance. Longer emails perform better only after the prospect has shown engagement (opened, clicked, replied).

**Opener style by persona (Email 1 only):**
- **Controller / AR Specialist:** Direct question about their process or time spent
- **CEO / Owner:** Peer observation → question ("I hear this from other founders...")
- **CFO:** Metric hook → question ("Do you know your current DSO?")
- **CAS Director:** Scale observation → question ("Managing AR across 50+ client books...")

### Sequence Architecture Overview

Each sequence follows a **5-email primary trunk** with **conditional branches** at key decision points. The ABM team builds and manages all sequences in Instantly. Sales only enters post-reply.

```
Email 1 (Day 0) — Pain Opener
    │
    ├─ OPENED, NO REPLY → Email 2A (Day 3) — Proof/Social Proof
    ├─ NOT OPENED → Email 2B (Day 4) — New subject line, same core angle
    │
    ├─ OPENED, NO REPLY → Email 3A (Day 7) — Different angle / secondary pain
    ├─ NOT OPENED → Email 3B (Day 8) — Complete reframe, shorter
    │
    ├─ OPENED, NO REPLY → Email 4A (Day 14) — Value drop (stat, insight, resource)
    ├─ NOT OPENED → Email 4B (Day 15) — Final subject line test, ultra-short
    │
    └─ Email 5 (Day 21) — Breakup / soft close (all paths converge)

REPLY AT ANY POINT:
    ├─ POSITIVE → Route to Sales (AE inbox) immediately
    ├─ NEUTRAL/QUESTION → ABM drafts response, Sales personalizes and sends
    ├─ NEGATIVE/OBJECTION → Route to objection-handling flow (see Section 3.6)
    ├─ OUT OF OFFICE → Pause sequence, resume 3 days after return date
    └─ UNSUBSCRIBE → Remove permanently, log reason
```

### Timing Logic (Optimized for B2B Decision-Makers)

| Gap | Rationale |
|---|---|
| Email 1 → 2: **3-4 days** | Enough time to open but not forget. Tuesday-Thursday sends only. |
| Email 2 → 3: **4-5 days** | Avoid fatigue. Shift to a new angle. |
| Email 3 → 4: **7 days** | Full week gap. This is the "value drop" — not a follow-up. |
| Email 4 → 5: **7 days** | Breakup email. Creates urgency through withdrawal. |
| **Total sequence length: 21-23 days** | Industry standard for SMB B2B ($5-10K ACV, <30-day close) |

### Send Time Optimization

| Day | Best Send Time | Rationale |
|---|---|---|
| Tuesday | 8:00-9:30 AM local | Decision-makers inbox-scan early. Avoids Monday backlog. |
| Wednesday | 10:00-11:00 AM local | Mid-morning after first meetings clear. |
| Thursday | 8:00-9:30 AM local | Before end-of-week mode kicks in. |

Never send on: Monday (inbox overload), Friday (checked-out), weekends.

---

## 3.2 — Persona Targeting Strategy

### MSP Vertical Personas

Based on your Knowledge Base personas (Jennifer, Bob, Lisa, Sarah), prioritized for cold email:

| Priority | Persona | Title Variants | Why They're Targeted | Primary Pain Angle |
|---|---|---|---|---|
| **P1** | Lisa (Controller) | Controller, Accounting Manager, Finance Manager, Bookkeeper | Primary evaluator. Feels the pain daily. Leads the search for solutions. | Manual reconciliation, month-end close time, DSO trending wrong |
| **P2** | Jennifer (CEO/Owner) | CEO, Owner, Founder, President, Managing Partner | Final decision-maker. Cares about customer experience and scalability. | Customer billing friction, growth blocked by back-office, peer founder stories |
| **P3** | Bob (CFO) | CFO, VP Finance, Finance Director | Budget approver. Needs ROI story and board-ready metrics. | DSO metrics, working capital, audit readiness, delayed hiring opportunity |
| **P4** | Sarah (AR Specialist) | AR Specialist, Billing Coordinator, Collections Specialist | Champion. Will advocate internally if she sees time savings. | Hours wasted on manual work, detective work, collections calls |

### Accounting Vertical Personas (NEW)

| Priority | Persona | Title Variants | Why They're Targeted | Primary Pain Angle |
|---|---|---|---|---|
| **P1** | Managing Partner / Firm Owner | Managing Partner, Partner, Owner, Principal, Founder | Decision-maker AND feels the pain. Unlike MSPs where CEO is removed from AR, accounting firm owners are closer to billing. Often handles or oversees client billing directly. | Client billing friction eroding relationships, inability to pass CC fees, manual invoicing eating into margins |
| **P2** | Director of CAS / CAS Practice Lead | Director of Client Accounting Services, CAS Manager, Outsourced Accounting Lead | Owns the P&L for the fastest-growing practice area. Directly responsible for AR efficiency across dozens of client books. | Scaling CAS without proportional headcount, managing AR across 50-100+ client books, reconciliation across QBO/Xero |
| **P3** | CFO / Controller (of the firm) | CFO, Controller, Finance Manager | At firms with 30+ employees, dedicated finance roles exist. Same evaluation criteria as MSP CFO. | DSO, cash flow visibility, fee structure optimization, audit-readiness |
| **P4** | Office Manager / Billing Lead | Office Manager, Billing Manager, Client Services Manager | Hands-on billing person at smaller firms (11-30 employees). Equivalent of "Sarah" in the MSP world. | Manual invoicing, chasing payments, QuickBooks Payments limitations, no client portal |

### Persona Selection Logic for Sequences

Since only ~20% of leads have tool/platform identification, and most leads have basic enrichment (name, title, company), the primary segmentation is by **persona (title)** and **vertical (MSP vs Accounting)**:

```
Lead enters system
    │
    ├─ Vertical: MSP or Accounting? (determined by list source / industry tag)
    │
    ├─ Persona: Match title to P1/P2/P3/P4 bucket
    │
    ├─ IF incumbent processor is known (20% of leads):
    │     └─ Add competitor-specific "spice" to Email 1 and Email 3
    │
    └─ IF tech stack is known (PSA + Accounting software):
          └─ Add integration-specific proof points to Email 2 and Email 4
```

---

## 3.3 — Master Email Sequences: MSP Vertical

### SEQUENCE A: MSP — Controller/Finance Manager (P1 Persona)

**Email 1 — Pain Opener (Day 0)** ⸻ *Max 45 words*
Subject: quick question about [Company]

> Hi {{firstName}},
>
> How much time does your team spend each month reconciling payments between your PSA and QuickBooks?
>
> Most MSP controllers I talk to say 10-15 hours. Curious if that's your experience at [Company].
>
> {{senderFirstName}}

*(39 words)* — Direct question about their time. One pain. No product mention. No meeting ask.

---

**Email 2A — Social Proof (Day 3, if opened but no reply)** ⸻ *Max 65 words*
Subject: RE: quick question about [Company]

> Hi {{firstName}},
>
> One data point — an MSP running {{PSA_or_fallback: "ConnectWise"}} + QBO cut month-end close from 7 days to 2 days after automating reconciliation. DSO dropped 9 days in the first quarter.
>
> The biggest shift: autopay adoption went from ~20% to 70%+ of their client base.
>
> If month-end close or DSO is on your radar, happy to share how.
>
> {{senderFirstName}}

*(62 words)*

---

**Email 2B — New Subject Line (Day 4, if NOT opened)** ⸻ *Max 55 words*
Subject: [Company] + payment reconciliation

> Hi {{firstName}},
>
> MSP controllers I talk to spend 10-15 hours a month on payment matching between their PSA and QuickBooks. Most assumed that's just how it works — until they saw it automated.
>
> Is that worth a 5-minute conversation, or is your process already dialed in?
>
> {{senderFirstName}}

*(48 words)*

---

**Email 3A — Different Angle (Day 7, if opened but no reply)** ⸻ *Max 60 words*
Subject: the fee pass-through question

> Hi {{firstName}},
>
> Different question — are you absorbing credit card fees, or passing them through to clients?
>
> The average MSP we talk to absorbs $1,500-3,000/month in CC fees without realizing there's a compliant pass-through option. That's $18-36K/year in recovered margin.
>
> Applies to [Company]?
>
> {{senderFirstName}}

*(49 words)* — Pivots to #1 pain point (fee opacity, 1,304 CRM mentions).

---

**Email 3B — Complete Reframe (Day 8, if NOT opened)** ⸻ *Max 40 words*
Subject: [Company]

> {{firstName}} — I help MSPs automate AR so finance teams stop chasing payments and reconciling spreadsheets.
>
> If that's a pain point at [Company], I'd love to hear about it.
>
> {{senderFirstName}}

*(30 words)*

---

**Email 4A — Value Drop (Day 14, if opened but no reply)** ⸻ *Max 90 words*
Subject: interesting data point for [Company]

> Hi {{firstName}},
>
> One stat from our data: MSPs that move from manual invoicing to automated AR see a 9-15 day DSO improvement in the first 90 days. For a company processing $50K+/month, that's meaningful cash flow acceleration.
>
> The biggest driver isn't collections calls — it's making it easy for clients to pay. Branded portal, autopay that adjusts to fluctuating invoice amounts, and reminders that don't feel like nagging.
>
> If improving cash flow timing is on your agenda this quarter, I think we'd have a good conversation.
>
> {{senderFirstName}}

*(85 words)* — The one email that earns length. Standalone value, not a follow-up.

---

**Email 4B — Hail Mary (Day 15, if NOT opened)** ⸻ *Max 30 words*
Subject: worth a conversation?

> {{firstName}} — if automating AR and improving cash flow is ever a priority for [Company], I'm here.
>
> {{senderFirstName}}

*(18 words)*

---

**Email 5 — Breakup (Day 21, all paths converge)** ⸻ *Max 35 words*
Subject: closing the loop

> {{firstName}} — looks like the timing isn't right. If you ever want to see how MSPs like {{customer_name_or_fallback: "Integris, Valiant, and TeamLogic IT"}} cut month-end close by 60%, the door is open.
>
> {{senderFirstName}}

*(34 words)*

---

### SEQUENCE B: MSP — CEO/Owner (P2 Persona)

**Email 1 — Pain Opener (Day 0)** ⸻ *Max 45 words*
Subject: question for you, {{firstName}}

> Hi {{firstName}},
>
> I hear from MSP founders every week that billing has become a friction point with clients — not because the work is bad, but because the payment experience is clunky.
>
> Is that something clients mention at [Company]?
>
> {{senderFirstName}}

*(38 words)* — Peer observation opener. No product mention. Jennifer hears billing friction from 3+ clients/quarter.

---

**Email 2A — Peer Proof (Day 3, if opened but no reply)** ⸻ *Max 65 words*
Subject: RE: question for you, {{firstName}}

> Hi {{firstName}},
>
> One MSP founder put it well: *"Billing used to be a friction point that threatened client relationships. Now customers actually compliment our process."*
>
> Their numbers: autopay adoption went from ~20% to 70%+, month-end close dropped from 7 days to 2.
>
> If client billing experience is on your radar, happy to share how.
>
> {{senderFirstName}}

*(55 words)*

---

**Email 2B — New Subject (Day 4, if NOT opened)** ⸻ *Max 55 words*
Subject: MSP billing + client experience

> Hi {{firstName}},
>
> The MSPs growing fastest made billing a competitive advantage, not just a back-office function. Their clients pay faster, complain less, and actually see the billing portal as a positive touchpoint.
>
> Is improving the client payment experience something on the radar at [Company]?
>
> {{senderFirstName}}

*(44 words)*

---

**Email 3A — Growth Angle (Day 7, if opened but no reply)** ⸻ *Max 60 words*
Subject: scaling [Company] without adding headcount

> Hi {{firstName}},
>
> Quick question — can [Company]'s current AR process handle 2x the client base without adding another person?
>
> Most MSP founders I talk to found the answer was no — until they automated invoicing, reminders, reconciliation, and autopay enrollment.
>
> If scaling without proportional headcount is the plan, worth a conversation?
>
> {{senderFirstName}}

*(50 words)* — Pivots to scalability, Jennifer's #3 concern.

---

**Email 3B — Short Reframe (Day 8, if NOT opened)** ⸻ *Max 40 words*
Subject: [Company]'s AR process

> {{firstName}} — I help MSP founders automate billing so their team focuses on growth instead of chasing payments.
>
> If that sounds relevant to [Company], I'd love to learn more.
>
> {{senderFirstName}}

*(28 words)*

---

**Email 4A — Customer Story (Day 14, if opened but no reply)** ⸻ *Max 90 words*
Subject: what other MSP founders are saying

> Hi {{firstName}},
>
> Three data points from MSP founders I've spoken with recently:
>
> *"I used to start every day with low-grade anxiety about cash. Now I glance at my phone and see green."*
>
> *"We can 2x revenue without 2x financial ops headcount. The system scales."*
>
> *"I've referred three MSPs. They all call me six months later to say thanks."*
>
> If hearing directly from another founder would be helpful, I'm happy to connect you. No pitch — just an introduction.
>
> {{senderFirstName}}

*(78 words)* — Founder-to-founder peer proof. Offers a connection, not a demo.

---

**Email 4B — Hail Mary (Day 15, if NOT opened)** ⸻ *Max 30 words*
Subject: one question

> {{firstName}} — if you could automate 80% of billing and collections, what would your team do with that time?
>
> {{senderFirstName}}

*(20 words)*

---

**Email 5 — Breakup (Day 21, all paths converge)** ⸻ *Max 35 words*
Subject: last note from me

> {{firstName}} — timing isn't right, and I respect that. If improving the client billing experience ever becomes a priority at [Company], I'm easy to find.
>
> {{senderFirstName}}

*(27 words)*

---

### SEQUENCE C: MSP — CFO (P3 Persona)

**Email 1 — Metrics Opener (Day 0)** ⸻ *Max 45 words*
Subject: [Company]'s DSO trend

> Hi {{firstName}},
>
> Do you know [Company]'s current DSO — and which direction it's trending?
>
> Most MSP CFOs I talk to are working from month-old spreadsheets while DSO creeps up quarter over quarter. Curious if that's your situation.
>
> {{senderFirstName}}

*(37 words)* — Metric hook opener. Bob needs real-time data, not month-old numbers.

---

**Email 2A — ROI Angle (Day 3, if opened but no reply)** ⸻ *Max 65 words*
Subject: RE: [Company]'s DSO trend

> Hi {{firstName}},
>
> Quick math — for an MSP processing $50-100K/month, every day of DSO improvement represents $1,600-$3,300 in accelerated cash flow. Our average in Q1 was a 9-day improvement.
>
> Factor in eliminated reconciliation labor and recovered CC fees through compliant pass-through — payback period is typically 3-4 months.
>
> Want to see the ROI model with [Company]'s numbers? Takes 15 minutes.
>
> {{senderFirstName}}

*(63 words)*

---

**Email 2B — New Subject (Day 4, if NOT opened)** ⸻ *Max 55 words*
Subject: MSP finance metrics + quick question

> Hi {{firstName}},
>
> I help MSP CFOs get real-time DSO and cash visibility without waiting for month-end. The ones I work with typically see a 9-day DSO improvement and 3-4 month payback.
>
> If that's relevant to [Company]'s finance team, I'd enjoy the conversation.
>
> {{senderFirstName}}

*(46 words)*

---

**Email 3A — Audit/Board Angle (Day 7, if opened but no reply)** ⸻ *Max 60 words*
Subject: board-ready AR metrics

> Hi {{firstName}},
>
> Different angle — when your board or investors ask about AR efficiency, how quickly can you pull the numbers?
>
> One MSP CFO told me: *"I used to prep for hours before investor calls. Now I prep for 10 minutes."*
>
> If audit readiness is on your list this year, this is worth a conversation.
>
> {{senderFirstName}}

*(54 words)* — Pivots to Bob's audit/investor readiness concern.

---

**Email 3B — Reframe (Day 8, if NOT opened)** ⸻ *Max 40 words*
Subject: [Company] finance ops

> {{firstName}} — real-time DSO, automated reconciliation, audit-ready documentation. If any of those matter to [Company]'s finance team, I'd like to hear about your current setup.
>
> {{senderFirstName}}

*(25 words)*

---

**Email 4A — Delayed Hire (Day 14, if opened but no reply)** ⸻ *Max 90 words*
Subject: the $55K question

> Hi {{firstName}},
>
> At [Company]'s current growth rate, when will you need another AR person?
>
> Most MSP CFOs I work with found they could delay that hire by 12-18 months through automation — saving $55K+ in fully-loaded cost while actually improving DSO. The math is simple: automated reconciliation eliminates 5-10 hours/week of manual labor, autopay cuts collection time, and compliant CC fee pass-through recovers $1,500-3,000/month in margin.
>
> If you're modeling next year's headcount, this might change the numbers.
>
> {{senderFirstName}}

*(79 words)* — Bob's language: headcount modeling, ROI, margin recovery.

---

**Email 4B — Hail Mary (Day 15, if NOT opened)** ⸻ *Max 30 words*
Subject: quick ROI question

> {{firstName}} — $55K+ in delayed AR hiring plus recovered CC fees. Would the math be worth 15 minutes?
>
> {{senderFirstName}}

*(18 words)*

---

**Email 5 — Breakup (Day 21, all paths converge)** ⸻ *Max 35 words*
Subject: closing the loop

> {{firstName}} — timing isn't right. When DSO, month-end close, or AR headcount becomes a priority, I'll be here with the ROI math ready.
>
> {{senderFirstName}}

*(24 words)*

---

### SEQUENCE D: MSP — AR Specialist/Billing Coordinator (P4 Persona)

**Email 1 — Empathy Opener (Day 0)** ⸻ *Max 45 words*
Subject: the reconciliation spreadsheet

> Hi {{firstName}},
>
> Are you still managing AR across {{accounting_software_or_fallback: "QuickBooks"}}, your PSA, a bank portal, and at least one spreadsheet holding it all together?
>
> Most AR specialists I talk to assumed that's just how it works. Curious if that's your setup at [Company].
>
> {{senderFirstName}}

*(42 words)* — Empathy opener. Sarah manages ~200 invoices across 4+ systems daily.

---

**Email 2A — Social Proof (Day 3, if opened but no reply)** ⸻ *Max 65 words*
Subject: RE: the reconciliation spreadsheet

> Hi {{firstName}},
>
> One AR specialist described her old process as "financial detective work" — 200+ invoices, 35+ clients, mystery payments, and 10-15 hours a month just on reconciliation.
>
> After automating, she went from overwhelmed to strategic — building client relationships instead of chasing payments.
>
> If you're doing similar detective work at [Company], I think you'd find the comparison interesting.
>
> {{senderFirstName}}

*(58 words)*

---

**Email 2B — New Subject (Day 4, if NOT opened)** ⸻ *Max 55 words*
Subject: AR automation for [Company]

> Hi {{firstName}},
>
> If you could eliminate manual reconciliation, automate payment reminders, and get 70%+ of clients on autopay — what would you do with the extra 10+ hours a month?
>
> Curious if that resonates at [Company], or if your process is already dialed in.
>
> {{senderFirstName}}

*(43 words)*

---

**Email 3A — Autopay Angle (Day 7, if opened but no reply)** ⸻ *Max 60 words*
Subject: autopay that actually works

> Hi {{firstName}},
>
> Quick question — does your autopay break when invoice amounts change?
>
> That's the #2 complaint I hear from MSP billing teams. Fluctuating seat counts mean autopay cancels, and you're manually charging each card.
>
> Autopay that adjusts to fluctuating amounts + client self-enrollment. Worth a quick look?
>
> {{senderFirstName}}

*(47 words)* — Pivots to broken autopay, #2 pain in QBP win analysis (20+ deals).

---

**Email 3B — Reframe (Day 8, if NOT opened)** ⸻ *Max 40 words*
Subject: billing team question

> {{firstName}} — I help MSP billing teams eliminate manual reconciliation and get clients on autopay that doesn't break. If your team is spending hours on payment admin weekly, this might help.
>
> {{senderFirstName}}

*(30 words)*

---

**Email 4A — Collections Angle (Day 14, if opened but no reply)** ⸻ *Max 90 words*
Subject: collections calls — the worst part of the job?

> Hi {{firstName}},
>
> Most AR specialists I know hate collections calls more than anything. It's awkward, damages relationships, and rarely works.
>
> What if you never had to make another one — and still got paid faster?
>
> One billing coordinator I work with went from calling 15-20 overdue accounts per month to zero calls. Collections Assist has an ~80% recovery rate on 30+ day invoices, without picking up the phone.
>
> If collections is a pain at [Company], this is worth seeing.
>
> {{senderFirstName}}

*(78 words)* — Sarah hates collections calls. This is her personal pain.

---

**Email 4B — Hail Mary (Day 15, if NOT opened)** ⸻ *Max 30 words*
Subject: save 10+ hours/month on AR?

> {{firstName}} — 10-15 hours a month on reconciliation and payment matching. Sound familiar? Happy to show you what "after" looks like.
>
> {{senderFirstName}}

*(21 words)*

---

**Email 5 — Breakup (Day 21, all paths converge)** ⸻ *Max 35 words*
Subject: last note

> {{firstName}} — if you ever want to see what AR looks like without the spreadsheets, I'm here. Wishing you a smooth month-end close.
>
> {{senderFirstName}}

*(24 words)*

---

## 3.4 — Master Email Sequences: Accounting Vertical

### SEQUENCE E: Accounting — Managing Partner/Owner (P1 Persona)

**Email 1 — Pain Opener (Day 0)** ⸻ *Max 45 words*
Subject: quick question about billing at [Company]

> Hi {{firstName}},
>
> I talk to accounting firm partners every week — one frustration keeps surfacing: absorbing credit card fees because there's no clean way to pass them through.
>
> Is that something [Company] deals with, or have you found a workaround?
>
> {{senderFirstName}}

*(40 words)* — #1 switch reason from QBP win analysis (30+ deals). No product mention.

---

**Email 2A — Social Proof (Day 3, if opened but no reply)** ⸻ *Max 65 words*
Subject: RE: quick question about billing at [Company]

> Hi {{firstName}},
>
> One data point — an accounting firm absorbing $2,400/month in CC fees recovered all of it through compliant pass-through. That's $28,800/year in margin. They also got 70%+ of CAS clients on autopay and cut month-end close from a week to 2 days.
>
> If billing admin is eating into advisory time, I'd enjoy hearing how you're thinking about it.
>
> {{senderFirstName}}

*(60 words)*

---

**Email 2B — New Subject (Day 4, if NOT opened)** ⸻ *Max 55 words*
Subject: CC fees at [Company]

> Hi {{firstName}},
>
> If [Company] processes client payments through QuickBooks Payments or similar, you might be absorbing $1,500-5,000/month in CC fees without a clean pass-through option.
>
> That's real margin for CAS firms. Worth a 5-minute conversation, or is that not a pain point?
>
> {{senderFirstName}}

*(44 words)*

---

**Email 3A — Scaling CAS Angle (Day 7, if opened but no reply)** ⸻ *Max 60 words*
Subject: scaling CAS without adding billing headcount

> Hi {{firstName}},
>
> CAS is growing 17% YoY at most firms. But every new client adds invoices, reminders, reconciliation, and collections follow-ups.
>
> Most partners I talk to are scaling client count faster than billing operations can keep up. If [Company] is growing CAS, that gap only widens.
>
> Worth discussing?
>
> {{senderFirstName}}

*(49 words)* — Real market data from GTM plan. Speaks to growth ambitions.

---

**Email 3B — Reframe (Day 8, if NOT opened)** ⸻ *Max 40 words*
Subject: [Company] + AR automation

> {{firstName}} — I help accounting firms automate billing and collections so their team focuses on advisory instead of chasing invoices.
>
> If that's a priority at [Company] this year, I'd love to learn more.
>
> {{senderFirstName}}

*(31 words)*

---

**Email 4A — Partnership/Referral Angle (Day 14, if opened but no reply)** ⸻ *Max 90 words*
Subject: something accounting firms are doing differently

> Hi {{firstName}},
>
> Here's something underappreciated: accounting firms are uniquely positioned to recommend AR automation to their own clients.
>
> Your clients trust you with their books. If you're using a platform that improves their AR too — you become the hero who saved them money and time. Some firms are earning referral revenue on top of that.
>
> Every accounting firm partnership is also a channel opportunity. If you're interested in how firms are turning AR into both an efficiency win and a revenue stream, happy to share the model.
>
> {{senderFirstName}}

*(85 words)* — GTM insight: "every accounting firm opp is a partnership opp."

---

**Email 4B — Hail Mary (Day 15, if NOT opened)** ⸻ *Max 30 words*
Subject: worth a conversation?

> {{firstName}} — recovering absorbed CC fees, automating billing, reducing month-end close. If any of those matter to [Company], I'm here.
>
> {{senderFirstName}}

*(19 words)*

---

**Email 5 — Breakup (Day 21, all paths converge)** ⸻ *Max 35 words*
Subject: last note from me

> {{firstName}} — timing isn't right. If your firm ever wants to see how CAS practices are recovering $20-50K/year in absorbed CC fees, I'm easy to find.
>
> {{senderFirstName}}

*(29 words)*

---

### SEQUENCE F: Accounting — CAS Director / Practice Lead (P2 Persona)

**Email 1 — Pain Opener (Day 0)** ⸻ *Max 45 words*
Subject: managing AR across 50+ client books

> Hi {{firstName}},
>
> Running CAS for {{companySize_or_fallback: "dozens of"}} clients means managing AR across dozens of QBO files — each with different schedules, terms, and collection challenges.
>
> Most CAS leaders call it "death by a thousand cuts." Is that your experience at [Company]?
>
> {{senderFirstName}}

*(43 words)* — Scale observation opener. CAS Directors feel aggregate volume pain.

---

**Email 2A — Social Proof (Day 3, if opened but no reply)** ⸻ *Max 65 words*
Subject: RE: managing AR across 50+ client books

> Hi {{firstName}},
>
> One CAS director told me: *"I'm not just doing AR for my firm. I'm doing AR for my firm's clients too. That's 60+ sets of invoices, reconciliations, and collections."*
>
> After automating, her team managed the same 60+ clients in half the time — one dashboard across all client books instead of logging into QBO separately.
>
> Worth sharing how she did it?
>
> {{senderFirstName}}

*(60 words)*

---

**Email 2B — New Subject (Day 4, if NOT opened)** ⸻ *Max 55 words*
Subject: CAS practice efficiency at [Company]

> Hi {{firstName}},
>
> Managing AR across dozens of client books in QBO is a grind. One dashboard, automated reminders, and autopay across all clients — would that change your team's capacity?
>
> If that sounds relevant to [Company]'s CAS practice, I'd enjoy the conversation.
>
> {{senderFirstName}}

*(41 words)*

---

**Email 3A — Fee Pass-Through Angle (Day 7, if opened but no reply)** ⸻ *Max 60 words*
Subject: are your CAS clients absorbing CC fees?

> Hi {{firstName}},
>
> Different angle — are your CAS clients absorbing CC fees because their payment tool has no clean pass-through option?
>
> If so, you can save each client $1,000-5,000/year and position yourself as the advisor who found the savings.
>
> Interested in how other CAS practices are handling this?
>
> {{senderFirstName}}

*(49 words)* — Pivots to fee pass-through. Positions CAS Director as hero to their clients.

---

**Email 3B — Reframe (Day 8, if NOT opened)** ⸻ *Max 40 words*
Subject: CAS + AR automation

> {{firstName}} — scaling CAS without scaling billing headcount. That's the problem I help solve. If your team is feeling the squeeze, let's talk.
>
> {{senderFirstName}}

*(24 words)*

---

**Email 4A — Capacity Benchmark (Day 14, if opened but no reply)** ⸻ *Max 90 words*
Subject: the 7.4 clients-per-FTE benchmark

> Hi {{firstName}},
>
> Industry data shows the median CAS practice manages 7.4 clients per FTE. Top performers manage 10.2.
>
> The difference isn't talent — it's tooling. Specifically, how much of the billing/collections/reconciliation cycle is automated vs. manual. The firms hitting 10+ clients per FTE automated reminders, reconciliation, and autopay enrollment so their team spends time on advisory instead of admin.
>
> If [Company]'s CAS practice is closer to the median and you'd like to close the gap, I think we'd have a productive conversation.
>
> {{senderFirstName}}

*(82 words)* — Exact CAS benchmarks from GTM plan (median 7.4, top 10.2 clients/FTE).

---

**Email 4B — Hail Mary (Day 15, if NOT opened)** ⸻ *Max 30 words*
Subject: CAS efficiency question

> {{firstName}} — how many clients can your CAS team manage before you need another hire? If the answer is "we're at capacity," we should talk.
>
> {{senderFirstName}}

*(27 words)*

---

**Email 5 — Breakup (Day 21, all paths converge)** ⸻ *Max 35 words*
Subject: closing the loop

> {{firstName}} — I'll take the hint. If CAS scaling, AR automation, or improving client-per-FTE ratios becomes a priority, I'm here.
>
> {{senderFirstName}}

*(20 words)*

---

### SEQUENCE G: Accounting — CFO/Controller (P3 Persona)

**Email 1 — Metrics Opener (Day 0)** ⸻ *Max 45 words*
Subject: [Company]'s DSO across client books

> Hi {{firstName}},
>
> Do you have real-time DSO visibility across [Company]'s client books — or are you working from month-old QBO reports?
>
> Most accounting firm CFOs I talk to know the number isn't great but can't see it in real time. Sound familiar?
>
> {{senderFirstName}}

*(42 words)* — Metric hook. Same DSO pain as MSP CFO, adapted for multi-book accounting context.

---

**Email 2A — ROI Angle (Day 3, if opened but no reply)** ⸻ *Max 65 words*
Subject: RE: [Company]'s DSO across client books

> Hi {{firstName}},
>
> Quick math — for a firm processing $50-100K/month across client books, every day of DSO improvement represents $1,600-$3,300 in accelerated cash flow. Our average in Q1 was a 9-day improvement.
>
> Add recovered CC fees through compliant pass-through and eliminated reconciliation labor — payback is typically 3-4 months.
>
> Want to see the model with [Company]'s numbers?
>
> {{senderFirstName}}

*(57 words)*

---

**Email 2B — New Subject (Day 4, if NOT opened)** ⸻ *Max 55 words*
Subject: accounting firm finance metrics

> Hi {{firstName}},
>
> I help accounting firm CFOs get real-time DSO and cash visibility across client books without waiting for month-end. Firms I work with typically see a 9-day DSO improvement and 3-4 month payback.
>
> If that's relevant to [Company]'s finance team, I'd enjoy the conversation.
>
> {{senderFirstName}}

*(46 words)*

---

**Email 3A — Audit Readiness Angle (Day 7, if opened but no reply)** ⸻ *Max 60 words*
Subject: audit-ready AR documentation

> Hi {{firstName}},
>
> Different angle — when audit season hits, how quickly can you pull AR documentation across all client books?
>
> One accounting firm CFO told me: *"I used to prep for days before audits. Now the data is always ready."*
>
> If audit readiness or client profitability analysis is on your list this year, worth a conversation.
>
> {{senderFirstName}}

*(55 words)* — Pivots to audit readiness, the accounting-specific version of Bob's "board readiness."

---

**Email 3B — Reframe (Day 8, if NOT opened)** ⸻ *Max 40 words*
Subject: [Company] finance ops

> {{firstName}} — real-time DSO, automated reconciliation across client books, audit-ready documentation. If any of those matter to [Company]'s finance team, I'd like to hear about your current setup.
>
> {{senderFirstName}}

*(27 words)*

---

**Email 4A — Delayed Hire (Day 14, if opened but no reply)** ⸻ *Max 90 words*
Subject: the $55K question

> Hi {{firstName}},
>
> At [Company]'s current growth rate, when will you need another AR person?
>
> Accounting firm CFOs I work with found they could delay that hire by 12-18 months through automation — saving $55K+ in fully-loaded cost while improving DSO across client books. The math: automated reconciliation eliminates hours of manual QBO work per week, autopay cuts collection time, and compliant CC fee pass-through recovers $1,500-5,000/month in margin.
>
> If you're modeling next year's headcount, this might change the numbers.
>
> {{senderFirstName}}

*(80 words)* — Same delayed-hire math, adapted for accounting firm context.

---

**Email 4B — Hail Mary (Day 15, if NOT opened)** ⸻ *Max 30 words*
Subject: quick ROI question

> {{firstName}} — $55K+ in delayed AR hiring plus recovered CC fees across client books. Would the math be worth 15 minutes?
>
> {{senderFirstName}}

*(20 words)*

---

**Email 5 — Breakup (Day 21, all paths converge)** ⸻ *Max 35 words*
Subject: closing the loop

> {{firstName}} — timing isn't right. When DSO, audit readiness, or AR headcount becomes a priority, I'll be here with the ROI math ready.
>
> {{senderFirstName}}

*(23 words)*

---

### SEQUENCE H: Accounting — Office Manager/Billing Lead (P4 Persona)

**Email 1 — Empathy Opener (Day 0)** ⸻ *Max 45 words*
Subject: the reconciliation grind

> Hi {{firstName}},
>
> Are you managing AR across dozens of client QBO files — logging into each one separately for invoicing, reconciliation, and payment follow-ups?
>
> Most office managers I talk to assumed that's just how it works. Curious if that's your setup at [Company].
>
> {{senderFirstName}}

*(42 words)* — Empathy opener adapted for multi-book accounting context.

---

**Email 2A — Social Proof (Day 3, if opened but no reply)** ⸻ *Max 65 words*
Subject: RE: the reconciliation grind

> Hi {{firstName}},
>
> One billing lead at a CAS firm described her process as "logging into QBO 30 times a day" — different client books, different invoice schedules, different payment statuses. She spent 15+ hours a month just on reconciliation across all books.
>
> After automating, one dashboard replaced all those logins. She manages the same client count in half the time.
>
> Sound familiar?
>
> {{senderFirstName}}

*(59 words)*

---

**Email 2B — New Subject (Day 4, if NOT opened)** ⸻ *Max 55 words*
Subject: AR automation for [Company]

> Hi {{firstName}},
>
> If you could replace logging into 30+ QBO files with one dashboard — automated reminders, autopay for retainer clients, reconciliation across all books — what would you do with the extra 10+ hours a month?
>
> Curious if that resonates, or if your process is already dialed in.
>
> {{senderFirstName}}

*(47 words)*

---

**Email 3A — Autopay Angle (Day 7, if opened but no reply)** ⸻ *Max 60 words*
Subject: autopay for retainer clients

> Hi {{firstName}},
>
> Quick question — do your CAS retainer clients actually stay on autopay, or does it break when monthly amounts change?
>
> That's a common complaint. Billing amounts fluctuate, autopay cancels, and you're manually charging each client.
>
> Autopay that adjusts to changing amounts + client self-enrollment through a branded portal. Worth a quick look?
>
> {{senderFirstName}}

*(52 words)* — Autopay pain adapted for accounting retainer/CAS billing context.

---

**Email 3B — Reframe (Day 8, if NOT opened)** ⸻ *Max 40 words*
Subject: billing team question

> {{firstName}} — I help accounting firm billing teams eliminate manual reconciliation across client books and get clients on autopay that doesn't break. If your team spends hours on payment admin weekly, this might help.
>
> {{senderFirstName}}

*(32 words)*

---

**Email 4A — Collections Angle (Day 14, if opened but no reply)** ⸻ *Max 90 words*
Subject: chasing payments across client books

> Hi {{firstName}},
>
> Collections across 30-50+ client books is a different beast than single-company AR. Each client has different terms, different payment habits, and different excuses. Tracking who's overdue across all those books takes detective work.
>
> One billing manager I work with went from manually tracking overdue clients across dozens of QBO files to automated collections with an ~80% recovery rate on 30+ day invoices — no phone calls required.
>
> If chasing payments across client books is a pain at [Company], this is worth seeing.
>
> {{senderFirstName}}

*(84 words)* — Collections pain magnified by multi-book context.

---

**Email 4B — Hail Mary (Day 15, if NOT opened)** ⸻ *Max 30 words*
Subject: save 10+ hours/month on AR?

> {{firstName}} — 15+ hours a month reconciling across client QBO files. Sound familiar? Happy to show you what "after" looks like.
>
> {{senderFirstName}}

*(21 words)*

---

**Email 5 — Breakup (Day 21, all paths converge)** ⸻ *Max 35 words*
Subject: last note

> {{firstName}} — if you ever want to see what AR looks like without logging into 30 QBO files a day, I'm here. Wishing you a smooth month-end close.
>
> {{senderFirstName}}

*(30 words)*

---

## 3.5 — Competitor-Specific "Spice" Modules

When enrichment data confirms a competitor (applies to ~20% of leads), inject these angles into Emails 1 and 3:

### MSP Vertical Competitors

**ConnectBooster (Highest-value segment: $653 avg MRR)**
- Email 1 spice: "I noticed [Company] might be using ConnectBooster — mind if I ask, when you have a payment syncing issue, do you call CB, BNG, or Clearent? And how long does it take to figure out whose fault it is?"
- Email 3 spice: "One thing I hear from CB users: three separate bills every month (ConnectBooster platform, BNG gateway, Clearent processing). Have you checked your BNG and Clearent statements recently? Most partners find rates have crept up 20-30% through pass-through hikes."

**QuickBooks Payments ($335 avg MRR, high volume)**
- Email 1 spice: "Quick question — is [Company] using QuickBooks Payments? If so, are you absorbing CC fees or have you found a workaround? QB Payments has no built-in way to pass them through."
- Email 3 spice: "Fun fact: QB Payments recently raised ACH fees to 1.75% for some accounts. For MSPs processing $50K+/month in ACH, that's $875/month in fees alone. Our ACH is free on all plans."

**WisePay ($473 avg MRR)**
- Email 1 spice: "I've been talking to MSPs using WisePay and a common theme is low adoption — clients aren't actually using the portal. Is that something you've seen at [Company]?"
- Email 3 spice: "WisePay's adoption rates are typically lower than expected because the setup process creates friction for end-clients. We've seen MSPs jump from 20% to 70%+ portal usage after switching."

**Stripe ($368 avg MRR)**
- Email 1 spice: "Stripe is great for transactions — but it wasn't built for B2B AR. No client portal, no branded experience, no collections workflow. Is that the gap you're feeling at [Company]?"
- Email 3 spice: "Stripe charges per-transaction. At $50K/month in volume, our flat subscription saves most MSPs 30-50% vs. Stripe's percentage-based model."

**Manual/Checks ($372 avg MRR, greenfield)**
- Email 1 spice: "I noticed [Company] might still be collecting payments primarily by check or manual ACH. Mind if I ask — what percentage of your clients pay online vs. by check today?"
- Email 3 spice: "MSPs that transition from manual/check collection to automated AR with a client portal typically see 60-80% of clients move to digital payments within 90 days. The key is making it easier to pay online than to write a check."

### Accounting Vertical Competitors

**Ignition (Likely biggest competitor per GTM plan)**
- Email 1 spice: "If [Company] uses Ignition — great for proposals and upfront billing. But I'm curious: what happens after the engagement letter is signed? How does your team handle ongoing collections, reminders, and reconciliation?"
- Email 3 spice: "Ignition stops at billing. Alternative Payments starts where Ignition ends — automating the entire AR lifecycle from invoice to collection to reconciliation."

**CPACharge**
- Email 1 spice: "CPACharge handles payment acceptance well — but are you still manually sending reminders, chasing overdue invoices, and reconciling payments by hand?"
- Email 3 spice: "CPACharge is payment acceptance. We're payment automation. The difference is hours per week your team gets back."

**Aiwyn (Enterprise/Top 300 firms)**
- Email 1 spice: "Aiwyn is impressive tech — but I've heard from firms that the implementation is complex, the pricing scales aggressively per-client, and the platform feels like it was built for Top 100 firms, not growing CAS practices."
- Email 3 spice: "Aiwyn's acquisition-stitched platform (they've acquired 3 companies in the last year alone) means integration gaps between modules. We're purpose-built from Day 1."

**QuickBooks Payments (Same as MSP, universally applicable)**
- Use the same spice from MSP section — the QBP pain points (no fee pass-through, broken autopay, rising ACH fees, no portal, manual reconciliation) are identical for accounting firms.

---

## 3.6 — Reply Handling Framework

### Positive Reply Routing

When a lead replies positively (interested, asks a question, wants to learn more):

1. **Instantly auto-tags** the lead as "Positive Reply" and pauses the sequence
2. **Notification fires** to the assigned AE's Slack channel within 5 minutes
3. **AE responds within 2 hours** (speed-to-lead is critical)
4. **Response template:**

> Hi {{firstName}},
>
> Thanks for getting back to me — really glad this resonated.
>
> I'd love to learn more about [Company]'s current setup before jumping into anything. Would you be open to a 20-minute call this week? I'll keep it conversational — no slides, no pitch. Just want to understand your world and see if there's a fit.
>
> Here are a few times that work on my end: [insert 3 options]
>
> {{AE_name}}

### Objection Reply Handling

Based on your Knowledge Base objection handling (6 objections documented):

| Objection | Response Strategy | Template Key Line |
|---|---|---|
| "Not a priority right now" | Acknowledge, ask what IS priority, position for future | "What's taking up most of your focus right now? That way if this makes sense later, I can frame it around what matters most to you." |
| "We already have something" | Ask what they use, probe for hidden pain | "Totally fair — how's that working for you overall? Most folks I talk to think things are fine until adoption or collections start dragging." |
| "Send me an email" | Ask what to include to personalize, keep discovery alive | "What caught your attention or what would you want to see in that email?" |
| "Our clients pay fine" | Pivot from "payment problems" to "payment experience and efficiency" | "Even for firms with good-paying clients, it's usually more about efficiency than fixing bad payers." |
| "Not looking at new tools" | Explore if it's satisfied or bad timing, offer side-by-side comparison | "Is that because everything's working exactly how you want, or just not the right time?" |
| "Not the decision-maker" | Get the DM name, ask for their day-to-day perspective anyway | "Who typically handles decisions around payments or billing tools? I'd still love to hear from you given you deal with the day-to-day." |

### Negative Reply Handling

When a reply is clearly negative ("not interested," "remove me," "stop emailing"):

1. **Immediately stop sequence** — no exceptions
2. **Reply with grace:**

> Understood, {{firstName}}. Removing you now. If anything changes down the road, I'm easy to find. Appreciate your time.

3. **Log in HubSpot** as "Opted Out — Cold Outreach" with date
4. **Do NOT re-add** to any outbound sequence for minimum 6 months

---

## 3.7 — Personalization Variable Reference

### Required Variables (must exist for every lead)

| Variable | Source | Fallback |
|---|---|---|
| `{{firstName}}` | Lead data | "Hi there" (NEVER use, clean your list) |
| `{{Company}}` | Lead data | No fallback — required |
| `{{senderFirstName}}` | Instantly sender config | Always populated |

### Enrichment Variables (available for ~15-20% of leads)

| Variable | Source | Fallback Value |
|---|---|---|
| `{{PSA_or_fallback}}` | Enrichment/list data | "ConnectWise and similar PSAs" (MSP) / omit for Accounting |
| `{{accounting_software_or_fallback}}` | Enrichment/list data | "QuickBooks" |
| `{{incumbent_processor}}` | Enrichment/list data | Omit competitor spice, use general pain angle |
| `{{companySize_or_fallback}}` | Enrichment | "dozens of" |
| `{{customer_name_or_fallback}}` | Reference data | "Integris, Valiant, and TeamLogic IT" (MSP) / "FlexKeeper, Stride Services" (Accounting) |

### Best Practice: Two-Tier Personalization

Since 85% of leads have only basic data, every email is written to work with ZERO enrichment variables. The enrichment variables are "spice" that get layered in when available — never required.

---

## 3.8 — A/B Testing Framework

### What to Test (Priority Order)

| Priority | Element | How to Test in Instantly | Success Metric |
|---|---|---|---|
| **1** | Subject lines | A/B split on Email 1 across all sequences | Open rate (target: 55%+) |
| **2** | Pain angle (Email 1) | Run fee-pain vs. manual-process pain as separate sequences for same persona | Reply rate (target: 3-5%+) |
| **3** | CTA style | "Is that worth a conversation?" vs. "Would you be open to 15 minutes?" | Positive reply rate |
| **4** | Email length | Short (3 sentences) vs. medium (5-7 sentences) on Email 3 | Reply rate on non-openers |
| **5** | Social proof format | Customer quote vs. data point vs. peer comparison | Reply rate on Email 2 |

### Testing Rules

1. **Minimum sample size:** 200 sends per variant before drawing conclusions
2. **One variable at a time:** Never change subject AND body simultaneously
3. **Test duration:** Run each test for minimum 2 full sequence cycles (6 weeks)
4. **Winner threshold:** Variant must beat control by 20%+ to declare a winner
5. **Document everything:** Log all test results in a shared sheet (see Milestone 7 for Metabase tracking)

---

## 3.9 — Sending Infrastructure Recommendation

### Optimal Setup for Scale

| Component | Recommendation | Rationale |
|---|---|---|
| **Mailboxes per sender identity** | 5 mailboxes per "person" | Industry best practice for reputation distribution. If one mailbox gets flagged, others continue. |
| **Sends per mailbox per day** | 30-40 emails/day max | Conservative limit preserves deliverability. Aggressive senders at 50+ see inbox placement drop. |
| **Total daily capacity per sender** | 150-200 emails/day | 5 mailboxes × 30-40 = 150-200/day per sender identity |
| **Number of sender identities** | Match to AE/SDR team size | Use real team member names and photos. Each AE should have 5 warmed mailboxes. |
| **Warm-up period** | 14-21 days minimum | Start at 5/day, ramp by 3-5/day every 2 days. Never skip warm-up. |
| **Domain strategy** | Separate sending domains from primary | Use domains like `alt-pay.com` or `altpayments.co` — never send cold email from `alternativepayments.io` |
| **SPF/DKIM/DMARC** | All three configured on every sending domain | Non-negotiable for inbox placement. |

### Mailbox Rotation Strategy

```
Sender: "Jessica Smith" (AE)
├── jessica@alt-pay.com (primary)
├── jessica.smith@alt-pay.com
├── j.smith@altpayments.co
├── jessica@ap-team.com
└── jessica.smith@ap-team.com

Rotation: Round-robin across all 5
Daily cap: 35 emails each = 175/day total
```

---

# MILESTONE 4: DELIVERABILITY & SENDING HEALTH CHECKLIST

## Daily Checks (ABM Team — 10 minutes)

| Check | Tool | What to Look For | Action if Red |
|---|---|---|---|
| Bounce rate | Instantly dashboard | Must be < 2% | Pause sending, clean list, verify emails |
| Spam complaint rate | Instantly + Google Postmaster | Must be < 0.1% | Pause campaign, review copy for spam triggers |
| Open rate trend | Instantly analytics | Should be 45-60% | Check subject lines, sending time, or deliverability issue |
| Reply rate | Instantly analytics | Should be 2-5%+ | Review copy, personalization, targeting |
| Unsubscribe rate | Instantly | Should be < 1% per campaign | Review targeting — wrong audience if high |
| Warm-up status | Instantly warm-up tab | All mailboxes should show "healthy" | Re-warm any flagged mailboxes |
| Send volume per mailbox | Instantly sending tab | No mailbox exceeding 40/day | Redistribute if any mailbox is overloaded |

## Weekly Checks (ABM Team — 30 minutes, every Monday)

| Check | What to Do | Benchmark |
|---|---|---|
| **Deliverability audit** | Run a deliverability test on each sending domain using Mail-tester.com or GlockApps | Score > 8/10 or 90%+ inbox placement |
| **Blacklist check** | Check all sending IPs and domains against major blacklists (MXToolbox) | Zero blacklist appearances |
| **Google Postmaster review** | Check domain reputation, spam rate, authentication results | Domain reputation: "High" |
| **Sequence performance review** | Compare all active sequences: open rate, reply rate, positive reply rate | Identify underperformers (below 40% open or <1% reply) |
| **A/B test check** | Review any running tests — sufficient sample size? Ready to call a winner? | 200+ sends per variant minimum |
| **List hygiene** | Review bounced emails from the week — pattern? Bad list source? | Remove bad sources, document quality by list provider |
| **Reply sentiment review** | Categorize all replies from the week: positive, neutral, negative, objection | Track positive reply rate trend week-over-week |

## Monthly Checks (ABM Team + Sales Manager — 60 minutes, first Monday)

| Check | What to Do | Benchmark |
|---|---|---|
| **Full funnel review** | Emails sent → Opens → Replies → Positive replies → Demos booked → Deals closed | Track conversion at every stage |
| **Domain health audit** | Review all sending domains — any degradation in reputation? | Rotate or retire degraded domains |
| **New mailbox provisioning** | Assess if volume needs require additional mailboxes | Plan 21-day warm-up for any new mailboxes |
| **Content refresh** | Review top-performing and bottom-performing emails — update bottom performers | Bottom 20% of emails by reply rate get rewritten |
| **List source quality** | Compare performance by list source (Apollo, ZoomInfo, manual, etc.) | Drop sources with >3% bounce rate or <30% open rate |
| **Competitor intelligence update** | Any new competitor developments that should be reflected in sequences? | Update battlecard spice modules if needed |
| **Persona performance** | Which personas are responding best? Reallocate volume toward top performers | Shift 20% of volume toward best-performing persona |
| **Vertical performance** | MSP vs. Accounting — which vertical is converting better? | Optimize messaging for the lagging vertical |
| **Compliance check** | CAN-SPAM compliance review — all emails have company address, unsubscribe works | Zero compliance gaps |

## Quarterly Checks (ABM Team + Leadership — 2 hours)

| Check | What to Do |
|---|---|
| **Sequence overhaul** | Full review of all sequences — rewrite underperformers, test new angles |
| **Infrastructure audit** | Domain age, mailbox health, IP reputation — plan replacements for anything aging |
| **Competitive landscape review** | Update all battlecard spice modules based on latest intel |
| **ICP refinement** | Based on 3 months of data — which segments, titles, company sizes close best? |
| **Budget/ROI review** | Cost per demo booked from cold email — is it below $500 CPL target? |

---

# MILESTONE 5-6: SALES TEAM ACTIVITY CADENCES

## Roles & Responsibilities

| Role | Cold Outreach Responsibility | Post-Reply Responsibility |
|---|---|---|
| **ABM Team** | Builds lists, writes sequences, manages Instantly, monitors deliverability, A/B tests | Triages replies, routes to AEs, drafts responses for objection replies |
| **SDRs** | No Instantly involvement — SDRs focus on phone outreach and LinkedIn | Book demos from warm leads (replied positively), qualify inbound |
| **AEs** | Mailboxes used as sender identities (managed by ABM) | Own all conversations post-reply, run demos, close deals |
| **Sales Manager** | Reviews performance dashboards, coaches on reply handling | Manages pipeline, forecasts, escalates stuck deals |

---

## ABM Team Daily Cadence

| Time | Task | Duration | Tool |
|---|---|---|---|
| 8:00 AM | Review overnight replies — categorize as positive/neutral/negative/OOO | 15 min | Instantly + Slack |
| 8:15 AM | Route positive replies to assigned AEs via Slack with context | 10 min | Slack |
| 8:30 AM | Run daily health checks (bounce rate, spam rate, warm-up status) | 10 min | Instantly dashboard |
| 8:45 AM | Draft response suggestions for objection/neutral replies | 20 min | — |
| 9:15 AM | Check sequence send status — any paused? Any errors? | 5 min | Instantly |
| Ongoing | Monitor new replies throughout the day — route within 1 hour | — | Instantly notifications |
| 4:00 PM | End-of-day reply sweep — ensure nothing missed | 10 min | Instantly |
| 4:15 PM | Update reply tracking sheet (positive/negative/objection counts) | 10 min | Google Sheets → Metabase |

## ABM Team Weekly Cadence

| Day | Task | Duration |
|---|---|---|
| **Monday** | Weekly deliverability audit + blacklist check + Google Postmaster review | 30 min |
| **Monday** | Sequence performance review — identify underperformers | 20 min |
| **Tuesday** | List building / enrichment for next week's sends | 2 hrs |
| **Wednesday** | A/B test review — call winners, set up new tests | 30 min |
| **Wednesday** | New sequence drafting or existing sequence optimization | 1 hr |
| **Thursday** | Reply sentiment analysis — categorize and trend week-over-week | 30 min |
| **Friday** | Weekly report: sends, opens, replies, positive replies, demos booked | 30 min |
| **Friday** | Clean bounced emails, update suppression lists | 20 min |

## ABM Team Monthly Cadence

| Task | Duration |
|---|---|
| Full funnel analysis: emails → opens → replies → demos → pipeline → closed-won | 2 hrs |
| Content refresh: rewrite bottom 20% of emails by reply rate | 3 hrs |
| List source quality audit — drop bad sources, invest in good ones | 1 hr |
| Persona and vertical performance analysis — reallocate volume | 1 hr |
| Infrastructure audit: domain health, mailbox capacity, warm-up status | 1 hr |
| Monthly report to leadership with trends and recommendations | 1 hr |

---

## AE Daily Cadence (Post-Reply Focus)

| Time | Task | Duration | Tool |
|---|---|---|---|
| 8:00 AM | Check Slack for overnight positive reply routing from ABM | 5 min | Slack |
| 8:15 AM | Respond to all positive replies (within 2 hours of routing) | 20 min | Email (from Instantly mailbox) |
| 8:30 AM | Review any objection replies — personalize ABM-drafted responses | 15 min | Email |
| 9:00 AM | Pre-call research for booked demos (LinkedIn, website, CRM notes) | 30 min | LinkedIn + HubSpot |
| 10:00-12:00 | Demo block — run scheduled demos | 2 hrs | Zoom |
| 1:00 PM | Follow-up on demos from this week — send proposals, next steps | 30 min | Email + HubSpot |
| 2:00 PM | Mid-day reply check — respond to any new positive replies | 10 min | Slack + Email |
| 3:00 PM | Pipeline management — update deal stages, notes in HubSpot | 20 min | HubSpot |
| 4:00 PM | End-of-day reply sweep | 5 min | Email |
| 4:15 PM | Log all activity in HubSpot — emails sent, demos held, proposals sent | 15 min | HubSpot |

## AE Weekly Cadence

| Day | Task | Duration |
|---|---|---|
| **Monday** | Pipeline review with Sales Manager — stuck deals, next steps | 30 min |
| **Monday** | Review ABM weekly report — understand what's coming in the pipeline | 15 min |
| **Wednesday** | Deal strategy session — prep for high-value demos this week | 30 min |
| **Thursday** | Follow-up on all pending proposals from previous weeks | 30 min |
| **Friday** | Update forecast in HubSpot — commit vs. best case vs. pipeline | 20 min |
| **Friday** | Share reply quality feedback with ABM team (what angles are resonating) | 15 min |

## AE Monthly Cadence

| Task | Duration |
|---|---|
| Closed-won analysis — which sequences, angles, and personas drove best deals? | 1 hr |
| Win/loss review with Sales Manager — what's working, what's not | 1 hr |
| Provide input to ABM on sequence improvements based on conversation insights | 30 min |
| Customer reference cultivation — identify 2-3 new referenceable customers per month | 30 min |

---

## Sales Manager Daily Cadence

| Time | Task | Duration | Tool |
|---|---|---|---|
| 8:30 AM | Review overnight reply volume and AE response times | 10 min | Slack + Instantly |
| 9:00 AM | Check that all positive replies got AE response within 2 hours | 5 min | Instantly + Slack |
| 10:00 AM | Spot-check AE reply quality — coaching opportunities | 15 min | Email review |
| 2:00 PM | Pipeline dashboard review — any deals stuck? Any at risk? | 15 min | HubSpot |
| 4:30 PM | End-of-day Slack summary to team: replies handled, demos booked today | 5 min | Slack |

## Sales Manager Weekly Cadence

| Day | Task | Duration |
|---|---|---|
| **Monday** | Team standup — pipeline review, deal strategy, blockers | 30 min |
| **Monday** | Review ABM weekly report — reply rates, demo conversion, sequence health | 20 min |
| **Wednesday** | 1:1 coaching with each AE (deal-level coaching) | 30 min per AE |
| **Thursday** | Review speed-to-lead metrics — AE response time to positive replies | 15 min |
| **Friday** | Weekly forecast roll-up to leadership | 30 min |
| **Friday** | Align with ABM team on next week's priorities | 15 min |

## Sales Manager Monthly Cadence

| Task | Duration |
|---|---|
| Full funnel review with ABM team and leadership | 2 hrs |
| AE performance review — quota attainment, demo-to-close rate, response time | 1 hr |
| Competitive intelligence debrief — what are AEs hearing in demos? | 30 min |
| Sequence effectiveness review with ABM — close rate by sequence/angle | 1 hr |
| Hiring/capacity planning — do we need more AEs or mailbox capacity? | 30 min |

---

# MILESTONE 7: METABASE TRACKING & ATTRIBUTION

## 7.1 — Data Architecture

### Data Sources and Flow

```
INSTANTLY.AI (Cold Email)
    │
    ├── API → PostgreSQL/MySQL database → Metabase
    │         (Instantly API pulls: campaigns, sequences,
    │          leads, emails sent, opens, clicks, replies)
    │
HUBSPOT (CRM — Source of Truth)
    │
    ├── API → Same database → Metabase
    │         (Deals, contacts, lifecycle stages,
    │          deal amounts, close dates, pipeline stages)
    │
SALESFORCE (Sales Team)
    │
    ├── API → Same database → Metabase
    │         (Opportunity data, AE activity, closed-won)
    │
    └── MERGE KEY: Email address (primary) + Company domain (secondary)
```

### Database Schema (What to Push to Metabase)

**Table 1: `instantly_campaigns`**

| Column | Type | Source | Description |
|---|---|---|---|
| campaign_id | VARCHAR | Instantly API | Unique campaign identifier |
| campaign_name | VARCHAR | Instantly API | Name of the campaign |
| vertical | VARCHAR | Derived | "MSP" or "Accounting" |
| persona | VARCHAR | Derived | "P1_Controller", "P2_CEO", etc. |
| sequence_type | VARCHAR | Derived | "A", "B", "C", etc. |
| status | VARCHAR | Instantly API | Active, paused, completed |
| created_date | DATE | Instantly API | Campaign creation date |
| total_leads | INT | Instantly API | Number of leads in campaign |

**Table 2: `instantly_leads`**

| Column | Type | Source | Description |
|---|---|---|---|
| lead_id | VARCHAR | Instantly API | Unique lead ID |
| email | VARCHAR | Instantly API | Lead email (merge key) |
| first_name | VARCHAR | Instantly API | Lead first name |
| last_name | VARCHAR | Instantly API | Lead last name |
| company | VARCHAR | Instantly API | Company name |
| company_domain | VARCHAR | Derived | Company domain (secondary merge key) |
| title | VARCHAR | Instantly API | Job title |
| vertical | VARCHAR | Derived | "MSP" or "Accounting" |
| persona_bucket | VARCHAR | Derived | P1/P2/P3/P4 |
| incumbent_processor | VARCHAR | Enrichment | Known processor or NULL |
| tech_stack_psa | VARCHAR | Enrichment | ConnectWise, HaloPSA, etc. or NULL |
| tech_stack_accounting | VARCHAR | Enrichment | QBO, Xero, etc. or NULL |
| list_source | VARCHAR | ABM tag | Apollo, ZoomInfo, manual, etc. |
| campaign_id | VARCHAR | Instantly API | Which campaign they're in |

**Table 3: `instantly_events`**

| Column | Type | Source | Description |
|---|---|---|---|
| event_id | VARCHAR | Generated | Unique event ID |
| lead_id | VARCHAR | Instantly API | Link to lead |
| campaign_id | VARCHAR | Instantly API | Link to campaign |
| event_type | VARCHAR | Instantly API | "sent", "opened", "replied", "bounced", "unsubscribed" |
| email_step | INT | Instantly API | Which email in the sequence (1-5) |
| email_variant | VARCHAR | Instantly API | "A" or "B" variant |
| event_timestamp | TIMESTAMP | Instantly API | When the event occurred |
| reply_sentiment | VARCHAR | ABM manual tag | "positive", "neutral", "negative", "objection", "ooo" |

**Table 4: `hubspot_deals`**

| Column | Type | Source | Description |
|---|---|---|---|
| deal_id | VARCHAR | HubSpot API | Unique deal ID |
| contact_email | VARCHAR | HubSpot API | Contact email (merge key) |
| company_domain | VARCHAR | HubSpot API | Company domain (secondary merge key) |
| deal_name | VARCHAR | HubSpot API | Deal name |
| deal_stage | VARCHAR | HubSpot API | Pipeline stage |
| amount_mrr | DECIMAL | HubSpot API | Monthly recurring revenue |
| created_date | DATE | HubSpot API | Deal creation date |
| close_date | DATE | HubSpot API | Actual or expected close date |
| deal_source | VARCHAR | HubSpot API | "Cold Email", "Inbound", "Referral", etc. |
| sequence_id | VARCHAR | Derived | Which Instantly sequence generated this deal |
| persona | VARCHAR | Derived | Persona bucket |
| vertical | VARCHAR | Derived | MSP or Accounting |
| incumbent_processor | VARCHAR | HubSpot API | Current processor |
| days_to_close | INT | Calculated | close_date - created_date |

**Table 5: `attribution_events`**

| Column | Type | Source | Description |
|---|---|---|---|
| attribution_id | VARCHAR | Generated | Unique ID |
| deal_id | VARCHAR | HubSpot | Link to deal |
| lead_id | VARCHAR | Instantly | Link to lead |
| first_touch_campaign | VARCHAR | Derived | First Instantly campaign that touched this lead |
| first_touch_date | DATE | Derived | Date of first email sent |
| reply_date | DATE | Instantly | Date of first positive reply |
| demo_booked_date | DATE | HubSpot | Date demo was booked |
| deal_created_date | DATE | HubSpot | Date deal was created in CRM |
| deal_closed_date | DATE | HubSpot | Date deal was closed-won |
| total_emails_sent | INT | Calculated | Total emails sent to this lead across all campaigns |
| email_that_generated_reply | INT | Instantly | Which email step (1-5) triggered the positive reply |
| time_to_reply_hours | DECIMAL | Calculated | Hours from first email to first positive reply |
| time_to_demo_days | DECIMAL | Calculated | Days from positive reply to demo |
| time_to_close_days | DECIMAL | Calculated | Days from demo to closed-won |

---

## 7.2 — Metabase Dashboards

### Dashboard 1: Cold Email Operations (ABM Team — Daily View)

**Cards to build:**

| Card | Visualization | Data |
|---|---|---|
| Emails Sent Today | Number | COUNT of events WHERE event_type = "sent" AND date = today |
| Open Rate (7-day rolling) | Gauge (target: 50%) | Opens / Sends for last 7 days |
| Reply Rate (7-day rolling) | Gauge (target: 3%) | Replies / Sends for last 7 days |
| Positive Reply Rate (7-day rolling) | Gauge (target: 1.5%) | Positive replies / Sends for last 7 days |
| Bounce Rate | Gauge (red above 2%) | Bounces / Sends for last 7 days |
| Replies by Sentiment | Pie chart | Positive, neutral, negative, objection, OOO |
| Sequence Performance Table | Table | Campaign name, sends, opens, open rate, replies, reply rate, positive replies |
| Reply Heatmap by Day/Hour | Heatmap | When are replies coming in? Optimize send times. |
| Active Campaigns | Table | All active campaigns with current status and health metrics |

### Dashboard 2: Funnel Conversion (Sales Manager — Weekly View)

**Cards to build:**

| Card | Visualization | Data |
|---|---|---|
| Full Funnel Waterfall | Funnel chart | Emails Sent → Opened → Replied → Positive Reply → Demo Booked → Deal Created → Closed-Won |
| Conversion Rates by Stage | Table | Stage-to-stage conversion percentages |
| Demos Booked This Week | Number | COUNT of deals WHERE demo_booked_date in current week |
| Demos Booked by Sequence | Bar chart | Which sequences are generating the most demos? |
| AE Response Time | Bar chart | Average hours from positive reply routing to AE response, by AE |
| Pipeline Created This Month | Number | SUM of amount_mrr WHERE deal_created_date in current month |
| Win Rate by Sequence | Table | Closed-won / Demos booked, by sequence |
| Speed to Lead | Number (target: <2 hrs) | Average time from positive reply to AE first response |

### Dashboard 3: Attribution & ROI (Leadership — Monthly View)

**Cards to build:**

| Card | Visualization | Data |
|---|---|---|
| Revenue Attributed to Cold Email | Number | SUM of amount_mrr WHERE deal_source = "Cold Email" AND closed-won |
| Cost per Demo Booked | Number (target: <$500) | Total outbound costs / Demos booked |
| Cost per Closed Deal | Number | Total outbound costs / Deals closed |
| LTV/CAC Ratio | Number (target: >3x) | (ACV × avg customer lifetime) / Cost per closed deal |
| Revenue by Vertical | Bar chart | MSP vs. Accounting closed-won MRR |
| Revenue by Persona | Bar chart | Which persona generates highest-value deals? |
| Revenue by Sequence | Bar chart | Which sequence generates most revenue? |
| Revenue by Incumbent Processor | Bar chart | Which competitor displacements generate most revenue? |
| Monthly Trend: Demos Booked | Line chart | 12-month trend of demos booked from cold email |
| Monthly Trend: Closed-Won MRR | Line chart | 12-month trend of cold-email-attributed closed-won MRR |
| Best Performing Email | Table | Which specific email step + variant generates the most positive replies that convert to deals |
| Sequence-to-Close Timeline | Histogram | Distribution of days from first email to closed-won |

### Dashboard 4: A/B Testing Results (ABM Team — As Needed)

**Cards to build:**

| Card | Visualization | Data |
|---|---|---|
| Active Tests | Table | All running A/B tests with current sample sizes |
| Test Results | Table | Completed tests: variant A vs B, metric, winner, confidence |
| Subject Line Performance | Bar chart | Open rate by subject line across all active campaigns |
| Email Body Performance | Bar chart | Reply rate by email variant |
| Historical Test Winners | Timeline | Log of all declared winners with dates and impact |

---

## 7.3 — Attribution Model

### First-Touch Attribution (Primary)

Cold email gets credit when:
1. Lead's first meaningful interaction was an Instantly email (sent → opened → replied)
2. Lead was NOT in HubSpot before the Instantly campaign
3. The positive reply directly led to a demo booking

### How to Track It

```
Step 1: Instantly sends email to lead@company.com
Step 2: Lead replies positively
Step 3: AE books demo → creates Deal in HubSpot
Step 4: AE sets Deal Source = "Cold Email - [Sequence Name]"
Step 5: Nightly ETL job matches:
        - instantly_leads.email = hubspot_deals.contact_email
        - Populates attribution_events table
Step 6: Metabase dashboards pull from attribution_events
```

### Multi-Touch Attribution (Secondary)

For leads who were already in HubSpot (e.g., downloaded content, attended webinar) but were later activated by cold email:

| Touch | Attribution Weight |
|---|---|
| First touch (original lead source) | 40% |
| Cold email that generated reply | 40% |
| Demo that closed the deal | 20% |

### UTM Tagging Convention

For any links included in emails (rare in cold email, but used in value-drop emails):

```
?utm_source=instantly
&utm_medium=cold_email
&utm_campaign=[sequence_name]
&utm_content=[email_step]_[variant]
&utm_term=[persona]_[vertical]
```

Example:
```
?utm_source=instantly&utm_medium=cold_email&utm_campaign=msp_controller_seq_a&utm_content=email_4a&utm_term=p1_msp
```

---

## 7.4 — Data Pipeline Setup

### Option 1: Instantly API → Python ETL → PostgreSQL → Metabase (Recommended)

```
┌─────────────┐     ┌──────────────┐     ┌──────────────┐     ┌──────────┐
│ Instantly    │────→│ Python ETL   │────→│ PostgreSQL   │────→│ Metabase │
│ API          │     │ (scheduled)  │     │ Database     │     │          │
└─────────────┘     └──────────────┘     └──────────────┘     └──────────┘
                           │
┌─────────────┐           │
│ HubSpot     │───────────┘
│ API          │
└─────────────┘
```

**Schedule:** ETL runs every 4 hours (6x/day). Daily is acceptable; real-time is unnecessary for cold email.

**ETL Jobs:**
1. `pull_instantly_campaigns.py` — Pulls all campaign metadata
2. `pull_instantly_leads.py` — Pulls all leads and their current status
3. `pull_instantly_events.py` — Pulls all send/open/reply/bounce events since last run
4. `pull_hubspot_deals.py` — Pulls all deals with contact info
5. `build_attribution.py` — Matches Instantly leads to HubSpot deals, populates attribution table

### Option 2: Zapier/Make → Google Sheets → Metabase (Simpler, Less Robust)

Use if engineering resources are limited:
1. Zapier triggers on Instantly events (send, open, reply)
2. Pushes to Google Sheets (one sheet per event type)
3. Metabase connects to Google Sheets as data source

**Limitations:** Slower, harder to scale, limited join capabilities. Recommended only as a stopgap.

---

## 7.5 — KPIs & Benchmarks

### Operational KPIs (Track Weekly)

| KPI | Target | Industry Best-in-Class | Action if Below Target |
|---|---|---|---|
| **Open Rate** | 50%+ | 60%+ | Test subject lines, check deliverability |
| **Reply Rate** | 3-5% | 7%+ | Rewrite copy, check targeting, try new angle |
| **Positive Reply Rate** | 1.5-2.5% | 3%+ | Improve pain relevance, add social proof |
| **Bounce Rate** | < 2% | < 0.5% | Clean lists, verify emails before sending |
| **Unsubscribe Rate** | < 1% | < 0.3% | Review targeting — wrong audience |
| **Spam Complaint Rate** | < 0.1% | < 0.05% | Immediate pause, review copy and frequency |

### Revenue KPIs (Track Monthly)

| KPI | Target | How to Calculate |
|---|---|---|
| **Cost per Demo (CPD)** | < $500 | (Instantly subscription + tool costs + ABM labor allocation) / Demos booked |
| **Demo-to-Close Rate** | 30-35% | Closed-won deals / Demos held |
| **Average Deal Size** | $450-500 MRR | SUM(MRR) / COUNT(deals) from cold email |
| **Time to Close** | < 30 days | AVG(close_date - demo_date) for cold email deals |
| **Cold Email Pipeline Created** | $X/month | SUM of MRR in pipeline from cold email source |
| **Cold Email Revenue Closed** | $X/month | SUM of MRR closed-won from cold email source |
| **LTV/CAC Ratio** | > 3x | (ACV × avg months retained) / Cost per closed deal |

### Leading Indicators (Track Daily)

| Indicator | Why It Matters |
|---|---|
| **Replies received today** | Early signal of tomorrow's demos |
| **Positive replies today** | Direct pipeline predictor |
| **AE response time to replies** | Speed-to-lead directly impacts conversion |
| **Emails sent today** | Volume health check |
| **Warm-up health** | Prevents future deliverability problems |

---

## Appendix A: Seasonality Calendar

### MSP Vertical

| Month | Outbound Strategy |
|---|---|
| January | Heavy outbound — new year budgets, fresh priorities |
| February | Heavy outbound — budget allocation happening |
| March | Heavy outbound — Q1 push |
| April | Standard outbound |
| May | Standard outbound |
| June | Heavy outbound — mid-year budget reviews |
| July | Lighter outbound — summer vacations |
| August | Ramp back up — September planning |
| September | Heavy outbound — Q4 budget decisions |
| October | Heavy outbound — year-end planning |
| November | Standard outbound (before Thanksgiving) |
| December | Lighter outbound (holiday season) — plant seeds for January |

### Accounting Vertical

| Month | Outbound Strategy |
|---|---|
| January | Standard outbound — firms busy with year-end |
| February | Lighter outbound — tax season ramp-up |
| March | PAUSE or very light — tax season peak |
| April 1-15 | PAUSE — tax deadline crunch |
| April 16-30 | Resume — post-deadline recovery |
| May | **HEAVY outbound — golden window** (capacity freed up, evaluation mode) |
| June | **HEAVY outbound — prime buying window** |
| July | Standard outbound |
| August | Standard outbound |
| September | Standard outbound — extension deadline approaching |
| October 1-15 | PAUSE or light — extension filing deadline Oct 15 |
| October 16-31 | Resume — post-extension recovery |
| November | **HEAVY outbound — second golden window** |
| December | Standard outbound (before holidays) — budget planning for next year |

---

## Appendix B: Instantly Campaign Naming Convention

```
[Vertical]_[Persona]_[Sequence]_[Version]_[Date]

Examples:
MSP_P1-Controller_SeqA_v1_2026-03
MSP_P2-CEO_SeqB_v1_2026-03
ACCT_P1-Partner_SeqE_v1_2026-04
ACCT_P2-CASDir_SeqF_v1_2026-04

A/B Test variants:
MSP_P1-Controller_SeqA_v1-SubjectTest_2026-03
MSP_P1-Controller_SeqA_v1-PainAngleTest_2026-03
```

---

## Appendix C: Tech Stack Requirements

| Tool | Purpose | Priority |
|---|---|---|
| **Instantly.ai** | Email sequencing, sending, warm-up, A/B testing | Required (in place) |
| **HubSpot** | CRM, deal tracking, source of truth | Required (in place) |
| **Salesforce** | AE pipeline management | Required (in place) |
| **PostgreSQL** | Central data warehouse for Metabase | Required (to build) |
| **Python ETL** | Data pipeline from Instantly + HubSpot APIs → PostgreSQL | Required (to build) |
| **Metabase** | Dashboards, reporting, attribution | Required (in place) |
| **Mail-tester.com or GlockApps** | Weekly deliverability testing | Recommended |
| **MXToolbox** | Blacklist monitoring | Recommended |
| **Google Postmaster Tools** | Domain reputation monitoring | Required (free) |
| **Apollo / ZoomInfo** | Lead enrichment and list building | Recommended |

---

## Appendix D: Accounting Vertical Persona Deep Dives

### Managing Partner / Firm Owner — Full Profile

**Who they are:** The founder or managing partner of an accounting/CAS firm with 11-100 employees. Unlike MSP CEOs who may be removed from billing, accounting firm owners are typically much closer to the AR process because billing IS their core business. They understand invoicing, collections, and reconciliation intimately.

**What keeps them up at night:**
- CAS practice is growing 17% YoY but billing complexity is growing faster
- Credit card fees are eating 2-5% of every payment with no clean pass-through
- Their best people are spending time on billing admin instead of client advisory
- Client billing friction is eroding the professional image they've built over 10+ years
- Tax season creates massive billing backlogs that take months to clear

**Their evaluation lens:**
- "Will this make my clients' experience better?" (relationship-first, like Jennifer)
- "Can we implement this without disrupting tax season?" (timing-sensitive)
- "Does this work with our QBO/Xero workflow, or is it another tool to manage?"
- "What do other firm owners say about it?" (peer validation is everything)

**Red flags for this persona:**
- Long-term contracts (they've been burned before)
- Complex implementations that require dedicated IT resources (they don't have IT)
- Solutions that don't integrate natively with QBO/Xero
- Aggressive sales tactics (they sell trust for a living — they can smell inauthenticity)

---

### CAS Director / Practice Lead — Full Profile

**Who they are:** The person running the Client Advisory Services practice within a mid-sized accounting firm. They manage a team of 3-10 bookkeepers/accountants who collectively handle AR for 50-100+ client businesses. They are measured on practice profitability, client retention, and efficiency metrics like clients-per-FTE.

**What keeps them up at night:**
- Managing AR across 50-100+ QBO/Xero files with no unified view
- Clients-per-FTE ratio is below the top-performer benchmark (10.2)
- The team is spending 40% of their time on billing admin instead of advisory
- Reconciliation errors across multiple client books are hard to catch
- Every new CAS client adds proportional billing workload

**Their evaluation lens:**
- "Can I see all my client books in one place?"
- "Will this help my team manage more clients without hiring?"
- "How fast can we implement across our existing client base?"
- "What does the client experience look like?"

---

*End of Framework Document*
*Alternative Payments — Instantly.ai Cold Outreach Master Framework v1.0*
