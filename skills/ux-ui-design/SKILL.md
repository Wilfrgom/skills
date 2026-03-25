---
name: ux-ui-design
description: >
  Design high-quality UX/UI wireframes, mockups, design systems, user flows,
    and interactive prototypes as HTML/CSS artifacts. Use this skill when the
      user wants to design a screen, app, or website interface; create a component
        library or design system; map a user journey or task flow; conduct a UX
          audit of an existing interface; define information architecture; or produce
            annotated wireframes. Trigger whenever the user says "design", "mockup",
              "wireframe", "user flow", "UI", "prototype", "component", or "design system"
                in a product, app, or web context. Also trigger for UX reviews, heuristic
                  evaluations, or accessibility audits of existing interfaces.
                  ---

                  # UX/UI Design

                  A skill for designing interfaces that are both beautiful and easy to use.

                  ## Before designing, clarify

                  - **User and goal**: Who is this for? What are they trying to accomplish?
                  - **Primary action**: What is the one thing this screen should make easy?
                  - **Platform**: Web (responsive?), iOS, Android, desktop app?
                  - **Fidelity**: Wireframe (structure only) or high-fidelity mockup (full visual)?
                  - **Design system**: Are there existing tokens, components, or brand guidelines?
                  - **Constraints**: Accessibility requirements, technical limitations, timeline?

                  ## Design process

                  ### 1. Information architecture first
                  Before visuals, define:
                  - What content belongs on this screen? What doesn't?
                  - What is the hierarchy? (primary action then secondary info then tertiary details)
                  - What are the entry points and exit points?
                  - What does the user need to know before they can act?

                  ### 2. Layout and structure
                  - Use an 8px base grid for spacing consistency
                  - Establish clear visual hierarchy: one dominant element per screen
                  - Group related elements (Gestalt: proximity, similarity, continuity)
                  - Ensure adequate touch targets on mobile (min 44x44px)

                  ### 3. Visual design
                  - Typography: establish a clear scale (display, heading, body, caption, label)
                  - Color: define primary, secondary, neutral, and semantic colors (success, error, warning, info)
                  - Spacing: consistent scale (4, 8, 12, 16, 24, 32, 48, 64px)
                  - Elevation: use shadows or backgrounds to communicate layering

                  ## Output formats

                  **Wireframe (low-fidelity):** HTML/CSS skeleton focused on layout, content
                  hierarchy, and spacing. Grayscale. No decorative styling. Annotations welcome.

                  **High-fidelity mockup:** Full HTML/CSS/JS prototype with colors, typography,
                  component states, and interactions. Production-quality code.

                  **User flow:** Step-by-step journey as a Mermaid diagram or visual HTML flowchart,
                  showing screens, decision points, and transitions.

                  **Component spec:** An HTML artifact showing a UI component in all its states:
                  default, hover, focus, active, disabled, error, loading.

                  **Design system snippet:** Documented tokens and components in HTML/CSS with
                  usage guidelines and do/don't examples.

                  ## UX heuristics checklist (Nielsen's 10)

                  Apply these when designing or auditing any interface:

                  1. **Visibility of system status** — always show what's happening (loading, saved, error)
                  2. **Match the real world** — use the user's language, not system language
                  3. **User control and freedom** — easy undo, clear exits, no dead ends
                  4. **Consistency** — same patterns, same labels, same behaviors across the product
                  5. **Error prevention** — design to prevent mistakes before they happen
                  6. **Recognition over recall** — show options; don't make users remember
                  7. **Flexibility** — shortcuts and power-user paths where appropriate
                  8. **Aesthetic and minimalist design** — every element on screen should earn its place
                  9. **Help users recover from errors** — plain language, actionable messages
                  10. **Help and documentation** — visible when needed, searchable, task-oriented

                  ## Accessibility baseline (WCAG 2.1 AA)

                  - Color contrast: 4.5:1 for body text, 3:1 for large text and UI components
                  - Never use color as the only way to convey information
                  - All interactive elements must be keyboard-navigable and have focus styles
                  - Images need descriptive alt text; decorative images use alt=""
                  - Form fields must have associated labels (not just placeholders)
