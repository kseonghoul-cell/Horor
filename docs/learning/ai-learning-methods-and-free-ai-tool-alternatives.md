# AI Learning Methods and Free-Tool Alternatives

> Sources:
> - TikTok slideshow by [@zhenia_youtube](https://www.tiktok.com/@zhenia_youtube/photo/7694264256182652181), posted 2026-10-08: “Зачем платить за AI? Платные топы и их бесплатные аналоги”.
> - TikTok slideshow by [@zhenia_youtube2](https://www.tiktok.com/@zhenia_youtube2/photo/7708049905176268052), posted 2026-11-14: “Освойте любой навык за 4 часа с помощью Claude”.
>
> This document records what was actually visible in the slides, separates creator claims from verified facts, and adapts the useful parts to a realistic analyst-learning path. It does not endorse the creators or their Telegram channels.

## 1. Video: paid AI products and alleged free alternatives

The first post is a seven-page slideshow. The retrieved post data contained six images: a cover, slides 02–05, and a Telegram call-to-action. Slide 06/07 was not present in the retrieved image set, so its contents are unknown.

### Visible comparisons

| Category | Paid product shown | Alternative shown as free |
|---|---|---|
| Text and coding | Claude — $20/month | Kimi — $0/month |
| Image generation | Midjourney — $30+/month | FLUX — $0/month |
| Video and avatars | HeyGen — $29/month | Hedra — $0/month |
| Code completion | GitHub Copilot — $10/month | Codeium — $0/month |

The prices and “free” labels above are transcribed from the creator's graphics. They are not a reliable current price list and should not be treated as proof that every feature, model, usage level, or commercial right is free.

### Practical fact-check notes (checked 2026-11-26)

- **FLUX:** Black Forest Labs' current official pricing page lists pay-as-you-go API prices for its hosted models. Some FLUX models have open weights and can be run on suitable hardware, but that is not the same as unlimited free hosted generation. Hardware, electricity, setup and licensing terms still matter. See [Black Forest Labs pricing](https://bfl.ai/pricing) and [official FLUX repository](https://github.com/black-forest-labs/flux).
- **Hedra:** its official Play pricing page currently lists paid Basic, Pro, Teams and Ultra plans; the page does not support the slide's blanket “$0/month” claim. Check the current account-specific offer and limits before relying on it. See [Hedra pricing](https://www.hedra.com/play/pricing).
- **GitHub Copilot:** GitHub currently offers a Free plan, but it is limited (the official page lists 2,000 code completions per month and limited chat/agent usage). A free tier exists, but it is not equivalent to unlimited paid Copilot. See [GitHub Copilot plans](https://github.com/features/copilot/plans) and [GitHub billing documentation](https://docs.github.com/en/copilot/concepts/billing-and-usage/individuals/billing).
- **Kimi, Claude, Midjourney, HeyGen and Codeium/Windsurf:** plan names, free allowances, regional access and product branding can change. Check the vendor's own pricing and terms at the moment of use. Do not enter payment details or assume commercial-use rights based only on a TikTok graphic.

### Useful conclusion

Treat this slideshow as a **discovery list**, not as a buying guide. Before adopting an alternative, compare:
1. The exact task and output quality required.
2. Free quota, rate limits, watermarks and queue priority.
3. Whether the feature works in the user's country.
4. Commercial-use and data/privacy terms.
5. Export formats and whether the output can be used in the actual workflow.

For a zero-budget learning setup, start with tools that have a clearly documented free tier or can be run locally. Do not build a workflow around a “free” label until the limit is tested.

## 2. Video: six AI-assisted learning methods

The second post is an eight-image educational slideshow. It presents six prompt-based methods. The creator's headline says a skill can be mastered in four hours; that is an attention-grabbing claim, not a realistic promise of professional competence.

### 1. Break the learning curve

Ask the AI tutor to make you functional at one narrow task in a short session. Require it to prioritise:
- What to learn first.
- What can be postponed.
- One high-value exercise.
- A concrete output that demonstrates basic ability.

**Good use:** “I have 45 minutes. Teach me to write a SQL query that groups orders by month and calculates revenue. Give me a dataset, one exercise and a pass/fail criterion.”

### 2. Simulate real mistakes

Instead of receiving a lecture, solve a realistic task. The tutor should:
- Present a problem before explaining the concept.
- Let the learner attempt a solution.
- Diagnose the reasoning error with a question rather than immediately revealing the answer.
- Repeat until the learner can solve a similar task independently.

**Good use:** practise SQL joins, spreadsheet formulas, KPI definitions or requirements writing using intentionally imperfect examples.

### 3. Translate difficult material

When a concept is confusing, ask for:
1. The single core idea that unlocks the rest.
2. A plain-language explanation and everyday analogy.
3. Three comprehension questions.
4. No progression until the learner can answer and explain the idea.

**Good use:** understand primary keys, joins, correlation, API requests, functional requirements or acceptance criteria.

### 4. Architect a personal learning plan

Specify:
- The real-world outcome, not just the topic.
- The deadline.
- What is already known.
- One task per day.
- A time box (the video suggests 45 minutes).
- A visible completion criterion.
- What to deliberately ignore for now.

**Good use:** build a seven-day mini-plan to produce one small SQL/Excel analysis rather than “learn all of SQL”.

### 5. Detect hidden gaps

Ask the tutor to challenge claimed knowledge with a small diagnostic:
- Five deceptively simple questions.
- Questions that expose misconceptions, not memorised definitions.
- Feedback explaining what each answer reveals.
- Follow-up exercises for weak areas.

**Good use:** test whether SQL joins, grouping, NULL handling, KPI calculations or statistics are genuinely understood.

### 6. Forced Feynman method

Explain the topic as if teaching a ten-year-old. The tutor should stop the explanation when it contains:
- Undefined jargon.
- Missing reasoning steps.
- Incorrect simplification.
- A conclusion that does not follow from the evidence.

At the end, the tutor identifies exactly which parts remain unclear.

**Good use:** explain a dashboard, a query, an analytical conclusion or a proposed system requirement in plain language.

## 3. How to apply this to the analyst career plan

Use the six methods as a repeatable learning loop, not as six separate courses:

1. **Set one outcome:** e.g. “write and explain a SQL JOIN query”.
2. **Get a short prioritised lesson:** learn only what is needed for that outcome.
3. **Solve a realistic task:** do not read the solution first.
4. **Use hints to debug:** the tutor asks questions before giving the answer.
5. **Explain the result in plain language:** use the Feynman method.
6. **Take a short diagnostic:** find gaps and repeat the weak part.
7. **Save evidence:** query, spreadsheet, diagram, short write-up or GitHub commit.

A useful 45-minute session:
- 5 minutes — define the outcome and recall what is already known.
- 10 minutes — learn the minimum necessary concept.
- 20 minutes — solve a task without copying the answer.
- 5 minutes — explain the result in plain language.
- 5 minutes — record mistakes and the next practice task.

For difficult topics, split the work into multiple sessions. A four-hour sprint can introduce a narrow task; it cannot replace repetition, feedback, independent problem-solving or real project experience.

## 4. Reusable tutor prompt

Use this prompt with any available AI assistant. Replace the bracketed fields before starting.

> Act as a strict, practical tutor. My goal is **[specific outcome]** by **[date]**. My current level is **[what I can already do]**.
>
> I have **[available time]** for this session. Teach only what is necessary to achieve the outcome. Prioritise the highest-value concepts and tell me what can safely wait.
>
> Do not give me a long lecture. First give me a short explanation, then a realistic exercise. Let me attempt it before showing a solution. If I make a mistake, ask a diagnostic question and let me try again. Do not silently fix my work.
>
> After the exercise, ask me to explain the idea in plain language. Stop me when I use terms I cannot define, skip a reasoning step or make an inaccurate simplification.
>
> Finish with a small diagnostic test, a clear pass/fail criterion, the gaps you found and the next practice task. Distinguish verified facts from assumptions. For technical topics, ask me to test code or queries and verify important details against official documentation.
>
> Do not claim I have mastered a skill merely because I completed one session.

## 5. Guardrails

- AI is a tutor and reviewer, not an authority that is always correct.
- Run code and SQL yourself; check outputs against expected results.
- Verify changing product features, prices, usage limits and licenses on official vendor pages.
- Do not paste passwords, API keys, private customer data or confidential employer data into prompts.
- A completed exercise is evidence of that exercise, not proof of job readiness.
- Keep a learning log with the task, your first attempt, mistakes, corrected solution and what you can now do without help.

## Sources and limitations

- [First TikTok slideshow — paid AI tools and free alternatives](https://www.tiktok.com/@zhenia_youtube/photo/7694264256182652181)
- [Second TikTok slideshow — six AI-assisted learning methods](https://www.tiktok.com/@zhenia_youtube2/photo/7708049905176268052)
- [Black Forest Labs pricing](https://bfl.ai/pricing)
- [Official FLUX repository](https://github.com/black-forest-labs/flux)
- [Hedra Play pricing](https://www.hedra.com/play/pricing)
- [GitHub Copilot plans](https://github.com/features/copilot/plans)
- [GitHub Copilot billing documentation](https://docs.github.com/en/copilot/concepts/billing-and-usage/individuals/billing)

The first slideshow's slide 06/07 was not included in the retrieved post images. No content has been inferred for that missing slide. Pricing and availability notes are a snapshot checked on 2026-11-26 and can change.
