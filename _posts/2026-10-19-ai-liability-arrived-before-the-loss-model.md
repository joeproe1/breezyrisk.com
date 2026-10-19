---
layout: post
title: "AI Liability: The Insurance Arrived Before the Loss Model"
description: "Three different approaches are emerging to price AI liability without historical loss data. Endorsements will scale fastest, but the companies building measurement alongside coverage are making the better bet."
date: 2026-10-19
author: Joerg Proeve
category: Industry Trends
read_time: "9 min read"
image: /assets/images/Blog-AI-Liability-Arrived-Before-Loss-Model.png
image_alt: "AI liability insurance inversion — the coverage arrived before the loss model to price it"
permalink: /insights/ai-liability-arrived-before-the-loss-model/
---

More than a dozen companies, from Lloyd's coverholders to Munich Re, are now offering some form of AI liability coverage. The hard question is whether anyone knows how to price it.

Existing commercial and specialty insurance wasn't designed for AI liability. A CGL policy covers bodily injury and property damage, not an AI agent giving wrong professional advice. Tech E&O covers software bugs and service failures, not autonomous decisions a company never reviewed. Cyber covers data breaches, not algorithmic errors.

More than 90% of AI risks covered by insurance are silent (according to [Aon](https://www.aon.com/en/insights/reports/global-insurance-market-opportunities/insuring-ai)) -- neither explicitly affirmed nor excluded. ISO filed standardized generative AI exclusion endorsements in January, and carriers are adopting them. Marsh pushed back earlier this month, writing that it "cannot support broad or absolute AI, or generative AI, exclusions" ([The Insurer](https://www.theinsurer.com/)). Most policyholders won't notice either way until a claim is denied.

Companies like AIUC and Mayflower are building dedicated AI liability products, while established carriers, like Munich Re and CFC, are adding AI coverage through existing lines. 257 AI-related lawsuits (per [AI Lawsuit Tracker](https://ailawsuittracker.com/)) have been filed so far. But the risk the carriers and startups are all trying to price may not respond to traditional actuarial methods at all.

![AI liability insurance — the coverage arrived before the loss model](/assets/images/Blog-AI-Liability-Arrived-Before-Loss-Model.png)
<p style="text-align: center; font-style: italic; color: #555; margin-top: -8px;">The insurance arrived before the loss model.</p>

## Why this risk is different

Traditionally, the insurance industry prices risk by studying what happened in the past and projecting what will happen next. Loss triangles, frequency and severity models, actuarial projections. The approach works when the underlying risk stays roughly stable between policy periods. A building's fire risk doesn't fundamentally change every year.

AI liability breaks this assumption.

First, the risk is non-stationary. The AI model that carriers evaluated and underwrote might have already changed at policy inception. The company connects it to new data sources, gives it access to new tools, deploys it in new use cases. The regulatory exposure shifts constantly. It's not just that the foundation model changes versions. The harness around it, the data it touches, and the decisions it's allowed to make all evolve continuously. The risk drifts before the policy expires.

Correlation is a separate problem. Thousands of companies run on the same foundation models, each deploying differently. But a systematic flaw in one model, or a single training-data lawsuit that changes the legal landscape, creates a correlated trigger across all of them. Foundation model providers generally disclaim liability for their output. The risk flows downstream to the deployers.

And the failure modes have no historical analogues. Hallucinations, prompt injection, autonomous agent decisions that bypass explicit constraints, escalation failures where the AI doesn't hand off to a human when it should. In July, 700 of OpenAI's autonomous AI agents [escaped their sandbox](https://tech-insider.org/openai-hugging-face-ai-agent-hack-report-2026/) during an internal red-team test, self-organized, and compromised Hugging Face's production infrastructure over several days before anyone noticed. None of these map to existing professional liability or tech E&O loss tables. Layer on social inflation and the trend toward nuclear verdicts, and severity modeling becomes pure guesswork. There is no actuarial basis to extrapolate from, because nothing like this came before.

Cyber insurance was here a decade ago and eventually built loss tables. But cyber risk, for all its complexity, runs on infrastructure that changes in years, not months. AI capabilities shift between quarterly board meetings. Jeffrey Sharer (Sharer Consulting LLC) puts it well:

> "Boiler inspection preceded boiler rating. The engineer came first, and the rate followed."

For AI liability, the inspection regime is still forming. The rates aren't waiting.

## Three bets

If traditional actuarial methods don't apply to AI liability, what replaces them? The market is currently splitting into three bets.

<table style="width: 100%; border-collapse: collapse; font-size: 14px; margin: 24px 0;">
<thead>
<tr>
<th style="text-align: left; padding: 10px 12px; color: #fff;">Approach</th>
<th style="text-align: left; padding: 10px 12px; color: #fff;">Examples</th>
<th style="text-align: left; padding: 10px 12px; color: #fff;">Pricing basis</th>
</tr>
</thead>
<tbody>
<tr style="border-bottom: 1px solid #E5E7EB;">
<td style="padding: 10px 12px;"><strong>1. AI endorsements on existing products</strong></td>
<td style="padding: 10px 12px;">CFC, HSB, Cowbell</td>
<td style="padding: 10px 12px;">Historical loss data (professional liability, tech E&O, etc.)</td>
</tr>
<tr style="border-bottom: 1px solid #E5E7EB;">
<td style="padding: 10px 12px;"><strong>2. Standalone AI liability products</strong></td>
<td style="padding: 10px 12px;">Mayflower, Armilla, Testudo, Relm</td>
<td style="padding: 10px 12px;">Governance quality of the deployment of the AI model</td>
</tr>
<tr>
<td style="padding: 10px 12px;"><strong>3. Certification-led underwriting</strong></td>
<td style="padding: 10px 12px;">AIUC</td>
<td style="padding: 10px 12px;">Evaluation against published standard (e.g., AIUC-1)</td>
</tr>
</tbody>
</table>

### The first bet: add AI language to existing products

This is where most established carriers are heading. CFC is adding affirmative AI coverage across seven product lines. HSB (Hartford Steam Boiler), a subsidiary of Munich Re, launched SME AI coverage. Cowbell is endorsing AI liability onto existing cyber policies.

George Beattie, Head of Innovation at CFC, makes the case: "AI will be hard to discern from normal business in the future. Existing products will need to accommodate AI risks as a cause of loss." Companies will be held liable for AI agent errors the way employers are liable for employee errors, he argues, especially when guardrails are lacking.

The distribution channel is proven. This is how cyber coverage started before standalone policies emerged. The tension: these endorsements are still priced off historical professional liability and tech E&O loss data. That extrapolation doesn't hold when the risk is this different.

### The second bet: build standalone AI liability products

Mayflower, Armilla, Testudo, and Relm are writing dedicated AI liability policies. A handful of others are getting ready. Mayflower is the most developed, with modular products covering AI-specific D&O, EPL, E&O, and a DIC excess that drops down where legacy policies are silent. Underwriting is governance-based: price on how well the company manages the risk, the way D&O prices on board quality rather than historical director liability losses.

Jeremy Epstein, Mayflower's founder, explains: "Two businesses using the same model can present materially different loss potential depending on the authority delegated to it, reliance on its outputs and the effectiveness of the tools." What matters for pricing is how failures enter consequential workflows: client work product, employment decisions, professional advice. Whether governance quality actually predicts AI loss outcomes is the open question, but these products are at least asking it directly.

### The third bet: replace loss history with evaluation

AIUC is a category of one. Evaluate the AI system against a published standard (AIUC-1, ~5,000 risk and attack combinations), certify it, insure it. The certification IS the underwriting. Quarterly retesting addresses the non-stationary problem. AIUC's model has supported coverage up to $50M through Lloyd's-linked capacity.

Rajiv Dattani, AIUC co-founder: "When electricity was burning down houses, the insurers paying the bill funded Underwriters Laboratories to test and certify products. AI needs the same combination of standards, testing and insurance." *([SiliconANGLE](https://siliconangle.com/2026/09/15/ai-agent-certification-startup-aiuc-raises-40m-to-begin-auditing-frontier-models/))*

What's driving purchases today is the certification, not the insurance. AIUC-1 unblocks enterprise procurement the way SOC 2 unblocks SaaS sales. If contractual requirements for AI liability insurance emerge the way cyber insurance requirements did, the purchase driver shifts. That hasn't happened yet.

This last bet is the most ambitious: evaluation data replacing actuarial loss data entirely. Nobody has demonstrated that at scale.

### My take

<div class="callout callout-green">
<p>Initially, endorsements will capture most of the premium. But these endorsements are pricing AI risk off data that predates the risk. The first major AI liability claim will test whether that holds true. If it doesn't, the standalone and certification-led products will look like they were a better bet.</p>
</div>

### Who buys first, and why

The early buyers aren't purchasing AI liability insurance because they fear a loss. They're buying it because they can't close a deal without it. AI vendors need to demonstrate governance and financial responsibility to enterprise procurement teams. Certification and insurance together function as a commercial unlock, the way cyber insurance became a standard contractual requirement. The risk transfer is almost secondary. The purchase driver is market access.

## Where this leaves us

AI liability losses are still few and scattered today. That won't last much longer. The technology is being deployed everywhere. The litigation pipeline is already growing.

Three different pricing approaches are forming, and none is backed by a proven loss model. Endorsements will scale fastest. That's how it typically works in insurance. But speed doesn't mean accuracy. The carriers adding AI language to existing products should ask themselves how confident they are in the loss assumptions underneath those endorsements. Some are adding AI coverage with sublimits at 10% of the policy. That tells you how confident they are. File the endorsement, cap the exposure, figure out the pricing later.

The startups building standalone products and certification-led models are taking a harder path with a more honest starting point. They don't have the distribution. They don't have the premium volume. But they're building the measurement infrastructure that the entire market will eventually need. If the endorsement pricing breaks under the first significant claims, these are the models the industry will turn to.

I'd watch the companies that are doing two things: writing coverage now while investing in the capability to price it better over time. For AI liability, the insurance arrived before the loss model. The companies building the measurement capability alongside the coverage are making the better bet.

---

<p style="font-size: 15px; color: #6B7B8D; line-height: 1.6;">This article is a follow-up to <a href="/insights/ai-liability-measurement-gap/">Insuring AI Liability Without Measuring the Risks</a>, which mapped the first cohort of AI liability writers and the measurement gaps underneath them.</p>
