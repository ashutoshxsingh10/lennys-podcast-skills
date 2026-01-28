---
name: prd-writing
description: Write complete Product Requirements Documents that engineering can build from. Use when defining features, writing specs, scoping projects, or documenting product decisions. Wisdom sourced from Lenny's Podcast transcripts.
license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

# PRD Writing

## What This Skill Produces
- Complete Product Requirements Documents
- Feature specifications with user stories
- Success metrics and acceptance criteria
- Technical requirements and edge cases

## User Input Required
Provide brief context (3-5 sentences):
- What feature/product are you speccing?
- Who is it for?
- What problem does it solve?

---

## Embedded Wisdom: Working Backwards (Amazon Method)

### Ian McAllister's Complete Framework

"There's the concept of working backwards from what you're trying to accomplish. What are we trying to accomplish for the business or for a customer? Start there. If they have a problem that is interfering with their ability to be profitable or accomplish a goal, start with that problem."

**The Press Release Method**
"The mechanism Amazon used to enforce working backwards: the press release has a paragraph about the problem. That's what you write first. Then you write the solution paragraph, then the customer quote. Then the FAQ - is there a legitimate plan to succeed?"

### PRD Structure (Amazon-inspired)

**1. Press Release Format**
- Start with the customer problem (1 paragraph)
- Describe the solution (1 paragraph)  
- Include a customer quote (what they'd say about it)
- FAQ: Address skeptical questions

**2. Working Backwards Questions**
- What customer problem are we solving?
- What would the customer say about this solution?
- What's the simplest solution?
- What would make this a must-have vs nice-to-have?

---

## Embedded Wisdom: Strategy & Scoping

### Geoff Charles on Strategy

"Strategy means a lot of different things. In my mind, strategy is about how do we get to our goals? It's not a roadmap and it's not a vision, it's something right in between. So the first thing: align on what are the goals. Then the hypothesis - why do you think this will work? Figure out why we're uniquely positioned to get after that goal. Figure out the metrics by which you would measure success, then talk about the initiatives, the risks, and the long-term outcomes."

### PRD Elements from Strategy
1. **Goal alignment**: How does this feature connect to company goals?
2. **Hypothesis**: Why do we believe this will work?
3. **Unique positioning**: Why are we the right team to build this?
4. **Success metrics**: How will we measure if it worked?
5. **Risks**: What could go wrong?

### Shreyas Doshi: Three Levels of Product Work

"There are three levels of product work: impact, execution, and optics. Once you understand it, it explains a lot of what you see on product teams."

**Impact**: Does this move the needle on what matters?
**Execution**: Can we actually build and ship this well?
**Optics**: How will this be perceived by stakeholders?

A good PRD addresses all three levels.

### Dylan Field: The Tradeoff Triangle

"Quality, features, deadline - choose two."

When scoping a PRD, be explicit:
- **Quality + Features**: Deadline slips
- **Quality + Deadline**: Features cut
- **Features + Deadline**: Quality suffers

"The beautiful thing about software is you can keep iterating. You can ship with features and deadline, then improve quality iteratively over time."

---

## Embedded Wisdom: Hypothesis-Driven Development

### Framing Features as Experiments

Every feature is a bet. A good PRD makes the bet explicit:
- **Hypothesis**: We believe that [change] will [outcome] for [users] because [rationale]
- **Test**: How will we know if we're right?
- **Decision criteria**: What results mean ship/iterate/kill?

### Itamar Gilad: Confidence-Based Investment

"Tie your investment into the idea based on the level of confidence. Early on, do the cheap stuff just to gain more confidence, then invest more."

**Low confidence hypothesis**: 
- Validate before building
- PRD should include validation plan first

**High confidence hypothesis**:
- Full spec appropriate
- PRD should include complete requirements

---

## Embedded Wisdom: Scoping & Prioritization

### What's In vs Out of Scope

**Melissa Perri on Scope**
"In those early phases, finding product market fit, it's really about execution. Rapidly experimentation, trying to figure that out. All hands on deck."

**Scoping Questions**:
- What's the minimum to test the hypothesis?
- What can wait for v2?
- What would we build if we only had 2 weeks?

### The "Aha Moment" Focus

**Sean Ellis**: "How do you shape that first user experience so they actually use it in the right way and it's not so difficult that they give up?"

Your PRD should explicitly identify:
- What's the "aha moment" this feature enables?
- What's the shortest path to that moment?
- What can be cut that doesn't serve the aha moment?

---

## PRD Patterns by Feature Type

### New Feature PRD
Focus on: Hypothesis, success metrics, MVP scope
Key question: What's the minimum to validate the hypothesis?

### Improvement PRD  
Focus on: Current state, target state, migration plan
Key question: How do we improve without breaking existing users?

### Platform/Infrastructure PRD
Focus on: Technical requirements, scalability, dependencies
Key question: What does this enable for future features?

### Growth Feature PRD
Focus on: Funnel impact, experimentation plan, rollout strategy
Key question: How will we measure lift?

---

## Output Template

```markdown
# PRD: [Feature Name]

## Overview
**Author**: [Name]
**Status**: Draft | Review | Approved
**Target Release**: [Date/Sprint]
**Last Updated**: [Date]

---

## 1. Problem Statement

### Customer Problem
[One paragraph describing the customer problem - working backwards from their perspective]

### Current State
[How do users currently solve this problem? What's broken/frustrating?]

### Opportunity
[Why is now the right time? What's the business opportunity?]

---

## 2. Hypothesis

We believe that [solution/feature]
will [outcome/benefit]
for [target users]
because [rationale/evidence].

### Success Metrics
| Metric | Current | Target | Measurement |
|--------|---------|--------|-------------|
| Primary: [metric that proves hypothesis] | | | |
| Secondary: [supporting metric] | | | |
| Guardrail: [metric that must not degrade] | | | |

### Decision Criteria
- **Ship**: [Primary metric] improves by >[X]%, guardrails held
- **Iterate**: Mixed signals, run follow-up experiment
- **Kill**: Primary metric flat or negative, or guardrails broken

---

## 3. Solution

### Proposed Solution
[Describe the solution in 2-3 paragraphs. What will users be able to do?]

### User Flow
1. User [action] →
2. System [response] →
3. User [sees/does] →
4. Outcome: [end state]

### Key Features
| Feature | Priority | Rationale |
|---------|----------|-----------|
| [Feature 1] | Must-have | [Why essential for hypothesis] |
| [Feature 2] | Should-have | [Why important] |
| [Feature 3] | Nice-to-have | [Why lower priority] |

---

## 4. User Stories & Acceptance Criteria

### User Story 1: [Name]
**As a** [user type]
**I want to** [action]
**So that** [outcome/benefit]

**Acceptance Criteria**:
- [ ] Given [context], when [action], then [result]
- [ ] Given [context], when [action], then [result]
- [ ] [Edge case handling]

### User Story 2: [Name]
...

---

## 5. Scope

### In Scope (v1)
- [ ] [Feature/capability 1]
- [ ] [Feature/capability 2]
- [ ] [Feature/capability 3]

### Out of Scope (Future)
| Item | Reason | When to Revisit |
|------|--------|-----------------|
| [Feature X] | [Not needed for hypothesis] | v2 if v1 succeeds |
| [Feature Y] | [Technical complexity] | After [dependency] |

### What We're NOT Building
[Explicitly state what this is not, to prevent scope creep]

---

## 6. Design

### Mockups/Wireframes
[Link to Figma/designs or embed key screens]

### UX Considerations
- [Key interaction pattern]
- [Accessibility requirements]
- [Mobile considerations]

---

## 7. Technical Requirements

### API Changes
[Describe new/modified endpoints]

### Data Model Changes
[Describe schema changes, new tables, etc.]

### Dependencies
- [Dependency 1]: [Status/Timeline]
- [Dependency 2]: [Status/Timeline]

### Performance Requirements
- [Latency requirement]
- [Load expectation]
- [Scalability consideration]

---

## 8. Edge Cases & Error Handling

| Scenario | Expected Behavior | Error Message |
|----------|------------------|---------------|
| [Edge case 1] | [How we handle] | [User-facing message] |
| [Edge case 2] | [How we handle] | [User-facing message] |
| [Failure mode] | [Recovery behavior] | [User-facing message] |

---

## 9. Risks & Mitigations

| Risk | Likelihood | Impact | Mitigation |
|------|------------|--------|------------|
| [Technical risk] | Low/Med/High | Low/Med/High | [How we'll address] |
| [User adoption risk] | | | |
| [Business risk] | | | |

---

## 10. Launch Plan

### Rollout Strategy
- [ ] Feature flag: [Flag name]
- [ ] Phase 1: [X]% of users / [Segment]
- [ ] Phase 2: [Y]% of users / [Segment]  
- [ ] Phase 3: 100%

### Rollback Criteria
Rollback if:
- [Metric] drops below [threshold]
- [Error rate] exceeds [threshold]
- [Qualitative signal]

### Launch Checklist
- [ ] QA complete
- [ ] Metrics instrumented
- [ ] Feature flag configured
- [ ] Documentation updated
- [ ] Support team briefed
- [ ] Monitoring/alerts set up

---

## 11. Open Questions

| Question | Owner | Due Date | Resolution |
|----------|-------|----------|------------|
| [Question 1] | [Name] | [Date] | [Answer when resolved] |
| [Question 2] | | | |

---

## Appendix

### Customer Quotes
[Evidence from user research supporting this feature]

### Competitive Analysis
[How competitors handle this, if relevant]

### Historical Context
[Previous attempts, learnings from past features]
```
