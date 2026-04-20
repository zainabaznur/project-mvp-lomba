```markdown
# Design System: Architectural Intelligence & Fluid Precision

## 1. Overview & Creative North Star: "The Digital Blueprint"

This design system is built upon the **Creative North Star: The Digital Blueprint**. We are moving away from the "SaaS template" look toward an editorial, high-precision experience that mirrors the workflow of a modern architect. 

The system prioritizes **Atmospheric Depth** over flat layouts. By utilizing intentional asymmetry, expansive breathing room (whitespace), and overlapping glass modules, we create an environment that feels both ultra-stable and technologically advanced. We do not just show data; we draft an experience.

### Design Principles
*   **Precision Brutalism:** Sharp typography and technical labels meet soft, organic glass containers.
*   **Intentional Asymmetry:** Break the grid. Use staggered layouts for hero sections to guide the eye through "architectural" paths.
*   **Radiant Focus:** Use the `Electric Emerald` color sparingly, like a laser level in a dark room—only where action or intelligence is happening.

---

## 2. Colors: Tonal Depth & The Obsidian Field

Our palette is rooted in the depth of `Deep Obsidian`. We treat the screen not as a flat canvas, but as a dark space where light and glass define the form.

### Core Tones
*   **Base Background:** `#0B0E11` (The void from which designs emerge).
*   **Primary Action:** `primary` (`#a2ffbf`) and `primary_container` (`#00fd93`). This is the "AI Pulse."
*   **Typography:** `on_surface` (`#f8f9fe`) for high-impact text; `on_surface_variant` (`#a9abaf`) for secondary technical data.

### The "No-Line" Rule
Traditional 1px solid borders are strictly prohibited for sectioning. Structural separation must be achieved through:
1.  **Background Shifts:** Transitioning from `surface` to `surface_container_low`.
2.  **Negative Space:** Using the spacing scale to create "valleys" between content groups.
3.  **Elevation Layering:** Nesting a `surface_container_high` card inside a `surface_container_low` section.

### The "Glass & Gradient" Rule
To achieve an ultra-modern aesthetic, use **Glassmorphism** for all floating panels (Modals, Hover-cards, Navigation).
*   **Surface:** `surface_variant` at 60% opacity.
*   **Backdrop Blur:** 12px to 20px.
*   **Signature Texture:** Use a linear gradient on Primary CTAs: `primary` (#a2ffbf) to `primary_dim` (#00ed89) at a 135-degree angle to simulate light hitting a physical edge.

---

## 3. Typography: Minimalist Sophistication

We utilize two typefaces to balance human-centric design with technical precision.

*   **Primary Typeface:** `Plus Jakarta Sans`. Used for all headers and body text. It provides a clean, professional, yet "Gen Z" approachable feel.
*   **Technical Typeface:** `Space Grotesk`. Used exclusively for `label-md` and `label-sm` (technical specs, coordinates, AI confidence scores).

### Typographic Hierarchy
*   **Display-LG (3.5rem):** Use for hero statements. Set with tight letter-spacing (-0.02em) to mimic high-end architectural journals.
*   **Headline-SM (1.5rem):** Used for section headers. Always paired with a `label-md` "kicker" text in `primary` color.
*   **Body-MD (0.875rem):** The workhorse. Maintain a line-height of 1.6 for maximum readability against the dark background.

---

## 4. Elevation & Depth: Tonal Layering

In this design system, shadows are light, and borders are ghosts.

### The Layering Principle
Hierarchy is achieved by stacking surface containers. 
*   **Level 0:** `surface_dim` (#0b0e11) - Main workspace.
*   **Level 1:** `surface_container_low` - Secondary sidebars or content groupings.
*   **Level 2:** `surface_container_high` - Active cards or interactive modules.

### Ambient Shadows
For floating elements, use a "Luminous Shadow" instead of a dark one. 
*   **Shadow:** `0px 20px 40px rgba(0, 0, 0, 0.4), 0px 0px 10px rgba(0, 255, 148, 0.05)`. 
*   The subtle emerald tint makes the element feel like it is powered by the AI engine.

### The "Ghost Border"
If a container requires a boundary (e.g., in complex architectural data views), use a **Ghost Border**:
*   **Stroke:** 1px.
*   **Color:** `outline_variant` at 15% opacity. 
*   It should be felt, not seen.

---

## 5. Components

### Buttons (The Interaction Points)
*   **Primary:** Solid `primary_container` (#00fd93) with `on_primary` (#006437) text. Bold, high-contrast. Use `xl` (0.75rem) roundedness.
*   **Secondary/Glass:** Background `surface_variant` at 20% opacity with a 1px "Ghost Border." On hover, increase opacity to 40%.
*   **AI Action:** Utilize a "Claymorphism" style—subtle inner glows and a slight 3D lift to signify an AI-generated result.

### Cards & Modules
*   **Strict Rule:** No dividers. Separate content using `headline-sm` titles and generous vertical padding (e.g., 32px or 48px).
*   **Architecture Preview Cards:** Use a "frosted glass" footer at the bottom of the card for metadata, utilizing the `surface_container_highest` token with 70% opacity.

### Claymorphic 3D Icons
*   Icons are not flat. They should have a soft, matte 3D quality (Claymorphism) in `secondary_fixed_dim`. When active, they "glow" with a `primary` drop shadow.

### Input Fields
*   **State:** Default fields are `surface_container_lowest` with a bottom-only border using `outline_variant`.
*   **Focus:** The border expands to 2px and transitions to `primary`. Add a 4px soft glow in `primary` to indicate the "active cursor."

---

## 6. Do's and Don'ts

### Do:
*   **Embrace the Dark:** Allow the `Deep Obsidian` to dominate. It provides the "premium" feel.
*   **Use Wide Tracking:** For labels and small caps, increase letter spacing slightly to improve readability on OLED screens.
*   **Micro-animations:** Elements should "slide" into place with a subtle `cubic-bezier(0.16, 1, 0.3, 1)` easing, mimicking a camera lens focusing.

### Don't:
*   **No "Pure" White:** Never use #FFFFFF. Use `Soft Slate Gray` (#F0F2F5) to reduce eye strain and maintain the atmospheric mood.
*   **No Hard Grids:** Avoid boxing everything in. Let elements "float" and overlap—it feels more like a drafting table and less like a spreadsheet.
*   **No High-Contrast Borders:** If the border is the first thing you see, it’s too heavy. Reduce opacity until it’s barely visible.

---
*Director’s Closing Note: This system is about the tension between the void of the screen and the precision of the architect. Every pixel must feel calculated, yet every layout should feel like it has room to breathe.*```