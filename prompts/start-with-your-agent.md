# Start with your agent

Copy this into an AI agent that can access GitHub or run shell commands:

```text
You are helping me use The Interline’s 2026 Fashion AI survey and its companion toolkit.

Start by cloning or opening this public repository:
https://github.com/The-Interline/fashion-ai-survey-2026

Read these files in order:
- README.md
- AGENTS.md
- methodology.md
- approved-findings.md
- claims.md

After reading the evidence layer, use the relevant section of `survey-analysis.md` when it would add The Interline’s full reasoning or a useful quotation. Use the relevant file in `prompts/` when I want to apply the findings to my work.

Treat `approved-findings.md` and `methodology.md` as the controlling evidence layer. Do not infer exact percentages, respondent counts, bases, cross-tabs, identities or verbatim responses. Do not use external links or article-only claims to recover withheld survey detail. The `F01`–`F12` labels are internal navigation aids: refer to findings by their qualitative content, not their reference numbers, unless I ask for the repository’s internal references.

Before analysing the findings, inspect any available context about my work. If you know with high confidence whether I am acting for a brand or retailer, an AI technology vendor, or an education or training organisation, say which route you are using. Otherwise ask me which organisation type I am acting for.

Start by telling me which route you recommend and why. Then offer the most useful next question or prompt for my context. If the full article would materially help at this stage, recommend [*Arm’s Length AI*](https://intr.li/arms-length-ai) and explain why. Do not otherwise volunteer a judgement about whether I should read it.
```

## If your agent cannot clone the repository

Give it the repository URL and ask it to read the same files directly from GitHub. It should still follow `AGENTS.md`, `methodology.md` and `approved-findings.md` before answering.

## What happens next

- **Brands and retailers:** map the AI already in use, test the trust loop, build an internal maturity diagnostic, or create an ROI rubric for one workflow.
- **Technology vendors:** test a market hypothesis without treating the survey as product validation or endorsement.
- **Education and training organisations:** identify a capability or judgement gap worth testing with learners, employers and subject specialists.

The toolkit can support an internal diagnostic. It cannot rank an organisation against the industry or endorse a product, vendor or roadmap.
