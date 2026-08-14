---
name: muji-style-app-design
description: A design skill for creating minimalist Japanese MUJI-inspired mobile applications. Focuses on information architecture, navigation hierarchy, cognitive load reduction, calm visual systems, and essential-first UX.
---

# MUJI Style App Design Skill

## Overview

This skill defines a minimalist mobile application design philosophy inspired by MUJI (無印良品).

The goal is not simply to create a visually empty interface, but to achieve:

"Complex thinking behind simple appearance."

A MUJI-style app removes unnecessary complexity while preserving essential user value.

The design principle:

> Remove everything that does not directly serve the user's intention.

---

# 1. Core Philosophy

## 1.1 Minimalism is subtraction, not reduction

Do not interpret minimalism as:

- fewer screens
- fewer features
- empty layouts
- simple decoration

Instead:

Minimalism means:

- fewer unnecessary decisions
- fewer visual interruptions
- clearer priorities
- shorter user paths

Every element must answer:

"Why does this exist?"

If the answer is unclear, remove or hide it.

---

# 2. Information Architecture

## 2.1 Primary Navigation Rule

The bottom navigation bar should contain only the most important user goals.

Recommended:

- 3-5 primary sections

Avoid:

- 6+ tabs
- feature-based navigation
- exposing every capability

Navigation should represent:

"Where users repeatedly want to go"

Not:

"Everything the product can do"

Example:

Good:
Home
Explore
Create
Collection
Profile

Bad:

Shopping
Coupon
Activity
Message
Settings
History
Membership
Search

---

# 3. Feature Classification

Every feature should be classified into three layers.

## Layer 1: Core Action

Always visible.

Characteristics:

- high frequency
- high user value
- repeated daily behavior

Examples:

- Create
- Search
- Purchase
- Check status

---

## Layer 2: Supporting Action

Accessible but not dominant.

Placement:

- secondary pages
- cards
- contextual actions

Examples:

- recommendations
- filters
- history

---

## Layer 3: Hidden Complexity

Move into:

- hamburger menu
- settings
- profile area

Examples:

- account management
- preferences
- rarely used tools

Principle:

"Users should not pay cognitive cost for functions they rarely use."

---

# 4. Navigation Order Principle

## Default order ≠ importance order

Traditional apps often arrange:

Most important → first tab

MUJI-style thinking:

Navigation position should consider:

1. Usage frequency
2. Duration of stay
3. User expectation

Example:

A membership/passport page:

- visited frequently
- user checks information quickly
- short interaction duration

Therefore:

It can appear first after app launch,
while remaining last in navigation.

Reason:

The launch state serves immediate user intention,
not navigation hierarchy.

---

# 5. Home Screen Principle

## The first screen should answer:

"What does the user want right now?"

Not:

"What does the company want to promote?"

Avoid:

- excessive banners
- marketing walls
- feature announcements

Prefer:

- current user goal
- personalized content
- immediate value

---

# 6. Commerce App Principle

For shopping applications:

Prioritize user motivation.

Typical priority:

1. Current benefit
2. Existing needs
3. New discovery

Example:

User thinking:

"Is anything discounted?"

before:

"What products are new?"

Therefore:

Promotion / sale information should often be integrated into recommendation areas.

Do not separate:

- Sale
- Recommendation
- New products

if they serve the same shopping intention.

---

# 7. Visual Language

## 7.1 Color

Use:

- neutral backgrounds
- natural tones
- low saturation colors

Avoid:

- excessive gradients
- aggressive promotional colors
- unnecessary contrast

Color should communicate hierarchy.

Not decoration.

---

## 7.2 Typography

Use:

- clear hierarchy
- generous spacing
- readable sizes

Avoid:

- dense information blocks
- excessive font variation

Recommended hierarchy:
Large title
Medium section title
Body content
Supporting information


---

# 8. Space and Emptiness

## Empty space is an interaction resource

Whitespace provides:

- focus
- calmness
- visual breathing room
- emotional comfort

Do not fill every pixel.

The interface should feel:

"quiet"

rather than:

"empty"

---

# 9. Component Design Rules

## Cards

Avoid:

- excessive shadows
- rounded containers everywhere
- information overload

Prefer:

- simple grouping
- natural spacing
- clear boundaries

---

## Buttons

Primary actions:

- obvious
- limited quantity

Avoid:

Multiple competing CTA buttons.

One screen:

One primary intention.

---

# 10. Interaction Philosophy

## Reduce decision fatigue

Bad:

User sees:

- 10 options
- 5 buttons
- 8 recommendations

Good:

System understands:

"What is probably needed now"

and presents:

- one clear path
- optional exploration

---

# 11. AI Design Generation Prompt

When generating a MUJI-style application:

Follow these constraints:
Create a minimalist Japanese-inspired mobile app.
Prioritize:
essential functions
calm information hierarchy
reduced cognitive load
intentional whitespace
simple navigation
hidden secondary complexity
Navigation:
Maximum 5 tabs.
Primary interface:
Only show frequent user goals.
Secondary functions:
Move into menus or contextual locations.
Visual style:
Natural colors,
clean typography,
quiet premium feeling,
functional minimalism.
Avoid:
excessive cards
aggressive marketing banners
unnecessary animations
feature overload.
The final experience should feel:
calm,
rational,
timeless,
and human-centered.


---

# 12. Design Checklist

Before shipping:

- [ ] Does every visible element have a clear purpose?
- [ ] Are low-frequency functions hidden?
- [ ] Is navigation limited to 3-5 core destinations?
- [ ] Does the first screen match user intention?
- [ ] Can users complete the main task quickly?
- [ ] Is whitespace improving focus?
- [ ] Does the interface feel calm rather than empty?

---

# Final Principle

A MUJI-style application is not an app with fewer things.

It is an app where every remaining thing matters.

"Less interface.
More understanding."
