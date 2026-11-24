---
name: "Forever Scrapbook"
description: "A romantic, retro-browser scrapbook design system pairing deep navy framing, soft sky-blue windows, and warm cream paper textures with expressive serif and humanist typography."
---

## Overview

Forever Scrapbook is a nostalgic, heartfelt web design system crafted for interactive anniversary keepsakes, digital love letters, and personal memory galleries. It blends the charm of early-2000s retro browser windows with tactile paper scrapbooking—polaroids, torn note cards, wax seals, and dashed-border pill buttons.

The visual language balances playfulness and sincerity: deep navy grounds the experience with emotional warmth and contrast, while soft sky-blue windows and warm cream paper surfaces keep every memory light, intimate, and inviting.

## Colors

The palette is anchored by a deep **Midnight Navy** primary (`#0A2457` / `#253B6E` container) paired with a soft **Sky Blue** secondary (`#BCDAFF` container) and **Warm Cream** paper surfaces (`#FAF8FE` / `#FFFFFF`).

- **Primary:** Deep navy used for outer scrapbook framing, wax-sealed envelopes, primary action pills, and high-contrast headings.
- **Secondary:** Soft sky blue used for retro browser window chrome, gingham accents, and gentle highlight containers.
- **Tertiary:** Warm caramel/parchment accent used sparingly for vintage tape, pushpins, and warm keepsake details.

```yaml
colors:
  light:
    primary: "#0A2457"
    on-primary: "#FFFFFF"
    primary-container: "#253B6E"
    on-primary-container: "#DAE2FF"
    secondary: "#436181"
    on-secondary: "#FFFFFF"
    secondary-container: "#BCDAFF"
    on-secondary-container: "#113250"
    tertiary: "#3C2100"
    on-tertiary: "#FFFFFF"
    tertiary-container: "#5A3400"
    on-tertiary-container: "#FFDCBC"
    error: "#BA1A1A"
    on-error: "#FFFFFF"
    error-container: "#FFDAD6"
    on-error-container: "#93000A"
    background: "#FAF8FE"
    on-background: "#1B1B1F"
    surface: "#FAF8FE"
    surface-dim: "#DBD9DE"
    surface-bright: "#FAF8FE"
    surface-container-lowest: "#FFFFFF"
    surface-container-low: "#F5F3F8"
    surface-container: "#EFEDF2"
    surface-container-high: "#E9E7EC"
    surface-container-highest: "#E3E2E7"
    on-surface: "#1B1B1F"
    surface-variant: "#E1E2ED"
    on-surface-variant: "#44464F"
    outline: "#757780"
    outline-variant: "#C5C6D1"
    inverse-surface: "#303034"
    inverse-on-surface: "#F2F0F5"
    inverse-primary: "#B1C5FF"
    shadow: "#000000"
    scrim: "#000000"
  dark:
    primary: "#B1C5FF"
    on-primary: "#172E61"
    primary-container: "#253B6E"
    on-primary-container: "#DAE2FF"
    secondary: "#ABC9EE"
    on-secondary: "#113250"
    secondary-container: "#2D4B6A"
    on-secondary-container: "#D0E4FF"
    tertiary: "#F6BB7C"
    on-tertiary: "#492900"
    tertiary-container: "#5A3400"
    on-tertiary-container: "#FFDCBC"
    error: "#FFB4AB"
    on-error: "#690005"
    error-container: "#93000A"
    on-error-container: "#FFDAD6"
    background: "#121317"
    on-background: "#E3E2E7"
    surface: "#121317"
    surface-dim: "#121317"
    surface-bright: "#38393D"
    surface-container-lowest: "#0D0E12"
    surface-container-low: "#1B1B1F"
    surface-container: "#1F1F23"
    surface-container-high: "#292A2E"
    surface-container-highest: "#343438"
    on-surface: "#E3E2E7"
    surface-variant: "#44464F"
    on-surface-variant: "#C5C6D1"
    outline: "#8F909A"
    outline-variant: "#44464F"
    inverse-surface: "#E3E2E7"
    inverse-on-surface: "#303034"
    inverse-primary: "#485D92"
    shadow: "#000000"
    scrim: "#000000"
```

## Typography

Forever Scrapbook pairs **Cormorant Infant** for romantic, editorial display titles and italic script accents with **PT Sans** for crisp, friendly UI controls and heartfelt letter copy, and **PT Mono** for retro browser URL bars and date stamps.

```yaml
typography:
  display-lg:
    fontFamily: "Cormorant Infant"
    fontSize: 52px
    fontWeight: 700
    lineHeight: 58px
    letterSpacing: -0.5px
  display-lg-mobile:
    fontFamily: "Cormorant Infant"
    fontSize: 32px
    fontWeight: 700
    lineHeight: 38px
    letterSpacing: -0.25px
  display-md:
    fontFamily: "Cormorant Infant"
    fontSize: 40px
    fontWeight: 600
    lineHeight: 46px
    letterSpacing: -0.25px
  display-md-mobile:
    fontFamily: "Cormorant Infant"
    fontSize: 28px
    fontWeight: 600
    lineHeight: 34px
    letterSpacing: 0px
  headline-lg:
    fontFamily: "Cormorant Infant"
    fontSize: 34px
    fontWeight: 700
    lineHeight: 40px
    letterSpacing: 0px
  headline-lg-mobile:
    fontFamily: "Cormorant Infant"
    fontSize: 24px
    fontWeight: 700
    lineHeight: 30px
    letterSpacing: 0px
  headline-md:
    fontFamily: "Cormorant Infant"
    fontSize: 24px
    fontWeight: 600
    lineHeight: 30px
    letterSpacing: 0px
  title-lg:
    fontFamily: "PT Sans"
    fontSize: 18px
    fontWeight: 700
    lineHeight: 24px
    letterSpacing: 0.5px
  body-lg:
    fontFamily: "PT Sans"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 24px
    letterSpacing: 0px
  body-md:
    fontFamily: "PT Sans"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 20px
    letterSpacing: 0px
  label-lg:
    fontFamily: "PT Sans"
    fontSize: 14px
    fontWeight: 700
    lineHeight: 18px
    letterSpacing: 1px
  label-sm:
    fontFamily: "PT Mono"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 16px
    letterSpacing: 0.5px
```

## Layout & Spacing

The layout centers a **Retro Browser Window** (`max-w-4xl`) on a full-bleed deep navy or warm cream canvas, giving each screen a focused, framed stage with generous breathing room around decorative stickers and polaroids. Spacing follows a strict 4px/8px rhythm.

```yaml
spacing:
  gutter-xs: 4px
  gutter-sm: 8px
  gutter-md: 16px
  gutter-lg: 24px
  gutter-xl: 32px
  section: 48px
  page-margin: 32px
```

## Elevation & Depth

Depth is achieved through **Tactile Paper Layering** and **Crisp Retro Outlines** rather than heavy blurred drop shadows:
- Retro browser windows use crisp `2px` navy borders (`border-light-primary-container`) with subtle offset solid shadows or clean tonal separation.
- Polaroids and torn paper notes sit on `surface-container-lowest` (`#FFFFFF`) with soft ambient shadows (`shadow-sm` / `shadow-md`) and gentle `1deg–4deg` rotations to feel hand-placed.

## Shapes

The shape language mixes **structured retro window frames** (`rounded-xl` / `rounded-lg`) with **soft pill-shaped navigation buttons** (`rounded-full`) featuring delicate inner dashed borders, and **crisp polaroid photo frames** (`rounded-sm`).

```yaml
rounded:
  sm: 4px
  DEFAULT: 8px
  md: 12px
  lg: 16px
  xl: 24px
  full: 9999px
```

## Motion & Micro-interaction

Motion feels tactile and playful—like opening a keepsake box or flipping a polaroid. Interactive stickers and pill buttons respond briskly on hover with a gentle lift or tilt, while view transitions glide smoothly.

```yaml
motion:
  state-change:
    duration: 150ms
    delay: 0ms
    timingFunction: ease-out
  surface-enter:
    duration: 300ms
    delay: 0ms
    timingFunction: cubic-bezier(0.2, 0, 0, 1)
  surface-exit:
    duration: 200ms
    delay: 0ms
    timingFunction: cubic-bezier(0.3, 0, 1, 1)
```

## Voice & Content Strategy

- **Tone of voice:** Warm, affectionate, and personal—never corporate or generic. Copy speaks directly to a partner ("Tap 'Start' to open my surprise", "Click the disc to play our song", "My letter for you").
- **Capitalisation:** Uppercase tracking on compact pill buttons (`START`, `NEXT`, `BACK`, `TAP TO OPEN`) and section badges (`OUR MEMORIES`, `WHY I LOVE YOU`); sentence case for heartfelt letter paragraphs and reason lists.
- **Button and action labels:** Short, inviting action cues (`START`, `NEXT`, `BACK`, `GIFT FOR YOU`, `MY LETTER TO YOU`, `MEMORIES`).

## Components

Component implementations live as individual HTML sticker sheet files in
`components/`. Each file contains the canonical, styled HTML components with
`<!-- COMPONENT: name -->` comment markers. Read each file before use.

- **Button** → `@components/button.html`: `button-primary`, `button-icon`, `button-with-icon`
- **Card** → `@components/card.html`: `card-elevated`, `card-action`, `card-interactive`, `card-interactive-2`
- **Typography** → `@components/typography.html`: `typography-display`, `typography-body`, `typography-label`
