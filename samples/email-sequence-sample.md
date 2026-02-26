# SaaS Onboarding Email Sequence (5-Email Series)

*Sample by Streamy Digital | B2B SaaS onboarding flow*

---

## Email 1: Welcome (Sent immediately after signup)

**Subject:** You're in. Here's your one thing to do today.

Hi {{first_name}},

Welcome to [Product]. You just made a smart move.

I know you're busy, so I'll keep this short. The customers who get the most value from [Product] all do one thing in their first 24 hours:

**→ [Set up your first workflow](link)**

It takes about 4 minutes. Once it's done, you'll immediately see how [Product] fits into your day-to-day.

If you get stuck, reply to this email. I'm a real person and I actually read these.

— [Name], Head of Customer Success

P.S. Don't worry about getting it perfect. You can edit everything later.

---

## Email 2: Day 2 — Value Reinforcement

**Subject:** You're leaving 3 hours/week on the table

Hi {{first_name}},

Quick question: how much time does your team spend on [pain point] each week?

Our average customer saves 3.2 hours per week after their first month with [Product]. That's 160+ hours a year — an entire month of work, back in your pocket.

Here's how they do it:

1. **Automate the repetitive stuff** — [Feature A] handles [specific task] automatically
2. **Kill the status meetings** — [Feature B] gives everyone visibility without the calendar bloat
3. **Stop context-switching** — [Feature C] brings everything into one place

{{#if completed_onboarding}}
You've already set up your first workflow — nice work. Ready for step two?

**→ [Connect your first integration](link)**
{{else}}
You haven't set up your first workflow yet. It only takes 4 minutes:

**→ [Set up your first workflow](link)**
{{/if}}

— [Name]

---

## Email 3: Day 4 — Social Proof

**Subject:** How [Similar Company] cut their [metric] by 40%

Hi {{first_name}},

[Similar Company] had the same problem you're solving right now.

Their team of {{team_size_range}} was spending too much time on [pain point], and it was costing them in [downstream impact — missed deadlines, slow response times, etc.].

After switching to [Product]:
- **[Metric] dropped 40%** in the first month
- **Team satisfaction scores went up 25%** (yes, they measure that)
- **[Specific outcome]** within 90 days

"[One-sentence testimonial quote from the customer]" — [Name, Title, Company]

Want similar results? Here's what to do next:

**→ [Invite your team](link)** — [Product] gets exponentially better with more people using it.

— [Name]

---

## Email 4: Day 7 — Overcome Objections

**Subject:** The #1 reason people don't finish setup (and the fix)

Hi {{first_name}},

I've onboarded thousands of teams onto [Product]. The most common thing I hear at this stage is:

*"I like it, but I don't have time to set it up properly right now."*

I get it. Here's the thing though — you don't need to set it up "properly." You need to set it up *at all*.

The teams that succeed with [Product] don't do a big-bang rollout. They:

1. Start with **one workflow** (you may have already done this ✓)
2. Add **one integration** to reduce manual work
3. Invite **one teammate** to try it with them
4. Iterate from there

Total time investment: about 15 minutes.

**The cost of waiting** is real — every week you delay is another [X hours/dollars] spent on the old way.

{{#if inactive_7_days}}
I noticed you haven't logged in recently. Want me to set up a 15-minute call to walk you through it? Just reply "yes" and I'll send a calendar link.
{{else}}
You're making good progress. Keep the momentum going:

**→ [Your next recommended action](link)**
{{/if}}

— [Name]

---

## Email 5: Day 14 — Re-engagement or Upsell

**Subject:** {{#if active}}Your first two weeks in numbers{{else}}Should I close your account?{{/if}}

{{#if active}}
Hi {{first_name}},

You've been using [Product] for two weeks now. Here's what you've accomplished:

📊 **Your [Product] Scorecard:**
- Workflows created: {{workflows_count}}
- Time saved (estimated): {{time_saved}}
- Team members active: {{active_members}}

You're in the top {{percentile}}% of new users. That usually means you're ready for the next level.

**→ [Explore Pro features with a 14-day free trial](link)**

Pro unlocks [specific high-value feature], [specific high-value feature], and [specific high-value feature] — the features our power users say they can't live without.

{{else}}
Hi {{first_name}},

I noticed you haven't used [Product] much since signing up. No hard feelings — maybe the timing wasn't right.

I want to be respectful of your inbox, so I have two options for you:

1. **Reply "pause"** — I'll check back in 30 days
2. **Reply "help"** — I'll personally walk you through setup in 15 minutes
3. Do nothing — I'll send one more email next week, then stop

Either way, your account and data will be here whenever you're ready.

{{/if}}

— [Name]

---

## Sequence Performance Benchmarks

| Email | Open Rate Target | Click Rate Target |
|-------|-----------------|-------------------|
| Welcome | 65-75% | 25-35% |
| Day 2 | 45-55% | 15-20% |
| Day 4 | 40-50% | 10-15% |
| Day 7 | 35-45% | 10-15% |
| Day 14 | 30-40% | 8-12% |

*All templates are Klaviyo/Mailchimp/Customer.io compatible with Liquid templating.*
