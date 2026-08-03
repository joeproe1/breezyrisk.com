---
layout: post
title: "The Revenue Your Policy Ignores: Cyber BI Doesn't Cover a Bank's Primary Income"
card_title: "The Revenue Your Policy Ignores"
description: "Most cyber BI definitions exclude interest income, which is the bulk of a community bank's revenue. The exclusion is real, but it does not bite where most people point. Here is where it actually costs you."
date: 2026-07-10
author: Joerg Proeve
category: Policy Deep-Dive
read_time: "6 min read"
image: /assets/images/Blog-Revenue-Your-Policy-Ignores.png
image_alt: "Community bank interest income excluded from cyber policy business interruption coverage"
permalink: /insights/the-revenue-your-policy-ignores/
last_modified_at: 2026-08-03
---

A community bank loses its core platform for five days. No wires, no ACH, no online banking, no originations. It files a business interruption claim on the cyber policy and recovers $48,000, against a five-day revenue figure well north of $200,000.

That comparison gets used to sell a lot of policy reviews. I used it myself in the first version of this article. It is the wrong comparison, and working out why it is wrong tells you more about your cyber policy than the original point did.

## The arithmetic that does not hold

Start with what makes a bank different. Net interest income, the spread between what the loan book earns and what the deposit book costs, is the large majority of a community bank's revenue. Fee and service income is the rest. Pull your last call report if you want your own split; the non-interest income line gives it to you directly.

From there the intuition is easy and wrong: if the systems that run the bank stop, the income the bank earns stops with them.

It doesn't. A loan accrues interest under its note. A deposit accrues interest expense under its terms. Neither obligation is conditioned on whether the servicing platform is up. When the core comes back, the accruals are sitting there. The income was earned during the outage in the only sense that matters, which is contractually. Multiplying net interest income by outage days produces a large and frightening number that is not a loss.

<div style="background: #0A2540; border-radius: 12px; padding: 32px; margin: 32px 0; color: #fff;">
<h3 style="color: #00D4AA; margin-top: 0; font-size: 18px;">What a Five-Day Outage Does to Each Revenue Stream</h3>
<div style="display: flex; flex-wrap: wrap; gap: 16px; margin-bottom: 4px;">
<div style="flex: 1; min-width: 200px; background: rgba(255,255,255,0.06); border-left: 4px solid #94A3B8; border-radius: 8px; padding: 20px;">
<div style="color: #94A3B8; font-weight: 700; font-size: 14px; text-transform: uppercase; letter-spacing: 0.05em; margin-bottom: 10px;">Net Interest Income</div>
<div style="font-size: 26px; font-weight: 700; color: #94A3B8; line-height: 1.2;">Keeps accruing</div>
<div style="color: rgba(255,255,255,0.7); font-size: 15px; margin-top: 8px;">Excluded or ambiguous in most BI definitions. In a short outage there is little here to claim, because little of it was lost.</div>
</div>
<div style="flex: 1; min-width: 200px; background: rgba(0,212,170,0.12); border-left: 4px solid #00D4AA; border-radius: 8px; padding: 20px;">
<div style="color: #00D4AA; font-weight: 700; font-size: 14px; text-transform: uppercase; letter-spacing: 0.05em; margin-bottom: 10px;">Fee &amp; Service Income</div>
<div style="font-size: 26px; font-weight: 700; color: #00D4AA; line-height: 1.2;">Stops, and does not return</div>
<div style="color: rgba(255,255,255,0.7); font-size: 15px; margin-top: 8px;">NSF and overdraft, interchange, wire fees, service charges, ATM. This is the real business interruption claim.</div>
</div>
</div>
</div>

## What actually stops

Fee income. Overdraft and NSF charges, interchange, wire fees, service charges, ATM fees. Those are earned per transaction, and a transaction that does not happen does not come back. No customer overdrafts twice the following week to make up for the week your systems were down.

Two more categories sit next to it. Loan originations deferred during the outage, most of which get booked afterward, so the damage is timing rather than principal. And remediation and extra expense, which is real money and usually sits under a separate part of the cyber policy with its own sublimit.

Add that up and the honest reading of the opening scenario changes. The $48,000 recovery that looked like it covered less than a fifth of the loss may have covered most of what was actually lost.

## So why does the exclusion matter

Because the five-day outage is not the event that hurts you.

Run the clock out to two or three weeks and two things happen that do not happen in five days. Depositors who cannot reach their money start moving it, and replacing runoff means paying up for funding on a loan book you cannot reprice at the same speed. That compresses the spread. Separately, borrowers under stress stop paying, loans migrate toward non-accrual, and previously booked interest gets reversed off the income statement.

Both of those are interest income losses in the plain sense. They are also exactly what the exclusion bars.

So the gap is real, and the market has it priced backwards. It is overstated for the short outage that every tabletop exercise models, and understated for the severe event that almost nobody models.

<div style="background: #0A2540; border-radius: 12px; padding: 28px 32px; margin: 32px 0; color: #fff;">
<h3 style="color: #00D4AA; margin-top: 0; margin-bottom: 16px; font-size: 18px;">Where the Exclusion Bites</h3>
<div style="display: flex; flex-wrap: wrap; gap: 16px;">
<div style="flex: 1; min-width: 220px; padding: 4px 0;">
<div style="color: #94A3B8; font-weight: 700; font-size: 13px; text-transform: uppercase; letter-spacing: 0.05em; margin-bottom: 10px;">Short outage, three to five days</div>
<div style="color: rgba(255,255,255,0.85); font-size: 15px; line-height: 1.6;">Interest accrues through it. Fee income is the loss, and most BI definitions cover fee income. The exclusion costs you little.</div>
</div>
<div style="flex: 1; min-width: 220px; padding: 4px 0; border-left: 1px solid rgba(0,212,170,0.35); padding-left: 24px;">
<div style="color: #00D4AA; font-weight: 700; font-size: 13px; text-transform: uppercase; letter-spacing: 0.05em; margin-bottom: 10px;">Severe event, two weeks and beyond</div>
<div style="color: rgba(255,255,255,0.85); font-size: 15px; line-height: 1.6;">Deposit runoff raises funding cost. Non-accrual reversals claw back booked interest. Now interest income is a genuine loss, and now the exclusion bars it.</div>
</div>
</div>
</div>

## Three ways it shows up in the form

**Explicit exclusion.** The income definition carves out "interest or investment income" by name. This is the cleanest version, and the easiest to argue about before a claim rather than during one.

**Ambiguous definition.** The form says "income from business operations" or "net profit before income taxes" and never addresses interest income. For a commercial business those phrases capture the main revenue stream and nobody thinks about it. For a bank they leave the largest line on the income statement to be characterized by a carrier at claim time.

**Flat hourly rate.** Some programs pay BI at a set rate per hour. One I reviewed paid $500. A flat rate is not a measurement of anything; it is a substitute for measuring. It does not ask what you lost, which means it can overpay a short outage and badly underpay a long one, and the bank has no way to tell which side it is on until the claim is open.

Most banks I reviewed had one of these three. One had solved it.

## The fix

Some carriers write an endorsement that deletes the interest and investment income exclusion from the income definition. Where I have seen it, it cost between nothing and $2,000 a year. One bank in my sample had it, and given what a severe event does to a bank's accrual book, it was the single most valuable endorsement in their program.

If your carrier does not offer it, ask for written confirmation that "income from business operations" includes net interest income for a financial institution. Ask at renewal, in writing, and keep the answer. An ambiguity resolved in advance is worth more than an argument you win eighteen months into a claim.

<div style="background: #f8faf9; border-radius: 10px; padding: 28px 32px; margin: 24px 0;">
<div style="display: flex; gap: 16px; margin-bottom: 16px;">
<div style="min-width: 32px; height: 32px; background: #00D4AA; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: 700; color: #0A2540; font-size: 16px;">1</div>
<div><strong>Find the BI or Income Loss definition in your cyber policy.</strong> Look for "interest income" by name. If it is absent, and the definition rests on "income from business operations," you have an ambiguity the carrier controls at claim time.</div>
</div>
<div style="display: flex; gap: 16px; margin-bottom: 16px;">
<div style="min-width: 32px; height: 32px; background: #00D4AA; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: 700; color: #0A2540; font-size: 16px;">2</div>
<div><strong>If your BI pays a flat hourly rate, ask what the rate was based on.</strong> Note the rate and the waiting period. If nobody at the carrier or the brokerage can tell you how the number was derived for a bank, it was not derived for a bank.</div>
</div>
<div style="display: flex; gap: 16px; margin-bottom: 16px;">
<div style="min-width: 32px; height: 32px; background: #00D4AA; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: 700; color: #0A2540; font-size: 16px;">3</div>
<div><strong>Ask your broker about an interest income endorsement.</strong> Some carriers offer one. If yours does not, that belongs in the renewal decision alongside price.</div>
</div>
<div style="display: flex; gap: 16px;">
<div style="min-width: 32px; height: 32px; background: #00D4AA; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: 700; color: #0A2540; font-size: 16px;">4</div>
<div><strong>Size it from fee income, not from net interest income.</strong> Take the non-interest income line off your call report, reduce it to a daily figure, and apply your outage assumption. That is your realistic BI claim. Then model the severe case separately: what two or three weeks down does to deposit runoff and to your accrual book. The second number is the one that belongs in the risk register, and it is the one the exclusion is standing in front of.</div>
</div>
</div>

Your cyber policy was written to cover system outages for businesses that stop earning when the systems stop. A bank does not work that way, and the BI definition was never adjusted for it. In a short outage that mismatch is mostly harmless. In the event that actually threatens the institution, it is the difference between a covered loss and an argument.

The interest income exclusion is one of several gaps that only surface when cyber, fidelity bond, and D&O policies are read together. I map the full picture in [Five Audits. Same Gaps.]({{ '/insights/five-audits-same-gaps/' | relative_url }}).

Find out whether your cyber BI definition counts net interest income as covered revenue. [Get in touch]({{ '/contact/' | relative_url }}).

<div style="border-top: 1px solid #e5e7eb; margin-top: 40px; padding-top: 20px; font-size: 14px; color: #6b7280; line-height: 1.6;">
<strong>Updated August 3, 2026.</strong> The original version of this article quantified the gap by multiplying net interest income by outage days, and presented a five-day recovery shortfall of 77 to 82 percent. That arithmetic does not hold, because interest accrues under the note whether or not the core platform is running. I have corrected the analysis and moved the exposure to where it belongs, which is the severe extended event rather than the short outage. The exclusion itself, the three policy patterns, and the endorsement fix are unchanged.
</div>
