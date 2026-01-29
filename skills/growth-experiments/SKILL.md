license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---
name: growth-experiments
description: Design and run growth experiments with proper hypothesis, metrics, and analysis. Use when testing feature changes, optimizing funnels, or validating growth hypotheses.
license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

# Growth Experiments

## What This Skill Produces
- Experiment specifications with hypotheses
- Metric definitions and success criteria
- Decision matrices
- Results analysis templates

## User Input Required
Provide brief context (3-5 sentences):
- What change are you testing?
- What metric are you trying to improve?
- What's your current baseline?

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Embedded Wisdom: Experiment Economics

### Laura Schaffer on Validation Costs

"AB testing is one of the most expensive kinds of ways to validate an experiment. It often requires design and engineering and the PM or growth person who's crafting it. All these things are investments that take a lot of time, even for simple things. And then you have the time factor - how long do you have to run it to have an impact?"

**Key Insight**: A/B testing should be the last resort, not the first. Cheaper validation methods exist.

### Validation Hierarchy (Cheapest First)

| Level | Method | Time | Cost | When to Use |
|-------|--------|------|------|-------------|
| 1 | Expert opinion / gut check | Hours | $ | Low-risk, reversible changes |
| 2 | Qualitative research | Days | $$ | Understanding motivation |
| 3 | Fake door / painted door | Days | $$ | Testing demand before building |
| 4 | Prototype testing | Week | $$$ | Testing usability |
| 5 | A/B test | Weeks | $$$$ | High-stakes, need statistical proof |

### Itamar Gilad: Confidence-Based Investment

"Tie your investment into the idea based on the level of confidence you've found. Early on you want to do the cheap stuff just to gain more confidence, then you can invest more."

"Some ideas you don't need to test. Sometimes the expert opinion is enough. If you're just changing the order of settings, no one sees this or no one will be impacted. The risk is low, you can launch without testing."

**Decision Framework**:
- Low confidence + High cost of being wrong = Invest in validation
- Low confidence + Low cost of being wrong = Just ship it
- High confidence + High cost = A/B test for confirmation
- High confidence + Low cost = Ship without testing

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Embedded Wisdom: Experiment Win Rates

### Albert Cheng (Duolingo) on Reality of Experiments

"The typical win rate is often something like 30 to 50%. Usually you're trying a bunch of things, a lot of hypotheses turn out not to be true. But when you do find a thing that breaks through the noise - and it could actually be a hugely losing experiment too - those are super valuable."

**Implications**:
- Expect most experiments to fail or be neutral
- Failure is data, not waste
- Celebrate learning, not just wins
- Run many small experiments, not few big ones

### Shreya Shankar: Error Analysis First

"A lot of people prematurely do A-B tests because they've never done any error analysis in the first place. They just have hypothetically come up with their product requirements and believe 'we should test these things.' But when you get into the data, the errors you're seeing are not what you thought. They were these weird handoff issues."

**Before Running an A/B Test**:
1. Analyze existing data for patterns
2. Look at actual user behavior, not assumed behavior
3. Identify where users are struggling/dropping off
4. Ground your hypothesis in observed problems

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Embedded Wisdom: Testing Philosophy

### Duolingo's "Test It" Culture

"Duolingo has a strong 'test it' philosophy. We're willing to test a lot of different things. Honestly, we'd much rather test it than debate it for days and days."

**Principles**:
- Testing beats debating
- Fast iteration beats perfect planning
- Data settles disagreements
- Ship and learn

### When NOT to A/B Test

**Itamar Gilad**: "Part of the trick is knowing when to stop, not just trying to force your way all the way up when you don't have to."

**Don't A/B Test When**:
- Change is easily reversible
- Impact is obviously minimal
- You have strong prior evidence
- The cost of the test exceeds potential value
- It would take too long to reach significance

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Experiment Design Patterns

### Pattern: The Fake Door Test
Test demand before building.
1. Add a button/link for a feature that doesn't exist
2. Track clicks/interest
3. Show "Coming soon" message when clicked
4. Decide whether to build based on interest

### Pattern: The Holdout Group
Measure long-term impact of a launched feature.
1. Launch feature to 95% of users
2. Hold back 5% as control
3. Compare long-term metrics between groups
4. Decide whether to roll out to 100%

### Pattern: The Sequential Test
When you need results faster.
1. Start with a small group
2. If early results are strongly positive/negative, stop early
3. If neutral, continue to full sample size
4. Reduces time for clear-cut decisions

### Pattern: The Multivariate Test
Test multiple variables at once.
1. Test combinations of changes (e.g., headline + image + CTA)
2. Identify which combinations work best
3. Requires more traffic but answers more questions
4. Use when you have sufficient volume

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Metrics Framework

### Primary Metric Selection

**Must be**:
- Directly influenced by the change
- Measurable within experiment timeframe
- Meaningful to business goals
- Not easily gamed

**Examples by Experiment Type**:
| Change | Primary Metric |
|--------|---------------|
| Onboarding flow | Activation rate |
| Pricing page | Conversion rate |
| Feature adoption | Feature usage rate |
| Retention feature | Return rate |
| Growth loop | Viral coefficient |

### Guardrail Metrics

"Metrics that must not degrade, even if primary metric improves."

**Common Guardrails**:
- User satisfaction / NPS
- Support ticket volume
- Revenue per user
- Unsubscribe rate
- Page load time

### Statistical Considerations

**Sample Size**:
- Larger effect = fewer users needed
- Higher confidence = more users needed
- Use a sample size calculator before starting

**Duration**:
- Account for weekly patterns (run full weeks)
- Account for novelty effects (run longer than minimum)
- Account for network effects (may need longer for social features)

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Output Template

```markdown
# Experiment: [Name]

## Overview
**Owner**: [Name]
**Status**: Planning | Running | Analysis | Complete
**Start Date**: [Date]
**End Date**: [Date]

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Hypothesis

We believe that [change/intervention]
will [expected outcome]
for [target users]
because [rationale/evidence].

### Confidence Level
- [ ] Low - Need validation before investing
- [ ] Medium - Some evidence, testing to confirm
- [ ] High - Strong evidence, testing for measurement

### Supporting Evidence
- [Data point or research supporting hypothesis]
- [User feedback or observation]
- [Competitive insight or best practice]

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Validation Approach

### Did We Consider Cheaper Methods First?
| Method | Applicable? | Result |
|--------|-------------|--------|
| Expert opinion | [Yes/No] | [What we concluded] |
| Qualitative research | [Yes/No] | [What we learned] |
| Fake door test | [Yes/No] | [Interest level] |
| Prototype test | [Yes/No] | [Usability findings] |

### Why A/B Test?
[Justification for using A/B test vs. cheaper methods]

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Experiment Design

### Type
- [ ] A/B Test (two variants)
- [ ] Multivariate (multiple variants)
- [ ] Holdout (measuring launched feature)
- [ ] Sequential (early stopping allowed)

### Variants
| Variant | Description | Traffic % |
|---------|-------------|-----------|
| Control | [Current experience] | 50% |
| Treatment | [New experience] | 50% |

### Targeting
**Who sees this**: [All users / Segment]
**Exclusions**: [Who doesn't see this]

### Duration
**Minimum**: [X days] (based on sample size calculation)
**Planned**: [Y days] (including buffer for patterns)
**Maximum**: [Z days] (if inconclusive, we stop here)

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Metrics

### Primary Metric
**Metric**: [Name]
**Definition**: [Exact definition]
**Current baseline**: [Value]
**Minimum detectable effect (MDE)**: [X%]
**Expected lift**: [Y%]

### Secondary Metrics
| Metric | Expected Direction | Why Tracking |
|--------|-------------------|--------------|
| [Metric 1] | ↑ Increase | [Reason] |
| [Metric 2] | → Neutral | [Reason] |

### Guardrail Metrics
| Metric | Must Not | Alert Threshold |
|--------|----------|-----------------|
| [User satisfaction] | Decrease | -[X]% |
| [Revenue] | Decrease | -[X]% |
| [Load time] | Increase | +[X]ms |

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Decision Framework

### Success Criteria
**Ship if**:
- Primary metric shows ≥[X]% lift with p<0.05
- All guardrails held (no significant degradation)
- No major qualitative concerns

### Decision Matrix
| Primary Result | Guardrails | Qualitative | Decision |
|----------------|------------|-------------|----------|
| ✅ Significant positive | ✅ Held | ✅ Positive | **Ship** |
| ✅ Significant positive | ✅ Held | ⚠️ Concerns | Investigate, then ship/iterate |
| ✅ Significant positive | ❌ Violated | - | Do not ship, investigate |
| ➖ Neutral | ✅ Held | - | Do not ship, learn and iterate |
| ❌ Significant negative | - | - | Do not ship, learn why |

### If Results Are Inconclusive
- [ ] Extend experiment duration
- [ ] Increase traffic allocation
- [ ] Accept result as neutral and move on
- [ ] Redesign and re-test

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Implementation

### Technical Requirements
- [ ] Feature flag created: [Flag name]
- [ ] Metrics instrumented
- [ ] QA completed
- [ ] Rollback plan ready

### Rollout Plan
1. [ ] Soft launch to internal users
2. [ ] Launch to [X]% of target segment
3. [ ] Monitor for [Y] hours
4. [ ] Expand or kill based on early signals

### Rollback Triggers
Immediately roll back if:
- Error rate increases by >[X]%
- [Guardrail metric] degrades by >[Y]%
- Critical user complaints

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Pre-Launch Checklist
- [ ] Hypothesis documented and reviewed
- [ ] Sample size calculated and achievable
- [ ] Primary metric clearly defined
- [ ] Guardrail metrics identified
- [ ] Feature flag configured
- [ ] Metrics instrumented and verified
- [ ] QA approved
- [ ] Rollback plan documented
- [ ] Stakeholders informed

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Results (Complete After Experiment)

### Summary
**Date completed**: [Date]
**Actual duration**: [Days]
**Total users**: Control: [N] | Treatment: [N]

### Metric Results
| Metric | Control | Treatment | Lift | P-value | Significant? |
|--------|---------|-----------|------|---------|--------------|
| Primary: [Metric] | [Value] | [Value] | [%] | [Value] | [Yes/No] |
| Secondary: [Metric] | | | | | |
| Guardrail: [Metric] | | | | | |

### Decision
**Result**: Ship | Iterate | Kill | Inconclusive

**Rationale**: [Why this decision]

### Learnings
Regardless of outcome, what did we learn?
- [Learning 1]
- [Learning 2]

### Follow-up Actions
- [ ] [Next step 1]
- [ ] [Next step 2]
```
