license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---
name: feature-prioritization
description: Prioritize features and product work using rigorous frameworks. Use when planning roadmaps, making build/defer decisions, or allocating team resources.
license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

# Feature Prioritization

## What This Skill Produces
- Prioritized feature backlogs
- Decision documents with rationale
- Tradeoff analysis
- Resource allocation recommendations

## User Input Required
Provide brief context (3-5 sentences):
- What features/work are you prioritizing?
- What are your constraints (time, team, resources)?
- What are you optimizing for?

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Embedded Wisdom: Four Types of Product Work

### Fareed Mosavat + Casey Winters Framework

"For every great product leader, you go from being an expert in some type of product work to now owning a portfolio of work across different dimensions."

### Type 1: Feature Work
**What it is**: Adding new features, product experiences to drive engagement with existing customers and solve a wider range of problems.

**When to prioritize**: 
- Core users asking for capabilities
- Competitive pressure on features
- Increasing depth of value for retained users

**Risk**: Can become a "feature factory" without strategy

### Type 2: Growth Work
"How do I help customers connect with experiences we already have, and drive top-line growth or monetization?"

**What it is**: Helping more users discover and activate on existing features. Optimization, not creation.

**When to prioritize**:
- Good product-market fit exists
- Funnel has known drop-offs
- Existing features are underutilized

**Risk**: Optimizing something that doesn't work fundamentally

### Type 3: PMF Expansion
**What it is**: Taking the same product to new audiences OR adding new products for the same audience.

"There are two forms: taking the same product and finding a new audience (internationalization, verticals) or selling a different product to the same audience (bundling strategies)."

**When to prioritize**:
- Core PMF is solid
- Growth in core market is slowing
- Clear adjacent opportunities exist

**Risk**: Spreading too thin before core is strong

### Type 4: Scaling Work
**What it is**: Technical and operational work required because of growth.

"Most people think of technical scaling, but I also put trust, safety, and 'user scaling problems' in this category. Problems that come up just because you have 10,000 users instead of 10."

**When to prioritize**:
- Growing fast
- Technical debt creating problems
- Scale revealing new failure modes

**Risk**: Invisible until it breaks, often under-invested

### Portfolio Balance
"How do you lead across different kinds of work? We've all seen what happens when a growth leader takes over and everything becomes a growth problem. Everything is an experiment. That's not necessarily true for scaling or feature work."

**Question to Ask**: "What percentage of our effort is going to each type? Is that the right allocation for our stage?"

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Embedded Wisdom: Confidence-Based Investment

### Itamar Gilad Framework

"Tie your investment into the idea based on the level of confidence you've found. Early on you want to do the cheap stuff just to gain more confidence, then you can invest more."

### Confidence Levels

| Confidence | Evidence | Investment Level |
|------------|----------|------------------|
| **Low** | Gut feeling, untested hypothesis | Validate before building |
| **Medium** | Some user research, competitive data | Limited prototype, time-boxed |
| **High** | Strong data, successful tests | Full implementation |

### Investment Matching

**Low Confidence Ideas**:
- Don't assign engineering yet
- Start with user interviews, fake door tests
- Time-box research: "2 weeks to get to medium confidence or kill"

**Medium Confidence Ideas**:
- Limited prototype or MVP
- Real but constrained investment
- Define success criteria upfront

**High Confidence Ideas**:
- Full team, full scope
- Still A/B test for optimization
- But don't question whether to build

"Some ideas you don't need to test. Sometimes the expert opinion is enough. If you're just changing the order of settings, the risk is low, you can launch without testing."

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Embedded Wisdom: Scoping Tradeoffs

### Dylan Field's Triangle

"Quality, features, deadline - choose two."

| Choose | Sacrifice | When This Makes Sense |
|--------|-----------|----------------------|
| Quality + Features | Deadline | Building platform, API, high-stakes |
| Quality + Deadline | Features | Launch window matters, MVP sufficient |
| Features + Deadline | Quality | Can iterate later, low switching costs |

"The beautiful thing about software is you can keep iterating. You can ship with features and deadline, then improve quality iteratively over time."

### Shreyas Doshi: Three Levels of Work

"There are three levels of product work: impact, execution, and optics. Once you understand it, it explains a lot."

**Impact**: Does this move the needle on what matters?
- Is this a high-leverage opportunity?
- How many users affected? By how much?

**Execution**: Can we actually deliver this well?
- Do we have the skills/resources?
- What are the dependencies/risks?

**Optics**: How will this be perceived?
- What do stakeholders expect?
- Is this visible to leadership?

**The Trap**: Optimizing for optics at the expense of impact. "Looking busy" vs. "being effective."

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Prioritization Frameworks

### Framework 1: Impact/Effort Matrix

Simple 2x2 for quick decisions:

```
High Impact │ Do Later    │ Do First
            │ (big bets)  │ (quick wins)
────────────┼─────────────┼────────────
Low Impact  │ Don't Do    │ Do If Easy
            │ (time sinks)│ (fillers)
            └─────────────┴────────────
              High Effort   Low Effort
```

### Framework 2: RICE Score

**R**each: How many users affected?
**I**mpact: How much does it affect them? (0.25/0.5/1/2/3)
**C**onfidence: How sure are we? (0-100%)
**E**ffort: Person-weeks to build

Score = (Reach × Impact × Confidence) / Effort

### Framework 3: Weighted Scoring

Define criteria, weight by importance, score each feature:

| Feature | Strategic Fit (30%) | User Value (40%) | Effort (30%) | Total |
|---------|---------------------|------------------|--------------|-------|
| Feature A | 8 | 9 | 6 | 7.8 |
| Feature B | 5 | 7 | 9 | 6.8 |

### Framework 4: Opportunity Scoring

From JTBD research - prioritize based on unmet needs:

Opportunity = Importance + (Importance - Satisfaction)

High importance + Low satisfaction = Big opportunity

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Prioritization Patterns

### Pattern: Time-Boxed Discovery

For low-confidence ideas:
1. Allocate fixed time (e.g., 2 weeks)
2. Define what "medium confidence" looks like
3. At end of time-box: Continue, pivot, or kill
4. Never extend time-box - make a decision

### Pattern: Bet Sizing

Match investment to confidence:
- Small bet: 1 engineer, 2 weeks
- Medium bet: 2-3 people, 4-6 weeks
- Large bet: Full team, quarter+

"If we're wrong about a small bet, we lose 2 weeks. If we're wrong about a large bet, we lose a quarter."

### Pattern: One Big Thing

Each planning period, identify ONE thing that matters most:
- Everything else is secondary
- If you have to cut scope, protect the one big thing
- Success = shipping the one big thing well

### Pattern: Kill Criteria

Before starting, define conditions for stopping:
- "If we don't see X by week 4, we stop"
- "If metric doesn't improve by Y%, we don't scale"
- Makes killing easier (not a judgment call)

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Output Template

```markdown
# Prioritization: [Quarter/Sprint]

## Strategic Context

### Company Goals
- [Goal 1]
- [Goal 2]

### Product Strategy
[What we're focused on and why]

### Key Constraints
- Team capacity: [X engineers, Y designers]
- Time: [Z weeks]
- Dependencies: [External blockers]

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Portfolio Analysis

### Four Types of Work Allocation

| Type | Current % | Recommended % | Rationale |
|------|-----------|---------------|-----------|
| Feature Work | [%] | [%] | [Why] |
| Growth Work | [%] | [%] | [Why] |
| PMF Expansion | [%] | [%] | [Why] |
| Scaling Work | [%] | [%] | [Why] |

### Rebalancing Needed?
[Are we over/under-invested in any area?]

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Feature Evaluation

### Tier 1: Must Do (High confidence, high impact)

| Feature | Impact | Confidence | Effort | Rationale |
|---------|--------|------------|--------|-----------|
| [Feature A] | High | High | [weeks] | [Why must-do] |
| [Feature B] | High | High | [weeks] | [Why must-do] |

**Total Effort**: [X weeks]

### Tier 2: Should Do (Medium+ confidence, good impact)

| Feature | Impact | Confidence | Effort | Rationale |
|---------|--------|------------|--------|-----------|
| [Feature C] | Med-High | Medium | [weeks] | [Why should-do] |
| [Feature D] | Med | High | [weeks] | [Why should-do] |

**Total Effort**: [Y weeks]

### Tier 3: Could Do (If time permits)

| Feature | Impact | Confidence | Effort | Rationale |
|---------|--------|------------|--------|-----------|
| [Feature E] | Med | Medium | [weeks] | [Why lower priority] |

### Needs Validation First (Low confidence)

| Idea | Validation Method | Time-Box | Success Criteria |
|------|-------------------|----------|------------------|
| [Idea X] | [User interviews] | [2 weeks] | [What = medium confidence] |
| [Idea Y] | [Fake door test] | [1 week] | [Interest threshold] |

### Not Doing (And Why)

| Feature | Reason | When to Reconsider |
|---------|--------|-------------------|
| [Feature Z] | [Low impact relative to effort] | [Trigger] |
| [Feature W] | [Doesn't align with strategy] | [If strategy changes] |

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Scoping Decisions

### Tradeoff: [Quality / Features / Deadline]
**We're choosing**: [Two of three]
**We're sacrificing**: [The third]
**Rationale**: [Why this tradeoff makes sense]

### Scope Cuts Made
| Removed | Reason | Impact |
|---------|--------|--------|
| [Feature/scope] | [Why cut] | [What we lose] |

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Dependencies & Risks

### External Dependencies
| Dependency | Owner | Status | Risk if Delayed |
|------------|-------|--------|-----------------|
| [Dependency] | [Team/person] | [Status] | [Impact] |

### Key Risks
| Risk | Likelihood | Impact | Mitigation |
|------|------------|--------|------------|
| [Risk] | High/Med/Low | High/Med/Low | [How we address] |

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Success Criteria

### Primary Outcome
[What does success look like at end of period?]

### Metrics We'll Track
| Metric | Current | Target | Owner |
|--------|---------|--------|-------|
| [Metric 1] | [X] | [Y] | [Who] |
| [Metric 2] | [X] | [Y] | [Who] |

### Kill Criteria
We will stop/pivot if:
- [Condition 1]
- [Condition 2]

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Communication

### Stakeholders Informed
- [ ] [Stakeholder 1]: [What they need to know]
- [ ] [Stakeholder 2]: [What they need to know]

### What We're Explicitly NOT Doing
[Clear statement of scope limits to manage expectations]
```
