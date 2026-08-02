---
layout: post
title: "Five Common Cyber Incidents, Three Policies, and the Gaps Between Them"
card_title: "Five Incidents, Three Policies, and the Gaps Between Them"
description: "Most community banks carry cyber and D&O policies, plus a fidelity bond, from different carriers. Here is how those policies respond when five common cyber incidents hit, and where coverage falls apart."
date: 2026-04-15
author: Joerg Proeve
category: Case Study
read_time: "4 min read"
image: /assets/images/Blog-Policy-Interaction-Map.png
image_alt: "Policy interaction map showing how five cyber incidents trigger gaps between cyber, D&O, and fidelity bond policies"
last_modified_at: 2026-06-26
permalink: /insights/five-incidents-three-policies/
---

Most community banks carry three policies that touch cyber risk: a cyber policy, a directors and officers (D&O) policy, and a fidelity bond. Often these come from two or even three different carriers. Each one was underwritten separately. Nobody reads them together.

That is the problem. When a cyber incident hits, it does not stay inside the boundaries of one policy. A ransomware attack triggers the cyber policy, but the board's response lands on the D&O, and the ransom payment may hit the fidelity bond's computer fraud clause. Three carriers, three claims processes, three sets of exclusions. Each carrier points the finger at the other two.

The policy interaction map below shows how this plays out, row by row.

<p style="font-size:14px;font-weight:700;text-transform:uppercase;letter-spacing:0.05em;color:#64748b;margin:24px 0 8px 0;">Policy Interaction Map</p>
<div style="position:relative;margin:0 0 8px;">
<div style="position:absolute;top:52px;right:16px;background:#00D4AA;color:rgba(255,255,255,.85);padding:6px 12px;border-radius:999px;font-size:12px;font-weight:800;letter-spacing:.08em;z-index:1;">SAMPLE</div>
<img src="{{ '/assets/images/Policy-Interaction-Map.png' | relative_url }}" alt="Policy Interaction Map: five incidents mapped against cyber, D&O, and fidelity bond policies showing coverage gaps" style="width:100%;border-radius:10px;border:1px solid #e2e8f0;display:block;" loading="lazy">
</div>

## Row by Row: How Policies Respond to Cyber Incidents

### Wire Fraud

Wire transfer fraud may be the most common and most expensive cyber-related loss at community banks. The cyber policy does not respond, and not because it was not bought: cyber carriers generally do not write eCrime or social engineering coverage to financial institutions. That puts the entire exposure on one policy. The fidelity bond does cover wire fraud, and every bond I have read carries a social engineering endorsement, but with structural conditions attached: a sublimit well below the bond's headline limit, a deductible, on some carriers a co-payment, and a verification step the bank may not have documented. The D&O does not respond directly. The result: the bank's largest realistic loss is often the one with the weakest coverage. I wrote a [detailed walkthrough of how this plays out]({{ '/insights/the-wire-nobody-covers/' | relative_url }}) in a separate post.

### Ransomware

Most cyber policies cover this. That is the straightforward one. The fidelity bond may also respond, but typically with a sublimit on the extortion or computer fraud clause. The real question is whether the ransom payment and the business interruption loss both fall under the cyber limit, or whether the bond picks up part of it. If nobody has mapped this in advance, the bank finds out during the claim.

### Vendor Outage

When a critical vendor (e.g. FIS, Fiserv, Jack Henry) goes down and the bank cannot operate, the cyber policy may cover the business interruption, but only if the vendor qualifies under the policy's definition. Many cyber policies limit dependent business interruption to IT vendors and exclude non-IT service providers. The D&O does not cover this. The fidelity bond does not cover this. If the bank's core processor or cloud provider is not listed, the loss is uninsured.

### Data Breach and Regulatory Investigation

A data breach triggers the cyber policy for breach response costs: forensics, notification, credit monitoring. That part usually works. The gap shows up on the regulatory side. When state regulators or the OCC opens an investigation, defense costs can run into six figures. If the D&O carries a cyber exclusion, which many do, that policy is out and the whole regulatory response rides on the cyber form. Whether it responds from the first examiner letter or only once a formal proceeding opens depends on how that form defines a claim, and the community bank forms split on exactly that point.

### Board Liability After a Breach

After a significant cyber event, the question shifts from "what happened" to "who is responsible." Shareholder derivative claims, regulatory enforcement actions, and examiner scrutiny all land on the board. The D&O should answer, but many D&O policies now carry broad cyber exclusions that carve out any claim "arising from" a data breach or cyber event.

The cyber policy is the fallback, and it works better than most boards assume: open the definitions section and directors are named as insureds. Two things narrow it. There is no Side A layer, so the board's defense competes for the same limit the bank has been spending on notification since day one. And the securities exclusion varies enormously between forms. One community bank form reaches common law claims "pled in tandem with, or in lieu of" a securities violation, brought "directly or derivatively," which is broad enough to capture a post-breach derivative suit. Others are limited to securities transactions and would not.

## What the Map Tells You

Look at the policy interaction map as a whole. The rows with the most red are the ones where coverage breaks down: wire transfer fraud, regulatory investigations, board liability after a breach. These are not outliers. They are the incidents that land on a community bank CFO's desk. On the last two, the failure is rarely a flat denial. It is one policy stepping out and the other carrying more than it was priced to carry.

Most banks that carry all three policies assume they are covered. But nobody has read the policies together and asked: for this specific incident, which carrier pays? Until someone does that work, each carrier has a reason to say no, and the bank holds the loss. For a closer look at how each of these failures plays out, see [six ways coverage fails at claim time]({{ '/coverage-gaps/' | relative_url }}).

Find out which carrier pays on each of these five incidents, using your actual limits and exclusions. [Get in touch]({{ '/contact/' | relative_url }}).
