# Design System

| Field | Value |
| ------ | ------ |
| Status | Draft |
| Version | 1.0 |
| Last Updated | July 2026 |
| Owner | Tanyieleke Nkolaka |
| Repository | portfolio |

---

## Purpose

This document defines the reusable visual language, interaction patterns, and interface standards for the engineering website.

Its purpose is to ensure consistency across the entire product while allowing the website to evolve over time.

Whenever new pages or features are introduced, they should follow the standards defined here rather than introducing new design patterns.

---

## Relationship to Other Documents

This document should be read alongside:

- Product Requirements
- Site Map
- Design Principles
- Content Architecture

The Design Principles explain *why* the website is designed this way.

The Design System explains *how* those principles are implemented.

---

## Foundations

### Design Philosophy

The interface should feel:

- Professional
- Calm
- Technical
- Modern
- Spacious
- Timeless

The interface should never distract from the engineering work it presents.

---

## Layout

### Layout Model

The website uses a centered content layout.

Primary content should never span the full width of the browser.

Long-form reading content should remain comfortably readable on large displays.

---

### Grid

Use a responsive 12-column grid.

Layouts should adapt naturally across desktop, tablet, and mobile devices.

---

### Content Width

Three primary container widths:

- Reading Width (case studies, articles)
- Standard Width (general pages)
- Wide Width (diagrams, galleries, architecture illustrations)

---

## Typography

Typography is the primary method of creating visual hierarchy.

### Typeface

Primary Typeface:

Inter

Fallback:

System UI fonts

---

### Hierarchy

Display

↓

H1

↓

H2

↓

H3

↓

Body

↓

Caption

↓

Code

Every page should follow the same hierarchy.

---

### Reading Experience

Prioritize:

- generous line height
- comfortable paragraph spacing
- moderate line lengths
- clear heading separation

Technical writing should remain enjoyable to read.

---

## Spacing

Whitespace is considered an active design element.

Spacing should create structure rather than merely separating elements.

Adopt a consistent spacing scale throughout the website.

---

## Color Philosophy

Color should communicate meaning rather than decoration.

The interface should rely primarily on typography, spacing, and layout.

Color should reinforce hierarchy instead of replacing it.

---

### Semantic Colors

Define colors by purpose rather than hexadecimal values.

Examples:

- Primary
- Secondary
- Accent
- Surface
- Background
- Border
- Success
- Warning
- Error
- Information

Actual color values may evolve without changing their semantic meaning.

---

## Navigation Patterns

Navigation should always answer:

Where am I?

Where can I go next?

Primary navigation:

- Home
- About
- Projects
- Notes
- Open Source
- Resume
- Contact

Footer navigation may contain:

- Now
- GitHub
- LinkedIn
- Resume
- Email

---

## Content Patterns

### Hero

Purpose

Introduce the engineer and communicate the website's primary message.

---

### Project Snapshot

Every project begins with a concise summary.

Include:

- Status
- Category
- Duration
- Role
- Technologies
- Repository
- Demo
- Last Updated

---

### Engineering Case Study

Every project follows the same structure:

- Overview
- Problem
- Motivation
- Solution
- Architecture
- Technology Stack
- Implementation
- Challenges
- Trade-offs
- Results
- Lessons Learned
- Future Improvements

---

### Evidence Panel

Whenever possible, support claims with evidence.

Examples:

- Repository
- Demo
- Screenshots
- Metrics
- Architecture Diagram
- Documentation

---

### Technology Stack

Display technologies consistently.

Avoid decorative logo walls.

Prioritize readability over visual density.

---

## UI Patterns

Reusable patterns include:

- Buttons
- Cards
- Tags
- Status Badges
- Callouts
- Code Blocks
- Tables
- Timeline
- Forms
- Alerts
- Image Galleries

Each pattern should evolve independently while remaining visually consistent.

---

## Status System

Standardize project maturity.

| Status | Meaning |
| -------- | ------- |
| Published | Production-ready and showcased |
| In Progress | Active development |
| Planned | Approved but not started |
| Archived | Preserved but no longer maintained |

These statuses may be reused throughout the website.

---

## Motion

Motion should support usability.

Appropriate uses include:

- hover feedback
- page transitions
- menu expansion
- scrolling cues

Avoid decorative animations that do not improve understanding.

---

## Imagery

Images should communicate engineering work.

Examples:

- architecture diagrams
- screenshots
- workflows
- data visualizations
- implementation photos

Images should include descriptive captions whenever appropriate.

---

## Accessibility

Accessibility is required.

The website should support:

- semantic HTML
- keyboard navigation
- visible focus states
- sufficient color contrast
- descriptive alternative text
- reduced motion preferences
- responsive layouts

---

## Responsive Design

The website should function effectively across:

- Desktop
- Laptop
- Tablet
- Mobile

Content should adapt without sacrificing readability.

---

## Non-Goals

The website intentionally avoids:

- autoplay media
- unnecessary animations
- excessive gradients
- cluttered layouts
- technology logo walls
- distracting visual effects
- unsupported marketing claims

---

## Future Extensions

Future versions of this Design System may define:

- Timeline pattern
- Publications
- Speaking engagements
- Interactive demos
- Search interface
- Design tokens
- Dark mode
- Component variants

---

## Open Questions

- Should project pages support embedded video by default?
- Should architecture diagrams follow a standard style?
- How should interactive demos be presented?

---

## Related Documents

- Product Requirements
- Site Map
- Design Principles
- Content Architecture
- Decision Log
