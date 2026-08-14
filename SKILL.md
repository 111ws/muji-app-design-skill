# MUJI Style App Design Guidelines

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[中文版](./README.zh-CN.md)

A practical guide for designing minimalist mobile apps inspired by MUJI.  
Help designers and developers quickly understand and apply simple, restrained design principles to create products focused on core experience.

## Table of Contents

- [Introduction](#introduction)
- [Design Principles](#design-principles)
- [Architecture & Navigation](#architecture--navigation)
- [Content Strategy](#content-strategy)
- [Launch Page & High-Frequency Entry](#launch-page--high-frequency-entry)
- [Practical Advice](#practical-advice)
- [Contributing](#contributing)
- [License](#license)

---

## Introduction

The design of MUJI style apps continues MUJI's consistent philosophy of simplicity, nature, and restraint.  
Its core is to present only necessary information and functions, allowing users to focus on core tasks.  
This guide summarizes its key design decisions and is suitable for e-commerce, tool, or lifestyle apps pursuing a clean experience.

---

## Design Principles

1. **Simplicity First**  
   - The main interface only keeps the most core function entries to avoid information overload.  
   - The visual style is clean with ample whitespace to reduce visual noise.

2. **Functional Focus**  
   - The bottom main navigation bar contains only 5 major functional modules — no more, no less.  
   - Secondary functions are hidden in a hamburger menu to keep the main interface clean.

3. **User Needs First**  
   - Content display order should follow the user's real concerns (e.g., discount information > new products).  
   - High-frequency but single-purpose functions should receive special entry strategies.

---

## Architecture & Navigation

### Main Navigation Design

- **Quantity**: The bottom navigation bar fixes 5 tabs, representing the most core functional modules.  
- **Selection Criteria**: Only keep the functions that users use most frequently and that provide the highest value.  
- **Secondary Functions**: All non-core functions (e.g., settings, help, history, etc.) are hidden in the hamburger menu.

**Example Structure:**

Bottom navigation: [Featured] [Categories] [Cart] [My Account] [Passport]  
Hamburger menu: Settings, Order History, Coupons, Help Center, About, etc.

### Core Logic

- **Don't pile up features**: Better to be few and refined than many and cluttered.  
- **Balance discoverability and simplicity**: Core functions are directly visible, secondary functions are expanded on demand.

---

## Content Strategy

### Discount Information Displayed First

- **User Psychology**: Users usually care more about "what is on sale" than about new product launches.  
- **Design Suggestions**:  
  - Integrate discount information (e.g., SALE, discount zone) into the homepage or recommendation module and display it with priority.  
  - Even if promotions are not always available, reserve a prominent entry (e.g., banner, badge).  
  - Reference case: Tmall flagship store uses a large "SALE" visual to capture attention immediately.
---

## Launch Page & High-Frequency Entry

### Special Launch Logic

- **Phenomenon**: After launch, the app first enters not the first navigation tab but the last one (e.g., "Passport").  
- **Reason Analysis**:  
  - The function has a very high usage frequency (users often check points/membership status).  
  - But the function is single-purpose and users only stay for a short time.  
  - Therefore it is placed at the end of the navigation but displayed first at launch, balancing frequency and navigation simplicity.

### Design Implications

- **High-frequency but lightweight functions**: Consider showing them briefly at launch or setting them as the default page, without occupying a prominent position in the main navigation.  
- **Flexible default page**: Dynamically set the launch page based on user behavior data to improve efficiency.

---

## Practical Advice

1. **Regularly review navigation structure**: Use user behavior analysis to confirm whether the top 5 core functions still meet user needs.  
2. **Optimize content priority**: Put the information users care about most (e.g., discounts, promotions) in the front to reduce search cost.  
3. **Use launch page for high-frequency light functions**: For example, points, check-in, message reminders, etc., to reduce user operation steps.  
4. **Stay restrained**: When adding new features, consider putting them in the hamburger menu first rather than adding main navigation tabs.

---

## Contributing

Issues and Pull Requests are welcome to improve this guide.  
Please ensure the content follows these principles:

- Objective, practical, and actionable.  
- Cite real cases with sources when referenced.  
- Keep the Markdown format clean.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

### How to Use This Guide

- **Designers**: Use this document as a design review checklist to check whether the product meets simplicity principles.  
- **Developers**: Refer to the navigation structure and launch logic to implement more reasonable page flows.  
- **Product Managers**: Optimize information architecture according to the content strategy to improve user satisfaction.

---

**Enjoy designing with simplicity.**

**Example Layout:**
