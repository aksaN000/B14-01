# AI Prompts — Placeholder Section (DevConf Hackathon 2026)

This documents the AI prompt(s) used to ideate and build the **Placeholder / AI Challenge**
section of the DevConf 2026 landing page, as required by the assignment.

## Section idea
A **"DevConf Hackathon 2026"** section presented as a **code terminal** — a developer-themed,
visually distinct block that reuses the site's existing colors (navy `#0d1b2a` + blue `#1d4ed8`)
so it fits the rest of the page while standing out from the card grids used elsewhere.

## Prompt used

> I'm building a landing page for a developer conference ("DevConf 2026"). The page already
> has a navbar, a dark hero, a "Meet the Speakers" card grid, and a 3-tier pricing section.
> The colors are: primary blue `#1d4ed8`, dark navy `#0d1b2a`, gray text `#575757`, light
> borders `#e5e7eb`, white background, Inter font.
>
> I need one brand-new section that fits this theme and visual style but feels unique compared
> to the card grids I already have. Suggest a creative idea, then build it with plain HTML and
> CSS only (no JS, no frameworks).
>
> Requirements:
> - Must be relevant to a developer conference.
> - Must reuse my existing color palette so it looks cohesive.
> - Should be responsive (stack on mobile).
> - No Lorem Ipsum — write real, on-theme copy.

## Why this section
- **Unique:** styled like a code editor / terminal (traffic-light dots, monospace, syntax colors,
  blinking cursor) — a look not used anywhere else on the page.
- **On-theme:** a 24-hour hackathon is a natural fit for a developer conference.
- **Cohesive:** uses the same navy/blue palette, rounded cards, shadows, and the shared
  `.register-btn` button style as the rest of the site.

## Follow-up tweaks I directed
- Keep the terminal text aligned in monospace and color-code prompt / comments / strings / numbers.
- Add three highlight stats (prize pool, duration, mentors) beside the terminal.
- Make the layout a 2-column grid that collapses to a single column under 768px.
