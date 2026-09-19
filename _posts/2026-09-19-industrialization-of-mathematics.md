---
title: "On the industrialization of mathematics"
date: 2026-09-19
description: "Mostly obvious thoughts on the industrial age of mathematics, largely written
prior to the Navier-Stokes announcement."
---

Sir Andrew Wiles famously worked for 8 years to prove Fermat's Last Theorem (FLT). Widely regarded as one of the greatest mathematicians of his generation, the final result of his 8 years of continuous work was 129 pages of mathematics which brought an end to the nearly 400 year old FLT problem.

It now seems likely that AI systems will be able to autonomously produce proofs, complete with Lean formalizations, of this caliber, in the near future. But from hitting enter on the keyboard to spitting out the pdf, how long will it take them? If current times are any guess, the time to produce a Wiles-level proof could soon be measured in a single or double digit number of hours. It seems more difficult to assess the probable cost, but, whatever it is, trends suggest that it will geometrically decrease[^1], becoming affordable in short order. Rather than speculate on exactly when this will come to pass (but my bet would be within a few years), I want to speculate on something else:

<div align="center"> <b> 
What will the world look like when FLT-level proofs are available in hours (or less) for the cost of a pair of shoes (or less)?</b> </div> <br>

It's worth thinking about this in concrete terms: *what it took Andrew Wiles, one of the greatest living mathematicians, to do in 8 years, will soon be done in hours for very little money and no human effort.*

Let's start with the obvious consequences.

<img src="/assets/essays/industrialization-of-mathematics/arxiv_math_daily_average.png" alt="Average daily arXiv mathematics submissions" width="707">

<br>

**There will be an exponentially increasing number of papers.** Even if we assume a fixed amount of financial resources are devoted to mathematical research (across both humans and AI) per year, then geometric improvements in intelligence per dollar[^1] will imply that there will be exponentially more mathematics produced. This is already borne out by the growth in arXiv submissions pictured above.

**The journal system will collapse unless it accepts automated reviewing.** The exponential increase in the number of papers will mean that, if a current-day mathematician spends perhaps 10% of their time reviewing papers, then within a short period of time, to keep up with the review load they will need to spend the majority of their time reviewing.

Therefore, the only possibility is to either close journals or increasingly automate review. It does actually seem plausible to automate review via a combination of Lean certificates and AI reviewers, but at that point it is not clear what purpose journals would serve. The same effect could be accomplished by having a simple public repository which collects data on whether AI's have verified a given preprint. 

And notice this is all true even if we assume AI's match human skill in exposition. If they are worse, then the time it takes to review a given paper will only increase and the end of human review will only be hastened.

Now for the more speculative effects.

**Research mathematicians in active areas will spend nearly all of their time understanding the frontier, rather than pushing it.** Assuming that humans are still involved at all, just to understand what is open and what techniques are relevant in the field will be a full-time job. There will still be a bit of time to prompt the AI's to go further, but if one doesn't invest disproportionately more time in understanding than prompting, this will quickly lead to a point of absurdity where one cannot identify the significance or meaning of the results the AI is producing. Contrary to public perception, this will probably look fairly similar to current day-to-day work, since the only certain way to deeply understand frontier research is to actively wrestle with it.

**Mathematicians will only read papers with an AI intermediary.** Just imagine that it is 2028 and a FLT-level result (or hundreds of them) is appearing on the arxiv every day. Each is over a hundred pages (and perhaps much longer than that -- see below) and involves extremely intricate and technical arguments. There is no way to even begin to process such a deluge without an AI intermediary. *The audience of proofs will thus become AI's, not humans.* This latter change will lead to shifts larger than the previous ones.

**The medium of mathematics will no longer be articles.** Writing for AI's rather than humans will call into question basic practices of the research community. Most fundamentally, why do we organize and store our produced knowledge the way we currently do? Concretely, why do we favor preprints of a double digit number of pages rather than books or 10,000 page documents? Essentially, it's a parallelism strategy. By keeping the size of any given contribution bounded, we can parallelize understanding and verifying highly technical fields across many independent researchers, each with highly constrained resources.

For example, imagine bundling together Wiles' FLT paper with every one of its cited papers. According to ChatGPT, the result would be 2,629 pages. No single human could be plausibly expected to read, understand, and verify such a document. As a real-world comparison, Mochizuki's infamous attempt on the abc conjecture spanned a relatively light 720 pages, and it still took years for the professional community to begin to come to a consensus on its (in-)correctness. However, these limitations don't apply to AI's, which could well verify arbitrarily long technical documents, if only by dispatching copies of themselves to verify each sub-component.

As a more mundane example, well-written preprints in present day generally spend a significant amount of text on background results and situating themselves in the literature. And that makes sense when you write for human readers, because human readers haven't memorized every paper that was ever written. However, with AI's there is no need for such content.

Therefore, I expect that this kind of capability level will lead, in the near-term, to extremely long and increasingly un-readable preprints. In the medium term, I expect that we will eventually converge upon a multi-layer representation of mathematics, where at the base layer (perhaps in Lean code) are representations used by the AI's while in the most abstract layer we have human-parseable, probably interactive, mathematics, with AI intermediating the layers.

**Mathematicians and theoretical scientists will raise their sights.** This is the bright dawn promised by the labs: once FLT-level results become commonplace, mathematicians will recalibrate and begin consciously aiming towards increasingly profound and ultimate questions such as P vs. NP and the Riemann Hypothesis. We will be speed-running what would have been hundreds and thousands of years of mathematical progress.

**The number of professional mathematicians will fall precipitously.** The change of the profession from hands-on knowledge production to knowledge organization and AI-steering will mean many mathematicians will no longer want to participate in the new system. The public perception of mathematics as solved will drastically reduce the flow of talent into professional mathematics. However, this will be balanced somewhat by the rise of contributions from non-professionals, again mediated by AI's. Paradoxically, there will be more work than ever for human mathematicians.

**The deepest, most impactful work, will be direction setting.**  What is the next horizon once all of the Millenium Prize problems are solved? What is beyond P vs. NP? Who today has the kind of vision required to seriously answer these questions? The mathematical universe is infinite and it will be up to the humans allocating AI compute to determine where to explore.

[^1]: In late 2024, OpenAI's model o3 achieved a breakthrough on arc-agi-1 with a score of 87.5%. However, many critics pointed out that the result costed them hundreds of thousands of dollars. Less than two years later, better performance on that benchmark can be achieved for hundreds of dollars with open models. This represents an approximately 1000x improvement in model intelligence per dollar over two years, suggesting a roughly 30x improvement per year. Similar or better trends hold [across other benchmarks](https://artificialanalysis.ai/trends#language-model-inference-price-by-intelligence-index-band-over-time).
