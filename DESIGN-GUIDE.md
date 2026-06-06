# ScholrBee Design Guide (Tailwind CSS v4)

This guide explains how to use the "Academic-Chic" design tokens defined in `DESIGN.md` using Tailwind CSS utility classes.

## Colors

Use these semantic tokens for backgrounds, text, and borders.

| Semantic Name | CSS Token | Tailwind Class Examples | Hex Value |
| :--- | :--- | :--- | :--- |
| **Deep Ivy (Primary)** | `--color-primary` | `bg-primary`, `text-primary`, `border-primary` | `#012d1d` |
| **Lavender Haze (Secondary)** | `--color-secondary` | `bg-secondary`, `text-secondary` | `#4f55ae` |
| **Solar Flare (Accent)** | `--color-on-tertiary-container` | `bg-on-tertiary-container`, `text-on-tertiary-container` | `#d89b00` |
| **Surface** | `--color-surface` | `bg-surface`, `bg-surface-container` | `#f7f9ff` |
| **On Surface** | `--color-on-surface` | `text-on-surface`, `text-on-surface-variant` | `#181c20` |

## Typography

Apply these custom utilities for consistent editorial typography. These are defined as `@utility` classes in `global.css`.

- **Headline XL:** `text-headline-xl`  
  *Fraunces, 48px, Bold, -0.02em tracking*
- **Headline LG:** `text-headline-lg`  
  *Fraunces, 32px (Desktop) / 28px (Mobile), Semi-bold*
- **Headline MD:** `text-headline-md`  
  *Fraunces, 24px, Medium*
- **Body LG:** `text-body-lg`  
  *Inter, 18px, Regular*
- **Body MD:** `text-body-md`  
  *Inter, 16px, Regular*
- **Body SM:** `text-body-sm`  
  *Inter, 14px, Regular*
- **Label MD:** `text-label-md`  
  *Inter, 12px, Semi-bold, Uppercase tracking*

## Spacing & Layout

The system uses an **8px grid**.

- **Unit:** `p-unit`, `m-unit`, `gap-unit` (8px)
- **Gutter:** `p-gutter`, `gap-gutter` (24px)
- **Margin Desktop:** `px-margin-desktop` (48px)
- **Max Width:** `max-w-max-layout` (1280px)

## Shapes & Depth

- **Pill Buttons:** `rounded-full`
- **Cards:** `rounded-lg`
- **Subtle Shadow:** `shadow-subtle` (Uses a Deep Ivy tinted shadow)

## Implementation Examples

### A Scholarly Card
```html
<div class="bg-white rounded-lg border border-on-surface/5 shadow-subtle p-gutter max-w-md">
  <h2 class="text-headline-md text-primary mb-unit">Modern Scholarly Journal</h2>
  <p class="text-body-md text-on-surface-variant mb-gutter">
    The fusion of traditional scholarly prestige and modern AI-driven efficiency.
  </p>
  <button class="bg-primary text-white rounded-full px-6 py-2 text-label-md hover:opacity-90 transition-opacity">
    Explore More
  </button>
</div>
```

### AI Interface Panel (Glassmorphism)
```html
<div class="bg-secondary-container/80 backdrop-blur-md rounded-xl p-gutter border border-white/20">
  <span class="text-label-md text-on-secondary-container uppercase tracking-wider">AI Thinking...</span>
  <p class="text-body-lg text-secondary">Analyzing your latest research notes.</p>
</div>
```
