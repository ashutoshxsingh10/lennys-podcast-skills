---
name: behavior-ux-design
description: Design product experiences using behavioral psychology to drive desired user actions. Use when designing engagement mechanics, habit-forming features, or behavior change interventions. Wisdom sourced from Lenny's Podcast transcripts.
license: MIT
metadata:
  source: "Lenny's Podcast by Lenny Rachitsky"
  source_url: "https://www.lennysnewsletter.com/podcast"
  credits: "All product wisdom derived from Lenny's Podcast guest interviews"
  version: "1.0"
---

# Behavior & UX Design

## What This Skill Produces
- Behavior intervention specifications
- Habit loop designs
- Nudge and friction analysis
- Engagement mechanic specifications

## User Input Required
Provide brief context (3-5 sentences):
- What behavior do you want users to adopt?
- What product/feature is this for?
- Who is the target user?

---

## Embedded Wisdom: Three Bs Framework

### Kristen Berman's Complete Methodology

"There are so many mistakes that humans make - biases, heuristics. Our team uses psychologies. What are the psychologies that drive us? Our team created a model of behavior change we call the three Bs. We've used this at Google, Microsoft, LinkedIn."

### B1: Behavior (Define the Specific Action)

"First B is behavior. In order to change behavior, you have to pick a behavior that you want to change. Companies are really good at outcomes, but just not as sharp at picking the behavior. When I say behavior, I mean action - the thing that you want someone to do."

**Common Mistake**: Defining outcomes instead of behaviors
- Wrong: "We want users to be more engaged"
- Right: "We want users to complete one lesson per day"

**The Uncomfortably Specific Test**:
Ask: "If I watched a user on camera, could I clearly see them doing this behavior?"
- Wrong: "Use the product more" (too vague)
- Right: "Click the 'Start Lesson' button at 9am" (observable)

**Behavior Definition Template**:
- WHO: [Specific user segment]
- DOES WHAT: [Exact action]
- WHEN: [Time/trigger]
- WHERE: [Context/location]
- HOW OFTEN: [Frequency target]

### B2: Barriers (Remove Friction)

"The second B is barriers. What is stopping the user from doing the behavior? This is where we look at ability, time, cognitive load, and anxiety."

**Types of Barriers**:

| Barrier Type | Question | Example |
|--------------|----------|---------|
| Ability | Can they physically do it? | Form too complex |
| Time | Do they have time? | Takes too long |
| Cognitive | Is it confusing? | Too many choices |
| Social | Is it embarrassing? | Fear of judgment |
| Anxiety | Are they worried? | Fear of making mistakes |

**Barrier Reduction Strategies**:
- **Reduce steps**: Every click is a chance to drop off
- **Provide defaults**: Don't make users choose when you can choose for them
- **Remove decisions**: Paradox of choice - fewer options = more action
- **Add progress indicators**: Uncertainty causes abandonment

### B3: Benefits (Make Rewards Visible)

"The third B is benefits. How do we make the reward immediate and visible? People discount future rewards heavily."

**Immediate vs. Delayed Rewards**:
- Humans heavily discount future benefits
- "You'll be healthier in 10 years" < "You'll feel accomplished right now"
- Design for immediate feedback on every action

**Types of Benefits to Design**:
1. **Progress signals**: Show advancement toward goal
2. **Social validation**: Recognition from others
3. **Intrinsic satisfaction**: The action itself feels good
4. **Tangible rewards**: Points, badges, unlocks

---

## Embedded Wisdom: Habit Formation (Hooked Model)

### Nir Eyal's Framework

"Master the internal triggers. When you say 'I'm going to check email,' there's some underlying emotion that you're trying to escape. Understanding that emotion is key to building habits."

### The Hook Cycle

**1. Trigger** (What prompts the behavior)

**External Triggers**: Things in the environment
- Notifications
- Emails
- Visual cues
- Time-based prompts

**Internal Triggers**: Emotions that precede the behavior
- Boredom → Social media
- Loneliness → Messaging apps
- Anxiety → News checking
- Uncertainty → Search

"The most powerful triggers are internal. External triggers get you started, but internal triggers create habits."

**2. Action** (The behavior itself)

**Fogg Behavior Model**: Behavior = Motivation × Ability × Trigger
- All three must be present
- Increase any one to increase behavior

**Make Action Easy**:
- Reduce friction (fewer clicks)
- Simplify the UI
- Provide clear affordances
- Make the default the desired action

**3. Variable Reward** (Unpredictable payoff)

"Variable rewards are more engaging than predictable ones. It's why slot machines work."

**Three Types of Variable Rewards**:
- **Tribe**: Social rewards - likes, comments, recognition
- **Hunt**: Resources - information, money, deals
- **Self**: Personal achievement - mastery, completion, leveling up

**Key**: The reward must be variable, not guaranteed. Predictable rewards lose power over time.

**4. Investment** (User puts something in)

"Investment increases the likelihood of the next pass through the hook cycle."

**Types of Investment**:
- Data/content (uploads, posts, saves)
- Reputation (followers, karma, history)
- Skill (learning the interface)
- Social (connections, relationships)

**Investment creates**:
- Stored value (product gets better with use)
- Commitment (sunk cost)
- Next trigger (sets up future engagement)

---

## Embedded Wisdom: Streak Systems

### Duolingo's Streak Lessons

"Duolingo has a strong 'test it' philosophy. We actually tested: what if we make it even easier to extend your streak? If you do one exercise, just one exercise, it extends your streak."

**The Result**: "DAUs moved not one bit. What we were doing by making it too easy was cheapening the streak."

**Key Insight**: "Nobody thinks about 'I just want to do one question on Duolingo.' We had dumbed down the unit of measure. A lesson is the meaningful unit, not a question."

### Streak Design Principles

1. **Meaningful unit**: The action required should feel accomplishment-worthy
2. **Recovery mechanism**: Allow ways to recover broken streaks (streak freeze, repair)
3. **Progressive value**: Longer streaks should feel increasingly valuable
4. **Loss aversion**: The pain of losing a streak motivates return

### Streak Frequency Matching

"Figure out what your usage pattern is and build your streak around it."

| Natural Usage | Streak Type | Example |
|---------------|-------------|---------|
| Daily | Daily streak | Duolingo, meditation apps |
| Weekly | Weekly streak | Peloton, fitness apps |
| Variable | Activity streak | X activities per week |

"Peloton has weekly streaks because the idea of doing a workout every single day was too hard. But a weekly streak was something users could keep up."

---

## Embedded Wisdom: Emotional Design

### Bob Moesta on Context & Outcome

"One of the biggest misconceptions is that it's pain and gain. It's actually context and outcome."

**Application to UX**:
- Don't just address the "pain" (problem)
- Design for the desired outcome (how they want to feel after)
- The emotional end state matters more than the functional solution

### Adam Fishman on Emotional Framing

"Most people come to your product with an emotional frame. A lot of people want to appeal to their logical brain right away. Don't do that."

**Emotional-First Design**:
1. Acknowledge their current state (anxiety, frustration, hope)
2. Show you understand their goal (the outcome they want)
3. Build confidence before asking for action
4. Celebrate progress to reinforce emotional reward

---

## Behavior Design Patterns

### Pattern: Progressive Commitment

Start with small asks, build to larger ones.

1. **Micro-commitment**: Tiny first action (click, view)
2. **Small commitment**: Low-effort action (like, save)
3. **Medium commitment**: Moderate effort (create, post)
4. **Large commitment**: Significant investment (invite, pay)

### Pattern: Default to Desired Behavior

"People rarely change defaults."

- Pre-select the option you want users to choose
- Make the desired behavior the path of least resistance
- Require action to deviate from the good choice

### Pattern: Social Proof Nudges

"X people are doing Y right now"
"Users who did X saw Y result"

- Show others' behavior to normalize the action
- Especially effective for uncertain users

### Pattern: Loss Aversion

People feel losses more than gains.

- "You'll lose your progress" > "You'll gain progress"
- Streak systems leverage loss aversion
- Free trials with countdown create urgency

### Pattern: Commitment Devices

Help users commit to future behavior.

- "Remind me tomorrow"
- Pre-scheduled actions
- Public commitments

---

## Output Template

```markdown
# Behavior Design: [Feature/Product Name]

## Target Behavior Definition

### The Behavior (Uncomfortably Specific)
| Component | Specification |
|-----------|---------------|
| WHO | [Specific user segment] |
| DOES WHAT | [Exact observable action] |
| WHEN | [Time/trigger/context] |
| WHERE | [Location/state in product] |
| HOW OFTEN | [Frequency goal] |

### Observable Test
"If I watched on camera, I would see the user [exact action]"

### Current Behavior
What users do now instead: [Current state]

### Behavior Change Type
- [ ] Start doing (new behavior)
- [ ] Stop doing (eliminate behavior)
- [ ] Do more of (increase frequency)
- [ ] Do differently (modify existing behavior)

---

## Three Bs Analysis

### B1: Behavior Clarity Check
- [ ] Behavior is specific and observable
- [ ] Behavior is achievable by target users
- [ ] Behavior directly leads to desired outcome
- [ ] Behavior can be measured/tracked

### B2: Barrier Analysis
| Barrier Type | Current Barrier | Design Solution |
|--------------|-----------------|-----------------|
| Ability | [What makes it hard?] | [How to make easier] |
| Time | [Why no time?] | [How to make faster] |
| Cognitive | [What's confusing?] | [How to simplify] |
| Social | [What's embarrassing?] | [How to normalize] |
| Anxiety | [What's scary?] | [How to reassure] |

### B3: Benefit Design
| Benefit Type | Current State | Design Solution |
|--------------|---------------|-----------------|
| Immediate reward | [What happens now?] | [New immediate payoff] |
| Progress signal | [How is progress shown?] | [Better visualization] |
| Social validation | [Recognition?] | [Social features] |
| Intrinsic satisfaction | [Does it feel good?] | [Enhance satisfaction] |

---

## Hook Cycle Design

### Trigger Design

**External Triggers**:
| Trigger | Timing | Channel | Message |
|---------|--------|---------|---------|
| [Trigger 1] | [When] | [How] | [What it says] |
| [Trigger 2] | [When] | [How] | [What it says] |

**Internal Trigger Target**:
The emotion we're connecting to: [Boredom / Anxiety / Loneliness / etc.]
When users feel [emotion], we want them to think of [our product/action]

### Action Design

**Current friction points**:
1. [Friction 1] → Remove by: [Solution]
2. [Friction 2] → Remove by: [Solution]

**Minimum viable action**:
The smallest possible version of the behavior: [Micro-action]

### Variable Reward Design

**Reward Type**: Tribe / Hunt / Self

**Implementation**:
- What varies: [Element of unpredictability]
- Range of outcomes: [Min to max reward]
- Frequency of reward: [How often]

### Investment Design

**What users invest**:
| Investment Type | How It Accumulates | Switching Cost |
|-----------------|-------------------|----------------|
| [Data/content] | [How] | [High/Med/Low] |
| [Reputation] | [How] | [High/Med/Low] |
| [Relationships] | [How] | [High/Med/Low] |

**How investment loads next trigger**:
[How completing action sets up return]

---

## Streak/Progress System (If Applicable)

### Streak Design
**Unit of measure**: [What counts as completion]
**Frequency**: Daily / Weekly / [Custom]
**Justification**: Natural usage pattern is [X], so streak matches

### Recovery Mechanism
- Streak freeze: [How it works]
- Repair option: [How users can recover]

### Progressive Value
- 7-day streak: [Reward/recognition]
- 30-day streak: [Reward/recognition]
- 100-day streak: [Reward/recognition]

---

## Implementation Specs

### UI/UX Changes
| Element | Current State | New Design | Behavioral Rationale |
|---------|---------------|------------|---------------------|
| [Element] | [Current] | [New] | [Why this works] |

### Copy/Messaging
| Context | Current | New | Principle Applied |
|---------|---------|-----|-------------------|
| [Prompt] | [Current] | [New] | [Behavioral principle] |

### Notification Design
| Trigger | Timing | Message | Expected Response |
|---------|--------|---------|-------------------|
| [Event] | [When] | [Text] | [Action] |

---

## Metrics

### Primary Behavior Metrics
| Metric | Baseline | Target | Measurement |
|--------|----------|--------|-------------|
| Behavior frequency | [Current] | [Goal] | [How measured] |
| Time to first behavior | [Current] | [Goal] | |
| Behavior retention (D7, D30) | [Current] | [Goal] | |

### Supporting Metrics
| Metric | Purpose | Target |
|--------|---------|--------|
| [Trigger → Action rate] | Trigger effectiveness | |
| [Action → Reward rate] | Reward delivery | |
| [Investment completion] | Stickiness | |

---

## Guardrails

### Ethical Considerations
- [ ] Behavior serves user's genuine interests
- [ ] Users can easily opt out
- [ ] No dark patterns or manipulation
- [ ] Transparent about how system works

### What We Won't Do
- [Manipulative tactic we're avoiding]
- [Dark pattern we reject]
```
