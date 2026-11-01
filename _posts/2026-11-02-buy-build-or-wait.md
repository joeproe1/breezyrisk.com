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

Buying AI software is procurement. Building AI capability is organizational development. Procurement gives you tools. Organizational development gives you the muscle to use them and know when to override them.

The senior underwriter who knows when the model is wrong (she's seen enough cycles, enough edge cases, enough claims that didn't follow the pattern) is the most valuable person in the building. AI doesn't reduce the need for that judgment. It raises the cost of not having it. A carrier that skips the organizational development part has outsourced judgment to a vendor.

## Three questions

I've been on both sides. At a global carrier, I designed the governance framework that determined which technology investments moved forward. Most proposals that cleared the technical bar stalled on operating model fit. The technology was ready, but the organization needed to change around it, and that change didn't have a sponsor. At a cyber MGA, we built the policy admin system from scratch. No legacy system, no committee. The build was still harder than anyone expected. State-by-state compliance, rating algorithms, carrier integrations, and the domain complexity of insurance turned a few months into over a year.

Any carrier evaluating its AI path should answer three questions. If you buy: from whom, and how does the vendor's output enter your existing workflow? If you build: can your engineering team explain what a loss ratio is, why a state filing matters, and how an endorsement changes the risk? If you wait: how long before your competitors' AI advantage compounds into a permanent gap?

Guidewire and Duck Creek have made their choice. The core system vendors are buying AI because they know their carrier clients can't build it and won't wait forever. Whether that AI serves the carrier's interests or the vendor's is the question nobody is asking loudly enough.
