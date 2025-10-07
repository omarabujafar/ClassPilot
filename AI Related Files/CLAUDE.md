# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

ClassPilot is a **Student Operating System** that unifies classes, deadlines, and goals into a single, proactive companion. It answers: "What matters now, why, and how do I finish it on time?"

### Core Value Proposition
- Centralizes scattered learning platforms, calendars, and tasks into one intelligent hub
- Prioritizes tasks based on urgency, grade impact, and personal goals
- Guides students from first reminder to final submission with actionable steps
- Reduces cognitive overload and academic stress through calm, context-aware support

### Target Users
- **The Striver**: ambitious GPA targets; needs goal-aligned guidance
- **The Juggler**: limited time; needs ruthless prioritization
- **The Starter**: new to college/HS systems; needs clarity and coaching
- **The Returner**: working adult learners; needs predictability and low cognitive load

## Product Pillars

1. **Unification** — one hub synchronized with the learner's academic world
2. **Guidance** — transforms information into prioritized, doable steps
3. **Foresight** — makes grade impact and scheduling implications obvious
4. **Momentum** — creates small wins and steady progress
5. **Trust** — privacy-first, student-first, transparent and respectful

## Core Features (Planned)

### Dashboard
- **Today View**: current priorities with impact, urgency, and time estimates
- **Plan Ahead**: conflict detection and smart scheduling for upcoming tasks
- **What-If Calculator**: grade forecasting based on hypothetical scores
- **Submission Path**: clear hand-off to LMS or submission portal
- **Progress Tracking**: streaks, badges, and weekly digest (minimal, meaningful)

### UI/UX Direction
- **Tone**: Calm, capable, encouraging—never frantic or patronizing
- **Theme Support**: Both light and dark modes (see mockups in `AI Related Files/`)
- **Design Principles**: Quiet focus, clarity, and visible progress
- **Accessibility**: Keyboard/screen-reader friendly, inclusive language

### Key Sections (from mockups)
- **Profile & Stats**: GPA tracking, level/XP system, active classes, submissions
- **Class Cards**: Course-specific views with upcoming assignments and due dates
- **To-Do List**: Context-aware task management with academic relevance
- **Calendar Integration**: Visual planning with conflict highlighting
- **Classmate AI**: Student-facing assistant for planning and guidance

## Design Ethos

### What ClassPilot IS
- A unified view that reduces uncertainty and increases momentum
- Smart prioritization based on grade impact and personal goals
- Gentle accountability without notification fatigue

### What ClassPilot IS NOT
- Not a replacement LMS
- Not a shortcut to bypass learning
- Not a notification machine trading attention for metrics

### Brand Voice
- Character: A reliable upper-class mentor who knows the system
- Language: Clear, actionable, supportive
- Tagline: "Know what matters now" / "Clarity → Momentum"

## Architecture Considerations

### Integration Strategy
- Cross-platform by design: must work with multiple LMS systems (Canvas, Blackboard, Moodle, etc.)
- Student-first surface that respects institutional tools
- Privacy-preserving: student controls all connections and can disconnect anytime

### Success Metrics
- Earlier submissions (≥24h before deadline)
- Reduced missed assignments
- Steady weekly engagement during term
- Self-reported stress reduction
- Goal attainment rates (GPA, completion)

## Academic Integrity
- All guidance focuses on understanding and planning, never shortcuts
- Respects institutional academic integrity policies
- Helps students manage time and priorities, not complete work for them

## Development Phase

**Current Status**: Project initialization
- Vision document and UI mockups completed
- No implementation files yet present
- Ready for technical architecture and stack selection

When implementing:
- Reference the vision document at `AI Related Files/ClassPilot Vision.txt`
- Use the mockups in `AI Related Files/` as UI reference for both light and dark themes
- Prioritize student privacy and data control in all architectural decisions
- Design for scalability across multiple educational institutions and LMS platforms
