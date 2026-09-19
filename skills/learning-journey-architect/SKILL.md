---
name: learning-journey-architect
description: Apply Ed Reif's integrated ISD + LXD + XMAL method to turn performance requirements, SOPs, objectives, legacy slide courses, and SME content into scroll-native learning journeys. Preserve objective, condition, standard, safety, and assessment rigor while designing human-centered experiences around mental models, practice, friction, decisions, transfer, field support, and evidence.
---

# Learning Journey Architect / XMAL

Use this skill when the user needs to architect a learning journey rather than default to a slide course.

## Operating premise

**ISD engineers the capability. LXD engineers the journey. XMAL engineers the experience.**

**The learner moves through meaning, not slides.**

Do not turn a performance problem into a course by default.

## Two-layer architecture

### ISD backbone
Preserve the technical chain:

**TASK → TLO/EO → CONDITION → PERFORMANCE → STANDARD → PRACTICE → EVIDENCE**

Ask:
- What must the learner perform?
- Under what conditions?
- To what standard?
- What errors matter?
- What evidence demonstrates competence?

### LXD journey
Design the human path:

**ORIENT → EXPLORE → NOTICE → DECIDE → PRACTICE → REFLECT → APPLY → PROVE**

Ask:
- Who is the learner?
- What do they already know?
- What frustrates or overloads them?
- What must become intuitive?
- Where should guidance disappear?
- What belongs in the workflow instead of memory?

## XMAL experience model

Prefer scroll-native, responsive progression over slide-by-slide navigation when the content and platform support it.

Replace:

**SCREEN → NEXT → SCREEN → NEXT → QUIZ**

with:

**SCROLL → ENCOUNTER → INTERACT → DECIDE → CONSEQUENCE → CONTINUE**

A journey may include bounded simulations or screens when they are the right interaction. The rule is not anti-slide; it is anti-default.

## Workflow

### 1. Establish the performance requirement
Extract the task, TLO, enabling objectives, conditions, standards, constraints, safety limits, error consequences, and evidence requirements.

### 2. Build the task decomposition
Map performance steps to tools, conditions, standards, likely errors, consequences, prerequisite knowledge, and decision points.

### 3. Understand the learner in context
Identify experience level, motivation, mental state, device/workflow, time pressure, cognitive load, interface friction, environmental distraction, and accessibility needs.

### 4. Decide whether training is actually required
Consider alternatives or complements:
- interface/workflow redesign;
- quick-reference card;
- checklist;
- searchable knowledge object;
- coaching;
- simulation;
- guided practice;
- performance support;
- automation or system feedback.

### 5. Map the journey
For each phase specify:
- target objective/capability;
- learner mindset;
- cognitive load;
- touchpoint/media;
- experience intervention;
- practice;
- feedback;
- evidence;
- transfer mechanism.

### 6. Design mental models before mechanics
Give the learner enough causal understanding to interpret the system. Avoid front-loading exposition that is not needed for performance.

### 7. Scaffold deliberate practice
Start with guidance, then progressively remove support. Feedback should explain consequences and reasoning rather than merely display Correct/Incorrect.

### 8. Introduce purposeful friction
Use ambiguity, faults, time pressure, competing signals, degraded resources, handoffs, or changing conditions only when they reflect the target performance environment.

### 9. Design for judgment
Where procedure becomes insufficient, use:

**SIGNAL → CONDITION → LIMIT → DECISION → EVIDENCE**

### 10. Design transfer
Move non-critical recall out of working memory when appropriate. Provide field support at the point of performance and define how formal learning transitions into real work.

### 11. Define evidence across the journey
Measure more than completion. Connect formative evidence, performance assessment, field behavior, and operational evidence.

### 12. Choose the delivery pattern
Prefer the simplest medium that develops the capability. For scroll-native digital journeys, use XMAL principles. For custom Rise interactions, invoke or follow the companion `rise-360-html-build` skill.

### 13. Test and update
Use field evidence to revise the journey, support, scenarios, thresholds, and assumptions.

## Required output pattern

Unless requested otherwise, produce:

1. **Performance requirement / TLO**
2. **Enabling objectives**
3. **ISD task decomposition**
4. **Learner/context analysis**
5. **Training vs performance-support decision**
6. **Integrated learner journey map**
7. **XMAL scroll architecture**
8. **Practice + friction plan**
9. **Assessment / evidence plan**
10. **Transfer + Level 3 behavior plan**
11. **Delivery recommendation**
12. **Update loop**

## Design rules

- Never discard the ISD matrix when moving into LXD.
- Never use engagement as a substitute for competence.
- Never use compliance completion as proof of performance.
- Never add interaction merely to create clicks.
- Never require memorization when reliable point-of-performance support is the better design.
- Do not hide critical standards, limits, or error consequences inside visual polish.
- Reduce unnecessary cognitive friction while preserving productive performance friction.
- Design mobile/responsive behavior from the start for scroll-native journeys.
- Preserve accessibility as part of the architecture, not a final QA step.

## Canonical XMAL implementation example

Use this live implementation as a reference for the XMAL direction:

**https://edcreates.s3.us-west-1.amazonaws.com/xmandash.html**

It demonstrates a vertically stacked, interactive instructional-design control panel rather than a conventional fixed slide sequence. Treat it as a reference implementation, not a template that must be copied visually.

See `references/xmal.md`.

## Rise 360 companion skill

The supplied **rise-360-html-build** skill is the production/engineering companion for custom HTML/CSS/JS interactions inside Articulate Rise 360.

Learning Journey Architect decides **what experience should exist and why**.

Rise 360 HTML Build decides **how a custom interaction is engineered, constrained, packaged, made accessible, and wired for completion inside Rise**.

Do not collapse these into one concern.

See `references/rise-360-companion.md`.

## Relationship to the Ed Reif Field System

**BUILD → DECIDE → POSITION → TEST → UPDATE**

Learning Journey Architect sits across BUILD and TRANSFER:
- Operational Readiness validates field capability.
- Judgment at the Edge structures consequential decisions.
- Design the Bet supports uncertain choices where appropriate.
- Test Against Reality closes the evidence/update loop.

## Closing test

> What must this person be able to do, what journey develops that capability, what support belongs in the workflow, and what evidence proves the capability survived contact with reality?
