# Alternative Payments — ICP-Specific Email Sequences

**Version:** 1.0 | **Date:** March 25, 2026 | **Owner:** ABM Team
**Segment:** Leads with KNOWN incumbent tool (ConnectWise PSA users + QuickBooks Payments users)
**Relationship to Master Framework:** These are standalone sequences that REPLACE the general persona sequences (A–H) when the lead's current tool is confirmed. Leads route here instead.

---

## Routing Logic

```
Lead enters system
    │
    ├─ Tool identified as ConnectWise PSA user?
    │     └─ YES → Route to Sequences I–L (by persona)
    │
    ├─ Tool identified as QuickBooks Payments user?
    │     └─ YES → Route to Sequences M–P (by persona)
    │
    └─ Tool NOT identified (80% of leads)?
          └─ Route to general sequences A–H (master framework)
```

---

## Email Length Guidelines (Same as Master Framework)

| Email Stage | Max Words | Purpose |
|---|---|---|
| **Email 1 — Pain Opener** | **45 words** | One tool-specific pain. One question. |
| **Email 2A — Social Proof** (opened) | **65 words** | Tool-specific proof point. |
| **Email 2B — New Subject** (not opened) | **55 words** | Same angle, new hook. |
| **Email 3A — New Angle** (opened) | **60 words** | Pivot to secondary tool-specific pain. |
| **Email 3B — Reframe** (not opened) | **40 words** | Strip to core value prop. |
| **Email 4A — Value Drop** (opened) | **90 words** | Stat-heavy, earns length. |
| **Email 4B — Hail Mary** (not opened) | **30 words** | Curiosity one-liner. |
| **Email 5 — Breakup** | **35 words** | Graceful exit. Name-drop customers. |

**CRITICAL RULE: No links in any email. Landing pages are AE-only post-reply resources (see Post-Reply Resource Kit at the end of this document).**

---

# CONNECTWISE PSA USER SEQUENCES

These sequences target MSPs where ConnectWise PSA (Manage) is confirmed as their PSA platform. The messaging focuses on ConnectWise-specific billing pain — the gap between a world-class PSA and a clunky payment layer — without naming specific competitors.

---

## SEQUENCE I: ConnectWise MSP — Controller/Finance Manager (P1)

**Email 1 — Pain Opener (Day 0)** ⸻ *Max 45 words*
Subject: ConnectWise + payments at [Company]

> Hi {{firstName}},
>
> Quick question — how many hours does your team spend each month reconciling payments back to ConnectWise? PSA data in one system, payment data in another, and a spreadsheet holding it together.
>
> Is that the setup at [Company]?
>
> {{senderFirstName}}

*(38 words)* — CW-specific reconciliation pain. Every CW controller feels this.

---

**Email 2A — Social Proof (Day 3, if opened but no reply)** ⸻ *Max 65 words*
Subject: RE: ConnectWise + payments at [Company]

> Hi {{firstName}},
>
> One data point — a ConnectWise MSP processing ~$80K/month cut month-end close from 7 days to 2 after getting payments to sync bi-directionally with Manage. DSO dropped 11 days in the first quarter.
>
> The difference: payments post back to ConnectWise automatically — no manual matching, no broken records.
>
> If that gap exists at [Company], happy to share how.
>
> {{senderFirstName}}

*(60 words)*

---

**Email 2B — New Subject (Day 4, if NOT opened)** ⸻ *Max 55 words*
Subject: ConnectWise billing gap at [Company]

> Hi {{firstName}},
>
> ConnectWise is a great PSA. But the billing layer on top? That's where most controllers I talk to lose hours — matching payments to agreements, fixing sync errors, and manually reconciling between systems.
>
> Worth a 5-minute conversation, or is your process already dialed in?
>
> {{senderFirstName}}

*(46 words)*

---

**Email 3A — Fee Pass-Through Angle (Day 7, if opened but no reply)** ⸻ *Max 60 words*
Subject: CC fees on ConnectWise invoices

> Hi {{firstName}},
>
> Different question — is [Company] absorbing credit card fees on ConnectWise invoices, or passing them through to clients?
>
> Most CW MSPs I talk to absorb $1,500-3,000/month because their billing tool has no compliant pass-through. That's $18-36K/year in recovered margin.
>
> Applies to [Company]?
>
> {{senderFirstName}}

*(49 words)* — Pivots to fee absorption, #1 pain across all win data.

---

**Email 3B — Reframe (Day 8, if NOT opened)** ⸻ *Max 40 words*
Subject: [Company] + ConnectWise billing

> {{firstName}} — I help ConnectWise MSPs automate the billing layer so payments sync back to Manage without manual reconciliation.
>
> If that gap exists at [Company], I'd love to hear about it.
>
> {{senderFirstName}}

*(30 words)*

---

**Email 4A — Value Drop (Day 14, if opened but no reply)** ⸻ *Max 90 words*
Subject: ConnectWise billing data point

> Hi {{firstName}},
>
> One stat from ConnectWise MSPs we work with: 70%+ client autopay adoption within 90 days of switching to a billing layer that actually syncs with Manage.
>
> The biggest shift isn't chasing payments — it's that autopay adjusts to fluctuating invoice amounts (seat count changes, project work) without breaking. Clients self-enroll through a branded portal, payments post to ConnectWise automatically, and your team stops doing financial detective work at month-end.
>
> If that would move the needle at [Company], I think we'd have a good conversation.
>
> {{senderFirstName}}

*(87 words)* — The one email that earns length. Standalone value.

---

**Email 4B — Hail Mary (Day 15, if NOT opened)** ⸻ *Max 30 words*
Subject: ConnectWise + payments

> {{firstName}} — if payments synced back to ConnectWise automatically and your team never reconciled manually again, would that be worth a conversation?
>
> {{senderFirstName}}

*(22 words)*

---

**Email 5 — Breakup (Day 21, all paths converge)** ⸻ *Max 35 words*
Subject: closing the loop

> {{firstName}} — timing isn't right. If you ever want to see how ConnectWise MSPs like {{customer_name_or_fallback: "Integris, Valiant, and TeamLogic IT"}} eliminated manual reconciliation, the door is open.
>
> {{senderFirstName}}

*(29 words)*

---

## SEQUENCE J: ConnectWise MSP — CEO/Owner (P2)

**Email 1 — Pain Opener (Day 0)** ⸻ *Max 45 words*
Subject: quick question about [Company]

> Hi {{firstName}},
>
> I talk to ConnectWise MSP founders every week. One theme keeps surfacing — their PSA is world-class, but the billing experience clients see is clunky.
>
> Is that something you hear from clients at [Company]?
>
> {{senderFirstName}}

*(39 words)* — Peer observation. Jennifer cares about client experience + professionalism.

---

**Email 2A — Peer Proof (Day 3, if opened but no reply)** ⸻ *Max 65 words*
Subject: RE: quick question about [Company]

> Hi {{firstName}},
>
> One ConnectWise MSP founder put it well: *"We invested six figures in our PSA but were sending clients a clunky checkout link from our payment tool. It didn't reflect who we are."*
>
> After switching to a branded portal that syncs with Manage: 70%+ autopay adoption, month-end close went from 7 days to 2.
>
> Worth hearing more?
>
> {{senderFirstName}}

*(56 words)*

---

**Email 2B — New Subject (Day 4, if NOT opened)** ⸻ *Max 55 words*
Subject: client billing experience at [Company]

> Hi {{firstName}},
>
> The ConnectWise MSPs growing fastest made billing a competitive advantage — a branded portal clients actually use, autopay that works with fluctuating invoices, and a billing experience that reflects the professionalism of their managed services.
>
> Is upgrading the client payment experience on the radar at [Company]?
>
> {{senderFirstName}}

*(47 words)*

---

**Email 3A — Scalability Angle (Day 7, if opened but no reply)** ⸻ *Max 60 words*
Subject: scaling [Company] without adding billing headcount

> Hi {{firstName}},
>
> Can [Company]'s current ConnectWise billing setup handle 2x the client base without adding another person?
>
> Most CW MSP founders I talk to found the answer was no — their billing layer couldn't keep up with what Manage handled easily. Invoicing, reconciliation, and collections didn't scale.
>
> Worth a conversation?
>
> {{senderFirstName}}

*(50 words)* — Pivots to scalability, Jennifer's growth concern.

---

**Email 3B — Reframe (Day 8, if NOT opened)** ⸻ *Max 40 words*
Subject: [Company]'s billing layer

> {{firstName}} — I help ConnectWise MSP founders upgrade the billing layer so it matches their PSA. Branded portal, automated collections, and payments that sync back without manual work.
>
> Relevant to [Company]?
>
> {{senderFirstName}}

*(28 words)*

---

**Email 4A — Customer Story (Day 14, if opened but no reply)** ⸻ *Max 90 words*
Subject: what ConnectWise MSP founders are saying

> Hi {{firstName}},
>
> Three quotes from CW MSP founders I've spoken with recently:
>
> *"Clients used to complain about billing. Now they compliment it."*
>
> *"We can 2x revenue without 2x financial ops headcount. The billing layer finally keeps up with the PSA."*
>
> *"Three separate bills from our old setup. Three support queues. Now it's one vendor, one invoice, and it just works."*
>
> If hearing directly from another CW MSP founder would help, I'm happy to connect you. No pitch — just an introduction.
>
> {{senderFirstName}}

*(85 words)*

---

**Email 4B — Hail Mary (Day 15, if NOT opened)** ⸻ *Max 30 words*
Subject: one question

> {{firstName}} — if your clients could pay through a branded portal that syncs directly to ConnectWise, would that change the billing experience at [Company]?
>
> {{senderFirstName}}

*(24 words)*

---

**Email 5 — Breakup (Day 21, all paths converge)** ⸻ *Max 35 words*
Subject: last note from me

> {{firstName}} — timing isn't right. If upgrading the ConnectWise billing experience ever becomes a priority, I'm easy to find.
>
> {{senderFirstName}}

*(19 words)*

---

## SEQUENCE K: ConnectWise MSP — CFO (P3)

**Email 1 — Metrics Opener (Day 0)** ⸻ *Max 45 words*
Subject: [Company]'s DSO + ConnectWise

> Hi {{firstName}},
>
> Do you have real-time DSO visibility from ConnectWise — or does your team rebuild it from month-old exports?
>
> Most CW MSP CFOs I talk to know the number isn't great but can't see it in real time. Sound familiar?
>
> {{senderFirstName}}

*(42 words)* — Metric hook. Bob needs real-time data, not month-old spreadsheets.

---

**Email 2A — ROI Angle (Day 3, if opened but no reply)** ⸻ *Max 65 words*
Subject: RE: [Company]'s DSO + ConnectWise

> Hi {{firstName}},
>
> Quick math for a ConnectWise MSP processing $50-100K/month: every day of DSO improvement = $1,600-$3,300 in accelerated cash flow. Our average in Q1 was 9 days.
>
> Add recovered CC fees through compliant pass-through ($1,500-3,000/month for most CW MSPs) and eliminated reconciliation labor — payback is typically 3-4 months.
>
> Want the model with [Company]'s numbers? Takes 15 minutes.
>
> {{senderFirstName}}

*(63 words)*

---

**Email 2B — New Subject (Day 4, if NOT opened)** ⸻ *Max 55 words*
Subject: ConnectWise MSP finance metrics

> Hi {{firstName}},
>
> I help ConnectWise MSP CFOs get real-time DSO and cash visibility — data that syncs from Manage, not month-end exports. Typical results: 9-day DSO improvement, 3-4 month payback, and recovered CC fees through compliant pass-through.
>
> If relevant to [Company]'s finance team, worth a conversation?
>
> {{senderFirstName}}

*(47 words)*

---

**Email 3A — Vendor Cost Angle (Day 7, if opened but no reply)** ⸻ *Max 60 words*
Subject: how many bills for billing?

> Hi {{firstName}},
>
> Different angle — how many separate invoices does [Company] pay each month just to accept payment alongside ConnectWise?
>
> Many CW MSP CFOs I talk to are paying a platform fee, a gateway fee, and a processing fee — three bills from three vendors. That's before reconciliation labor.
>
> Is that your setup?
>
> {{senderFirstName}}

*(52 words)* — Pivots to vendor sprawl / hidden costs. Bob's TCO concern.

---

**Email 3B — Reframe (Day 8, if NOT opened)** ⸻ *Max 40 words*
Subject: [Company] finance ops

> {{firstName}} — real-time DSO from ConnectWise, recovered CC fees, and one flat invoice instead of three. If any of that matters to [Company]'s finance team, I'd like to hear your current setup.
>
> {{senderFirstName}}

*(31 words)*

---

**Email 4A — Delayed Hire (Day 14, if opened but no reply)** ⸻ *Max 90 words*
Subject: the $55K question

> Hi {{firstName}},
>
> At [Company]'s current growth rate, when will you need another AR person?
>
> ConnectWise MSP CFOs I work with found they could delay that hire by 12-18 months through billing automation that actually syncs with Manage — saving $55K+ in fully-loaded cost while improving DSO. The math: payments post to ConnectWise automatically, autopay handles fluctuating invoices, and compliant CC fee pass-through recovers $1,500-3,000/month in margin.
>
> If you're modeling next year's headcount, this might change the numbers.
>
> {{senderFirstName}}

*(81 words)*

---

**Email 4B — Hail Mary (Day 15, if NOT opened)** ⸻ *Max 30 words*
Subject: quick ROI question

> {{firstName}} — $55K+ in delayed AR hiring, recovered CC fees, and one bill instead of three. Would the math be worth 15 minutes?
>
> {{senderFirstName}}

*(23 words)*

---

**Email 5 — Breakup (Day 21, all paths converge)** ⸻ *Max 35 words*
Subject: closing the loop

> {{firstName}} — timing isn't right. When DSO, ConnectWise billing costs, or AR headcount becomes a priority, I'll be here with the ROI math ready.
>
> {{senderFirstName}}

*(24 words)*

---

## SEQUENCE L: ConnectWise MSP — AR Specialist/Billing Coordinator (P4)

**Email 1 — Empathy Opener (Day 0)** ⸻ *Max 45 words*
Subject: ConnectWise + the reconciliation spreadsheet

> Hi {{firstName}},
>
> Are you still matching payments to ConnectWise agreements by hand — logging into your payment tool, checking the bank, then updating Manage manually?
>
> Most AR specialists at CW MSPs I talk to assumed that's just how it works. Is that the setup at [Company]?
>
> {{senderFirstName}}

*(44 words)* — Empathy opener. Sarah manages payments across CW + bank + spreadsheet daily.

---

**Email 2A — Social Proof (Day 3, if opened but no reply)** ⸻ *Max 65 words*
Subject: RE: ConnectWise + the reconciliation spreadsheet

> Hi {{firstName}},
>
> One AR specialist at a CW MSP described her old process as "toggling between three systems for every payment" — Manage for invoices, the payment tool for transactions, and a spreadsheet to match them. 10-15 hours a month just on reconciliation.
>
> After automating, payments post to ConnectWise automatically. She got those hours back.
>
> Sound familiar?
>
> {{senderFirstName}}

*(57 words)*

---

**Email 2B — New Subject (Day 4, if NOT opened)** ⸻ *Max 55 words*
Subject: ConnectWise billing automation for [Company]

> Hi {{firstName}},
>
> If payments posted to ConnectWise automatically — no manual matching, no toggling between systems, no reconciliation spreadsheet — what would you do with the extra 10+ hours a month?
>
> Curious if that resonates at [Company], or if your process is already dialed in.
>
> {{senderFirstName}}

*(44 words)*

---

**Email 3A — Autopay Angle (Day 7, if opened but no reply)** ⸻ *Max 60 words*
Subject: autopay that works with ConnectWise

> Hi {{firstName}},
>
> Quick question — does your autopay break when ConnectWise invoice amounts change?
>
> That's the #1 complaint I hear from CW MSP billing teams. Fluctuating seat counts or project work mean autopay cancels, and you're manually charging each card.
>
> Autopay that adjusts to fluctuating CW invoices + client self-enrollment. Worth a quick look?
>
> {{senderFirstName}}

*(52 words)* — Broken autopay is #2 switch reason from QBP win analysis (universal pain).

---

**Email 3B — Reframe (Day 8, if NOT opened)** ⸻ *Max 40 words*
Subject: billing team question

> {{firstName}} — I help ConnectWise MSP billing teams eliminate manual reconciliation and get clients on autopay that doesn't break when invoice amounts change. If your team spends hours on payment admin, this might help.
>
> {{senderFirstName}}

*(33 words)*

---

**Email 4A — Collections Angle (Day 14, if opened but no reply)** ⸻ *Max 90 words*
Subject: collections calls — the worst part of the job?

> Hi {{firstName}},
>
> Most AR specialists I know hate collections calls. It's awkward, damages client relationships, and rarely works.
>
> What if you never had to make another one — and still got paid faster?
>
> One billing coordinator at a ConnectWise MSP went from chasing 15-20 overdue accounts per month to zero calls. Automated collections with an ~80% recovery rate on 30+ day invoices, all syncing back to Manage without manual updates.
>
> If collections is a pain at [Company], this is worth seeing.
>
> {{senderFirstName}}

*(82 words)*

---

**Email 4B — Hail Mary (Day 15, if NOT opened)** ⸻ *Max 30 words*
Subject: save 10+ hours/month on ConnectWise billing?

> {{firstName}} — 10-15 hours a month reconciling payments to ConnectWise. Sound familiar? Happy to show you what "after" looks like.
>
> {{senderFirstName}}

*(20 words)*

---

**Email 5 — Breakup (Day 21, all paths converge)** ⸻ *Max 35 words*
Subject: last note

> {{firstName}} — if you ever want to see what ConnectWise billing looks like without the spreadsheets, I'm here. Wishing you a smooth month-end close.
>
> {{senderFirstName}}

*(25 words)*

---

# QUICKBOOKS PAYMENTS USER SEQUENCES

These sequences target accounting/CAS firms where QuickBooks Payments is confirmed as their payment processor. The messaging focuses on QBP-specific limitations — fee absorption, broken autopay, no client portal, rising ACH fees — derived from 65 closed-won deal analyses and landing page proof points.

**Key QBP Stats to Weave In (1-2 per email max):**
- $2,340/month avg savings from surcharging (LP stat)
- 42% avg DSO reduction after switching (LP stat)
- 15 hrs/month saved on collections (LP stat)
- ACH fees rising to $25 cap in 2026 (battlecard)
- 2.9% + $0.30 per card with no pass-through (battlecard)
- 70%+ autopay adoption within 90 days (universal stat)

---

## SEQUENCE M: QBP Accounting — Managing Partner/Owner (P1)

**Email 1 — Pain Opener (Day 0)** ⸻ *Max 45 words*
Subject: quick question about QuickBooks Payments at [Company]

> Hi {{firstName}},
>
> Is [Company] absorbing credit card fees through QuickBooks Payments? QBP has no built-in way to pass them through — most firms I talk to are losing $1,500-5,000/month without realizing there's an alternative.
>
> Is that your situation?
>
> {{senderFirstName}}

*(39 words)* — #1 switch reason from 65 QBP closed-won deals. Direct, specific.

---

**Email 2A — Social Proof (Day 3, if opened but no reply)** ⸻ *Max 65 words*
Subject: RE: quick question about QuickBooks Payments at [Company]

> Hi {{firstName}},
>
> One accounting firm switched from QBP and recovered $2,800/month in CC fees through compliant surcharging — same clients, same invoices, just a different payment layer alongside QuickBooks.
>
> They also got 70%+ of CAS clients on autopay (QBP's autopay breaks when amounts change) and cut month-end close from a week to 2 days.
>
> Worth hearing more?
>
> {{senderFirstName}}

*(57 words)*

---

**Email 2B — New Subject (Day 4, if NOT opened)** ⸻ *Max 55 words*
Subject: QBP fees at [Company]

> Hi {{firstName}},
>
> QuickBooks Payments charges 2.9% + $0.30 per card — with no way to pass that to clients. On $30K monthly billing, that's $900+ out of pocket every month.
>
> Firms I work with keep invoicing in QuickBooks but process payments through a layer that recovers those fees.
>
> Worth a conversation?
>
> {{senderFirstName}}

*(51 words)*

---

**Email 3A — Autopay + Portal Angle (Day 7, if opened but no reply)** ⸻ *Max 60 words*
Subject: QBP autopay + the portal gap

> Hi {{firstName}},
>
> Beyond fees — does your QBP autopay break when invoice amounts change? And when clients want to see old invoices, do they email your team because QBP has no portal?
>
> One firm told us they fielded 50-60 invoice lookup emails a month before switching to a self-service client portal.
>
> Sound familiar?
>
> {{senderFirstName}}

*(53 words)* — Pivots to broken autopay + no portal, #2 and #4 switch reasons.

---

**Email 3B — Reframe (Day 8, if NOT opened)** ⸻ *Max 40 words*
Subject: [Company] + QuickBooks billing

> {{firstName}} — I help accounting firms keep invoicing in QuickBooks but upgrade the payment layer. Fee pass-through, working autopay, and a client portal.
>
> If QBP's limitations are a pain, I'd love to learn more.
>
> {{senderFirstName}}

*(33 words)*

---

**Email 4A — Full Value Drop (Day 14, if opened but no reply)** ⸻ *Max 90 words*
Subject: what QBP is actually costing [Company]

> Hi {{firstName}},
>
> Three numbers from firms that switched from QuickBooks Payments:
>
> **42% average DSO reduction.** Autopay that works + automated collections = clients pay faster.
>
> **$2,340/month saved.** Compliant surcharging recovers CC fees QBP forces you to absorb.
>
> **15 hours/month back.** No more manual payment reminders, reconciliation, or fielding "where's my invoice?" emails — a client portal handles it.
>
> You keep invoicing in QuickBooks. The payment layer just gets smarter. If any of those numbers matter to [Company], I think we'd have a good conversation.
>
> {{senderFirstName}}

*(89 words)* — The value drop. Uses all three LP headline stats.

---

**Email 4B — Hail Mary (Day 15, if NOT opened)** ⸻ *Max 30 words*
Subject: QuickBooks Payments question

> {{firstName}} — keep QuickBooks, drop the payment fees. Would recovering $1,500-5,000/month in absorbed CC fees be worth a conversation?
>
> {{senderFirstName}}

*(19 words)*

---

**Email 5 — Breakup (Day 21, all paths converge)** ⸻ *Max 35 words*
Subject: last note from me

> {{firstName}} — timing isn't right. If QBP's fees, broken autopay, or lack of a client portal ever becomes a priority, I'm easy to find.
>
> {{senderFirstName}}

*(25 words)*

---

## SEQUENCE N: QBP Accounting — CAS Director / Practice Lead (P2)

**Email 1 — Pain Opener (Day 0)** ⸻ *Max 45 words*
Subject: QuickBooks Payments across client books

> Hi {{firstName}},
>
> Running CAS across dozens of clients through QBP means no client portal, no real autopay, and CC fees you can't pass through — multiplied across every book.
>
> Is QBP's payment layer holding back [Company]'s CAS practice?
>
> {{senderFirstName}}

*(39 words)* — Scale observation. CAS Directors feel QBP limitations multiplied across books.

---

**Email 2A — Social Proof (Day 3, if opened but no reply)** ⸻ *Max 65 words*
Subject: RE: QuickBooks Payments across client books

> Hi {{firstName}},
>
> One CAS director managing 60+ client books through QBP told me: *"QBP autopay broke every month because amounts changed. I was manually charging each client's card."*
>
> After switching to a payment layer alongside QuickBooks: autopay handles fluctuating amounts, one dashboard replaces logging into QBO separately, and 70%+ of clients enrolled in autopay within 90 days.
>
> Worth sharing how?
>
> {{senderFirstName}}

*(59 words)*

---

**Email 2B — New Subject (Day 4, if NOT opened)** ⸻ *Max 55 words*
Subject: CAS billing beyond QBP

> Hi {{firstName}},
>
> QuickBooks Payments across dozens of CAS client books = no unified dashboard, no client portal, autopay that breaks on amount changes, and CC fees you absorb on every transaction.
>
> Firms I work with keep invoicing in QBO but process payments differently. Worth a conversation?
>
> {{senderFirstName}}

*(45 words)*

---

**Email 3A — Fee Recovery + Hero Positioning (Day 7, if opened but no reply)** ⸻ *Max 60 words*
Subject: recovering CC fees for your CAS clients

> Hi {{firstName}},
>
> Different angle — what if you could save each CAS client $1,000-5,000/year by switching their payment processing to one with compliant fee pass-through?
>
> QBP has no surcharging option. A better payment layer alongside QuickBooks does. You become the advisor who found the savings.
>
> Interested in how other CAS practices handle this?
>
> {{senderFirstName}}

*(53 words)* — Positions CAS Director as hero to their clients.

---

**Email 3B — Reframe (Day 8, if NOT opened)** ⸻ *Max 40 words*
Subject: CAS + QBP question

> {{firstName}} — scaling CAS on QuickBooks Payments means multiplying its limitations. Fee absorption, broken autopay, no portal — across every client book. If that squeeze is real, let's talk.
>
> {{senderFirstName}}

*(28 words)*

---

**Email 4A — Capacity Benchmark (Day 14, if opened but no reply)** ⸻ *Max 90 words*
Subject: the 7.4 clients-per-FTE benchmark

> Hi {{firstName}},
>
> Industry data: median CAS practice manages 7.4 clients per FTE. Top performers manage 10.2.
>
> The difference isn't talent — it's how much billing/collections time is automated vs. manual. QBP forces manual work at every step: broken autopay, no collection workflows, reconciliation by hand across each QBO file.
>
> CAS practices that replace QBP's payment layer (while keeping QuickBooks for invoicing) reclaim 15+ hours/month and push client-per-FTE ratios toward the top tier.
>
> If [Company]'s CAS practice wants to close that gap, I think we'd have a productive conversation.
>
> {{senderFirstName}}

*(90 words)* — CAS benchmarks + QBP as the bottleneck.

---

**Email 4B — Hail Mary (Day 15, if NOT opened)** ⸻ *Max 30 words*
Subject: QBP + CAS capacity

> {{firstName}} — how many CAS clients can your team manage before you need another hire? If QBP is the bottleneck, we should talk.
>
> {{senderFirstName}}

*(24 words)*

---

**Email 5 — Breakup (Day 21, all paths converge)** ⸻ *Max 35 words*
Subject: closing the loop

> {{firstName}} — I'll take the hint. If QBP's limitations start holding back your CAS growth, I'm here.
>
> {{senderFirstName}}

*(17 words)*

---

## SEQUENCE O: QBP Accounting — CFO/Controller (P3)

**Email 1 — Metrics Opener (Day 0)** ⸻ *Max 45 words*
Subject: [Company]'s DSO + QuickBooks Payments

> Hi {{firstName}},
>
> Do you know what QBP is actually costing [Company] beyond the transaction fees? DSO impact, reconciliation labor, absorbed CC fees — most CFOs I talk to haven't totaled it up.
>
> Have you run that number?
>
> {{senderFirstName}}

*(38 words)* — Metric hook reframed as hidden cost. Bob is analytical — give him a puzzle.

---

**Email 2A — ROI Angle (Day 3, if opened but no reply)** ⸻ *Max 65 words*
Subject: RE: [Company]'s DSO + QuickBooks Payments

> Hi {{firstName}},
>
> Quick math — firms that switch from QBP see a 42% average DSO reduction and $2,340/month in recovered CC fees through compliant surcharging. Add eliminated reconciliation labor (QBP forces manual matching) and the payback is typically under 90 days.
>
> You keep invoicing in QuickBooks. The payment layer just gets smarter.
>
> Want the model with [Company]'s numbers?
>
> {{senderFirstName}}

*(58 words)*

---

**Email 2B — New Subject (Day 4, if NOT opened)** ⸻ *Max 55 words*
Subject: QBP true cost at [Company]

> Hi {{firstName}},
>
> QuickBooks Payments: 2.9% + $0.30 per card, 1% ACH (cap rising to $25 in 2026), no fee pass-through, no automated collections. The visible fees are just the start — reconciliation labor and DSO drag add up fast.
>
> If that TCO matters to [Company], worth a conversation.
>
> {{senderFirstName}}

*(48 words)*

---

**Email 3A — ACH Fee Hike Angle (Day 7, if opened but no reply)** ⸻ *Max 60 words*
Subject: QBP's 2026 ACH fee increase

> Hi {{firstName}},
>
> Are you aware QBP is raising ACH fee caps by over 100% in 2026? Standard caps going from $3 to $5, Enterprise from $7 to $15. For a firm processing $50K+/month in ACH, that's a meaningful hit.
>
> We offer free ACH on all plans. Worth comparing the math?
>
> {{senderFirstName}}

*(52 words)* — Pivots to ACH fee hike. Timely, specific, quantifiable. Bob's language.

---

**Email 3B — Reframe (Day 8, if NOT opened)** ⸻ *Max 40 words*
Subject: [Company] payment processing

> {{firstName}} — real-time DSO, recovered CC fees, free ACH, and one flat invoice. If QBP's hidden costs concern [Company]'s finance team, I'd like to hear about your current setup.
>
> {{senderFirstName}}

*(28 words)*

---

**Email 4A — Delayed Hire + Fee Recovery (Day 14, if opened but no reply)** ⸻ *Max 90 words*
Subject: what QBP is costing vs. what it should

> Hi {{firstName}},
>
> Three line items QBP adds to [Company]'s cost structure that most CFOs don't bucket together:
>
> **1. CC fee absorption:** $1,500-5,000/month with no pass-through option.
> **2. ACH fees:** 1% per transaction, cap rising to $25 in 2026. Free elsewhere.
> **3. Reconciliation labor:** QBP forces manual matching — 10-15 hours/month at loaded cost.
>
> Total hidden cost for a mid-size firm: $4,000-8,000/month. Our flat subscription replaces all three.
>
> If you're evaluating finance ops efficiency this year, the math speaks for itself.
>
> {{senderFirstName}}

*(88 words)* — Bob's dream email. Three line items, clean math, no fluff.

---

**Email 4B — Hail Mary (Day 15, if NOT opened)** ⸻ *Max 30 words*
Subject: QBP cost question

> {{firstName}} — $4,000-8,000/month in hidden QBP costs (fees + labor + DSO drag). Would the math be worth 15 minutes?
>
> {{senderFirstName}}

*(19 words)*

---

**Email 5 — Breakup (Day 21, all paths converge)** ⸻ *Max 35 words*
Subject: closing the loop

> {{firstName}} — timing isn't right. When QBP's total cost of ownership becomes a priority, I'll be here with the ROI math ready.
>
> {{senderFirstName}}

*(21 words)*

---

## SEQUENCE P: QBP Accounting — Office Manager/Billing Lead (P4)

**Email 1 — Empathy Opener (Day 0)** ⸻ *Max 45 words*
Subject: QuickBooks Payments + the manual work

> Hi {{firstName}},
>
> Are you still sending QBP checkout links, manually chasing payments, and fielding "where's my invoice?" emails because there's no client portal?
>
> Most office managers I talk to assumed that's just how QuickBooks billing works. Is that the setup at [Company]?
>
> {{senderFirstName}}

*(42 words)* — Empathy opener. #4 QBP pain: no portal = constant inbound emails.

---

**Email 2A — Social Proof (Day 3, if opened but no reply)** ⸻ *Max 65 words*
Subject: RE: QuickBooks Payments + the manual work

> Hi {{firstName}},
>
> One billing lead at a CAS firm told us she fielded 50-60 "where's my invoice?" emails per month because QBP has no client portal. She also manually charged each client's card because QBP autopay broke when amounts changed.
>
> After switching: a client portal handles the emails, autopay actually works, and she saves 15+ hours a month.
>
> Sound familiar?
>
> {{senderFirstName}}

*(61 words)*

---

**Email 2B — New Subject (Day 4, if NOT opened)** ⸻ *Max 55 words*
Subject: QBP billing automation for [Company]

> Hi {{firstName}},
>
> If you could replace QBP checkout links with a client portal — where clients see all invoices, manage payment methods, and enroll in autopay that actually works — what would you do with the extra 15 hours a month?
>
> Curious if that resonates at [Company].
>
> {{senderFirstName}}

*(43 words)*

---

**Email 3A — Autopay Angle (Day 7, if opened but no reply)** ⸻ *Max 60 words*
Subject: QBP autopay — does it actually work?

> Hi {{firstName}},
>
> Quick question — does your QBP autopay break when invoice amounts change?
>
> That's the #1 complaint I hear. CAS billing amounts fluctuate monthly, QBP cancels autopay, and you're manually charging each client's card. One billing manager described it as "autopay that isn't auto."
>
> Working autopay + client self-enrollment. Worth a quick look?
>
> {{senderFirstName}}

*(52 words)* — #2 switch reason from 65 QBP closed-won deals.

---

**Email 3B — Reframe (Day 8, if NOT opened)** ⸻ *Max 40 words*
Subject: billing team question

> {{firstName}} — I help accounting firm billing teams replace QBP's manual work with a client portal, working autopay, and automated collections. If your team spends hours on payment admin, this might help.
>
> {{senderFirstName}}

*(30 words)*

---

**Email 4A — Collections Angle (Day 14, if opened but no reply)** ⸻ *Max 90 words*
Subject: chasing overdue payments without QBP helping

> Hi {{firstName}},
>
> QBP sends basic reminders. That's it. No escalation rules, no automated sequences, no collections workflow. When a client doesn't pay, you're chasing them manually — phone calls, personal emails, awkward conversations.
>
> One billing manager I work with went from manually tracking overdue accounts to automated collections with an ~80% recovery rate on 30+ day invoices. No phone calls. The system handles escalation, and payments sync back to QuickBooks automatically.
>
> If chasing payments is a pain at [Company], this is worth seeing.
>
> {{senderFirstName}}

*(84 words)* — QBP has zero collections logic. #5 switch reason.

---

**Email 4B — Hail Mary (Day 15, if NOT opened)** ⸻ *Max 30 words*
Subject: save 15 hours/month on billing?

> {{firstName}} — 15+ hours a month on manual QBP work (reminders, reconciliation, "where's my invoice?" emails). Sound familiar? Happy to show you "after."
>
> {{senderFirstName}}

*(23 words)*

---

**Email 5 — Breakup (Day 21, all paths converge)** ⸻ *Max 35 words*
Subject: last note

> {{firstName}} — if you ever want to see what billing looks like beyond QuickBooks Payments (while keeping QuickBooks), I'm here. Wishing you a smooth month-end close.
>
> {{senderFirstName}}

*(28 words)*

---

# POST-REPLY RESOURCE KIT

**Purpose:** When a lead from these sequences replies positively, AEs have tool-specific landing pages to share during the conversation. These links are NEVER included in cold email sequences — they are conversation assets for post-reply engagement only.

---

## ConnectWise PSA Users (Sequences I–L)

**Landing Page:** [https://go.alternativepayments.io/pmm/msp/lp-05-connectwise-billing-alternative](https://go.alternativepayments.io/pmm/msp/lp-05-connectwise-billing-alternative)

**What's on the page:**
- 4-way comparison table: AP vs. ConnectBooster vs. WisePay vs. Stripe
- Customer testimonials from CW MSPs who switched from ConnectBooster
- KPI highlights: 70%+ autopay adoption, $0 ACH fees, no long-term contracts
- Integration showcase: ConnectWise Manage, QBO, Autotask, HaloPSA, Sage + 9 more
- Live demo booking form with ConnectWise-specific data walkthrough

**When to share:**
- After the first positive reply, in the AE's response email or during the discovery call
- Frame it as: *"I'll send over a page that shows exactly how it works inside ConnectWise — it has a comparison table and some data from MSPs who made the switch."*
- Do NOT send as a standalone link with no context

**Suggested AE copy for sharing:**
> I put together a page that walks through how Alternative Payments runs inside ConnectWise — comparison data, results from MSPs who switched, and integration details. Here it is: [link]
>
> Worth a look before our call, but no pressure — we'll cover everything live.

---

## QuickBooks Payments Users (Sequences M–P)

**Landing Page:** [https://go.alternativepayments.io/pmm/accounting/lp-11-quickbooks-payments-alternative](https://go.alternativepayments.io/pmm/accounting/lp-11-quickbooks-payments-alternative)

**What's on the page:**
- Pain point breakdown: fee absorption (2.9%+$0.30), broken autopay, no portal, no collections
- Feature comparison: AP vs. QBP (8 categories)
- Results: 42% DSO reduction, $2,340/mo savings, 15 hrs/mo saved
- Customer testimonial from QBP switcher
- 3-step onboarding: Connect QB → Import → Start getting paid
- Live demo booking form

**When to share:**
- After the first positive reply, in the AE's response email or during the discovery call
- Frame it as: *"Here's a quick breakdown of how we work alongside QuickBooks — shows exactly what changes and what stays the same."*
- Emphasize: "You keep invoicing in QuickBooks. We just upgrade the payment layer."

**Suggested AE copy for sharing:**
> Here's a page that breaks down exactly how Alternative Payments works alongside QuickBooks — what you gain, what stays the same, and results from firms that switched from QBP: [link]
>
> Quick read before our call, or we can walk through it together.

---

## General Rules for Landing Page Sharing

1. **Never share in cold email** — these are post-reply assets only
2. **Always add context** — never send a bare link. Frame why it's relevant.
3. **Time it right** — share after the first positive reply or during discovery call scheduling, not after demo (too late)
4. **Track it** — log in HubSpot when the LP link is shared. Metabase can correlate LP views with deal progression.
5. **Don't over-rely on it** — the landing page supports the conversation, it doesn't replace it
