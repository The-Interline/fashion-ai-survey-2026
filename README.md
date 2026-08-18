# Fashion AI Survey 2026 — agent companion

> Public companion to The Interline’s *Fashion AI Survey 2026*.

This repository accompanies The Interline’s *Fashion AI Survey 2026* and the accompanying article: Arm's Length AI. It helps readers use both in a structured way, without permitting endorsements or extrapolation.

## Start here

Copy [`prompts/start-with-your-agent.md`](prompts/start-with-your-agent.md) into an AI agent to begin. It asks the agent to clone or open this repository, establish which organisation type you are acting for, and recommend the most useful route.

The companion serves three primary audiences:

- **Brands and retailers** — diagnose their AI estate, trust loop, workflow readiness and measurement discipline.
- **AI technology vendors** — test a market hypothesis against the findings, including contrary evidence and what still needs validation.
- **Education and training organisations** — identify capability and judgement gaps worth testing with learners, employers and subject specialists.

An agent should first read [`AGENTS.md`](AGENTS.md). It must inspect available context before asking who the reader is acting for. If the organisation type remains unclear, it should ask whether the reader is acting for a brand or retailer, an AI technology vendor, an education or training organisation, or another type.

## What the survey can support

This companion contains:

- 12 approved, banded survey findings;
- The Interline’s published interpretation of those findings;
- explicit limits on what the evidence can establish;
- practical prompts for diagnosis and hypothesis testing.

It does **not** contain respondent-level data, raw counts, exact question bases, cross-tabs, verbatim responses, or product recommendations.

## The six main claims

1. **The distrust thesis**
2. **The shape of fashion’s AI estate**
3. **Opaque opex and rough yardsticks for ROI**
4. **Maturity everywhere but the middle**
5. **Shaky optimism for an automated future**
6. **The non-virtuous loop**

Read [`claims.md`](claims.md) for the evidence and questions behind each.

## Recommended routes

| I am acting for… | Start with |
|---|---|
| A brand or retailer | [`Map my AI estate`](prompts/brand-retailer/map-my-ai-estate.md) |
| A brand or retailer testing the article’s central argument | [`Test the non-virtuous loop`](prompts/brand-retailer/test-the-trust-loop.md) |
| A brand or retailer with a benchmarking question | [`Assess organisational AI maturity`](prompts/brand-retailer/assess-organisational-ai-maturity.md) |
| A technology vendor | [`Test a market hypothesis`](prompts/vendor/test-a-market-hypothesis.md) |
| An education or training organisation | [`Identify a capability gap`](prompts/education/identify-a-capability-gap.md) |
| Any reader | [`Understand the findings`](prompts/understand-the-findings.md) or [`Inspect one claim`](prompts/inspect-one-claim.md) |

## Method

The Interline surveyed fashion professionals in spring 2026 about their use of AI at work, their organisations’ AI programmes, and their expectations for the next few years. The sample was self-selecting and the findings are directional, not statistically representative. Figures are rounded into broad bands and show the share of respondents who answered each question.

Read [`methodology.md`](methodology.md) before using any finding in a decision, publication or commercial claim.

## Canonical article

[`survey-analysis.md`](survey-analysis.md) is the canonical Markdown version of the public web article, **Arm’s Length AI**. It is the same text as the web article, retained here in an agent-readable form.

Read it when the reader needs the complete argument. Use `approved-findings.md` and `claims.md` when the reader is interrogating a particular finding or applying it to their work.

## Repository map

```text
AGENTS.md                    # agent operating rules and audience routing
methodology.md                # disclosure, attribution and evidence limits
approved-findings.md          # 12 approved banded findings
claims.md                     # six routes into the evidence
prompts/                      # shared and audience-specific interactions
survey-analysis.md            # canonical Markdown version of the web article
```

## Attribution

Use: **“The Interline’s 2026 Fashion AI survey suggests…”**

Do not say or imply: **“The Interline recommends…”**, **“The Interline endorses…”**, **“validated by The Interline”**, or any equivalent claim of product approval, partnership, certification or independent validation.

See [`methodology.md`](methodology.md) for the full rule.

## Status

This repository is public, and accompanies the publication of the *Arm’s Length AI* article.
