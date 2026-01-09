# Oracle System Schema v1.0

This file defines the strict structure of the Oracle system. Use it to validate your files and prevent drift.

---

## Core Principles (IMMUTABLE)

These principles MUST NOT change:

1. **The Oracle respects who you are** - Works WITH patterns, not against them
2. **5 specialized advisors** - Careers, Financial, Legal, Marketing, Psychologist
3. **Advisor consensus drives action** - When all 5 agree, that's the signal
4. **Pattern recognition over advice** - Identifies behavioral patterns, doesn't judge them
5. **Accountability over motivation** - Tracks actions, not feelings

---

## File Structure (REQUIRED)

```
oracle/
├── README.md                    # REQUIRED: Main entry point
├── SCHEMA.md                    # REQUIRED: This file (validation)
├── SETUP_WIZARD.md              # OPTIONAL: Setup guide
├── advisors/                    # REQUIRED: 5 advisor files
│   ├── CareersAdvisor.md       # REQUIRED
│   ├── FinancialAdvisor.md     # REQUIRED
│   ├── LegalAdvisor.md         # REQUIRED
│   ├── MarketingAdvisor.md     # REQUIRED
│   └── Psychologist.md         # REQUIRED
├── background/                  # OPTIONAL: Personal context
├── clients/                     # OPTIONAL: Relationship tracking
├── finances/                    # OPTIONAL: Financial tracking
├── plans/                       # OPTIONAL: Action plans
├── projects/                    # OPTIONAL: Case studies
├── skills/                      # OPTIONAL: Capabilities
└── outreach/                    # OPTIONAL: Marketing materials
```

---

## README.md Structure (STRICT)

### Required Sections (in order):

1. **WHO: Your Context**
   - Identity (role, expertise, key facts)
   - Capabilities (what you're good at)
   - Validated by Others (3+ quotes)
   - Core Patterns (5+ behavioral patterns)

2. **WHERE: Current Status**
   - Financial (buffer, recurring, runway, debt)
   - Operational (key status points)
   - Relationships (client/partner status)
   - State (one-line summary)

3. **WHY: The Problem This System Solves**
   - Your strengths (what you have)
   - Your challenges (5+ specific challenges)
   - What Oracle provides (5+ specific benefits)

4. **HOW: The Advisory System**
   - AdvisorOracle role
   - 5 Advisors (brief summary each)
   - Advisor Consensus (5+ points all agree on)

5. **WHEN: Next Actions**
   - This Week (3+ priority actions)
   - This Month (3+ execution goals)
   - Month 1 Target (3+ measurable outcomes)
   - The One Question (single accountability question)

6. **AI Instructions: How to Be the Oracle**
   - Context summary
   - Role definition
   - Folder structure reference
   - Activation prompt

### Forbidden Changes:

- ❌ DO NOT remove any required sections
- ❌ DO NOT change section order
- ❌ DO NOT add "motivational" language
- ❌ DO NOT remove pattern recognition
- ❌ DO NOT add "fix you" language

---

## Advisor File Structure (STRICT)

Each advisor file MUST contain:

### 1. Role (one sentence)
What this advisor does

### 2. Current Status
Where you are now (advisor-specific)

### 3. Analysis
Advisor's assessment of situation

### 4. Strategy
Advisor's recommended approach

### 5. Recommendations
- Immediate (this week)
- Short-term (this month)
- Long-term (this quarter)

### 6. Red Flags
What to avoid (advisor-specific)

### 7. Green Flags
What to pursue (advisor-specific)

### Forbidden Changes:

- ❌ DO NOT merge advisors
- ❌ DO NOT add advisors (keep 5)
- ❌ DO NOT remove red/green flags
- ❌ DO NOT add "positive thinking" sections

---

## Validation Checklist

Run this check weekly to prevent drift:

### README.md Validation:
- [ ] All 6 required sections present
- [ ] Sections in correct order
- [ ] WHO section has 5+ patterns listed
- [ ] WHERE section has financial runway
- [ ] WHY section has 5+ challenges
- [ ] HOW section has all 5 advisors
- [ ] WHEN section has "The One Question"
- [ ] AI Instructions section present

### Advisor Files Validation:
- [ ] All 5 advisor files exist
- [ ] Each has Role section
- [ ] Each has Recommendations (immediate/short/long)
- [ ] Each has Red Flags section
- [ ] Each has Green Flags section
- [ ] No advisor files merged or deleted

### Language Validation:
- [ ] No "you can do it" motivational language
- [ ] No "fix yourself" language
- [ ] Pattern recognition language present
- [ ] Accountability language present
- [ ] "Works WITH patterns" language present

### Consensus Validation:
- [ ] Advisor Consensus section has 5+ points
- [ ] All 5 advisors referenced in consensus
- [ ] Consensus drives WHEN section actions
- [ ] No single advisor overriding consensus

---

## Anti-Drift Rules

### Rule 1: Pattern Recognition Over Advice
**CORRECT:** "This is retreat-to-building mode. Financial runway is 2 weeks. Pattern check needed."
**INCORRECT:** "You should stop building and do outreach instead."

### Rule 2: Accountability Over Motivation
**CORRECT:** "Did you send 20 outreach emails?"
**INCORRECT:** "You can do this! Believe in yourself!"

### Rule 3: Consensus Over Individual Opinion
**CORRECT:** "All 5 advisors agree: Direct outreach."
**INCORRECT:** "CareersAdvisor says do outreach."

### Rule 4: Respect Patterns, Don't Fix Them
**CORRECT:** "Marketing resistance is high. Use direct outreach (minimal visibility)."
**INCORRECT:** "You need to overcome your marketing resistance."

### Rule 5: Facts Over Feelings
**CORRECT:** "Buffer: £1,224. Runway: 2 weeks. Survival budget: £2,495/month."
**INCORRECT:** "You're doing great! Keep going!"

---

## Version Control

Track changes to prevent drift:

```bash
# Check for drift
git diff README.md
git diff advisors/

# Revert drift
git checkout README.md
git checkout advisors/CareersAdvisor.md

# Tag stable versions
git tag -a v1.0 -m "Stable Oracle configuration"
```

---

## AI Prompt for Validation

Use this prompt to check for drift:

```
Review my Oracle system against SCHEMA.md and identify any drift:

1. Check README.md structure (all 6 sections present and in order?)
2. Check advisor files (all 5 present with required sections?)
3. Check language (pattern recognition vs advice? accountability vs motivation?)
4. Check consensus (all 5 advisors agree on key points?)
5. Identify any drift from core principles

Report violations and suggest corrections.
```

---

## Schema Version History

**v1.0 (January 2026)**
- Initial schema definition
- 5 advisor structure
- Pattern recognition focus
- Accountability over motivation
- Consensus-driven action

---

## Enforcement

This schema is STRICT. If AI suggests changes that violate it:

1. **Reject the change**
2. **Reference this schema**
3. **Ask AI to validate against schema**
4. **Revert if drift detected**

The Oracle works BECAUSE of its structure. Drift breaks it.
