---

## name: ai-visibility-prompt-builder description: Build a non-branded, category-level set of \~25 natural-language prompts (across 5-6 topics) for tracking how a brand's category shows up in AI answer engines like ChatGPT, Perplexity, Google AI Overviews, and Gemini. Use this whenever someone wants to test, audit, monitor, or improve their visibility/citations inside AI search or AI chatbots, wants to know "what do AI engines say about my category," is setting up AI-visibility or generative-engine tracking, or asks for prompts to run through an AI-visibility tool. Trigger this even if they just say "help me write prompts to see if AI recommends us."

# AI Visibility Prompt Builder

A repeatable method for building the prompt set that powers any AI-visibility / AI-search audit — the set of realistic buyer questions you feed into ChatGPT, Perplexity, Google AI Overviews, Gemini, or a dedicated AI-visibility tracking tool to see whether (and how) a brand's category gets surfaced and cited.

This skill produces the **prompt set only** — a clean, non-branded, natural-language list you can run through whatever tracking tool or manual process you use. It does not depend on any specific vendor or platform.

---

## Why this matters

Most people default to typing their product name into ChatGPT and checking if it shows up. That tells you almost nothing useful, because:

- Real buyers rarely start with a brand name — they ask about the *problem* or the *category*.  
- A prompt set skewed toward comparisons or branded questions over-indexes on demand that's already brand-aware, and misses the much larger pool of category-level conversations where a brand could earn a first impression.  
- Without variety across buyer intent (early research vs. late-stage decision), you can't tell *where* in the journey a brand is winning or losing visibility.

The fix is a deliberately constructed prompt set: category-level, non-branded, and spread across the different ways a real buyer thinks about a problem.

---

## Step 1 — Interview the person before writing anything

Do not generate prompts until you have these answers. Ask them directly (a short set of questions, not a form) if they haven't already been given:

1. **Domain / category** — What space is this in? (e.g., "expense management software," "boutique HR consulting," "commercial roofing.") Get specific enough that prompts won't read as generic filler.  
2. **What they offer** — Products or services, in the client's own words, so you understand what a "win" would actually look like for them. (This informs category selection — it is *not* used to write branded prompts. See Step 3 rules.)  
3. **The categories/topics they most want visibility in** — Every business has sub-areas where being recommended matters more than others. Ask them to name or help narrow to 5-6 of these. If they can't articulate them, propose candidates based on their offering and get a quick confirm/edit.  
4. **Which AI engines they care about** — ChatGPT, Perplexity, Google AI Overviews, Gemini, Copilot, or other. This doesn't change how prompts are *written* (see the note in Step 4), but it tells you which engines to actually run the finished set through, and it's worth flagging up front that different engines pull from different kinds of sources — that's something to observe once results come back, not something to guess at while writing prompts.  
5. **Anything explicitly off-limits** — competitor names they don't want surfaced by name, sensitive topics to avoid, etc. (optional, but ask)

If any of 1-3 is missing or vague, ask a follow-up before proceeding. Guessing at the category list produces a prompt set that won't reflect what the client actually wants tracked.

---

## Step 2 — Pick 5-6 categories/topics

From the interview, select **5 to 7 topics** (aim for 5-6) that:

- Best cover the buyer's actual problem space, not just the seller's product taxonomy.  
- Include the client's stated priority areas from Step 1\.  
- Are broad enough to generate multiple distinct, non-repetitive prompts, but specific enough to avoid generic filler ("best software" is too broad; "expense report automation for field teams" is workable).

Avoid defaulting to a flat, evenly-sized list. Some topics will naturally support more prompts than others — that's fine, and expected (see Step 4 sizing).

---

## Step 3 — The two hard rules (non-negotiable)

**1\. No brand names, ever.** No prompt may contain the client's company name, product name(s), or any other named brand — including the client's own. We are measuring how the *category* gets talked about, not how a specific name performs. A prompt like "What is \[Client\]'s pricing?" is invalid; "How much should \[category\] cost?" is valid.

**2\. No head-to-head brand comparisons.** Do not write prompts that pit two named companies or products against each other (e.g., "\[Brand A\] vs \[Brand B\]"). Most AI-visibility platforms already track competitor comparisons as a separate, native feature — duplicating that here wastes prompt slots and muddies the category-level signal this set exists to capture. General comparison *thinking* is fine ("Should I use an in-house team or an agency for this?") — named brand-vs-brand is not.

If a topic can't be phrased without brand names or without becoming a direct comparison, rework the topic — don't bend the rule.

---

## Step 4 — Write each prompt through five buyer-intent angles

For each topic, don't just write one obvious question — run the topic through these five angles to surface the range of ways a real buyer actually thinks about it. Not every topic needs all five; use judgment on which angles genuinely fit.

| \# | Angle | What the buyer is thinking |
| :---- | :---- | :---- |
| 1 | **Understanding** | "I don't really know this space yet — help me get oriented." |
| 2 | **Diagnosing** | "Something about my current situation feels off, but I can't name why." |
| 3 | **Comparing** | "I'm weighing two different approaches or paths." |
| 4 | **Deciding** | "I'm close to a decision and want confirmation I'm not missing something." |
| 5 | **Avoiding a mistake** | "I want to be careful before I commit — what trips people up?" |

**Worked example** — topic: *"choosing an expense management tool for a distributed team"*

- *Understanding* → "What should I be looking for in an expense management tool for a remote team?"  
- *Diagnosing* → "Why does our expense reporting process keep creating bottlenecks at month end?"  
- *Comparing* → "Is it better to build expense approval into our existing finance stack or use a dedicated tool?"  
- *Deciding* → "What actually separates a good expense tool from a mediocre one once you're down to a shortlist?"  
- *Avoiding a mistake* → "What are the most common mistakes companies make when rolling out a new expense tool?"

**Writing rules:**

- Phrase every prompt as a real person would type it into an AI chat — full natural-language questions, not keyword fragments ("expense tool remote team" is a keyword stub, not a prompt).  
- Strip time-bound qualifiers ("...in 2026," "...this year") so prompts don't go stale.  
- Keep each prompt to one clear question — don't stack two questions into one prompt.

**On engines:** write the prompt set once, the same way, regardless of which engines the person named in Step 1\. Don't pre-guess that a prompt needs different wording for ChatGPT versus Perplexity — there's no reliable basis for that assumption before you've seen actual results. Once the person runs this set through their chosen engines, *that's* when engine-specific differences (which sources get pulled, which phrasing gets cited) become something to observe and record — see Step 6\.

---

## Step 5 — Hit the sizing target

- **5-7 topics, \~25 prompts total.**  
- **3-7 prompts per topic** — richer topics naturally support more angles; thinner ones support fewer. Don't force a flat count per topic (a rigid "3 per topic" undershoots the target and produces a thin, repetitive set).  
- If the total lands meaningfully outside \~22-28, revisit topic selection (too few topics under-covers the category; too many spreads angles too thin to be useful per topic).

---

## Step 6 — Deliver as a tagged table

Always deliver the finished set as a table with three columns — never a bare list. The angle tag is what makes the set analyzable later (it lets someone see, once results come in, *which type of question* a given engine is or isn't answering well for this brand).

| Prompt | Topic | Angle |
| :---- | :---- | :---- |
| What should I be looking for in an expense management tool for a remote team? | Choosing a tool for distributed teams | Understanding |
| Why does our expense reporting process keep creating bottlenecks at month end? | Choosing a tool for distributed teams | Diagnosing |
| Is it better to build expense approval into our existing finance stack or use a dedicated tool? | Choosing a tool for distributed teams | Comparing |

After the table, briefly remind the person:

- **This set is a starting point, not a one-time artifact.** Re-run and refresh it as the category or their priorities shift — an 8-month-old prompt set drifts from what buyers are actually asking.  
- **Run it across every engine they named in Step 1\.** Track results separately per engine — don't average across engines, since which sources get cited can differ a lot engine to engine.  
- **Watch for patterns, not single citations.** One mention of a source isn't a trend. Look for a source or content type getting cited repeatedly for a given topic or angle before treating it as a real signal.  
- **Keep it fresh, not just repeated.** If a prompt set is re-run untouched every time, it stops reflecting how buyer language actually shifts — revisit topics and angles periodically rather than treating the set as permanent.

---

## Common mistakes to avoid

- **Sneaking a brand name into a prompt** ("What is \[Client\]'s approach to...") — even the client's own name breaks the category-level signal.  
- **Writing a disguised comparison** ("Should I pick the newer challenger or the established player in \[category\]?") — if it's functionally a named-brand comparison with the names removed, it's still off-limits in spirit; keep it a genuine open question.  
- **Keyword stubs instead of questions** — always write it the way someone would actually type it into a chat.  
- **Flat, repetitive angle use** — five nearly-identical "understanding" prompts across five topics isn't a real prompt set; vary the angles topic by topic based on what actually fits.  
- **Guessing engine-specific phrasing up front** — write one set, run it everywhere selected, and let the *results* show engine differences.

---

## Quick-start checklist

1. Ask: domain/category, what they offer, 5-6 priority topics, which engines they care about, anything off-limits.  
2. Confirm 5-7 final topics.  
3. For each topic, draft prompts across the five angles that genuinely fit (not all five for every topic).  
4. Check: no brand names, no named comparisons, natural-language phrasing, no stale time qualifiers.  
5. Check: \~25 prompts total, 3-7 per topic.  
6. Deliver as a Prompt | Topic | Angle table.  
7. Remind them to run it across their chosen engines, track per-engine, and refresh periodically.

