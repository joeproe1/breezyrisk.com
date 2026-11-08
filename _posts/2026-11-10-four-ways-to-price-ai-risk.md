---
layout: post
title: "Four Ways to Price AI Risk"
description: "Four companies are building four different ways to price AI liability. Certification, monitoring, governance, or loss data. Each covers part of the evidence chain. None covers all of it."
date: 2026-11-10
author: Joerg Proeve
category: "AI & Emerging Risks"
read_time: "6 min read"
image: /assets/images/Blog-Four-Ways-To-Price-AI-Risk.png
image_alt: "Four approaches to pricing AI liability risk — certification, monitoring, governance, and loss data"
permalink: /insights/four-ways-to-price-ai-risk/
---

An AI liability underwriter faces this existential question: what do you measure? No two companies in this nascent space define the risk the same way. The number of named perils and risk dimensions ranges from three to eight depending on who you ask. The causes of action are familiar -- misrepresentation, discrimination, defamation, negligence. The loss math depends on the deployment. How many people the AI reaches, what decisions it makes, whether a human confirms before it acts. One wrong answer to a customer booking a plane ticket is a nuisance claim. The same wrong answer served to thousands is a class action. Same legal theory, different zeros on the claim.

I see four distinct answers to this question, built by different companies. They overlap -- most combine elements from more than one approach -- but each leads with a different source of evidence: certification, monitoring, governance, or loss data.

<!-- Comparison table -->
<table style="width: 100%; border-collapse: collapse; font-size: 14px; margin: 24px 0 32px;">
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
<td style="padding: 10px 12px;">Third-party evaluation against published standard</td>
<td style="padding: 10px 12px;">Does passing predict fewer claims?</td>
</tr>
<tr style="border-bottom: 1px solid #E5E7EB;">
<td style="padding: 10px 12px;"><strong>Monitor</strong></td>
<td style="padding: 10px 12px;">Ollive</td>
<td style="padding: 10px 12px;">Continuous production behavior observation</td>
<td style="padding: 10px 12px;">Does observed behavior predict liability losses?</td>
</tr>
<tr style="border-bottom: 1px solid #E5E7EB;">
<td style="padding: 10px 12px;"><strong>Governance</strong></td>
<td style="padding: 10px 12px;">Mayflower</td>
<td style="padding: 10px 12px;">Self-reported deployment and governance characteristics</td>
<td style="padding: 10px 12px;">Does governance predict losses better than cyber governance did?</td>
</tr>
<tr>
<td style="padding: 10px 12px;"><strong>Loss Data</strong></td>
<td style="padding: 10px 12px;">Testudo</td>
<td style="padding: 10px 12px;">AI incidents, lawsuits, enforcement, proprietary claims</td>
<td style="padding: 10px 12px;">Can external data differentiate risks without internal access?</td>
</tr>
</tbody>
</table>

Each approach covers a different part of the evidence chain that connects what an AI system does to what it costs when something goes wrong. None covers the full chain.

<!-- Evidence chain matrix -->
<div style="margin: 40px 0; padding: 28px 24px; background: #f8f9fa; border-radius: 10px;">

<!-- Column headers -->
<div style="display: grid; grid-template-columns: 110px 1fr 1fr 1fr; gap: 8px; margin-bottom: 8px;">
<div></div>
<div style="text-align: center; padding: 10px 8px; background: #fff; border-radius: 8px; border: 1px solid #e5e7eb;">
<div style="font-size: 14px; font-weight: 700; color: #0A2540;">What the AI Does</div>
</div>
<div style="text-align: center; padding: 10px 8px; background: #fff; border-radius: 8px; border: 1px solid #e5e7eb;">
<div style="font-size: 14px; font-weight: 700; color: #0A2540;">What Goes Wrong</div>
</div>
<div style="text-align: center; padding: 10px 8px; background: #fff; border-radius: 8px; border: 1px solid #e5e7eb;">
<div style="font-size: 14px; font-weight: 700; color: #0A2540;">What It Costs</div>
</div>
</div>

<!-- Certify row -->
<div style="display: grid; grid-template-columns: 110px 1fr 1fr 1fr; gap: 8px; margin-bottom: 8px;">
<div style="display: flex; align-items: center; justify-content: flex-end; padding-right: 12px;">
<div style="font-size: 14px; font-weight: 700; color: #00D4AA;">Certify</div>
</div>
<div style="background: rgba(0, 212, 170, 0.12); border: 2px solid #00D4AA; border-radius: 6px; height: 40px;"></div>
<div style="border: 2px dashed #e5e7eb; border-radius: 6px; height: 40px;"></div>
<div style="border: 2px dashed #e5e7eb; border-radius: 6px; height: 40px;"></div>
</div>

<!-- Monitor row -->
<div style="display: grid; grid-template-columns: 110px 1fr 1fr 1fr; gap: 8px; margin-bottom: 8px;">
<div style="display: flex; align-items: center; justify-content: flex-end; padding-right: 12px;">
<div style="font-size: 14px; font-weight: 700; color: #F59E0B;">Monitor</div>
</div>
<div style="background: rgba(245, 158, 11, 0.12); border: 2px solid #F59E0B; border-radius: 6px; height: 40px;"></div>
<div style="border: 2px dashed #e5e7eb; border-radius: 6px; height: 40px;"></div>
<div style="border: 2px dashed #e5e7eb; border-radius: 6px; height: 40px;"></div>
</div>

<!-- Governance row -->
<div style="display: grid; grid-template-columns: 110px 1fr 1fr 1fr; gap: 8px; margin-bottom: 8px;">
<div style="display: flex; align-items: center; justify-content: flex-end; padding-right: 12px;">
<div style="font-size: 14px; font-weight: 700; color: #7C3AED;">Governance</div>
</div>
<div style="background: rgba(124, 58, 237, 0.12); border: 2px solid #7C3AED; border-radius: 6px; height: 40px;"></div>
<div style="border: 2px dashed #e5e7eb; border-radius: 6px; height: 40px;"></div>
<div style="border: 2px dashed #e5e7eb; border-radius: 6px; height: 40px;"></div>
</div>

<!-- Loss Data row -->
<div style="display: grid; grid-template-columns: 110px 1fr 1fr 1fr; gap: 8px;">
<div style="display: flex; align-items: center; justify-content: flex-end; padding-right: 12px;">
<div style="font-size: 14px; font-weight: 700; color: #EF4444;">Loss Data</div>
</div>
<div style="border: 2px dashed #e5e7eb; border-radius: 6px; height: 40px;"></div>
<div style="background: rgba(239, 68, 68, 0.12); border: 2px solid #EF4444; border-radius: 6px; height: 40px;"></div>
<div style="border: 2px dashed #e5e7eb; border-radius: 6px; height: 40px;"></div>
</div>
</div>

## Certify before you insure

AIUC certifies AI systems against a published standard (AIUC-1) based on thousands of adversarial scenarios, and writes the policy against the certification. Quarterly retesting addresses the problem of models changing between evaluations. The technical evaluations are conducted by third-party testers -- Schellman, Coalfire, and CPA firms through an AICPA partnership. AIUC's capacity provider Beazley has concurred that the testing is required for risk selection, and directly impacts premium.

The underwriting question: does passing the certification predict fewer or smaller claims? That link has not been publicly demonstrated.

## Monitor what the AI actually does

Ollive treats an AI agent not as a new technology but as a new employee, and monitors it accordingly, pricing from observed production behavior instead of what the applicant reported on a questionnaire. The architecture separates the judgment from the language model. The LLM extracts facts: what happened, who was affected, what the agent committed to. A separate layer built on formal verification evaluates those facts against legal and regulatory directives decomposed into machine-readable rules. The verdict chain is reproducible and mechanically checkable. Their explicit position: an LLM can explain why something looks compliant, but that's not the same as proving it actually is. The result is continuous, deployment-specific evidence rather than a point-in-time snapshot.

The underwriting question is the same as for every other approach: does this evidence predict actual liability losses? Nobody has shown that yet.

## Underwrite the governance, not the model

Mayflower Specialty has developed a proprietary underwriting framework for affirmative AI liability. Its approach recognizes that AI liability is not a homogeneous exposure, operating in different environments. Rather than relying solely on conventional underwriting proxies or historical loss experience, Mayflower seeks to differentiate these exposures through a purpose-built framework supporting disciplined risk selection and risk-adjusted pricing. The framework logic is sound: deployment and governance characteristics are observable and stay relatively stable even when the model underneath changes weekly.

The familiar question is how far application-based information can carry a pricing model. Cyber insurance underwrote on self-reported governance for years. Applicants checked "yes" on the MFA question. Travelers filed a rescission action in 2022 over alleged MFA misrepresentations. At a cyber MGA, I watched companies more scared of the application than of a cyber incident. The answers checked every box and told the underwriter almost nothing.

The underwriting question is whether self-reported AI governance predicts losses any better than self-reported cyber governance did.

## Price from AI loss data

Build underwriting from AI loss data -- not just lawsuit outcomes, but incidents, enforcement actions, and proprietary claims data. Testudo's core asset is a graph of companies, AI systems, and the events surrounding them. Their technology allocates each new loss event to the companies and AI systems involved, and maps which AI systems each company deploys, capturing both companies that have experienced losses and those that haven't. An applicant submits firmographic and technographic characteristics that place them alongside comparable risks in the graph, allowing Testudo to run inference against trained frequency models. No audits, no access to anyone's systems. Their data already challenges assumptions: more than 90% of AI liability risk drivers come from the interactions of the AI system with its environment -- bias, discrimination, and regulatory violations. Performance errors like hallucinations account for less than 10% and only occur in very specific AI deployment environments. The market is focused on the smaller problem and building confidence around a very narrow measure of risk.

"The vast majority of risk drivers sit in the environment surrounding an AI system, and we can assess much of that from the outside. We tested audits and certifications against our database and models. So far, they show no correlation with the liability a system or company ultimately faces. We continuously revisit our assumptions as new data comes in. If audits and certifications demonstrate any predictive value in the future, we will incorporate them into our pricing models." -- Martim Cruz, Founding Member of Technical Staff, Testudo

The underwriting question: if external loss data can differentiate risks without internal access, what does that mean for approaches built on audits and governance?

## Each approach generates useful data. None generates enough.

Certification tests behavior at a point in time but can't tell you what the system did on a specific Tuesday between evaluations. Monitoring watches runtime behavior but has no claims history to calibrate against. Governance assessment scales but hasn't been tested by losses. Loss data reflects the past.

No approach I've seen has connected the full evidence chain: an observable signal from an AI deployment, linked to the likelihood and cost of a liability loss, validated by enough claim or loss data points to price a portfolio. That chain needs three things the market doesn't have.

### 1. Deployment context

An AI hiring tool screening 50,000 applicants under EEOC disparate impact law is a fundamentally different risk from an internal document summarizer used by 10 employees. Some providers already collect deployment information, but deployment context as a primary underwriting variable -- weighted as heavily as governance in the pricing model -- is not yet standard. What the AI does and who it affects shapes which policy form responds and how.

### 2. Portable evidence

If every carrier builds its own proprietary assessment and the insured starts from scratch each time they switch, the measurement layer doesn't scale. The market needs portable records that travel with the insured the way a credit rating travels with a borrower. That gap is where the next institutional move happens.

### 3. Correlation with claims outcomes

Even a small set of matched records -- underwriting assessment at bind, claim outcome two years later -- would be a start. Nobody has publicly shown that link yet. And frequency is only the first link; what the policy actually pays depends on severity, coverage terms, and defense costs. Without paired data connecting underwriting signals to developed losses, every pricing approach is informed speculation.

Three of the four approaches start from the front end -- certify, monitor, or assess the AI, then wait for loss data to validate. The companies pricing from external loss data have a head start: they're testing models against existing events, not waiting for their own policy years to develop. But every company writing coverage is generating paired underwriting and claims data. The startups writing AI liability policies today, even at early premium volumes, are sitting on a valuable dataset -- assuming they retain access to the claims data generated on their capacity partners' paper. They just need enough policy years for the data to mean something. The clock is already running.

## The reinsurer will force the standard

My take on what forces measurement standards into the market: the reinsurer. I have seen this play out on the MGA side. Reinsurers ask for new data one treaty renewal at a time -- a question on a call, then a bordereaux field, then a condition of renewal. AI liability will see this cycle compress because the risk is evolving so rapidly and the technology adoption is so fast. A systematic flaw in one foundation model, or a single training-data lawsuit, hits multiple insureds and portfolios at once. In property, reinsurers demanded catastrophe models for exactly this reason: to see their aggregate exposure. Cyber insurance is going through the same reckoning now. Reinsurers will demand equivalent measurement data for AI liability. When evidence requirements become treaty conditions, every carrier and MGA writing on their paper has to comply. That's how measurement standards get adopted in insurance: through the capacity chain, not through regulation.

The first company that demonstrates its measurement approach actually predicts losses becomes the pricing reference for this market. The race is for the first credible dataset, not the best technology.

---

<p style="font-size: 14px; color: #6B7B8D; line-height: 1.6;"><strong style="color: #0A2540;">AI Liability Series</strong><br>Previous: <a href="/insights/ai-liability-arrived-before-the-loss-model/">AI Liability: The Insurance Arrived Before the Loss Model</a> -- the three pricing approaches and where they are heading.</p>
