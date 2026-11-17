---
name: human-premium-ui
description: >-
  Design and build high-end, human-crafted, Figma-grade agency websites and web applications.
  Enforces the 60-30-10 color rule (Warm Paper White, Soft Cream, Ink Black, Premium Gold),
  strict 2-font editorial typography, conversational shop-owner copy without AI buzzwords,
  and deliberate human details (hand-drawn SVG accents, subtle card tilts, authentic textures).
---

# Human-Premium UI Design System & Engineering Guide

This skill governs the visual design, typography, color discipline, layout structure, and copywriting for premium client websites and industry demo apps. It guarantees that any website built or revamped looks human-made, authentic, and agency-crafted in Figma rather than generic AI-generated templates.

---

## 1. Core Visual Principles (Anti-AI Aesthetic)

AI-generated websites fail because they rely on predictable tropes: pure white `#FFFFFF` backgrounds, generic sans-serif fonts everywhere, purple/cyan gradients, floating 3D glassmorphism, perfectly symmetric 3-column cards, and repetitive corporate buzzwords.

**To make a site look human-crafted:**
1. **Warm Natural Canvas**: Never use pure clinical `#FFFFFF` as the main canvas. Use Warm Paper White (`#FDFBF7`) or Warm Alabaster with subtle tactile grain.
2. **Strict 2-Font System**: Pair a distinguished editorial serif (`Fraunces` or `Playfair Display`) with an ultra-clean, legible grotesque sans (`Manrope` or `Inter`).
3. **Strict 60-30-10 Color Discipline**: Use accent colors sparingly (max 10% of viewport). Never use accent color as a full section background.
4. **Asymmetric Editorial Layout**: Alternate between centered heroes, left-aligned section headers, split text/image compositions, and subtle card tilts (0.6 deg on desktop) to break repetitive grids.
5. **Authentic Human Detailing**: Hand-drawn SVG underlines, subtle grain textures, clean 1.5px warm borders, and consistent tactile buttons.

---

## 2. Locked 60-30-10 Color System

| Role | Color Name | HEX | Usage |
| :--- | :--- | :--- | :--- |
| **60% Primary Background** | Warm Paper White | `#FDFBF7` | Main page background, hero section, demo grid canvas |
| **60% Alt Background** | Soft Cream | `#F5EFE3` | Alternating sections, card surfaces, pill backgrounds |
| **30% Dark Foundation** | Ink Black | `#111111` | Primary headlines, primary buttons, dark CTA sections |
| **30% Dark Secondary** | Deep Charcoal | `#1C1C1C` | Footers, dark cards, high-contrast modal backdrops |
| **10% Accent ONLY** | Premium Gold | `#A67C00` | Section badges, italic headline words, key icons, underlines |
| **10% Accent Hover** | Dark Bronze Gold | `#8A6500` | Button and interactive link hover states |
| **Text Primary** | Near Black | `#141414` | High-contrast readable headings and body titles |
| **Text Secondary** | Warm Grey | `#5C5A54` | Descriptive paragraphs, subtitles, helper text |
| **Text Muted** | Light Neutral Grey | `#A8A8A8` | Text on dark containers and footer links |
| **Borders & Dividers** | Light Warm Grey | `#E8E0D0` | Card borders, dividers, subtle input outlines |
| **WhatsApp Action** | WhatsApp Green | `#25D366` | ONLY for direct WhatsApp quick-action widgets |

### Palette Enforcement Rules:
* Gold is for **ACCENT ONLY** (max 10% screen space). Never make a full gold section background.
* Never use purple, neon cyan, or pink gradients anywhere.
* Never use glassmorphism or shiny neon drop-shadows.

---

## 3. Strict 2-Font Typography Architecture

Never use a single font for both headings and body text. That is the number one signature of generic AI templates.

| Usage | Font Family | Weights | Role & Style |
| :--- | :--- | :--- | :--- |
| **Headlines / Display** | `Fraunces` (or `Playfair Display`) | 600, 700 Serif | Bold, architectural, editorial. Always italicize ONE emotional keyword per headline in Gold `#A67C00`. |
| **Body / Navigation / Cards / Buttons** | `Manrope` (or `Inter`) | 400, 500, 600, 700 Sans | Clean, modern, highly readable across mobile and desktop. |

### Standard Type Scale:
* **H1 Hero**: `56px` to `64px` on desktop, `36px` to `40px` on mobile. Line height: `1.08`. Letter spacing: `-0.025em`.
* **H2 Section Title**: `40px` to `48px` on desktop, `28px` to `32px` on mobile. Line height: `1.15`.
* **H3 Card Title**: `20px` to `24px`. Line height: `1.25`.
* **Body Text**: `15px` to `17px`. Line height: `1.65`. Color: `#5C5A54`.
* **Pill Badges**: `11px` to `12px`, ALL CAPS, tracking `0.14em`, weight `600`, Gold on Cream pill with `#E8E0D0` border.

---

## 4. Grounded Human Copywriting Rules

Eliminate all corporate AI jargon. Write like a thoughtful human speaking directly to a real business owner.

### Banned AI Buzzwords (NEVER USE):
`Unlock`, `Elevate`, `Seamless`, `Cutting-edge`, `Delve`, `Engineered`, `Showcases`, `Representation`, `Transform`, `Supercharge`, `In today's fast-paced digital world`, `Revolutionize`, `Empower`.

### Strict Punctuation Constraint:
* **Strictly NO em-dashes (`—` or `–`)**: Use commas, periods, or standard bullet dots (`•`) only.

### Tone & Voice:
* Conversational, direct, respectful, and grounded.
* Focus on real customer actions: booking a table, scheduling an appointment, getting a quote, calling on WhatsApp.
* Give clear timelines (e.g. "Ready in 3 to 5 days") instead of vague promises ("Instant results").

---

## 5. Ergonomics, Buttons & Layout Rules

### Buttons Standard:
* **Height**: Exactly `52px` (or `h-12` / `48px` for compact cards).
* **Border Radius**: Exactly `12px` (`rounded-xl`). Never sharp 0px squares, never 9999px bubble pills for main CTAs.
* **Primary Action**: Ink Black `#111111` background, white text, right arrow icon (`ArrowRight`) with hover translate animation (`group-hover:translate-x-1`).
* **Secondary Action**: Soft Cream `#F5EFE3` background, 1px border `#E8E0D0`, `#141414` text.
* **Accent Gold Button**: Reserved for the final page CTA ("Request A Custom Website").

### Section & Spacing Structure:
* **Section Vertical Whitespace**: `80px` to `112px` padding on desktop, `56px` to `72px` on mobile. Give content breathing room.
* **Grid Gaps**: `24px` to `32px` (`gap-6` to `gap-8`).
* **Card Borders**: `1px` or `1.5px` border in `#E8E0D0`, hover border in `#A67C00`.
* **Card Tilt**: Add subtle asymmetric tilt (`rotate-[0.6deg]` on hover `rotate-0`) to one or alternate cards on desktop (`lg:rotate-[0.6deg]`) to break the mechanical grid.

---

## 6. Industry Adaptation Matrix

When building demo sites or category applications, adapt the accent color and feature tags inside the cards/sections while keeping the main frame in the warm 60-30-10 palette:

| Industry | Accent Token | Accent HEX | Highlight Feature | CTA Text |
| :--- | :--- | :--- | :--- | :--- |
| **Restaurant & Dining** | Warm Gold | `#A67C00` | QR Menu, Online Table Booking | `View Restaurant Demo →` |
| **Salon & Spa** | Soft Warm Taupe | `#C9A68C` | Service Rate Card, Stylist Booking | `View Salon Demo →` |
| **Construction & Engineering** | Safety Amber | `#E8A800` | Past Projects, Scope Estimator | `View Construction Demo →` |
| **Luxury Real Estate** | Architectural Charcoal | `#1C1C1C` / `#A67C00` | Floor Plan Switcher, Visit Booking | `View Real Estate Demo →` |
| **E-Commerce & Retail** | Deep Olive / Emerald | `#1B4332` | Product Drawer, Instant Checkout | `View Store Demo →` |

---

## 7. Implementation Checklist for Any Site

- [ ] Canvas is set to `#FDFBF7` Warm Paper, not `#FFFFFF`.
- [ ] Fonts imported: `Fraunces` for headings, `Manrope` for body text.
- [ ] Headlines feature italic serif gold emotional keyword.
- [ ] Underline has hand-drawn SVG treatment under key word.
- [ ] Brand logo is clean Black + Gold without purple/blue gradients or white pill boxes.
- [ ] Zero AI buzzwords in copy.
- [ ] Strictly zero em-dashes (`—` or `–`).
- [ ] All primary buttons have 12px radius, 52px height, and right arrow icon.
- [ ] Floating WhatsApp concierge configured with `#25D366`.
- [ ] Mobile view tested with no horizontal scroll and clean full-width CTAs.
