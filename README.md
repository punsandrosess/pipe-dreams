# pipe-dreams

*Two tools. Each opens in any browser — no setup, no login.*

Bad quarters aren't surprises. They're forecasts you didn't read early enough.

One of these tools exists because I got tired of finding out about pipeline gaps in week 12 of a quarter. By then you're not running a play — you're writing a post-mortem. The other is based on excellent work by **Sam Kuehnle**, and I am much better at playing with Claude Code than writing thank you cards.

Both tools were built in Claude Code. They're pre-loaded with real targets and real channel weights. Change any input and the math recalculates instantly.

---

## what's in here

**Pipeline Goals & Forecasting** — Set the revenue goal. Allocate by channel. Watch the gap close, or catch it before it doesn't.

**Funnel Health Dashboard** — Most funnels fail the same way. The fix depends on knowing which one.

Both open as HTML files in any browser. No account. No installation. No dashboard that requires a 45-minute onboarding call.

---

## mist opportunities

> *"Here lies the CMO who found out about the pipeline gap in week 12."*
> **Week 13 was the board meeting.**

Enter your ARR target, conversion rate, and marketing's pipeline contribution percentage. The tool builds the full pipeline requirement automatically — then breaks it down by channel, by quarter, by week.

**What it does:**

- Waterfall from ARR goal to total pipeline required to marketing's sourced pipeline number
- Channel-level goal allocation across Inbound, Paid, Events, SDR, and Webinars — weighted by historical contribution, editable to match your motion
- Implied revenue calculation from current pipeline: if what you have today converted at your rate, where do you land?
- Goal locking with audit trail — once the quarter is committed, mid-quarter changes require a written reason
- Weekly run rate per channel, so "on pace" has an actual definition before week 10

**The signal it's designed to surface:**

Implied revenue below ARR goal, visible in week 6, with enough time to act. Not enough time to explain.

---

## pipeline fitness

> *"Here lies the funnel that looked healthy in the board deck."*
> **It wasn't.**

Enter your funnel numbers and instantly see your health score, your primary issue, and where the breakdown is occurring — by stage.

**A full and direct credit note:** the framework powering this tool belongs entirely to [Sam Kuehnle](https://www.samkuehnle.com/). His February 2026 Substack post — ["I've audited 100+ funnels. Here's what I found."](https://www.samkuehnle.com/p/ive-audited-100-funnels-heres-what-i-found) — is one of the most clear-eyed distillations of B2B funnel diagnosis I've read. The four failure modes, the benchmark logic, the prioritization sequence for which lever to pull first — that's all Sam's thinking. I took his framework and transferred it into an interactive tool. If this dashboard is useful to you, the intellectual credit goes to him. Go read the original post and subscribe to his newsletter. It's worth your time.

**What it does:**

- Live funnel diagnostics: health score, primary issue, stage-by-stage breakdown
- Benchmark comparisons across SMB, Mid-Market, and Enterprise profiles — every conversion rate compared against benchmark ranges so you know what good actually looks like
- Stage improvement ranking: if each stage were fixed to benchmark midpoint, which one generates the most revenue uplift? Ranked automatically so you know where to spend the quarter
- Quarterly trend tracking: submit snapshots each quarter, compare health scores and conversion rates side by side over time
- One-click printable PDF report with diagnostic detail, root causes, and recommended actions per stage

**The four ways funnels actually fail** — Sam Kuehnle's framework, as built into the dashboard:

| Failure mode | Signal |
|---|---|
| Lead Gen 101 — volume looks healthy but leads are low-intent | Inflated lead count, abysmal SQL rate |
| Marketing / Sales misalignment — leads are qualified but stall at handoff | Good leads, low SQL conversion |
| Poor product / market fit — pipeline reaches mid-stage, win rates collapse | Strong pipeline, low win rate |
| Unrealistic goals — everything works, you still miss | Great metrics, missed ARR target |

The dashboard doesn't replace judgment. It makes sure you're asking the right question — which is the thing Sam's framework is designed to do.

---

## a note on how these were built

Both tools were built with Claude. I prompted, iterated, stress-tested against real scenarios, and rewrote where the logic didn't hold. The math is mine. The code got there faster than it would have otherwise.

I'm not a developer by training. I'm a marketing strategist who decided that "I don't know how to code" was a reason to learn, not a reason to stop. If something breaks or the logic doesn't match your motion, open an issue — I'll look at it.

---

## using these tools

1. Download the HTML file for whichever tool you need
2. Open it in any browser — Chrome, Safari, Firefox, Edge
3. Change the inputs to match your numbers
4. The math recalculates instantly

No login. No data leaves your machine. No version that requires you to talk to sales first.

---

*Part of [punsandrosess](https://github.com/punsandrosess) — AI tools for marketing leaders, built in public. Some work well. Some are wrong in interesting ways. I'll tell you which is which.*
