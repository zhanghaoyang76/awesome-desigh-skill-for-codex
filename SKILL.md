---
name: awesome-design-md-main
description: Use real website DESIGN.md references from VoltAgent awesome-design-md to guide UI and frontend design. Trigger when the user asks for an interface inspired by a named brand or product such as Stripe, Linear, Vercel, Apple, Figma, Supabase, Shopify, Notion, Airbnb, Spotify, Nike, Tesla, or when they ask to create, apply, compare, or follow DESIGN.md design-system guidance for a website, app, landing page, dashboard, or frontend experience.
---

# Awesome DESIGN.md

Use this skill to ground UI design work in the bundled design-md/ reference collection from VoltAgent's awesome-design-md repository.

## Workflow

1. Identify the target brand, product, or design language from the user's request.
2. Find the matching folder under design-md/.
3. Read only that folder's DESIGN.md or the smallest relevant local reference files.
4. Translate the reference into concrete interface decisions: layout, typography, spacing, color, motion, component treatment, density, and interaction states.
5. Adapt the design language to the user's actual product and audience. Do not copy trademarks, logos, proprietary text, or exact layouts unless the user explicitly owns or provided those assets.
6. For frontend implementation, combine this skill with the repo's existing design system and verify in browser screenshots when appropriate.

## Reference Lookup

Primary references live in:

`design-md/<brand-or-product>/DESIGN.md`

Useful examples include:

- `design-md/stripe/`
- `design-md/linear.app/`
- `design-md/vercel/`
- `design-md/apple/`
- `design-md/figma/`
- `design-md/supabase/`
- `design-md/shopify/`
- `design-md/notion/`
- `design-md/airbnb/`
- `design-md/spotify/`
- `design-md/nike/`
- `design-md/tesla/`

If the user names a brand that is not present, list nearby available references and choose the closest only when the user agrees or the intent is obvious.

## Output Expectations

When designing or implementing:

- Name the reference files used.
- Extract practical rules rather than pasting long sections.
- Preserve accessibility, responsive behavior, and product clarity over brand mimicry.
- Avoid one-note imitation. Blend the reference with the user's domain and existing app conventions.

When creating a DESIGN.md for a project:

- Use the selected reference as inspiration.
- Produce project-specific tokens, layout rules, components, interaction guidance, and anti-patterns.
- Keep the result actionable for coding agents.
