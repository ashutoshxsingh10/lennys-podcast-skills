# Evaluation Rubric

We used an LLM-as-judge approach with Claude to evaluate skill outputs. Each output was scored on 5 criteria.

## Scoring Criteria

### 1. Actionability (25% weight)

Can someone immediately use this output to do the work?

| Score | Meaning |
|-------|---------|
| 5 | Output is immediately usable as-is, no modifications needed |
| 4 | Minor additions needed, but core is ready to use |
| 3 | Requires moderate work to be usable |
| 2 | Framework is there but content is too generic to act on |
| 1 | Not usable without significant rework |

### 2. Framework Accuracy (25% weight)

Are product frameworks and methodologies applied correctly? (e.g., Jobs to Be Done, Three Bs, PMF measurement)

| Score | Meaning |
|-------|---------|
| 5 | Frameworks applied correctly with proper terminology and full methodology |
| 4 | Mostly correct application, minor misunderstandings |
| 3 | Partial understanding shown, some misapplication |
| 2 | Significant misuse of frameworks |
| 1 | Frameworks mentioned but incorrectly applied or missing entirely |

### 3. Completeness (20% weight)

Does the output cover all expected sections and topics?

| Score | Meaning |
|-------|---------|
| 5 | All expected sections fully addressed with depth |
| 4 | 90%+ sections covered, minor gaps |
| 3 | 70-90% sections covered |
| 2 | Major sections missing |
| 1 | Barely addresses the request |

### 4. Specificity (15% weight)

Is the output tailored to the specific context given?

| Score | Meaning |
|-------|---------|
| 5 | Highly specific to the product/context, with concrete examples |
| 4 | Good specificity with some generic filler |
| 3 | Mix of specific and generic content |
| 2 | Mostly generic advice that could apply to anything |
| 1 | Completely generic, no customization to context |

### 5. Transcript Fidelity (15% weight)

Does the output reflect insights from Lenny's Podcast / expert sources?

| Score | Meaning |
|-------|---------|
| 5 | Includes specific quotes, real examples, and expert methodologies |
| 4 | References specific concepts and frameworks from known sources |
| 3 | General concepts that align with expert knowledge |
| 2 | Vague references without specificity |
| 1 | No connection to established product expertise |

## Weighted Score Formula

```
Final Score = (Actionability × 0.25) + (Framework Accuracy × 0.25) + 
              (Completeness × 0.20) + (Specificity × 0.15) + 
              (Transcript Fidelity × 0.15)
```

## Test Cases

Each skill was tested with 5 diverse scenarios:

| Test | Product Type | Complexity |
|------|--------------|------------|
| 1 | Consumer App | Simple |
| 2 | B2B SaaS | Medium |
| 3 | EdTech | Medium |
| 4 | Marketplace | Complex |
| 5 | FinTech | Complex |

## Results Summary

| Metric | With Skill | Without Skill | Delta |
|--------|------------|---------------|-------|
| Average Score | 4.57 | 3.44 | **+1.13** |

### By Criteria (Averaged Across All Tests)

| Criteria | With Skill | Without Skill | Delta |
|----------|------------|---------------|-------|
| Framework Accuracy | 5.0 | 2.8 | **+2.2** |
| Transcript Fidelity | 4.0 | 1.8 | **+2.2** |
| Completeness | 5.0 | 4.2 | +0.8 |
| Actionability | 4.6 | 4.0 | +0.6 |
| Specificity | 4.8 | 4.2 | +0.6 |
