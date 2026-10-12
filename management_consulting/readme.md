# Managing Consultant

A Claude skill that helps you think and work like a managing consultant. It is built on the CALP problem-solving method from Masterclass 1 and 2, plus a short managing layer for running a team and owning the message.

## What it does

Pick one of three modes. Claude chooses the mode from what you ask.

| Mode | You say something like | You get |
|---|---|---|
| Solve | "Our app revenue has stalled. Where do we start?" | A structured answer: problem, driver tree, root cause, solutions, top 3 with reasoning |
| Review | "Here is my case answer, tear it apart" | CALP scorecard, the specific gaps, one rewrite, the single biggest fix |
| Plan execution | "We picked this solution. How do we test it?" | Metrics, test type, pilot design, research plan |

## The CALP method

| Step | Question | Trap |
|---|---|---|
| Clarify | What is actually happening? Is there a problem? | Jumping to fixes |
| Analyse | Which drivers really move the number? | Stopping at the first layer of the tree |
| List | Which solutions hit those drivers? | Brainstorming before C and A |
| Prioritise | What gives the best ROI, and can we launch it? | Ranking on theory only |

## What is inside

- CALP workflow with traps and prioritisation tools
- Measurement: metric strength ladder (vanity, perception, behaviour, business outcome) and test types (pre vs post, causal impact, A/B)
- Consumer research (qualitative vs quantitative) and competitor research
- Agoda stalled-revenue example as a reusable tree
- Managing layer: answer-first storyline, hypothesis-driven work, workstreams, stakeholders, scope and risk

## What is from the decks and what is not

- From the masterclasses: CALP, execution rules, measurement, research, Agoda case.
- Added by me, marked **[Addition]** in the skill: the managing layer. It is general consulting practice, not taught in the decks.
- Masterclass 2 content was taken from a pasted summary and has not been checked against the original deck.
- Numbers from the Agoda case (90%, 50x) are case-specific, not general benchmarks.

## How to use it

1. Install the skill by saving it from the card.
2. Start a new chat and describe your problem in plain words. You do not need to say "CALP".
3. For tech vendor or digital transformation cases, the `tech-consulting` skill is the better fit.

Example prompts:

- "A bank wants 10% more active users in 12 months. Structure this."
- "Review my answer to this case. I think my solutions are weak."
- "We will pilot a referral campaign. What should we measure and how do we test it?"

## Limits

- Not yet tested on sample prompts, so expect to tweak the wording after a few uses.
- It gives structure and reasoning, not real data. Where a number is missing, it will show how to estimate it and label it as an assumption.

## Files

- `SKILL.md`: the skill itself (what Claude reads)
- `README.md`: this file (for humans)