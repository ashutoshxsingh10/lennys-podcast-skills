license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---
name: product-metrics
description: Define and structure product metrics that drive good decisions. Use when establishing North Star metrics, building metric trees, or designing dashboards.
license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

# Product Metrics

## What This Skill Produces
- North Star metric definitions
- Metric trees and hierarchies
- Dashboard specifications
- Input vs. output metric frameworks

## User Input Required
Provide brief context (3-5 sentences):
- What product/feature is this for?
- What does success look like?
- What decisions need to be informed by metrics?

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Embedded Wisdom: North Star Metrics

### Sean Ellis on Value Capture

"Figure out a metric that essentially captures units of that value being delivered. That's what a north star metric is - something that reflects how many people are experiencing that product-market fit experience."

**Key Principle**: A North Star metric should capture value delivered to users, not just business extraction.

### Itamar Gilad on Meaningful Metrics

"Active learning users are users that found in the tool some insight that was so important that they shared it with at least two other users. It's a very powerful thing to point at this metric and say 'this is the most important metric combined with revenue.'"

**Example (Amplitude)**: Not just "active users" but "active LEARNING users" - those who found and shared insights.

### North Star Characteristics

**Good North Star**:
- Captures value delivered to users
- Correlates with revenue/retention
- Teams can influence it
- Inspires and aligns the company

**Bad North Star**:
- Pure vanity (downloads, signups)
- Lagging only (revenue alone)
- Unactionable (market size)
- Gameable (any metric if sole focus)

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Embedded Wisdom: Input vs. Output Metrics

### Bill Carr (Amazon) on End-to-End Measurement

"Map your end-to-end customer experience. Step one: they clicked on some ad and showed up. Now they're in the app, browsing and searching. How are we measuring the speed, quality, and ease of that browsing and searching? Now they're on a detail page. How are we measuring the different actions they may take?"

### Input vs. Output Framework

**Output Metrics** (Lagging):
- Revenue
- Retention
- NPS
- What you ultimately care about
- Can measure but hard to directly influence

**Input Metrics** (Leading):
- Actions users take
- Quality of experiences
- Conversion between steps
- Directly actionable
- Predict future outputs

**Amazon's Approach**: Focus team effort on INPUT metrics. Outputs follow.

| Output (Lagging) | Input (Leading) |
|------------------|-----------------|
| Revenue | Conversion rate, average order value |
| Retention | Activation rate, feature adoption |
| NPS | Task completion rate, time to value |

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Embedded Wisdom: Retention Metrics

### Albert Cheng (Duolingo) on Retention Focus

"Current user retention rate was the biggest thing for them. Especially if you have a product with daily frequency, that's the retention that matters most - your existing user base that has developed a habitual pattern, how sticky is your product? That retention rate really compounds."

### Retention Metric Types

**New User Retention** (Activation):
- D1, D7, D30 retention
- Do new users stick around?
- Focus: Onboarding, first experience

**Current User Retention** (Engagement):
- Week-over-week retention of active users
- Do engaged users STAY engaged?
- Focus: Core loop, habit formation

**Resurrection** (Win-back):
- Rate of churned users returning
- Can we bring people back?
- Focus: Re-engagement, new features

### Cohort Analysis

Track retention by signup cohort:
- Cohort Week 0: 100% (by definition)
- Cohort Week 1: X% returned
- Cohort Week 4: Y% returned
- Cohort Week 12: Z% returned

Look for:
- Retention curve flattening (good)
- Cohort-over-cohort improvement (very good)
- Sudden drops (investigate)

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Embedded Wisdom: Funnel Metrics

### AARRR Framework (Pirate Metrics)

**Acquisition**: How do users find you?
- Traffic sources, cost per acquisition

**Activation**: Do they have a good first experience?
- Signup completion, first action

**Retention**: Do they come back?
- D1/D7/D30 retention, engagement frequency

**Revenue**: Do they pay?
- Conversion to paid, ARPU, LTV

**Referral**: Do they tell others?
- Viral coefficient, referral rate

### Funnel Optimization Sequence

**Sean Ellis recommendation**:
1. Start with **Activation** - "that one's just so critical"
2. Then **Engagement** and **Retention**
3. Then **Referral** and revenue model
4. Only then obsess on **Acquisition**

"Product teams so focused on roadmap. Marketing so focused on bringing new people in. But how do you get those new people to a great first experience falls through the cracks."

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Metric Patterns by Product Type

### Consumer App Metrics

| Metric Type | Typical Metrics |
|-------------|-----------------|
| North Star | Daily Active Users (DAU), Weekly Active Users (WAU) |
| Engagement | Sessions per user, Time in app, Actions per session |
| Retention | D1, D7, D30 retention, Current user retention |
| Growth | Signups, Activation rate, Viral coefficient |

### B2B SaaS Metrics

| Metric Type | Typical Metrics |
|-------------|-----------------|
| North Star | Weekly Active Accounts, Feature adoption |
| Engagement | Seats used, Features used, API calls |
| Retention | Net Revenue Retention (NRR), Logo churn |
| Growth | MQLs, Conversion rate, Expansion revenue |

### Marketplace Metrics

| Metric Type | Typical Metrics |
|-------------|-----------------|
| North Star | Gross Merchandise Value (GMV), Transactions |
| Supply | Active sellers, Listings, Fill rate |
| Demand | Active buyers, Search success, Conversion |
| Efficiency | Take rate, Time to first transaction |

### EdTech Metrics

| Metric Type | Typical Metrics |
|-------------|-----------------|
| North Star | Weekly Active Learners, Lessons completed |
| Learning | Progress rate, Completion rate, Test scores |
| Engagement | Streak length, Return rate, Session length |
| Outcomes | Learning outcomes, Certification rate |

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Metric Tree Construction

### Building from North Star Down

```
                    North Star
                        │
            ┌───────────┼───────────┐
            │           │           │
        Input 1     Input 2     Input 3
            │           │           │
        ┌───┴───┐   ┌───┴───┐   ┌───┴───┐
        │       │   │       │   │       │
     Sub-1a  Sub-1b Sub-2a Sub-2b Sub-3a Sub-3b
```

### Example: E-commerce Metric Tree

```
                     Revenue
                        │
         ┌──────────────┼──────────────┐
         │              │              │
    Transactions    AOV          Repeat Rate
         │              │              │
    ┌────┴────┐    ┌────┴────┐    ┌────┴────┐
    │         │    │         │    │         │
 Traffic  Conv%  Items/  Price  Return  Freq
               order         rate
```

### Metric Tree Rules

1. **Decomposable**: North Star = f(inputs)
2. **MECE**: Inputs are mutually exclusive, collectively exhaustive
3. **Actionable**: Teams can influence leaf metrics
4. **Measurable**: Each metric is trackable

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Guardrail Metrics

### Purpose
Metrics that must NOT degrade, even if primary metrics improve.

### Common Guardrails

| Primary Focus | Guardrail |
|--------------|-----------|
| Growth | User satisfaction, quality |
| Revenue | Churn, support tickets |
| Engagement | User value, not just time spent |
| Efficiency | Customer experience |

### Jag Duggal on Leaky Buckets

"We look at metrics like churn to make sure we're not building a leaky bucket. I have built earlier in my career products that have leaky buckets, and that's a very frustrating treadmill. So I am personally maniacal about making sure the bucket doesn't have a hole in the bottom."

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Output Template

```markdown
# Metrics Framework: [Product Name]

## North Star Metric

### Definition
**Metric Name**: [Name]
**Definition**: [Precise definition - no ambiguity]
**Formula**: [How calculated]

### Why This Metric
- Captures user value: [How]
- Correlates with business outcomes: [Evidence]
- Actionable: [How teams influence it]

### Current & Target
| Period | Current | Target |
|--------|---------|--------|
| Now | [Value] | - |
| [Quarter] | - | [Target] |
| [Year] | - | [Target] |

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Metric Tree

```
                    [North Star]
                         │
         ┌───────────────┼───────────────┐
         │               │               │
    [Input 1]       [Input 2]       [Input 3]
         │               │               │
    ┌────┴────┐     ┌────┴────┐    ┌────┴────┐
    │         │     │         │    │         │
[Sub-1a] [Sub-1b] [Sub-2a] [Sub-2b] [Sub-3a] [Sub-3b]
```

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Input Metrics Detail

### Input 1: [Name]
**Definition**: [Precise definition]
**Current**: [Value]
**Target**: [Value]
**Owner**: [Team]

**How to Improve**:
- Lever 1: [Action] → Expected impact: [X%]
- Lever 2: [Action] → Expected impact: [Y%]

**Leading Indicators**:
- [Sub-metric] predicts this metric

### Input 2: [Name]
...

### Input 3: [Name]
...

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Funnel Metrics

| Stage | Metric | Definition | Current | Target | Owner |
|-------|--------|------------|---------|--------|-------|
| Acquisition | [Metric] | [Definition] | [Value] | [Target] | [Team] |
| Activation | [Metric] | [Definition] | [Value] | [Target] | [Team] |
| Retention | [Metric] | [Definition] | [Value] | [Target] | [Team] |
| Revenue | [Metric] | [Definition] | [Value] | [Target] | [Team] |
| Referral | [Metric] | [Definition] | [Value] | [Target] | [Team] |

### Funnel Conversion Rates
| Step | Conversion | Notes |
|------|------------|-------|
| Visit → Signup | [%] | |
| Signup → Activated | [%] | |
| Activated → Retained (D7) | [%] | |
| Retained → Paid | [%] | |

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Retention Metrics

### New User Retention
| Cohort Period | D1 | D7 | D14 | D30 |
|--------------|----|----|-----|-----|
| Current | [%] | [%] | [%] | [%] |
| Target | [%] | [%] | [%] | [%] |

### Current User Retention
**Definition**: Of users active last week, what % are active this week?
**Current**: [%]
**Target**: [%]

### Retention Curve Health
- [ ] Curve flattens (users who stay, stay)
- [ ] Improving cohort-over-cohort
- [ ] No unexpected drops

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Guardrail Metrics

| Metric | Purpose | Alert Threshold | Owner |
|--------|---------|-----------------|-------|
| [Satisfaction/NPS] | Quality check | < [X] | [Team] |
| [Churn rate] | Retention health | > [Y%] | [Team] |
| [Support tickets] | Issue detection | > [Z/week] | [Team] |
| [Page load time] | Performance | > [N]ms | [Team] |

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Dashboard Specification

### Executive Dashboard (Weekly Review)
**Audience**: Leadership team
**Refresh**: Weekly
**Contents**:
- North Star (trend + vs. target)
- Top 3 input metrics
- Funnel conversion summary
- Key wins/losses narrative

### Team Dashboard (Daily)
**Audience**: Product team
**Refresh**: Daily
**Contents**:
- Input metrics team owns
- Experiment results
- Leading indicators
- Alert status

### Alerts
| Condition | Severity | Notify | Action |
|-----------|----------|--------|--------|
| North Star drops >[X]% WoW | Critical | [Who] | [Response] |
| Guardrail breached | High | [Who] | [Response] |
| Funnel step drops >[Y]% | Medium | [Who] | [Response] |

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Review Cadence

| Review | Frequency | Focus | Participants |
|--------|-----------|-------|--------------|
| Daily standup | Daily | Leading indicators | Team |
| Weekly review | Weekly | North Star + inputs | Team + PM |
| Monthly deep-dive | Monthly | Trends, cohorts | Team + Leadership |
| Quarterly reassess | Quarterly | Are metrics still right? | Leadership |
```
