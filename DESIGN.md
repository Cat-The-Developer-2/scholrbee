---
name: StudyOS
colors:
  surface: "#f7f9ff"
  surface-dim: "#d7dadf"
  surface-bright: "#f7f9ff"
  surface-container-lowest: "#ffffff"
  surface-container-low: "#f1f4f9"
  surface-container: "#ebeef3"
  surface-container-high: "#e5e8ee"
  surface-container-highest: "#e0e3e8"
  on-surface: "#181c20"
  on-surface-variant: "#414844"
  inverse-surface: "#2d3135"
  inverse-on-surface: "#eef1f6"
  outline: "#717973"
  outline-variant: "#c1c8c2"
  surface-tint: "#3f6653"
  primary: "#012d1d"
  on-primary: "#ffffff"
  primary-container: "#1b4332"
  on-primary-container: "#86af99"
  inverse-primary: "#a5d0b9"
  secondary: "#4f55ae"
  on-secondary: "#ffffff"
  secondary-container: "#9aa0ff"
  on-secondary-container: "#2d328b"
  tertiary: "#342300"
  on-tertiary: "#ffffff"
  tertiary-container: "#503700"
  on-tertiary-container: "#d89b00"
  error: "#ba1a1a"
  on-error: "#ffffff"
  error-container: "#ffdad6"
  on-error-container: "#93000a"
  primary-fixed: "#c1ecd4"
  primary-fixed-dim: "#a5d0b9"
  on-primary-fixed: "#002114"
  on-primary-fixed-variant: "#274e3d"
  secondary-fixed: "#e0e0ff"
  secondary-fixed-dim: "#bfc2ff"
  on-secondary-fixed: "#02026b"
  on-secondary-fixed-variant: "#373c95"
  tertiary-fixed: "#ffdea9"
  tertiary-fixed-dim: "#ffba27"
  on-tertiary-fixed: "#271900"
  on-tertiary-fixed-variant: "#5e4100"
  background: "#f7f9ff"
  on-background: "#181c20"
  surface-variant: "#e0e3e8"
typography:
  headline-xl:
    fontFamily: Fraunces
    fontSize: 48px
    fontWeight: "700"
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Fraunces
    fontSize: 32px
    fontWeight: "600"
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Fraunces
    fontSize: 28px
    fontWeight: "600"
    lineHeight: 34px
  headline-md:
    fontFamily: Fraunces
    fontSize: 24px
    fontWeight: "500"
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: "400"
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: "400"
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: "400"
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: "600"
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  max-width: 1280px
---

## Brand & Style

The design system is built on the philosophy of "Academic-Chic," a fusion of traditional scholarly prestige and modern AI-driven efficiency. It targets high-achieving students and lifelong learners who value a focused, intentional environment. The emotional response should be one of "Empathic Focus"—reducing cognitive load through soft surfaces while maintaining the intellectual rigor of a premium leather-bound journal.

The style is a hybrid of **Minimalism** and **Tactile Modernism**. It leverages generous whitespace and high-end editorial typography to mimic the feeling of high-quality stationery. Elements are structured but not rigid, using soft shadows and "paper-like" layering to create a sense of calm and organization.

## Colors

This design system utilizes a palette inspired by classical academia and natural focus-enhancing environments.

- **Deep Ivy (Primary):** Used for primary actions, branding, and structural headers. It conveys stability and growth.
- **Lavender Haze (Secondary):** Used for highlighting AI-assisted features, tags, and secondary interactions. It adds a layer of modern empathy.
- **Solar Flare (Accent):** A high-visibility accent used sparingly for notifications, streaks, and "Aha!" moments.
- **Paper & Ink (Neutrals):** The foundation is a soft off-white surface (#F8F9FA) that reduces eye strain compared to pure white, paired with Ink (#212529) for maximum legibility.

## Typography

The typography system balances the literary authority of **Fraunces** with the functional clarity of **Inter**.

- **Fraunces** is the display voice. It should be used for all headings and significant narrative moments. Its soft serifs and variable weights provide a human, "hand-written" quality to the digital interface.
- **Inter** is the workhorse. It handles all UI labels, body text, and dense information. It ensures the AI-generated content remains highly readable and accessible.
- **Scale:** On mobile devices, headline sizes should reduce by 15-20% to maintain visual balance and prevent awkward line breaks.

## Layout & Spacing

The design system employs a **Fixed Grid** philosophy for desktop to maintain the "stationery" aesthetic, centering content within a refined 1280px container.

- **8px Grid System:** All spacing between elements must be a multiple of 8px. This creates a predictable rhythm and mathematical harmony.
- **Desktop:** 12-column grid with 24px gutters. Use wide margins (48px+) to create "breathable" whitespace that mimics the margins of a notebook.
- **Tablet/Mobile:** Content reflows to a 4-column grid. Margins shrink to 16px to maximize real estate while maintaining a clear safety zone.
- **Vertical Rhythm:** Use 32px or 48px spacing between major sections to emphasize the "clean desk" feel.

## Elevation & Depth

Depth is created through **Tonal Layers** rather than heavy shadows, maintaining the flat, high-end paper aesthetic.

- **Surface Levels:** The background is `Surface Paper`. Primary content containers use a pure white (#FFFFFF) to slightly "pop" against the paper background.
- **Shadows:** When necessary, use extremely subtle, diffused shadows (Blur: 20px, Opacity: 4%, Color: Deep Ivy). This makes elements feel like they are resting lightly on a desk rather than floating in space.
- **Glassmorphism:** Reserved specifically for AI-interfacing panels or floating action bars. Use a light backdrop blur (12px) with 80% opacity Lavender Haze to denote a "thinking" state.

## Shapes

The shape language is friendly yet structured.

- **Cards:** Use a standard 16px (`rounded-lg`) corner radius. This provides a soft, modern feel that contrasts beautifully with the sharp serifs of the display typography.
- **Buttons:** Always use **Pill-shaped** (full radius) buttons. This differentiates interactive elements from informational containers.
- **Micro-elements:** Chips and tags should also follow the pill-shape convention to maintain consistency in the interaction language.

## Components

- **Buttons:** Primary buttons are filled with `Deep Ivy` and white text. Secondary buttons use a `Lavender Haze` tint with `Deep Ivy` text. All buttons feature a 300ms transition on hover, deepening the color slightly.
- **Inputs:** Ghost-style inputs are preferred. They feature no fill, a 1px `Ink` border at 10% opacity, and a subtle bottom border that darkens on focus. This mimics the lines of a notebook.
- **Cards:** Cards should have a 1px solid stroke in `Ink` at 5% opacity to define their boundaries without adding visual weight.
- **Chips:** Small, pill-shaped indicators using `Lavender Haze` for "AI-Generated" labels and `Solar Flare` for "Urgent" or "High Priority" tasks.
- **Lists:** Use generous 16px vertical padding between list items. Hover states should apply a soft `Surface Paper` background highlight.
- **Checkboxes:** Custom square icons with 4px rounded corners, filling with `Deep Ivy` and a white checkmark when active.
