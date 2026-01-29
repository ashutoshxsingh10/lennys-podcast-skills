license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---
name: validation-testing
description: Validate ideas before full investment through prototyping and testing. Use when you have a new idea, uncertain hypothesis, or need to de-risk before building.
license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

# Validation & Testing

## What This Skill Produces
- Validation plans with method selection
- Test protocols and success criteria
- Prototype specifications
- Kill criteria and decision frameworks

## User Input Required
Provide brief context (3-5 sentences):
- What idea/hypothesis are you validating?
- What's the cost of being wrong?
- What's your current confidence level?

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Embedded Wisdom: Validation Philosophy

### Itamar Gilad on Confidence-Based Validation

"Tie your investment into the idea based on the level of confidence you've found. Early on you want to do the cheap stuff just to gain more confidence, then you can invest more."

"Some ideas you don't need to test. Sometimes the expert opinion is enough. If you're just changing the order of settings, no one sees this or no one will be impacted. The risk is low, you can launch without testing."

**Key Principle**: Match validation investment to uncertainty × stakes.

### Jake Knapp on Risk-First Thinking

"The team is going to say, 'What are the biggest risks that this hypothesis is not true? What do we need to assess right now?' Going to make a map of how customers discover the product, what that core experience looks like, and then figure out where's the key moment for assessing that risk."

"For one startup, the biggest risk was: do people even want this thing? They decided the key moment to test was actually on the landing page - before building anything."

### Ryan Singer (Shape Up) on Knowing the End

"We are not going to start something unless we can see the end from the beginning. We're not going to take a big concept and then say, 'What's the estimate for this thing?' We're going to go the other way around and say, 'What is our appetite for this? What is the maximum amount of time we're willing to go before we actually finish something?'"

### Ethan Evans (Amazon) on Surprise Launches

"Amazon loved surprise launches. They love the idea of 'we're going to be quiet, quiet, quiet and then it will just be there.'"

"The biggest thing I learned with surprise launches is that you're surprised by what doesn't work. So I shifted the approach to let's do a lot of beta testing."

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Embedded Wisdom: Validation Hierarchy

### The Validation Ladder

Start at the lowest level that can answer your question. Only move up if needed.

**Level 1: Expert Opinion (Hours)**
- Team discussion, gut check
- Check existing data
- Competitive analysis

When sufficient: Low-risk, easily reversible changes
Move up if: Stakes are high or team disagrees

**Level 2: Qualitative Research (Days)**
- 5-8 user interviews
- Concept testing with mockups
- Observe current behavior

When sufficient: Need to understand motivation/context
Move up if: Need to quantify or test at scale

**Level 3: Demand Validation (Days-Weeks)**
- Landing page test
- Fake door / painted door test
- Waitlist signup

When sufficient: Testing if people WANT something
Move up if: Need to test if solution WORKS

**Level 4: Solution Testing (Weeks)**
- Clickable prototype
- Usability testing
- Wizard of Oz (looks real, manual backend)

When sufficient: Testing if users CAN use solution
Move up if: Need real usage data

**Level 5: Market Test (Weeks-Months)**
- Concierge MVP (manual delivery)
- Limited release / beta
- A/B test

When sufficient: Testing if solution DELIVERS value
Move up if: Need to optimize (but you have validation)

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Embedded Wisdom: When NOT to Validate

### Itamar Gilad's Exceptions

"Part of the trick is knowing when to stop, not just trying to force your way all the way up when you don't have to."

**Skip Validation When**:
- Change is easily reversible
- Impact is obviously minimal
- Strong prior evidence exists
- Cost of testing > cost of being wrong
- Would take too long to reach significance

### Signs You're Over-Validating

- Testing things you already know
- Seeking permission rather than information
- Fear of making decisions
- Analysis paralysis
- Testing small optimizations expensively

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Validation Method Details

### Fake Door Test
**What**: Add UI for a feature that doesn't exist yet. Measure interest.

**How**:
1. Add button/link for the feature
2. Track clicks/interactions
3. Show "Coming soon" message when clicked
4. Optionally collect email for waitlist

**Success Criteria**: [X]% click-through rate indicates demand

**Pros**: Very cheap, real user intent
**Cons**: Can frustrate users, measures interest not value

### Concierge MVP
**What**: Deliver the value manually, even if it doesn't scale.

**How**:
1. Find first users willing to try
2. Deliver the value with human effort
3. Observe if it actually helps them
4. Get feedback, iterate

**Success Criteria**: Would they pay? Would they be "very disappointed" without it?

**Pros**: Tests actual value delivery, deep learning
**Cons**: Time-intensive, doesn't test scalability

### Wizard of Oz
**What**: Looks automated to user, but is manual behind the scenes.

**How**:
1. Build the user-facing interface
2. Human performs the "AI/automation" manually
3. User experiences the value without knowing it's manual
4. Measure satisfaction, willingness to pay

**Success Criteria**: Same as if it were automated

**Pros**: Tests UX and value without building backend
**Cons**: Labor-intensive, may not scale

### Prototype Testing
**What**: Test usability and comprehension with clickable mockups.

**How**:
1. Create clickable prototype (Figma, etc.)
2. Give users tasks to complete
3. Observe where they struggle
4. Ask comprehension questions

**Success Criteria**: [X]% task completion, users understand concept

**Pros**: Cheap to change, catches UX issues early
**Cons**: Doesn't test real value delivery

### Beta / Limited Release
**What**: Ship to small group before full launch.

**How**:
1. Identify beta cohort (internal, waitlist, segment)
2. Ship feature to limited group
3. Measure usage, satisfaction, bugs
4. Iterate before broader rollout

**Success Criteria**: Usage, NPS, bug rate thresholds

**Pros**: Real usage data, catches issues early
**Cons**: Takes longer, risk of negative word-of-mouth

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Kill Criteria Framework

### Before You Start, Define Failure

"What would make us STOP this project?"

Having clear kill criteria:
- Removes emotion from the decision
- Prevents sunk cost fallacy
- Gives team permission to stop

### Kill Criteria Examples

**Demand Validation**:
- "If <5% click the fake door, we don't build it"
- "If <20% of interviewees describe this problem, we pivot"

**Solution Validation**:
- "If <50% complete the core task in testing, we redesign"
- "If users can't explain what it does, we simplify"

**Market Test**:
- "If activation rate is <10%, we don't scale"
- "If <30% would be 'very disappointed,' we iterate"

### Decision Framework

| Result | Signal | Decision |
|--------|--------|----------|
| Strong positive | Exceeds criteria | Proceed with confidence |
| Moderate positive | Meets minimum criteria | Proceed with caution, monitor |
| Neutral | Below criteria but not clearly bad | Investigate, maybe iterate |
| Negative | Clearly fails criteria | Stop or pivot |

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Prototype Fidelity Guide

### Fidelity Dimensions

| Dimension | Low Fidelity | High Fidelity |
|-----------|--------------|---------------|
| Visual | Wireframes, sketches | Full visual design |
| Interaction | Static screens | Clickable, animated |
| Content | Lorem ipsum | Real copy/data |
| Backend | None | Working API |

### Fidelity Selection Matrix

| Testing | Visual | Interaction | Content | Backend |
|---------|--------|-------------|---------|---------|
| Concept comprehension | Low | Low | Med | None |
| Navigation/flow | Low | High | Low | None |
| Value proposition | Med | Med | High | None |
| Usability | High | High | High | None |
| Actual usage | High | High | High | Real or mocked |

### When to Go High Fidelity

**Always high fidelity for**:
- Final usability testing
- User value assessment
- Pricing/conversion testing

**Can be low fidelity for**:
- Early concept testing
- Internal alignment
- Flow/navigation testing

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Output Template

```markdown
# Validation Plan: [Feature/Product Name]

## Hypothesis
We believe that [user]
will [behavior/adoption]
for [solution/feature]
because [rationale].

## Risk Assessment

### Confidence Level
- [ ] Low - Major uncertainty, need validation before any build
- [ ] Medium - Some evidence, testing to confirm before full build  
- [ ] High - Strong evidence, testing for optimization

### Cost of Being Wrong
- [ ] Low - Easily reversible, minimal wasted effort
- [ ] Medium - Some wasted effort, but recoverable
- [ ] High - Significant investment at risk

### Validation Investment Warranted
Based on confidence × cost: [Low / Medium / High]

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Riskiest Assumptions

List assumptions in order of risk (if wrong, kills the idea):

1. **[Assumption 1]**: [What we assume is true]
   - Evidence for: [What suggests this is true]
   - Evidence against: [What suggests this might be false]
   - How to test: [Method]

2. **[Assumption 2]**: [What we assume]
   - Evidence for:
   - Evidence against:
   - How to test:

3. **[Assumption 3]**:
   ...

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Validation Plan

### Did We Consider Cheaper Methods First?

| Level | Method | Applicable? | Result/Decision |
|-------|--------|-------------|-----------------|
| 1 | Expert opinion | [Yes/No] | [What we concluded] |
| 2 | User interviews | [Yes/No] | [What we learned] |
| 3 | Fake door test | [Yes/No] | [Interest level] |
| 4 | Prototype test | [Yes/No] | [Usability findings] |
| 5 | Market test | [Yes/No] | [Value validation] |

### Selected Validation Approach

**Method**: [Which method and why]
**Why this level**: [Justification for this investment]

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Test Design

### Participants
**Target**: [N] participants
**Criteria**: [Who qualifies]
**Exclusions**: [Who doesn't qualify]
**Recruitment**: [How we'll find them]

### Test Protocol

**For Concept/Interview Testing**:
1. Introduction: [What we tell them]
2. Show: [What we present]
3. Ask: [Key questions]
4. Observe: [What we watch for]

**For Prototype Testing**:
1. Setup: [Context we provide]
2. Task 1: "[Instruction]" - Tests: [What we learn]
3. Task 2: "[Instruction]" - Tests: [What we learn]
4. Follow-up: [Questions after tasks]

**For Fake Door Testing**:
1. Placement: [Where the fake door appears]
2. CTA: [What it says]
3. Click behavior: [What happens when clicked]
4. Tracking: [What we measure]

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Prototype Specification (If Applicable)

### What We're Testing
[Specific hypothesis this prototype validates]

### Fidelity Levels
| Dimension | Level | Rationale |
|-----------|-------|-----------|
| Visual | Low/Med/High | [Why] |
| Interaction | Low/Med/High | [Why] |
| Content | Low/Med/High | [Why] |
| Backend | None/Mocked/Real | [Why] |

### Screens/States Needed
| Screen | Purpose | Fidelity Notes |
|--------|---------|----------------|
| [Screen 1] | [What it tests] | [Specifics] |
| [Screen 2] | [What it tests] | [Specifics] |

### What We're NOT Building
[Explicitly state what's out of scope for the prototype]

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Success Criteria

### Quantitative Criteria
| Metric | Threshold | Measurement |
|--------|-----------|-------------|
| [Metric 1] | >[X]% | [How measured] |
| [Metric 2] | >[Y]% | [How measured] |

### Qualitative Criteria
- [ ] Users can explain what the product does
- [ ] Users express genuine interest (not just politeness)
- [ ] [Specific comprehension/reaction criteria]

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Kill Criteria

We will NOT proceed if:
- [ ] [Quantitative failure condition]
- [ ] [Qualitative failure condition]
- [ ] [Time/resource limit exceeded]

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Decision Framework

| Result | Definition | Decision |
|--------|------------|----------|
| Strong positive | Exceeds all criteria | Proceed to [next phase] |
| Moderate positive | Meets minimum, some concerns | Proceed with [modifications] |
| Neutral | Mixed signals | [Specific response - iterate/investigate] |
| Negative | Fails criteria | Stop / Pivot to [alternative] |

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Timeline & Resources

### Timeline
| Phase | Duration | Dates |
|-------|----------|-------|
| Preparation | [X days] | [Dates] |
| Testing | [X days] | [Dates] |
| Analysis | [X days] | [Dates] |
| Decision | [X days] | [Dates] |

### Resources Needed
- [ ] [Person/role]: [What they do]
- [ ] [Tool/resource]: [What it's for]
- [ ] [Budget]: [What for]

license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

## Post-Validation

### Documentation
Where results will be recorded: [Location]

### Stakeholder Communication
Who needs to know results: [List]
How we'll share: [Method]

### Next Steps by Outcome
**If positive**: [What we do next]
**If negative**: [What we do instead]
**If unclear**: [How we resolve ambiguity]
```
