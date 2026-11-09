---
layout: post
title: "Four Ways to Price AI Risk"
description: "Every AI liability pricing approach on the market today is informed speculation. Four distinct approaches are emerging -- certification, monitoring, governance, and loss data. Each generates useful evidence. None generates enough."
date: 2026-11-10
author: Joerg Proeve
category: "AI & Emerging Risks"
read_time: "7 min read"
image: /assets/images/Blog-AI-Liability-Four-Ways.webp
image_alt: "Four approaches to pricing AI liability risk -- certification, monitoring, governance, and loss data"
permalink: /insights/four-ways-to-price-ai-risk/
---

An AI liability underwriter faces this existential question: what do I actually measure? No two companies in this nascent space define the risk the same way. Depending on who you ask, the number of named perils and risk dimensions ranges from three to eight. The causes of action are familiar: misrepresentation, discrimination, defamation, negligence. Pricing them is not. The loss math depends entirely on the deployment, and no two deployments look alike. One wrong answer to a customer booking a plane ticket is a nuisance claim. The same wrong answer served to thousands is a class action. Same legal theory, very different claim outcome.

I see at least four distinct answers to this question, each with multiple companies working on it. They overlap (most combine elements from more than one approach) but each leads with a different source of evidence: certification, monitoring, governance, or loss data.

<table style="width: 100%; border-collapse: collapse; font-size: 14px; margin: 24px 0;">
<thead>
<tr>
<th style="text-align: left; padding: 10px 12px; color: #fff;">Approach</th>
<th style="text-align: left; padding: 10px 12px; color: #fff;">Example</th>
<th style="text-align: left; padding: 10px 12px; color: #fff;">Evidence Source</th>
<th style="text-align: left; padding: 10px 12px; color: #fff;">Underwriting Question</th>
</tr>
</thead>
<tbody>
<tr style="border-bottom: 1px solid #E5E7EB;">
<td style="padding: 10px 12px;"><strong>Certify</strong></td>
<td style="padding: 10px 12px;">AIUC</td>
<td style="padding: 10px 12px;">Certification against published standard</td>
<td style="padding: 10px 12px;">Does passing predict fewer claims?</td>
</tr>
<tr style="border-bottom: 1px solid #E5E7EB;">
<td style="padding: 10px 12px;"><strong>Monitor</strong></td>
<td style="padding: 10px 12px;">Ollive</td>
<td style="padding: 10px 12px;">Observed production behavior</td>
<td style="padding: 10px 12px;">Does runtime evidence predict losses?</td>
</tr>
<tr style="border-bottom: 1px solid #E5E7EB;">
<td style="padding: 10px 12px;"><strong>Governance</strong></td>
<td style="padding: 10px 12px;">Mayflower</td>
<td style="padding: 10px 12px;">Deployment and governance characteristics</td>
<td style="padding: 10px 12px;">Does self-reported governance predict losses?</td>
</tr>
<tr>
<td style="padding: 10px 12px;"><strong>Loss Data</strong></td>
<td style="padding: 10px 12px;">Testudo</td>
<td style="padding: 10px 12px;">External AI loss data and incident graph</td>
<td style="padding: 10px 12px;">Can external data differentiate risks?</td>
</tr>
</tbody>
</table>

## Certify before you insure

AIUC certifies AI systems against a published standard based on thousands of adversarial scenarios, and then writes the policy against the certification. Quarterly retesting addresses the problem of models changing between evaluations. The technical evaluations are conducted by third-party testers (e.g., Schellman, Coalfire, and CPA firms). AIUC's capacity provider Beazley has concurred that the testing is required for risk selection, and directly impacts premium.

**The underwriting question:** does passing the certification predict fewer or smaller claims? That link has not yet been publicly demonstrated.

## Monitor what the AI actually does

Ollive treats an AI agent not as a new technology but as a new employee, and monitors it accordingly, pricing from observed production behavior instead of what the applicant reported on a questionnaire. The architecture separates the judgment from the language model.

The LLM extracts facts from the agent's actions. A separate layer built on formal verification evaluates those facts against legal and regulatory directives decomposed into machine-readable rules. The verdict chain is reproducible and mechanically checkable. Ollive's explicit position: an LLM can explain why something looks compliant, but that's not the same as proving it actually is. The result is continuous, deployment-specific evidence rather than a point-in-time snapshot.

**The underwriting question** is the same as for every other approach: does this evidence predict actual liability losses? Nobody has shown that yet.

## Underwrite the governance, not the model

Mayflower Specialty has developed a proprietary underwriting framework for affirmative AI liability. Its approach recognizes that AI liability is not a homogeneous exposure, because AI systems operate in different environments. Rather than relying solely on conventional underwriting proxies or historical loss experience, Mayflower seeks to differentiate these exposures through a purpose-built framework supporting disciplined risk selection and risk-adjusted pricing. The framework logic is sound: deployment and governance characteristics are observable and stay relatively stable even when the model underneath changes weekly.

The familiar question is how far application-based information can carry a pricing model. Cyber insurance underwrote on self-reported governance for years. Applicants checked "yes" on the MFA question. Travelers filed a rescission action in 2022 over alleged MFA misrepresentations. When I worked for a cyber MGA, I watched companies more scared of the application than of a cyber incident. The answers checked every box and told the underwriter almost nothing.

**The underwriting question** is whether self-reported AI governance predicts losses any better than self-reported cyber governance did.

## Price from AI loss data

Build underwriting from AI loss data - not just lawsuit outcomes, but incidents, enforcement actions, and proprietary claims data. Testudo's core asset is a graph of companies, AI systems, and the events surrounding them. Their technology allocates each new loss event to the companies and AI systems involved, and maps which AI systems each company deploys, capturing both companies that have experienced losses and those that haven't. An applicant submits firmographic and technographic characteristics that place them alongside comparable risks in the graph, allowing Testudo to run inference against trained frequency models. No audits, no access to anyone's systems.

Their data already challenges assumptions: more than **90%** of AI liability risk drivers come from the interactions of the AI system with its environment - bias, discrimination, and regulatory violations. Performance errors like hallucinations account for less than **10%** and only occur in very specific AI deployment environments. The market is focused on the smaller problem and building confidence around a very narrow measure of risk.

> "The vast majority of risk drivers sit in the environment surrounding an AI system, and we can assess much of that from the outside. We tested audits and certifications against our database and models. So far, they show no correlation with the liability a system or company ultimately faces. We continuously revisit our assumptions as new data comes in. If audits and certifications demonstrate any predictive value in the future, we will incorporate them into our pricing models."
>
> -- Martim Cruz, Founding Member of Technical Staff, Testudo

**The underwriting question:** if external loss data can differentiate risks without internal access, what does that mean for approaches built on audits and governance?

## Each approach generates useful data. None generates enough.

Certification tests behavior at a point in time but can't tell you what the system did on a specific Tuesday between evaluations. Monitoring watches runtime behavior but has no claims history to calibrate against. Governance assessment scales but hasn't been tested by losses. Loss data reflects the past.

No approach I've seen has connected the full evidence chain: an observable signal from an AI deployment, linked to the likelihood and cost of a liability loss, validated by enough claim or loss data points to price a portfolio.

<div style="margin: 32px 0; padding: 28px; background: #f8faf9; border-radius: 10px; text-align: center;">
<div style="font-size: 13px; font-weight: 700; color: #0A2540; text-transform: uppercase; letter-spacing: 0.05em; margin-bottom: 20px;">The evidence chain no one has yet connected</div>
<div style="display: flex; align-items: center; justify-content: center; gap: 12px; flex-wrap: wrap;">
<div style="background: #fff; padding: 20px 24px; border-radius: 10px; text-align: center; min-width: 170px; box-shadow: 0 1px 4px rgba(0,0,0,0.08);">
<div style="font-size: 15px; font-weight: 700; color: #0A2540; margin-bottom: 8px;">What the AI Does</div>
<div style="font-size: 12px; color: #6B7B8D; line-height: 1.5;">Deployment, behavior,<br>decisions</div>
</div>
<div style="font-size: 20px; color: #6B7B8D;">&#8594;</div>
<div style="background: #fff; padding: 20px 24px; border-radius: 10px; text-align: center; min-width: 170px; box-shadow: 0 1px 4px rgba(0,0,0,0.08);">
<div style="font-size: 15px; font-weight: 700; color: #0A2540; margin-bottom: 8px;">What Can Go Wrong</div>
<div style="font-size: 12px; color: #6B7B8D; line-height: 1.5;">Incidents, lawsuits,<br>enforcement</div>
</div>
<div style="font-size: 20px; color: #6B7B8D;">&#8594;</div>
<div style="background: #fff; padding: 20px 24px; border-radius: 10px; text-align: center; min-width: 170px; box-shadow: 0 1px 4px rgba(0,0,0,0.08);">
<div style="font-size: 15px; font-weight: 700; color: #0A2540; margin-bottom: 8px;">What It Will Cost</div>
<div style="font-size: 12px; color: #6B7B8D; line-height: 1.5;">Defense, settlement,<br>verdict</div>
</div>
</div>
</div>

That chain needs three things the market doesn't have.

<div style="margin: 32px 0; padding: 24px 28px; background: #f0f7f4; border-left: 4px solid #00D4AA; border-radius: 0 10px 10px 0;">
<div style="font-size: 13px; font-weight: 700; color: #0A2540; text-transform: uppercase; letter-spacing: 0.05em; margin-bottom: 16px;">Three gaps in the evidence chain</div>
<p style="margin: 0 0 12px 0; font-size: 14px; line-height: 1.6; color: #0A2540;"><strong>1. Deployment context.</strong> An AI hiring tool screening 50,000 applicants is a different risk from an internal document summarizer used by 10 employees. Some MGAs already collect deployment information, but deployment context as a primary underwriting variable (weighted as heavily as governance in the pricing model) is not yet standard.</p>
<p style="margin: 0 0 12px 0; font-size: 14px; line-height: 1.6; color: #0A2540;"><strong>2. Portable evidence.</strong> If every carrier builds its own proprietary assessment and the insured starts from scratch each time they switch, the measurement layer doesn't scale. The market needs portable records that travel with the insured the way a credit rating travels with a borrower.</p>
<p style="margin: 0; font-size: 14px; line-height: 1.6; color: #0A2540;"><strong>3. Correlation with claims outcomes.</strong> Even a small set of matched records (underwriting assessment at bind, claim outcome two years later) would be a start. Nobody has publicly shown that link yet. And frequency is only the first link; what the policy actually pays depends on severity, coverage terms, and defense costs. Without paired data connecting underwriting signals to developed losses, every pricing approach is informed speculation.</p>
</div>

Three of the four approaches start from the front end - certify, monitor, or assess the AI, then wait for loss data to validate. MGAs that are pricing from external loss data have a head start: they are testing models against existing events, not waiting for their own policy years to develop.

But every company that writes coverage is generating underwriting data paired with claims data. The MGAs writing AI liability policies today, even at low premium volumes, are sitting on a valuable dataset, assuming they retain access to the claims data that is generated on their capacity partners' paper. They just need enough policy years for the data to mean something. The clock is already running.

## What forces the standard

The reinsurer will force measurement standards into the market. I have seen this play out in cyber. Reinsurers ask for new data, a question on a call, then a bordereaux field, then a condition of renewal.

AI liability will see this cycle compress because the risk is evolving more rapidly and the technology adoption is even faster. A systematic flaw in one foundation model, or a single training-data lawsuit, can hit thousands of insureds at once. In property, reinsurers demanded cat models for exactly this reason: to see their aggregate exposure. Cyber insurance is going through the same reckoning right now.

Reinsurers will demand equivalent measurement data for AI liability. Once evidence requirements become treaty conditions, every MGA or carrier writing on their paper has to comply. That's how measurement standards get adopted in insurance: through the capacity chain, regulation will follow.

The first MGA that demonstrates its measurement approach actually predicts losses becomes the pricing reference for this market. The race is on for the first credible dataset, not the best technology.

---

<p style="font-size: 14px; color: #6B7B8D; line-height: 1.6;"><strong style="color: #0A2540;">AI Liability Series</strong><br>Previous: <a href="/insights/ai-liability-arrived-before-the-loss-model/">AI Liability: The Insurance Arrived Before the Loss Model</a> -- three bets carriers are making on AI liability without historical loss data.<br>This is the final article in the series.</p>
