---
name: Academic Clarity
colors:
  surface: '#fbf8ff'
  surface-dim: '#d7d8f5'
  surface-bright: '#fbf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f2ff'
  surface-container: '#edecff'
  surface-container-high: '#e7e6ff'
  surface-container-highest: '#e0e0fe'
  on-surface: '#181a2f'
  on-surface-variant: '#484553'
  inverse-surface: '#2d2f45'
  inverse-on-surface: '#f1efff'
  outline: '#787585'
  outline-variant: '#c9c4d6'
  surface-tint: '#5d49c7'
  primary: '#5a47c4'
  on-primary: '#ffffff'
  primary-container: '#7461df'
  on-primary-container: '#fffbff'
  inverse-primary: '#c8bfff'
  secondary: '#5e5d6d'
  on-secondary: '#ffffff'
  secondary-container: '#e4e0f4'
  on-secondary-container: '#646373'
  tertiary: '#006949'
  on-tertiary: '#ffffff'
  tertiary-container: '#00855d'
  on-tertiary-container: '#f5fff7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5deff'
  primary-fixed-dim: '#c8bfff'
  on-primary-fixed: '#190064'
  on-primary-fixed-variant: '#452eae'
  secondary-fixed: '#e4e0f4'
  secondary-fixed-dim: '#c8c4d7'
  on-secondary-fixed: '#1b1a28'
  on-secondary-fixed-variant: '#464555'
  tertiary-fixed: '#7df9c2'
  tertiary-fixed-dim: '#5edda8'
  on-tertiary-fixed: '#002114'
  on-tertiary-fixed-variant: '#005137'
  background: '#fbf8ff'
  on-background: '#181a2f'
  surface-variant: '#e0e0fe'
typography:
  display:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.03em
  display-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0em
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.03em
  code:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-lg: 1.5rem
  margin: 1rem
  margin-md: 1.5rem
  margin-lg: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.5rem
---

## Brand & Style

This design system balances the structured utility of professional issue trackers with the expressive modularity of modern digital workspaces. Tailored for university freshmen navigating academic transitions, the visual language avoids both institutional sterility and juvenile gamification. 

The aesthetic is clean, warm, and highly focused:
- **Calm Productivity:** Generous whitespace, subdued visual noise, and intentional color accents prevent cognitive overload during intense study blocks and assignment crunches.
- **Craft & Tactility:** Gentle corner radii, soft borders, and floating structural cards create an inviting, physical workspace feel on screen.
- **Information Hierarchy:** Strong typographic contrasts and systematic metadata chips ensure schedules, due dates, course tags, and project boards remain immediately scannable.

## Colors

The palette establishes an airy, high-clarity environment driven by purposeful accents against neutral canvas tiers.

### Functional Roles
- **Canvas (`#F7F8FC`):** The foundational application backdrop. Keeps contrast gentle over prolonged study sessions.
- **Surface (`#FFFFFF`):** High-priority workspace cards, active modals, and content containers.
- **Primary Accent (`#7C6AE8`):** Denotes primary actions, active navigation states, selected views, and focused interactions.
- **Primary Subtle / Light (`#EEEAFE`):** Used for hover fills, focused cell backgrounds, selection badges, and soft highlights.
- **Text & Foreground Primary (`#202238`):** High-contrast, slate-indigo black reserved for primary headings, table items, and readable prose.
- **Text & Foreground Secondary (`#8589A6`):** Supporting metadata, shortcuts, relative timestamps, and placeholder labels.
- **Border Subtle (`#E5E7F0`):** Soft dividing lines and card perimeters ensuring separation without harsh visual friction.

### Semantic Accents
- **Success (`#34B987`):** Completed tasks, GPA trackers, and submission verifications.
- **Warning (`#F5B544`):** Approaching deadlines, exam alerts, and tentative events.
- **Danger (`#F16D83`):** Overdue assignments, critical calendar conflicts, and destructive actions.

## Typography

The single-family implementation of Inter anchors the system in utilitarian clarity, leaning on weight transitions, tightened letter-spacing, and rhythmic vertical baselines.

- **Headlines:** Feature subtle negative tracking to yield an authoritative yet modern editorial feel inspired by Notion's document titles and Linear's project views.
- **Labels & Badges:** `label-sm` utilizes uppercase rendering with `0.03em` tracking for course acronyms (e.g., `CS 101`, `MATH 240`) and status tags.
- **Numbers & Metadata:** Digits in schedule grids and countdown timers should be configured with `font-feature-settings: 'tnum' 1` (tabular figures) to guarantee vertical alignment in lists and timelines.

## Layout & Spacing

The application implements a fluid multi-pane desktop architecture that transitions into a stacked, bottom-nav-anchored layout on mobile viewports.

### Breakpoints & Layout Model
- **Desktop (>= 1200px):** Permanent collapsible navigation rail (240px width), fluid main stage (max-width bounded at 1440px), and optional contextual inspector drawer (320px). Grid utilizes 12 columns with 24px (`gutter-lg`) spacing and 32px (`margin-lg`) canvas padding.
- **Tablet (768px - 1199px):** Narrow sidebar (collapsed icon-only at 64px or modal off-canvas). 8-column layout with 16px (`gutter`) spacing and 24px (`margin-md`) padding.
- **Mobile (< 768px):** Single-column vertical stream. Top app-bar accompanied by a persistent fixed bottom dock. 4-column layout with 12px gutters and 16px (`margin`) outer edge inset.

### Structural Flow
- Internal card padding scales between `space-lg` (16px) for compact dashboard widgets and `space-xl` (24px) for assignment detail views.
- Dense data rows (e.g., syllabus items, task lists) use `space-sm` (8px) vertical gaps to maintain high information density without visual crowding.

## Elevation & Depth

Visual hierarchy relies on crisp borders coupled with ambient, cool-toned drop shadows that prevent muddy overlaps on the `#F7F8FC` canvas.

### Surface Tiers
- **Tier 0 (Background):** `#F7F8FC`. Non-interactive backdrop.
- **Tier 1 (Resting Cards & Workspaces):** `#FFFFFF`. Outlined by a continuous 1px `#E5E7F0` border. Shadow: `0px 1px 3px rgba(32, 34, 56, 0.04), 0px 4px 12px rgba(32, 34, 56, 0.03)`.
- **Tier 2 (Hovered Cards & Interactive Controls):** `#FFFFFF`. Outline remains `#E5E7F0`. Shadow: `0px 4px 8px rgba(124, 106, 232, 0.06), 0px 8px 24px rgba(32, 34, 56, 0.06)`.
- **Tier 3 (Popovers, Dropdowns, Command Menus):** `#FFFFFF`. Outline: 1px `#E2E4ED`. Shadow: `0px 12px 32px rgba(32, 34, 56, 0.12), 0px 2px 6px rgba(32, 34, 56, 0.04)`.
- **Tier 4 (Modals & Overlays):** `#FFFFFF` paired with an ambient backdrop overlay (`rgba(32, 34, 56, 0.40)` with `backdrop-filter: blur(4px)`). Shadow: `0px 20px 48px rgba(32, 34, 56, 0.16)`.

## Shapes

The design system embraces an approachable, rounded-modern silhouette calibrated specifically across card dimensions:
- **Small Controls (Buttons, Inputs, Badges, Chips):** `8px` (`0.5rem`). Keeps interaction touch targets distinct and structured.
- **Medium Panels & Group Containers:** `14px` (`0.875rem`). Applied to inner cards, timetable blocks, and nested list containers.
- **Large Cards & Modals:** `18px` to `20px` (`1.125rem` - `1.25rem`). Applied to main dashboard cards, board columns, and focus widgets.
- **Avatars & Quick Pills:** Fully rounded / circular (`9999px`).

## Components

### Buttons
- **Primary:** Solid `#7C6AE8` background, `#FFFFFF` text, 8px border radius, height 38px. Hover shifts to `#6B57E0` with a subtle elevation lift; active scales slightly to `0.98`.
- **Secondary:** `#EEEAFE` background with `#7C6AE8` text. Hover transitions to `#E1DCFD`.
- **Ghost / Outline:** Transparent fill, 1px `#E5E7F0` border, `#202238` text. Hover adds `#F7F8FC` surface.
- **Icon Actions:** 32x32px square with 8px radius, text color `#8589A6`, shifting to `#202238` and `#EEEAFE` background on hover.

### Cards & Panels
- Resting border of 1px solid `#E5E7F0`, surface fill `#FFFFFF`, and corner radius from 14px to 20px depending on scale.
- Interactive cards (Kanban tasks, upcoming lecture cards) transition border color to `#D4CEF8` on mouse enter.

### Chips & Course Badges
- Compact pill height (24px), font `label-sm`, padding `0 10px`, corner radius 6px.
- Tinted backgrounds with high-contrast text:
  - Subject Tag: `#EEEAFE` background with `#7C6AE8` text.
  - Due Soon: `#FEF6E7` background with `#B87B19` text.
  - Complete: `#E8F8F1` background with `#22805D` text.

### Inputs & Search Bars
- Background `#FFFFFF`, 1px solid `#E5E7F0`, height 40px, font `body-md`, radius 8px.
- Focus state: border color `#7C6AE8`, accompanied by an outer glow `0 0 0 3px rgba(124, 106, 232, 0.15)`.
- Global command bar (`Cmd + K`): Minimal floating search with instant key shortcut indicators (`KBD` tag with `#F7F8FC` fill and `#E5E7F0` outline).

### Checkboxes & Progress Indicators
- Checkbox: 18x18px, 5px radius, 1.5px border `#8589A6`. Checked state fills `#34B987` with a white checkmark icon.
- Linear Progress Bars: 6px track height, `#EEEAFE` background, `#7C6AE8` progress fill with rounded pill caps.

### List & Table Views
- Notion-inspired dense table rows with hover highlighting (`#F7F8FC`), clean 1px row separators, and integrated quick-action icons that appear on row hover.

### Specialized Academic Components
- **Lecture Block (Calendar):** Color-coded left spine (4px accent bar), course title in `headline-sm`, room number in `body-sm` (`#8589A6`), and subtle badge for upcoming tests.
- **Syllabus Progress Ring:** Circular SVG gauge showcasing completed module weight vs. pending final grading.