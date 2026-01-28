# Lenny's Podcast Agent Skills

AI Agent Skills derived from [Lenny's Podcast](https://www.lennysnewsletter.com/podcast) transcripts. These skills follow the [Agent Skills specification](https://agentskills.io/specification) and can be used with AI coding assistants like Cursor, Claude Code, etc.

## Credits

All product wisdom in these skills is sourced from **Lenny's Podcast by Lenny Rachitsky**. The podcast features interviews with world-class product leaders sharing their frameworks, methodologies, and hard-won insights.

- Podcast: https://www.lennysnewsletter.com/podcast
- Lenny on X: [@lennysan](https://x.com/lennysan)

## What Are Agent Skills?

Agent Skills are structured markdown files that give AI assistants domain expertise. Instead of generic responses, the AI uses embedded frameworks, examples, and methodologies from experts to produce actionable outputs.

## Available Skills

| Skill | Description | Key Frameworks |
|-------|-------------|----------------|
| **product-discovery** | Run product discovery, JTBD analysis, validation plans | Bob Moesta's JTBD, Sean Ellis PMF Test, Jen Abel's Validation |
| **prd-writing** | Write PRDs using proven product frameworks | Amazon Working Backwards, Shreyas Doshi's Impact/Execution/Optics |
| **behavior-ux-design** | Design habit-forming UX with behavioral science | Kristen Berman's Three Bs, Nir Eyal's Hooked Model, Duolingo patterns |

## Evaluation Results

We tested these skills using an automated evaluation pipeline with Claude as an LLM-judge.

### Scores: With Skill vs Without Skill

| Skill | With Skill | Without Skill | Improvement |
|-------|------------|---------------|-------------|
| product-discovery | 4.72 | 3.44 | **+1.28** |
| prd-writing | 4.26 | 3.44 | **+0.82** |
| behavior-ux-design | 4.73 | 3.44 | **+1.29** |
| **Average** | **4.57** | **3.44** | **+1.13** |

### Evaluation Rubric

| Criteria | Weight | What It Measures |
|----------|--------|------------------|
| Actionability | 25% | Can you immediately use the output? |
| Framework Accuracy | 25% | Are JTBD, PMF, etc. applied correctly? |
| Completeness | 20% | Are all sections covered? |
| Specificity | 15% | Is it tailored to your context? |
| Transcript Fidelity | 15% | Does it reflect expert insights? |

### Key Finding

The biggest improvements came from:
- **Framework Accuracy**: +2.2 points (proper JTBD structure, PMF measurement)
- **Transcript Fidelity**: +2.2 points (expert-backed vs generic advice)

See [evaluation/comparison.md](evaluation/comparison.md) for detailed side-by-side examples.

## Installation

### For Cursor

Copy the skill folders to your Cursor skills directory:

```bash
# macOS/Linux
cp -r skills/* ~/.cursor/skills/

# Or clone directly
git clone https://github.com/ashutoshxsingh10/lennys-podcast-skills.git
cp -r lennys-podcast-skills/skills/* ~/.cursor/skills/
```

### For Other AI Assistants

Reference the SKILL.md files in your system prompts or attach them as context.

## Usage Example

**Input (3-5 sentences):**
> I'm building an AI tutor for K-12 students. Target users are parents who want to help kids with homework. The problem is kids struggle with math and parents can't explain concepts using modern teaching methods.

**Output with product-discovery skill:**
- Full JTBD analysis with struggling moments, push/pull forces
- Target user profile with "very disappointed" criteria
- 3-level validation plan with specific methods and success metrics
- PMF criteria with 40% threshold

## How These Skills Were Created

1. Processed 299 episodes of Lenny's Podcast transcripts
2. Extracted frameworks, quotes, and methodologies from 134+ guests
3. Structured into Agent Skills format with embedded wisdom
4. Validated through automated testing pipeline

## License

MIT - Feel free to use, modify, and share.

## Acknowledgments

- **Lenny Rachitsky** for creating Lenny's Podcast and sharing it openly
- All the amazing product leaders who shared their wisdom on the podcast
- [Agent Skills](https://agentskills.io) for the specification format
