---
layout: post
title: "Your Biggest Exposure, Your Smallest Sublimit"
card_title: "Vendor Risk Insurance Gaps"
description: "Banks depend on core vendors for everything. Most insure that dependency with a sublimit that could exhaust in days. Here is what to check."
date: 2026-05-28
author: Joerg Proeve
category: Policy Deep-Dive
read_time: "7 min read"
image: /assets/images/Blog-Vendor-Exposure.png
image_alt: "Community bank vendor dependency versus cyber policy sublimit showing the gap between exposure and coverage"
last_modified_at: 2026-07-31
permalink: /insights/your-vendor-is-your-biggest-exposure/
faq:
  - question: "Does cyber insurance cover vendor outages at community banks?"
    answer: "It depends on the policy's dependent business interruption coverage. Most community bank cyber policies sublimit vendor outages at $100,000 to $1 million, well below the cost of a multi-day core platform outage. Coverage also depends on the trigger: some policies only cover vendor outages caused by a cyberattack (Security Breach), not outages from software failures or infrastructure upgrades. If your core processor goes down due to a bug rather than a hack, the narrow trigger may exclude you entirely."
  - question: "What is dependent business interruption coverage in a bank cyber policy?"
    answer: "Dependent business interruption coverage pays for income losses and extra expenses when a third-party vendor's systems go down and disrupt your bank's operations. For community banks, this typically means a core processor outage (Jack Henry, Fiserv, FIS). The coverage is almost always sublimited, often has a waiting period of 8-10 hours before it kicks in, and may require a written contract with the vendor. The sublimit, trigger type, waiting period, and contract requirement all determine whether a real vendor outage would be covered."
---

A community bank with $500 million in assets opens on a Monday morning. Tellers log in to the core banking system. Nothing loads. The mobile app shows a maintenance screen. ACH files are not processing. Wire transfers are stuck.

The bank's IT director calls the core platform provider. The answer: a ransomware attack hit the vendor's data center over the weekend. Systems are down. No timeline for restoration.

The bank's own systems are unaffected. Its firewalls held. Its backups are intact. But none of that matters, because every transaction the bank processes runs through that vendor's platform.

By Wednesday, the bank is still down. Branch staff are handling deposits manually. Commercial loan closings are postponed. The bank is losing fee income, paying overtime, and fielding calls from regulators. The estimated financial impact: $1.8 million in lost income and extra expenses over five days.

The bank files a claim under its cyber policy. Dependent business interruption coverage. $5 million limit on the declarations page.

The adjuster comes back with a number: $1 million. That is the sublimit for dependent BI. The $5 million applies to the bank's own systems. The vendor outage falls under a carve-out buried on page 34.

## This Is Not Hypothetical

In August 2025, Marquis Software Solutions, a fintech vendor serving more than 700 banks and credit unions, was hit by ransomware. The Akira group exploited an access control vulnerability in a SonicWall firewall. Customer records for more than 823,000 individuals were exposed across dozens of institutions. The banks themselves were not breached. Their own security held. But they depended on Marquis for data analytics, compliance reporting, and customer relationship tools. When Marquis went down, those functions went with it.

In May 2025, a planned infrastructure upgrade at Fiserv went wrong and knocked out online banking, Zelle, ACH processing, and direct deposits for dozens of banks, including Bank of America and Capital One. It was resolved in about 12 hours. In late 2023, a ransomware attack hit Ongoing Operations, a Trellance-owned disaster recovery unit that markets itself as the provider keeping credit unions running when nothing else works. The business-continuity vendor went down. About 60 credit unions lost access to systems for days.

<div style="background: #0A2540; border-radius: 12px; padding: 28px 32px; margin: 32px 0; color: #fff;">
<h3 style="color: #00D4AA; margin-top: 0; font-size: 18px;">Examiner Attention Is Already Here</h3>
<p style="color: rgba(255,255,255,0.8); font-size: 15px; line-height: 1.65; margin: 0;">After the Marquis breach, vendor concentration became the top examiner concern in cybersecurity conversations with community banks. Regulators are now asking whether insurance programs respond when critical vendors fail.</p>
</div>

Your examiner asks about vendor risk. Your insurer sublimits it. Nobody is checking whether the coverage matches the dependency.

## The Dependency Nobody Prices Correctly

A community bank's core processor (Jack Henry, Fiserv, FIS, CSI, Corelation) touches every function: deposits, lending, wires, online banking, regulatory reporting. These platforms are not interchangeable. Switching core vendors takes 12 to 18 months. When one goes down, the bank does not switch to a backup. The bank waits.

In five consecutive bank reviews, dependent BI coverage ranged from $100,000 to not purchased at all. The best-positioned program carried a $1 million sublimit. A multi-day core platform outage can generate $1.5 million to $2.5 million in losses. The sublimit covers 40 to 65 cents on the dollar.

Calculate what a day of downtime costs your bank: lost income, staff overtime, manual workarounds, customer impact. Then compare that number to your sublimit. Most banks I talk to have not done that math.

<div style="border-left: 3px solid #F59E0B; padding: 16px 20px; background: rgba(245,158,11,0.05); border-radius: 0 8px 8px 0; margin: 24px 0; font-size: 18px; font-weight: 600; color: #333;">
The bank's most critical technology relationship is often its least-insured exposure.
</div>

## What the Policy Says (and What It Means)

Dependent business interruption coverage isn't straightforward. It includes conditions that determine whether a vendor outage triggers coverage at all.

<div style="background: #0A2540; border-radius: 12px; padding: 32px; margin: 32px 0; color: #fff;">
<h3 style="color: #00D4AA; margin-top: 0; font-size: 18px;">Four Questions That Determine Whether Your Vendor Outage Is Covered</h3>
<div style="margin-top: 16px;">
<div style="background: rgba(59,130,246,0.1); border-radius: 8px; padding: 16px 20px; margin-bottom: 12px;">
<div style="color: #93C5FD; font-weight: 700; font-size: 14px; margin-bottom: 6px;">1. What Triggers Coverage?</div>
<div style="color: rgba(255,255,255,0.85); font-size: 15px; line-height: 1.6;">Some policies only cover vendor outages caused by a "Security Breach" (a cyberattack). Others also cover System Failure (any cause). If your vendor goes down due to a software bug, the narrow trigger may exclude you. Some carriers offer a System Failure buy-back at a lower sublimit. Check whether you have it.</div>
</div>
<div style="background: rgba(59,130,246,0.1); border-radius: 8px; padding: 16px 20px; margin-bottom: 12px;">
<div style="color: #93C5FD; font-weight: 700; font-size: 14px; margin-bottom: 6px;">2. Does It Require a Written Contract?</div>
<div style="color: rgba(255,255,255,0.85); font-size: 15px; line-height: 1.6;">Many policies define "Dependent Business" as a vendor with a written contract. If the contract expired, was never formalized, or is a click-wrap agreement, the vendor may not qualify.</div>
</div>
<div style="background: rgba(59,130,246,0.1); border-radius: 8px; padding: 16px 20px; margin-bottom: 12px;">
<div style="color: #93C5FD; font-weight: 700; font-size: 14px; margin-bottom: 6px;">3. Is the Sublimit Shared or Separate?</div>
<div style="color: rgba(255,255,255,0.85); font-size: 15px; line-height: 1.6;">Language like "part of and not in addition to" means the vendor sublimit shares an envelope with your main BI limit. A bank's own outage and a vendor outage in the same policy year compete for the same dollars.</div>
</div>
<div style="background: rgba(59,130,246,0.1); border-radius: 8px; padding: 16px 20px; margin-bottom: 12px;">
<div style="color: #93C5FD; font-weight: 700; font-size: 14px; margin-bottom: 6px;">4. Is There a Waiting Period?</div>
<div style="color: rgba(255,255,255,0.85); font-size: 15px; line-height: 1.6;">Standard waiting periods are 8-10 hours before coverage begins. For a severe outage, the most chaotic and expensive phase is uninsured. Also check the indemnity period: some policies cap dependent BI at 30, 60, or 90 days. That cap can bite before the dollar sublimit does.</div>
</div>
<div style="background: rgba(0,212,170,0.08); border-radius: 8px; padding: 16px 20px;">
<div style="color: #00D4AA; font-size: 15px; line-height: 1.6; font-style: italic;">The Fiserv outage was a software upgrade gone wrong, not a cyberattack. A community bank whose policy carries a Security-Breach-only trigger would have no coverage for an outage like this.</div>
</div>
</div>
</div>

## No Other Policy Picks This Up

The D&O policy does not cover this. No claim against directors. The fidelity bond does not cover this. No fraud occurred. The bank's single most critical operational dependency sits under the weakest coverage on the program, and there is no second policy behind it.

## What to Check at Your Next Renewal

<div style="background: #f8faf9; border-radius: 10px; padding: 28px 32px; margin: 24px 0;">
<div style="display: flex; gap: 16px; margin-bottom: 20px;">
<div style="min-width: 32px; height: 32px; background: #00D4AA; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: 700; color: #0A2540; font-size: 16px;">1</div>
<div><strong>Model a realistic core vendor outage.</strong> Take your core banking platform offline for five to seven days on paper. Calculate lost income, extra expenses, and customer impact. If the sublimit covers less than 70 percent of the modeled loss, request an increase at renewal.</div>
</div>
<div style="display: flex; gap: 16px; margin-bottom: 20px;">
<div style="min-width: 32px; height: 32px; background: #00D4AA; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: 700; color: #0A2540; font-size: 16px;">2</div>
<div><strong>Check the trigger.</strong> Does your dependent BI cover "Security Breach only" or "Security Breach and System Failure"? If it only responds to a cyberattack, you have no coverage when a vendor system simply stops working.</div>
</div>
<div style="display: flex; gap: 16px; margin-bottom: 20px;">
<div style="min-width: 32px; height: 32px; background: #00D4AA; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: 700; color: #0A2540; font-size: 16px;">3</div>
<div><strong>Confirm your core vendor qualifies.</strong> Is your core banking vendor named in the policy, covered by class definition, or excluded because the contract is structured differently than the policy requires?</div>
</div>
<div style="display: flex; gap: 16px;">
<div style="min-width: 32px; height: 32px; background: #00D4AA; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: 700; color: #0A2540; font-size: 16px;">4</div>
<div><strong>Ask your broker: what happens if our core vendor goes down for a week?</strong> If the answer is a $1 million sublimit against a $2 million exposure, you know what to negotiate. And if the waiting period is 8-10 hours, know what you are absorbing before coverage begins.</div>
</div>
</div>

Your bank cannot operate without its core platform. One vendor, no substitute, 12 to 18 months to switch. The insurance should reflect that dependency. In most cases, it does not.

Vendor concentration is one of five incident types where coverage breaks down across all three bank policies. I map the full picture in [Five Common Cyber Incidents, Three Policies, and the Gaps Between Them]({{ '/insights/five-incidents-three-policies/' | relative_url }}).

Find out whether your dependent BI trigger covers a vendor outage that was not a cyberattack. [Get in touch]({{ '/contact/' | relative_url }}).
