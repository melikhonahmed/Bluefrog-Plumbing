# bluefrog Plumbing + Drain Design System

This document defines the visual direction, UI structure, and experience principles for the bluefrog Plumbing + Drain marketing website.

## Brand Direction

The brand should feel:
- trustworthy
- prompt and local
- clean and premium
- technically competent without feeling cold

The visual language combines polished corporate clarity with approachable home-service hospitality. The goal is to reduce anxiety for homeowners dealing with emergency plumbing issues while reinforcing speed, quality, and professionalism.

---

## Core Brand Colors

```css
--brand-blue: #0072ce;
--brand-blue-dark: #0059a4;
--brand-green: #78be20;
--brand-green-dark: #006e2d;
--surface: #f8fafd;
--surface-card: #ffffff;
--on-surface: #0b1c30;
--on-surface-variant: #4d5b6e;
--neutral-100: #f1f5f9;
--neutral-200: #e2e8f0;
--neutral-300: #cbd5e1;
```

### Usage
- Blue = trust, clarity, professionalism
- Green = service response, freshness, action
- White = cleanliness and premium simplicity
- Dark navy = authority and confidence

---

## Typography

Primary type: `Plus Jakarta Sans`

### Type Scale
- Hero heading: 48–58px, bold, tight tracking
- Section headings: 32–44px, bold
- Card titles: 18–24px, semibold
- Body text: 16–18px
- Small labels: 11–14px, uppercase tracking

---

## Layout System

The site uses a responsive, content-first grid with generous whitespace and premium breathing room.

### Breakpoints
- Mobile: under 768px
- Tablet: 768px–1024px
- Desktop: 1024px and above

### Structure
- Container max width: 1280px
- Large section spacing: 64–96px
- Card padding: 20–32px
- Radius: 16px–32px depending on component

---

## Visual Style

### Surfaces
- Page background: soft cool gray / white
- Cards: white with low-contrast border
- Floating header: white with blur, visible border, soft shadow

### Elevation
- Minimal but premium shadowing
- Soft blue glow accents around CTAs and key elements
- Hover states gently lift cards with subtle motion

---

## Buttons

### Primary CTA
- Background: brand green
- Text: white
- Radius: pill / soft rounded corners
- Purpose: emergency call, dispatch, booking

### Secondary CTA
- Background: white
- Border: light gray
- Text: slate dark
- Purpose: non-urgent phone or inquiry actions

### Motion
- Hover lift: slight Y motion
- Button shimmer on key CTAs
- Smooth transitions around 200–350ms

---

## Cards and Content Modules

### Service Cards
- White background
- Rounded corners
- Border with subtle shadow
- Strong icon + headline + short supporting paragraph

### Review Cards
- White or neutral surface
- Five-star icon treatment
- Trust badge and local area reference

### Membership / Offer Cards
- Dark navy background with green accent
- High-contrast CTA region
- Reinforces premium protection and peace of mind

---

## Form Styling

Inputs should be:
- clean white fields
- simple borders and gentle hover states
- clearly visible focus ring on active selection
- easy for mobile users with large touch targets

---

## Motion Principles

The motion system should remain subtle, modern, and premium.

Recommended patterns:
- fade-up entrance reveal on sections
- soft floating background accents
- slow hover tilts on media cards
- quick transitions on interactions
- reduced-motion support for accessibility

---

## Target Experience

The website should make a visitor feel:
- this company is responsive and local
- the team is professional and clean
- emergency help can be obtained quickly
- pricing and service are transparent and reassuring

---

## Deployment Notes

This project is built as a lightweight static website intended for fast, low-maintenance deployment on Vercel or similar hosting providers.

It prioritizes:
- fast loading
- simple setup
- clean maintenance
- no framework dependency required