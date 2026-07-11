---
layout: post
title: "I Audited Five Community Banks and Credit Unions. They All Had Similar Gaps."
card_title: "Five Audits, Similar Gaps"
description: "Five community banks and credit unions. Different carriers. Different program structures. Similar coverage failures appeared in every audit: wire fraud conditions, D&O cyber exclusions, vendor coverage mismatches, headline limits that overstate recovery, and revenue definitions that ignore interest income."
date: 2026-06-16
author: Joerg Proeve
category: Case Study
read_time: "7 min read"
image: /assets/images/Blog-Five-Audits-Same-Gaps.png
image_alt: "Five community bank insurance audits revealing similar coverage gaps across different carriers and program structures"
last_modified_at: 2026-07-10
permalink: /insights/five-audits-same-gaps/
faq:
  - question: "What are the most common insurance gaps at community banks?"
    answer: "Based on audits of five community banks and credit unions across different carriers and program structures, the most common gaps are: wire fraud conditions that can reduce recovery to zero (sublimits, verification warranties, co-payments, and classification swings), D&O cyber exclusions that leave board members uninsured after a breach, vendor outage coverage that does not match vendor dependence, headline limits that overstate realistic recovery by 70 to 85 percent, and business interruption definitions that exclude interest income, which is 70 to 85 percent of a bank's revenue."
  - question: "Is wire fraud covered by cyber insurance or the fidelity bond?"
    answer: "Wire fraud coverage sits primarily on the fidelity bond, not the cyber policy. Most carriers will not sell social engineering or eCrime coverage to financial institutions on the cyber side. However, fidelity bonds often impose conditions that reduce the payout: sublimits between $100,000 and $500,000, verification procedure warranties that void coverage if not followed, and co-payment clauses. Additionally, recovery depends on how forensics classifies the attack. The same wire fraud loss can recover the full bond limit under a computer fraud classification or only the sublimit under a social engineering classification, a swing of $4.25 million to $4.75 million across the banks audited."
  - question: "Does a D&O policy protect bank directors after a cyber breach?"
    answer: "In most community bank programs, the D&O policy excludes claims arising from a cyber event. The intent is to push those claims to the cyber policy, but the cyber policy covers breach response costs, not claims against individual board members for oversight failures. After a breach, directors can face personal liability with neither policy responding. This gap appeared in every bank audited."
  - question: "Does bank insurance cover vendor outages?"
    answer: "Coverage for vendor outages across the audited banks ranged from $100,000 to zero. One bank had not purchased the coverage at all, even though it was available in the policy form. A five-day outage at a core banking vendor could cost an estimated $500,000 or more, with no insurance recovery. Examiners are now asking about vendor risk management, but the insurance that backstops vendor failures does not match vendor dependence at most banks."
  - question: "Do headline insurance limits reflect what a bank will recover?"
    answer: "No. Across the five banks audited, combined headline limits ranged from $12 million to $27 million. Realistic recovery on a multi-front cyber incident ranged from $500,000 to $3 million, a gap of 70 to 85 percent. The erosion comes from sublimits that share the aggregate, defense costs paid inside the limit, co-payment clauses, D&O cyber exclusions, and coverage gaps between the three policies where each carrier points at the others."
  - question: "Does cyber insurance cover a bank's interest income during an outage?"
    answer: "Most cyber policies exclude interest income from the business interruption definition. For a community bank, interest income is 70 to 85 percent of revenue. Two banks in this sample had a flat hourly rate of $500 for BI payouts, against hourly interest income of $1,400 to $2,200. On a five-day outage, one bank would recover $48,000 on a $269,000 loss. Only one carrier in the sample offered an endorsement that fixes this. One bank had it. The rest did not."
---

Over the past months, I audited the insurance policies at five community banks and credit unions. I read the actual policy forms, the endorsements and amendments across their cyber and D&O policies, and their fidelity bonds.

The five financial institutions had little in common. Asset sizes ranged from under $500 million to over $1 billion. They reported to different regulators. They used different insurance program structures, and different carriers. Premiums varied across the group.

However, the gaps were similar.

Very similar structural problems appeared in every program, regardless of bank size or carrier. That pattern changes the conversation. One bank with a gap is a broker discussion. Five banks with five different programs yet similar coverage gaps, that's an industry problem.

<h2 style="display: flex; align-items: center; gap: 14px;"><svg width="34" height="34" viewBox="0 0 24 24" fill="none" stroke="#2563EB" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="flex-shrink: 0; margin-top: 0;" aria-hidden="true"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/><polyline points="22,6 12,13 2,6"/></svg><span>Gap 1: Wire Fraud Coverage Had Conditions That Could Reduce Recovery to Zero</span></h2>

Every bank had social engineering coverage on its fidelity bond. Not the cyber policy. Most carriers won't sell social engineering or eCrime coverage to financial institutions on the cyber side. That's not a broker miss. It's how the market is structured. The bond carries the full load.

The problem is what happens when you read the endorsement. Three catches appeared across the sample.

**Sublimits.** Social engineering limits ranged from $100,000 to $500,000. Every bank in this group moves multiples of that amount in wire transfers daily. The FBI estimates nearly $3 billion in annual wire fraud losses. The coverage doesn't match.

**Verification warranties.** All five banks had a callback verification requirement written as a condition precedent. For transfers over $25,000, the employee must call the requestor back on a pre-established number to confirm the instruction. If the employee skips the callback, coverage drops to zero. Not reduced. Eliminated. This was designed for email-based BEC, where a phone call could catch the fraud. It was not designed for deepfake voice calls, where the attacker clones the CFO's voice and answers the callback.

**Co-payments.** One bank had a 50% co-payment clause on all funds transfer claims. On a $2 million wire fraud, the bank pays more than $1 million out of pocket. This was the program with the highest annual premium of the five.

Even when the endorsement applies, recovery depends on how forensics classifies the attack. Every fidelity bond had multiple fraud coverages with different limits and non-overlapping definitions. "Computer Systems Fraud" might carry a $5 million limit. "Social Engineering" might carry only $250,000. The same loss, same dollar amount, same attacker, could recover either amount depending entirely on a forensic judgment call made weeks after the event. Across the banks, these swings ranged from $4.25 million to $4.75 million.

<div style="border-left: 3px solid #F59E0B; padding: 16px 20px; background: rgba(245,158,11,0.05); border-radius: 0 8px 8px 0; margin: 24px 0; font-size: 18px; font-weight: 600; color: #333;">
A $5 million bond can pay $250,000 if the attack is classified as "Social Engineering" instead of "Computer Fraud." And if the employee skipped the verification call, the bond pays nothing.
</div>

For the full analysis, see [The Wire Nobody Covers]({{ '/insights/the-wire-nobody-covers/' | relative_url }}) and [What Your Fidelity Bond Won't Pay]({{ '/insights/fidelity-bond/' | relative_url }}).

<h2 style="display: flex; align-items: center; gap: 14px;"><svg width="34" height="34" viewBox="0 0 24 24" fill="none" stroke="#DC2626" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="flex-shrink: 0; margin-top: 0;" aria-hidden="true"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/><line x1="9" y1="9" x2="15" y2="15"/><line x1="15" y1="9" x2="9" y2="15"/></svg><span>Gap 2: Every D&O Policy Had a Cyber Exclusion</span></h2>

Every D&O policy excluded claims "arising from a cyber event," with varying severity. One carrier excluded anything "arising out of or in any way involving" a data breach. That language blocks all D&O claims after a cyber incident, including regulatory investigations into whether the board met its oversight obligations. Another carrier narrowed the cyber exclusion and added an exception for certain privacy claims. That proves that tighter language is available. The default across all five programs, however, was broad cyber exclusion.

This exclusion matters even more as cyber threats are rapidly increasing and, at the same time, regulators are tightening board accountability. Over the past three years, the FFIEC, OCC, and FDIC have each raised expectations for board-level cybersecurity governance. The FFIEC examination handbook requires boards to provide "credible challenge" to management's cybersecurity assertions. The NCUA made board cybersecurity training a named supervisory priority for the first time in 2026. Publicly traded banks now face SEC cybersecurity disclosure requirements.

The regulatory direction is clear: boards are expected to understand and oversee cyber risk. The D&O exclusions are moving in the opposite direction.

After a breach, examiners will investigate whether directors met their duty of care. That investigation is a D&O matter. If the D&O policy excludes any cyber-related claims, the directors face it without coverage. And the cyber policy doesn't fill this gap. Cyber policies cover mainly breach response costs: forensics, notification, credit monitoring. They don't cover claims against individual board members for oversight failures.

<div style="border-left: 3px solid #DC2626; padding: 16px 20px; background: rgba(220,38,38,0.05); border-radius: 0 8px 8px 0; margin: 24px 0; font-size: 18px; font-weight: 600; color: #333;">
The policy that protects directors excludes cyber. The policy that covers cyber incidents doesn't protect directors. After a breach, neither one covers the investigation of the board.
</div>

For the full scenario, see [The Board Nobody Insures]({{ '/insights/the-board-nobody-insures/' | relative_url }}).

<h2 style="display: flex; align-items: center; gap: 14px;"><svg width="34" height="34" viewBox="0 0 24 24" fill="none" stroke="#7C3AED" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="flex-shrink: 0; margin-top: 0;" aria-hidden="true"><rect x="2" y="2" width="20" height="8" rx="2" ry="2"/><rect x="2" y="14" width="20" height="8" rx="2" ry="2"/><line x1="6" y1="6" x2="6.01" y2="6"/><line x1="6" y1="18" x2="6.01" y2="18"/></svg><span>Gap 3: Vendor Coverage Did Not Match Vendor Dependence</span></h2>

Every bank in this group depends on a core banking platform vendor. When that platform goes down, the bank can't process transactions, access accounts, or serve customers. An August 2025 data breach that affected more than 700 financial institutions through a single vendor made this the examiner's number one concern.

Coverage for vendor outages ranged from $100,000 to zero. One bank hadn't purchased the coverage at all, even though it was available in the policy form; it had never come up in the renewal process. A five-day outage at that bank's core vendor would cost an estimated $500,000, with no insurance recovery.

Examiners are now asking about vendor risk management. They want to see that the bank has assessed its critical vendor dependencies and has a plan if a vendor fails. The insurance that's supposed to backstop that risk doesn't come close.

For more on this gap, see [The Vendor You Cannot Replace]({{ '/insights/the-vendor-you-cannot-replace/' | relative_url }}).

<h2 style="display: flex; align-items: center; gap: 14px;"><svg width="34" height="34" viewBox="0 0 24 24" fill="none" stroke="#D97706" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="flex-shrink: 0; margin-top: 0;" aria-hidden="true"><line x1="12" y1="3" x2="12" y2="21"/><line x1="4" y1="7" x2="20" y2="7"/><polyline points="4 7 2 13 7 13"/><polyline points="20 7 17 13 22 13"/></svg><span>Gap 4: Headline Limits Overstated Recovery by 70 to 85 Percent</span></h2>

Every bank had what looked like adequate insurance on the declarations page. Combined limits across the cyber policy, the fidelity bond, and the D&O policy ranged from $12 million to $27 million. Those numbers are what the board sees at renewal. They are not what the bank collects after a loss.

The realistic recovery on a multi-front cyber incident, one that triggers wire fraud, breach response, regulatory investigation, and board liability at the same time, ranged from $500,000 to $3 million. The gap between the headline and the recovery was 70 to 85 percent.

The erosion comes from sublimits that share the aggregate ("part of and not in addition to" the policy limit), defense costs paid inside the limit rather than in addition to it, co-payment clauses, D&O cyber exclusions that zero out board protection, verification warranties that void wire fraud coverage, and the gaps between the three policies where each carrier points at the others. A $5 million cyber policy with typical sublimits can pay $650,000 on a $4.2 million ransomware loss. Stack that against a bond that pays the sublimit and a D&O that excludes the claim, and the bank's total recovery on a multi-front incident is a fraction of its combined limits.

One bank: $12 million in combined limits. Realistic multi-front recovery: approximately $500,000.

Most renewal conversations focus on the premium and the headline limit. The sublimit architecture underneath, the part that determines whether the bank recovers $3.5 million or $650,000, is in the policy forms. The forms are 60 pages of legal language. They are rarely read at renewal.

<div style="border-left: 3px solid #DC2626; padding: 16px 20px; background: rgba(220,38,38,0.05); border-radius: 0 8px 8px 0; margin: 24px 0; font-size: 18px; font-weight: 600; color: #333;">
The declarations page is a summary, not a promise. One bank: $12 million in combined limits, approximately $500,000 in realistic recovery.
</div>

For a detailed walkthrough, see [The Fine Print Inside the Coverage]({{ '/insights/the-fine-print-inside-the-coverage/' | relative_url }}).

<h2 style="display: flex; align-items: center; gap: 14px;"><svg width="34" height="34" viewBox="0 0 24 24" fill="none" stroke="#059669" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="flex-shrink: 0; margin-top: 0;" aria-hidden="true"><line x1="12" y1="1" x2="12" y2="23"/><path d="M17 5H9.5a3.5 3.5 0 0 0 0 7h5a3.5 3.5 0 0 1 0 7H6"/></svg><span>Gap 5: 70 Percent of Bank Revenue May Not Be Insured During a Cyber Outage</span></h2>

Community banks earn 70 to 85 percent of their revenue from net interest income. For a $500 million bank, that's $15 to $20 million per year, roughly $1,400 to $2,200 per hour during business operations.

Cyber policy business interruption is supposed to replace income lost during an outage. But most BI definitions were written for commercial businesses where interest income is incidental. For a bank, it's the business.

Two banks in this sample were on the same carrier program. Their cyber policies use a flat hourly rate for BI payouts: $500 per hour. At one bank, hourly interest income is approximately $2,200. On a five-day outage, total income loss is approximately $269,000. The BI recovery: $48,000. The gap is 82 percent.

Two other banks had BI definitions that use phrases like "income from business operations" without addressing interest income specifically. Not excluded by name. Not included by name. Ambiguous, worded in a way that pays when the carrier wants it to, not when the bank needs it to.

One bank had an endorsement that deletes the interest income exclusion entirely. It was the single most valuable endorsement in that bank's program. No other carrier in the sample offered an equivalent.

This gap wasn't in my initial methodology. I identified it after recognizing the pattern on the fifth audit. If an independent auditor focused on bank-specific risk missed it initially, the odds that a generalist broker is checking for it are low.

<div style="border-left: 3px solid #F59E0B; padding: 16px 20px; background: rgba(245,158,11,0.05); border-radius: 0 8px 8px 0; margin: 24px 0; font-size: 18px; font-weight: 600; color: #333;">
The carrier program used by two banks in this sample also insures approximately 1,700 community banks nationally. The interest income gap may not be a single-bank finding.
</div>

For the full analysis, see [The Revenue Your Policy Ignores]({{ '/insights/the-revenue-your-policy-ignores/' | relative_url }}).

## What the Pattern Means

If these were problems with one carrier's forms, the fix would be to switch carriers. But these gaps appeared across all programs and all carriers, and across different bank profiles. Similar issues showed up at the small mutual savings bank and the billion-dollar publicly traded institution.

The gaps are structural. The way bank insurance programs are designed, with breach response on the cyber policy, D&O written without reference to it, fraud pushed to the fidelity bond, and BI definitions borrowed from commercial lines, creates seams between the policies. Claims land in those seams. Headline limits mask the gaps. And the revenue definition that's supposed to make the bank whole ignores the bank's primary income. Nobody pays.

<div style="background: #0A2540; border-radius: 12px; padding: 32px; margin: 32px 0; color: #fff;">
<div style="color: #fff; font-weight: 700; font-size: 22px; margin-bottom: 24px;">Closing these coverage gaps costs a fraction of the exposure they create.</div>

<div class="stats-comparison" style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-bottom: 16px;">
<div style="background: rgba(220,38,38,0.1); border-radius: 8px; padding: 20px;">
<div style="color: #FCA5A5; font-weight: 700; font-size: 13px; text-transform: uppercase; letter-spacing: 0.05em; margin-bottom: 8px;">Uninsured Exposure</div>
<div style="color: #fff; font-size: 28px; font-weight: 700;">As high as $7M</div>
</div>
<div style="background: rgba(0,212,170,0.1); border-radius: 8px; padding: 20px;">
<div style="color: #00D4AA; font-weight: 700; font-size: 13px; text-transform: uppercase; letter-spacing: 0.05em; margin-bottom: 8px;">Cost to reduce 70% of the exposure</div>
<div style="color: #fff; font-size: 28px; font-weight: 700;">5-15% additional premium</div>
</div>
</div>
<p style="margin: 0; font-size: 13px; color: #fff; line-height: 1.5;">Numbers depend on the bank's size, program structure, and identified coverage gaps.</p>
</div>

## What the Banks Did With the Findings

Every bank received a prioritized action plan: which gaps to fix mid-term, which to address at renewal, and which to monitor, with estimated costs and specific negotiation language for the broker.

These audits started a conversation between the bank leaders, their brokers and carriers, and their boards that wasn't happening before. The banks have reduced their uninsured exposure, and the process of closing the remaining gaps is underway.

None of these banks were aware of these coverage gaps before the risk audit. Brokers review each policy individually and manage the renewal. A [Risk Intelligence Report]({{ '/insights/what-is-a-risk-intelligence-report/' | relative_url }}) reads the policies together, tests them against claim scenarios, and maps the seams between them. That's a different job.

## What This Means for Your Bank

Your bank may use a different carrier, a different program, a different broker. Based on my audits across carriers and program types, the structural gaps will likely be similar. The seams between cyber, D&O, and the fidelity bond are built into how these products are designed.

If nobody has read your policies side by side and tested which one pays for realistic cyber scenarios, you don't know where your coverage fails. You know what you bought. You don't know what you'll collect.

<div style="border-left: 3px solid #00D4AA; padding: 16px 20px; background: rgba(0,212,170,0.05); border-radius: 0 8px 8px 0; margin: 24px 0; font-size: 18px; font-weight: 600; color: #333;">
A Risk Intelligence Report costs less than the response to a single wire fraud. If you want to know what your insurance program really covers, <a href="{{ '/contact/' | relative_url }}" style="color: #00D4AA;">get in touch</a>.
</div>
