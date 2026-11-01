---
layout: post
title: "Buy, Build, or Wait"
description: "Core system vendors are acquiring the AI capabilities their carrier clients can't build. Two decades of outsourcing left carriers without the engineering bench to do it themselves."
date: 2026-11-02
author: Joerg Proeve
category: Carrier Technology Strategy
read_time: "5 min read"
image: /assets/images/Blog-Buy-Build-or-Wait.png
image_alt: "Dark blue header with the title Buy, Build, or Wait and the subtitle about core system vendors acquiring AI capabilities."
permalink: /insights/buy-build-or-wait/
---

Guidewire is acquiring hyperexponential for $1.7 billion, a London-based underwriting and pricing platform. Duck Creek acquired Send last July for its AI-native underwriting orchestration. Core system vendors are going upstream, buying AI capabilities they didn't build themselves.

The companies that sit between carriers and their data are the ones making the acquisitions.

## How we got here

Insurance carriers spent two decades reshaping their technology organizations. In the 2000s, the move was to outsource: managed services, offshore development, vendor-run infrastructure. IT became a cost center to be managed down.

Then the modernization wave arrived. Guidewire migrations that were supposed to take 18 months stretched past three years. Data lake initiatives consumed millions and delivered dashboards nobody trusted. The carriers that survived it learned that you can't modernize what you don't understand internally.

Most didn't finish rebuilding. The engineering bench had thinned to the point where "technology strategy" meant vendor selection. The same organizations that outsourced their way out of engineering in 2005 were trying to insource their way back by 2020, and the talent market had moved on.

Then AI arrived, and the talent that did exist started leaving. Mid-career AVPs and directors stuck behind deep promotion queues traded a slow carrier climb for equity and autonomy at AI-native startups. Federato poached its CRO from Duck Creek and its APAC lead from Guidewire. Reserv's founders came from Snapsheet. When carriers want AI capability at the leadership level now, they buy entire companies. Travelers paid $435 million for Corvus. ERGO paid $2.6 billion for NEXT Insurance. These are talent acquisitions as much as book acquisitions.

## The lock-in layer

Insurance has a problem most industries don't: core systems sit between AI and the work.

<div style="margin: 36px auto; max-width: 480px; font-family: var(--font-mono), 'JetBrains Mono', monospace;">
<!-- AI Layer -->
<div style="background: #0A2540; border: 2px solid #3B82F6; border-radius: 10px; padding: 18px 24px; text-align: center;">
<div style="font-size: 13px; font-weight: 700; color: #3B82F6; text-transform: uppercase; letter-spacing: 0.05em; margin-bottom: 6px;">AI Capabilities</div>
<div style="font-size: 12px; color: rgba(255,255,255,0.5); line-height: 1.5;">hyperexponential &middot; Send &middot; Planck &middot; Cytora</div>
</div>
<!-- Integration gap -->
<div style="display: flex; align-items: center; gap: 10px; padding: 10px 0; justify-content: center;">
<div style="flex: 1; height: 1px; background: repeating-linear-gradient(90deg, #F59E0B 0, #F59E0B 6px, transparent 6px, transparent 12px);"></div>
<span style="font-size: 11px; font-weight: 700; color: #F59E0B; text-transform: uppercase; letter-spacing: 0.08em; white-space: nowrap;">Integration Gap</span>
<div style="flex: 1; height: 1px; background: repeating-linear-gradient(90deg, #F59E0B 0, #F59E0B 6px, transparent 6px, transparent 12px);"></div>
</div>
<!-- Core Systems -->
<div style="background: #0A2540; border: 2px solid rgba(255,255,255,0.2); border-radius: 10px; padding: 18px 24px; text-align: center;">
<div style="font-size: 13px; font-weight: 700; color: #fff; text-transform: uppercase; letter-spacing: 0.05em; margin-bottom: 6px;">Core Systems</div>
<div style="display: flex; justify-content: center; gap: 24px; margin-top: 8px;">
<div>
<div style="font-size: 11px; font-weight: 600; color: rgba(255,255,255,0.7); margin-bottom: 4px;">PAS (Carrier)</div>
<div style="font-size: 11px; color: rgba(255,255,255,0.4); line-height: 1.5;">Guidewire<br>Duck Creek<br>Majesco</div>
</div>
<div style="width: 1px; background: rgba(255,255,255,0.1);"></div>
<div>
<div style="font-size: 11px; font-weight: 600; color: rgba(255,255,255,0.7); margin-bottom: 4px;">AMS (Distribution)</div>
<div style="font-size: 11px; color: rgba(255,255,255,0.4); line-height: 1.5;">Applied Epic<br>Vertafore</div>
</div>
</div>
</div>
<!-- Connector -->
<div style="display: flex; justify-content: center; padding: 6px 0;">
<div style="width: 1px; height: 20px; background: rgba(255,255,255,0.15);"></div>
</div>
<!-- Carrier Operations -->
<div style="background: #0A2540; border: 2px solid rgba(255,255,255,0.1); border-radius: 10px; padding: 18px 24px; text-align: center;">
<div style="font-size: 13px; font-weight: 700; color: rgba(255,255,255,0.5); text-transform: uppercase; letter-spacing: 0.05em; margin-bottom: 6px;">Carrier Operations</div>
<div style="font-size: 12px; color: rgba(255,255,255,0.35);">Underwriting &middot; Claims &middot; Pricing &middot; Distribution</div>
</div>
</div>

On the carrier side, the Policy Administration System (Guidewire, Duck Creek, Majesco, Socotra) organizes everything around the policy. Quote, bind, issue, endorse, renew, cancel. Every active policy lives in this system, along with billing, regulatory reporting, and claims data. You cannot rip out a PAS without migrating every in-force policy. AI that touches underwriting has to integrate with the PAS, and the PAS doesn't make that easy.

On the distribution side, the Agency Management System (Applied Epic, Vertafore) organizes everything around the account. The customer, the relationship, the book, the commissions. Applied Systems has made thirteen acquisitions including Planck and Cytora, embedding AI directly into the platform. Seven of the ten largest agencies run on Applied Epic.

This is why Guidewire buying hyperexponential matters. The vendors that own the system of record are embedding AI into their platforms. Carriers that buy from these vendors get AI that works within the ecosystem. Carriers that want to build independently have to solve the integration themselves.

Most carriers underestimate that integration complexity: how data moves between systems, what the standards are, and what breaks when something upstream changes. This knowledge lives inside the organization, or it doesn't exist at all. Carriers that lost it during the outsourcing wave are the ones struggling hardest to absorb AI tools now.

## Build what's differentiated, buy what's commodity

AI coding tools changed the math. McKinsey's 2026 data shows AI-assisted development reduces routine coding tasks by 35-50%. A third of companies in their survey decided to build internally instead of buying software because agentic coding tools made it feasible. Builds that were impractical on carrier timelines three years ago are now within reach.

That doesn't mean building is the right answer for every carrier. A mid-market carrier with one Guidewire instance and a 200-person IT organization cannot build a proprietary AI underwriting platform while maintaining its core systems. But it might build an AI layer on top of its existing platform that handles submission triage and risk scoring, using its own data and its own underwriting philosophy. That was not realistic in 2023.

The distinction: focus resources on the capabilities that compound with proprietary data. Underwriting models trained on your loss history. Risk scoring calibrated to your appetite and claims outcomes. These get better the longer you run them, and you don't expose your core assets to a vendor.

Don't build the commodity capabilities: submission intake, document parsing, basic extraction. Multiple vendors do them well for a reasonable cost, and they don't differentiate you.

## The judgment question

<div style="border-left: 3px solid #00D4AA; padding: 20px 24px; margin: 32px 0; background: rgba(0, 212, 170, 0.04); border-radius: 0 8px 8px 0;">
<p style="font-size: 18px; font-weight: 600; color: var(--primary); line-height: 1.6; margin: 0;">Buying AI software is procurement. Building AI capability is organizational development. Procurement gives you tools. Organizational development gives you the muscle to use them and know when to override them.</p>
</div>

The senior underwriter who knows when the model is wrong (she's seen enough cycles, enough edge cases, enough claims that didn't follow the pattern) is the most valuable person in the building. AI doesn't reduce the need for that judgment. It raises the cost of not having it. A carrier that skips the organizational development part has outsourced judgment to a vendor.

## Three questions

I've been on both sides. At a global carrier, I designed the governance framework that determined which technology investments moved forward. Most proposals that cleared the technical bar stalled on operating model fit. The technology was ready, but the organization needed to change around it, and that change didn't have a sponsor. At a cyber MGA, we built the policy admin system from scratch. No legacy system, no committee. The build was still harder than anyone expected. State-by-state compliance, rating algorithms, carrier integrations, and the domain complexity of insurance turned a few months into over a year.

Any carrier evaluating its AI path should answer three questions.

<div style="margin: 28px 0; display: flex; flex-direction: column; gap: 16px;">
<div style="display: flex; gap: 16px; align-items: baseline;">
<span style="font-family: var(--font-mono), 'JetBrains Mono', monospace; font-size: 12px; font-weight: 700; color: #00D4AA; text-transform: uppercase; letter-spacing: 0.05em; min-width: 52px;">Buy</span>
<span style="font-size: 16px; color: var(--text-secondary); line-height: 1.6;">From whom, and what happens to your underwriting data once it's inside their platform?</span>
</div>
<div style="display: flex; gap: 16px; align-items: baseline;">
<span style="font-family: var(--font-mono), 'JetBrains Mono', monospace; font-size: 12px; font-weight: 700; color: #00D4AA; text-transform: uppercase; letter-spacing: 0.05em; min-width: 52px;">Build</span>
<span style="font-size: 16px; color: var(--text-secondary); line-height: 1.6;">Can your engineering team explain what a loss ratio is, why a state filing matters, and how an endorsement changes the risk?</span>
</div>
<div style="display: flex; gap: 16px; align-items: baseline;">
<span style="font-family: var(--font-mono), 'JetBrains Mono', monospace; font-size: 12px; font-weight: 700; color: #00D4AA; text-transform: uppercase; letter-spacing: 0.05em; min-width: 52px;">Wait</span>
<span style="font-size: 16px; color: var(--text-secondary); line-height: 1.6;">How many renewal cycles before your competitors' pricing models are trained on data you haven't started collecting?</span>
</div>
</div>

Guidewire and Duck Creek have made their choice. The core system vendors are buying AI because they know their carrier clients can't build it and won't wait forever. Whether that AI serves the carrier's interests or the vendor's is the question nobody is asking loudly enough.
