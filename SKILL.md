---
name: muji-style-app-design
description: >
  Provides expert guidance on designing minimalist mobile apps following MUJI style principles.
  Covers navigation architecture, content priority, and launch page strategy.
version: 1.0.0
author: Your Name
tags: [design, minimalist, app, ux, mui]
---

# MUJI Style App Design Skill

## Purpose

This skill enables an AI assistant to offer design recommendations for mobile apps that follow the minimalist, restrained philosophy of MUJI (Mujirushi Ryohin).  
It is based on an analysis of the MUJI app's architecture and interaction patterns, distilled into actionable principles.

## When to Use

Use this skill when:

- A user asks for advice on designing a minimalist mobile app.
- A user wants to evaluate or improve an existing app's information architecture.
- A user specifically mentions MUJI style, minimalist design, or similar aesthetics.

## Core Principles

### 1. Simplicity First

- The main interface should only present the most essential functions.
- Avoid information overload; use generous whitespace and clean visuals.
- Secondary features must be hidden away, not competing for attention.

### 2. Functional Focus

- The bottom navigation bar should contain **exactly 5 main functional modules** — no more, no less.
- Select only the functions that users use most frequently and that provide the highest value.
- All non-core functions (settings, order history, help, etc.) go into a hamburger menu or secondary screen.

### 3. User Needs First

- Content display order should align with real user priorities.
- Users typically care more about **discounts and sales** than about new product launches.
- High-frequency but single-purpose features (e.g., points/status check) need special entry treatment.

## Navigation Design Guidelines

- **Bottom navigation**: 5 tabs only.  
  Example: `[Featured] [Categories] [Cart] [My Account] [Passport]`
- **Hamburger menu**: Everything else.  
  Example: `Settings, Order History, Coupons, Help Center, About`
- **Balance**: Keep core functions visible, secondary functions accessible but out of the way.

## Content Strategy: Discount Information First

- Always integrate discount information into the homepage or main recommendation module.
- Prioritize displaying "SALE" or promotional banners above new arrivals.
- Even if promotions are not always active, reserve a prominent entry (banner, badge, or tab).
- Reference: Tmall flagship store uses a large "SALE" visual as the first screen element.

## Launch Page & High-Frequency Entry

### Special Launch Logic

- After launch, the app may first show the **last** navigation tab (e.g., "Passport") rather than the first.
- **Reason**: This feature has very high usage frequency but short session duration (users just check points/status).
- **Design pattern**: Place it at the end of the navigation (low visual priority), but make it the default page at launch (high functional priority).

### Application Rules

- For high-frequency, lightweight functions, consider showing them briefly at launch or setting them as the default page.
- Dynamically adjust the launch page based on user behavior data if possible.
- Do not promote such functions to the first tab just because they are frequently used; keep navigation balanced.

## Practical Recommendations

1. **Review navigation regularly**: Use analytics to confirm the top 5 functions still meet user needs.
2. **Prioritize discounts**: Put sale/promotion information where users see it immediately.
3. **Use launch page for light functions**: Points, check-in, reminders — reduce steps for users.
4. **Stay restrained**: When adding new features, put them in the hamburger menu first, not the main nav.

## Example Interactions

### User asks: "How should I design the navigation for my minimalist shopping app?"

**AI Response (using this skill):**

> Based on MUJI style principles, your bottom navigation should have exactly 5 tabs representing the most essential functions. For a shopping app, a good structure might be:  
> `[Featured] [Categories] [Cart] [Profile] [Rewards]`  
> All other features (order history, settings, customer service) go into a hamburger menu.  
> Also, make sure to show sale/promotional content prominently in the Featured tab, because users care most about discounts.

### User asks: "Why does the MUJI app open to the passport page instead of the home page?"

**AI Response (using this skill):**

> The passport page has very high usage frequency — users check their points or membership status often — but each visit is very short. Placing it at the end of the navigation keeps the main tabs balanced, while making it the launch page satisfies the high-frequency need. This is a smart pattern: use the launch page to serve a frequent but lightweight task.

## Final Note

When applying this skill, always adapt the recommendations to the specific context of the user's product. The principles are guidelines, not rigid rules. The goal is to achieve clarity and focus, not to replicate MUJI exactly.
