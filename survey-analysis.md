# Title: Arm's Length AI

# Subtitle: An article for humans and a live, working toolkit for agents, to help both explore fashion's hesitant relationship with AI together, and to test themselves against it.

# Author: Ben Hanson

## The distrust thesis

You won't see this from looking at the usage statistics, but fashion is keeping the tallest wave of digital transformation to date at a safe distance. 

Around nine in ten professionals, from on-the-ground creatives to upper management, use AI every day - at home, at work, and with some serious crossover in between the two worlds. But usage does not equate to trust. Only a quarter or so of them are willing to peg important decisions to AI outputs. And roughly three in every five people working in fashion fear that sub-optimal choices could get made because of inaccurate, incomplete, or hallucinated information accepted as gospel from AI, far eclipsing more zeitgeist-y concerns around the ethics of model training or the environmental impact of data centres.

This gulf in trust is both a symptom *and* an ongoing cause of the industry's tentative relationship with potentially the biggest technology change in a lifetime. As bluntly as possible: fashion professionals distrust AI because they fear it'll give them bad answers, and because of that wariness, AI doesn't get connected to the enterprise systems and sources of truth that could make those answers more useful, grounded, and verifiable.

The upshot of that non-virtuous loop is that, for all the effort and investment fashion has made in AI, it's currently pushed to the periphery of the technology estate, with a marked drop-off in perceived value and maturity the closer it gets to real product creation and engineering, where the stakes are the highest.

These figures come from The Interline's [**AI Report 2026**](https://intr.li/ai-26). As part of that 230+ page report - available to download in full, for free - our team surveyed a cross-section of industry professionals, who anonymously shared their individual uptake patterns, outlooks, and attitudes on everything from the ethics of generative AI to where they see its biggest potential in 2027. We then analysed that directional dataset with the kind of objectivity you'd expect from a piece of downloadable research.

This article is both a more opinionated companion piece to, and a distillation of, that drier analysis. Instead of assessing more than 30 datapoints individually, and cross-referencing them by respondent type, my aim today is to tell a more succinct story by bundling the most important findings into digestible buckets, and condensing our interpretations of them down.

What you have in front of you now is, in effect, the **narrative** of the survey rather than the raw, percentage-point findings and the complete, analytical interpretation. And for the first time in The Interline's history, this piece has been written for two audiences: our human readers, and their AI agents.

If you're one of the small percentage of readers who **don't** have Claude, ChatGPT Work, Openclaw, Hermes Agent or something similar open on your desktop right now (or you just like sitting down, reading things, and making up your own mind) then you can scroll on to the next subheading and read this like a normal article. Everything here was written by a human, me, and I intended it to be read. If you want more depth, and more granular analysis, The AI Report 2026 is also written by people, cover to cover, and it's packed with stories, interviews, and more, all designed to be read over several sittings.

If you **do** spend your time with an AI agent by your side, as the data tells us a lot of you do, then this web article is just one part of a toolkit package, containing the same findings in a structured format, but turning them into a live, working asset you can use to test the findings against your own objectives and ideas. The next section explains how to use it with an AI agent.

Whether you choose to read this article alone, or work with it in partnership with AI, I hope it contributes to AI adoption that's more closely hooked into fashion's strategic objectives and technology ecosystems, rather than running in a loop off to the side of them.

## Use this toolkit with an AI agent

To use this article and its accompanying package as an AI toolkit, copy the agent prompt below and give it to your model and harness of choice. If your agent can access GitHub or run shell commands, it will clone a local copy of the toolkit before it begins. That gives it a structured set of Markdown files it can read, cite, and use throughout the session. (If it cannot clone the repository, it can still read the same files directly from GitHub.)

By copying the agent prompt and giving it to your model and harness of choice, this article, and the banded data behind it, can then be used to: 

- Have a personalised, multi-turn conversation about what we found, and what it might mean for your business - based on the memory your agent has about you.
- Contextualise the findings for your market segment.
- Run sector-specific, prewritten prompts to:
	- Build an internal maturity assessment against the questions raised by our data.
	- Build a rubric for assessing ROI on AI spend
	- Map out your technology estate, and understand where AI could fit into it
	- Test the "trust gap" in your own company
	- Understand whether your organisation, or institution, is teaching, training for, and supporting AI projects the right way
	- Validate or challenge a market hypothesis, if you're building an AI solution
- Conduct your own analysis of what we consider to be the most important results of the survey, with proper AI-native tooling, instead of asking an agent to parse a complicated PDF designed to be read by people.

The Interline gets no visibility into how you use this toolkit once it's cloned; every interaction is solely between you and your agent, based on its pre-existing knowledge, and you can continue the conversations for as long as you find them valuable. I'd encourage you to then graduate to reading the full AI Report 2026 to round out your understanding.

---

## The shape of fashion's AI estate

It's tempting to think about AI as something different to regular software. It's now been sold that way for nearly four years, after all.

In some senses that framing would be justified; no other class of software, except *maybe* distributed storage and compute, has changed so much about how we use computers at home and at work, and no other technology wave has washed over billions, or moved global markets, anywhere near as quickly.

In plenty of other ways, though, AI is behaving exactly the way we've seen software do since the advent of personal computing. What started out as a clean, coordinated transformation, with structured sellers, buyers, budgets, teams, scopes, standards, and handoffs quickly got messy. And today AI is in an "everyone for themself" phase, not a utopia of organised adoption. 

And in this sense, that personal computing analogy is a useful one. For anyone old enough to remember, there was a period where PCs and the applications they ran had leapfrogged enterprise hardware and software in power and usability. So workers who considered themselves early adopters would bring their home PCs into the office, unsanctioned, and use them to get an edge on colleagues who were reliant on the equipment and the software provided to them through corporate procurement policies. Social uptake of technology had run away from institutions' ability to adapt.

This is, beat for beat, what we see happening with AI today. Although the business world has coalesced around using Claude (listen to my recent interview with Ramp's Lead Economist, [Ara Kharazian](https://intr.li/GiT72ux), for some insights into why), everyone who works in fashion and uses AI, personally, has their own model of choice - from ChatGPT and Gemini, to the stable of hugely popular open-weights models developed in China - as well as their own library of skills, plugins, connectors, and custom instructions, all of which create a strong incentive to bring their home AI into work, rather than starting fresh.

The survey data backs this up: around two thirds of the professionals who took part exhibited this behaviour, and around a quarter of people were doing it without permission, meaning that the work they do with AI, or delegate to it, instantly vanishes over the horizon of corporate visibility.

As much potential disorder as this introduces to enterprise governance on its own, the challenge is also compounded by the way AI is sold, paid for, used, and scaled in the enterprise. 

Unlike the move to SaaS, where the subscription model created a lot of friction but was quickly made the de facto standard regardless, there is no single surface for using AI in fashion, and no one, accepted way to buy it. Professionals in fashion use AI under monthly subscriptions, annual licenses, pure token / usage billing, and a range of hybrid structures. And they use it in standalone chatbots, chat widgets added to existing tools, dedicated AI workspaces, MCP tools, Copilots, command lines, agent orchestration platforms, and plenty of other surfaces.

So it is, in a direct and meaningful way, difficult to say who within the walls of a brand is using AI, what they're doing with it, how they're accomplishing their tasks, and how much each activity is costing. 

And even in cases where AI usage is encouraged top-down, which should lead to more normalisation and structure in billing and data control, there's still a prevailing sentiment that the price of an average token, as consumed and outputted by an AI model, has become divorced from any reliable metric for measuring its value, precisely because those tokens are burnt, going in and coming out, in so many different places and for so many divergent purposes.

This will be a temporary state of affairs, just as it was with PCs. But these are still the cards that fashion is currently being dealt, and the ones it needs to figure out how to play.

---

## Opaque opex and rough yardsticks for ROI

Where there *is* more certainty and stability, is in the understanding that AI is a growing cost centre for most fashion companies, even if the value flowing back from that outgoing spend is difficult to determine.

Around three quarters of professionals say their organisations have expanded their AI activity in the last twelve months, and about two thirds of them expect the budget they allocate to AI to increase in the next year: summer 2026 to summer 2027. 

This seems like a natural correlation. Brands want to do new things with AI, so they must invest more to accomplish them. Makes sense. But the reality is far less clean. 

While new projects will, obviously, represent a decent share of additional AI spending, according to the people who took our survey, more companies actually expect the main driver of additional AI investment to be deeper pockets demanded by existing initiatives. 

That extra spending could, certainly, come in the form of scope-creep, which is by no means an AI-native problem, and which plagues every technology project. But AI initiatives also have the unique condition of requiring ongoing spend on inference that has inherently unpredictable pricing. While per-token costs for the same model family typically trend downwards over time, I've heard, off the record, of countless AI projects that began life using one model, and have been ported to others as the frontier has evolved. And while those newer models will often be cheaper per million tokens, the token consumption of state of the art reasoning models that are performing actual work, as opposed to simply ingesting and generating text, is much higher.

And unlike traditional software, which is generally unmetered once the customer has bought a license, AI solutions often carry usage caps because of the cost of the underlying commodity. Subscription-based tools typically operate on the assumption that light users will subsidise heavy ones, and even direct subscriptions to mainstay tools like Claude (which don't need to incorporate a margin for the third party developer) are considered a 'steal' for people who use AI regularly, because they represent a steep discount on the costs of using the same models through an API. But those subscriptions are still considered by many to be a limited-time deal, and as the frontier labs pursue public offerings, the expectation is that costs will rise.

All of which should, in theory, be contributing to an industry-wide culture of belt-tightening. To use a very rough and hypothetical analogy, if Adobe Illustrator had charged *per vertex* as well as per seat, we'd have expected to either see usage drop precipitously once the tools were bedded-in, or we'd have seen design briefs become far more specific and controlled, so that spending could be directly mapped to success as measured in design adoption and accuracy.

In practice, most AI projects in fashion will cost more to provision and support as they see increased usage, because every user incurs their own inference cost.

This, in and of itself, would not be a problem if those projects had clear goals and frameworks for measuring outcomes, because greater usage would escalate both cost and value. And provided those things were appropriately balanced per user, then even the costliest ongoing initiative would still create a net return. Unless the problem to be solved became more complex over time, this calculus would also permit companies to freeze model upgrades to avoid possible cost spikes; there's no requirement to remain at the bleeding edge of AI to keep doing the same thing, and today's frontier intelligence is next year's "flash" model. 

But most fashion professionals tell us that their AI projects are still pointed at nebulous outcomes like "productivity" and "efficiency". Soft metrics have never exactly been conducive to robust return on investment analysis, and they aren't here. Only around a quarter of people believe that their organisation has a good rubric for assessing the ROI of their AI projects. And, probably not surprisingly, roughly two in five have seen an AI initiative fail to deliver its stated goal in the past year - although very few of those projects have been outright abandoned.

The trend for fashion companies to be concerned about, then, is not just that they will spend more on AI in 2027 than they did in 2026, but rather that their budgets will inflate simply to sustain the work or realise the value they have already started going after, irrespective of whether that extra cost comes from pure scaling of inference-bound solutions, or because the underlying token economics change.

---

## Maturity everywhere but the middle

As tricky as it might be to sketch its scope, shape, spend, and return, fashion does have a pretty clear vision for where it wants and expects to use AI, and where it potentially doesn't. And this top-and-bottom-heavy structure aligns with the industry's subjective (and, depending on your perspective, potentially short-sighted) opinion of where AI models and applications are, and aren't, mature enough to create reliable, persistent value.

Today, both actual deployments and perception of technology maturity are concentrated at the beginning and the end of the product journey: in initial trend, market, and competitive analysis, and in content creation, marketing, and storytelling activities that happen once a product has been primed and packaged as a SKU.

From a long list of potential options, around a quarter of people chose market, trend, and competitive analysis as the *most* mature use case for AI today. Another quarter picked content and marketing. These represented the largest groupings of responses by a decent margin. 

The AI Report 2026 itself contains a piece, written by the CEO of change authority WGSN, that digs into why forecasting and analysis has become such a lightning rod for AI. And there are several technology vendor interviews (and another article from yours truly, called "Entering The Post-Image Era") in the report that explain the unit economics and the cultural impact of the rapid development of image-generation models, so there's plenty more to read if you want to dig into the assumptions and the thinking behind this view that AI is the most ready at the earliest and the latest stages of the product journey.

Of those two selections, the content and marketing use case is also, it appears, one that fashion is ready to place an even larger bet on between now and 2028. Around three quarters of the professionals we surveyed believe that the share of their consumer-facing creative output either generated or enhanced with AI will increase over the next two years.

Then, on the flipside, fashion professionals perceive AI to be the *least* ready in the middle of the journey. Around a third of people picked technical design, engineering, and pattern development as the least mature use case for AI today. And roughly a quarter picked sourcing and production. These, again, were the largest groupings of answers.

While we did receive plenty of impassioned feedback from garment technicians, patternmakers, and other skilled professionals who fear the decline of their disciplines, it's important to call out that these are not philosophical or ethical objections. As it turns out, most fashion professionals put ethics fairly low on the list of concerns they have about AI. Instead, this is purely market sentiment around what people believe AI can reliably do *today*, and what they believe it can't.

---

## Shaky optimism for an automated future

It's tempting to read any conflicted dataset as evidence that the underlying thing being studied isn't working and won't go anywhere. The reverse is true here: more than half of the fashion audience we surveyed are positive or downright optimistic about the future of AI, and nearly three quarters of them believe that AI could automate a third of the work they currently do by 2030.

These are not the opinions of a cohort that believes AI is a flash in the pan, or that thinks its long-term disruptive potential is over-inflated. There is concern that executives and sponsors put more faith in AI's ability to automate work than the actual workers do, but when has that *not* been true of a technology implementation project?

Still, both the numerical data and the qualitative feedback (which is stripped out of this article and toolkit, but appears in the full AI Report 2026, with verbatim quotes from a range of different perspectives) show that this reverence comes with no small measure of fear attached. More than a third of the industry is uncertain about what happens as we approach that four-year horizon.

Fashion brands are also not charities. And while big tech CEOs talk a lot about abundance, or the prospect of automation creating more work rather than less, around a quarter of the people we surveyed already believe they are seeing headcount reductions or hiring freezes attributable to AI within their organisations.

This unease is also the kind of thing that can grow if left unaddressed, and general optimism can easily flip, undermining some of the tacit permission that fashion companies will need to close the gap between usage and trust.
  
  ---
  
## The non-virtuous loop

In the mainstream press, the counter-revolution against AI gets as much coverage as the utopian promises being made by its biggest proponents. For every [essay about a bright future for everyone](https://www.meta.com/thefutureisforeveryone/), there's a well-attended demonstration against the building of a data centre, or a grassroots campaign for compensation, from creatives who see generative tools as larceny on the largest-ever scale.

In fashion, these concerns barely register. Even in our relatively small and slightly pre-selected study (people who read The Interline will naturally be more inclined to either use or actively rebel against AI than the wider population), environment and ethics are distant concerns compared to the fear that businesses are implementing tools, workspaces, and workflows that people don't currently trust to do the work they are supposed to support or automate.

As a reminder: only about a quarter of fashion professionals trust AI enough to base critical decisions on its output, and around three fifths of them picked the spectre of important choices being made on inaccurate, partial, or hallucinated information as a likely negative impact of AI adoption.

I want to end this article by talking about why that is, and what can be done about it. 

As I wrote in the introduction to this year's AI Report, I do believe agentic language models have reached a level of maturity in the last six months or so that makes them reliable enough to return accurate and robust insights from the platforms they're connected to. Combine this with the codification of [MCP](https://modelcontextprotocol.io/specification/2026-07-28) as the standard for integrating AI with existing systems, and I'm confident that, right now, it's feasible to ask natural language queries that, in a single turn of a frontier model, pull from multiple systems and synthesise answers that can move work forwards.

In a very real sense, though, those answers are contingent upon AI having access to those systems. There are only two ways that AI can become better at advancing real work in fashion: through pretraining on aggregate industry outputs and workflows, or through inference-time, atomic tool calls to the platforms that house real and contemporaneous product, collection, and brand data. And only the latter of those will ever advance the state of the art for how well AI can support or automate the work that *your* specific company does.

It's incredibly hard to understand the frontier capabilities of AI without real data to draw on. Even the most intelligent model will return empty platitudes and generic outcomes if it's kept isolated from live information.

That kind of isolation is common enough in fashion to be considered the rule. Around two thirds of professionals described their AI initiatives as either fully sandboxed, or primarily standalone, with limited connections to other enterprise systems. 

As a result, people in fashion keep interacting with AI that isn't grounded in real enterprise data, and they keep coming away unsatisfied with the results, because the missing citations sit somewhere else in their company's extended technology estate. And, to complete a turn of this non-virtuous loop, they then become more distrustful of AI's abilities, and less willing to connect it to those other systems, or to put it in front of customers or partners.

This is not, I need to point out, an argument for blindly giving LLMs read and write access to every sensitive system you have. As important a step as that might be, it's based on a right that has to be earned through controlled tests. But this *is* an argument that fashion has to give AI a chance to earn that right, and that the industry cannot afford to keep AI at arm's length if it wants to extend maturity and usage more evenly across the product lifecycle, and to bring the potential benefits of automation into the heart of product creation.

[Dario Amodei](https://techcrunch.com/2026/08/16/anthropic-ceo-says-ai-backlash-is-fundamentally-a-crisis-of-trust/) put the point pretty brutally recently: it's not enough to talk about curing cancer... you have to actually go and cure it.

And to reframe that for fashion: you don't cure cancer by just making floorplans for the facility where the miracle will happen, or by doing a faster, cheaper, and potentially better job of advertising it afterwards. At some point, you have to actually let AI into the lab.