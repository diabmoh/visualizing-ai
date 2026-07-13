# Museum Signal design system

Museum Signal is the shared visual and interaction language for Visualizing AI. It treats each topic as a digital science exhibit rather than a dashboard, slide deck, or product landing page.

## Principles

1. **Show causality.** Motion should reveal what changes, what caused it, and what happens next.
2. **Keep one visual stage.** Step-through stories update a dominant visual instead of stacking disconnected diagrams.
3. **Teach intuition first.** Main copy is written for a curious general audience. Technical depth belongs in optional native disclosures.
4. **Label simplifications.** Toy values, synthetic data, and compressed processes must be identified as illustrative.
5. **Make the quiet state useful.** Every scene must remain understandable with animation disabled.

## Visual language

- Cool neutral surfaces with one vermilion accent for active learning signals
- System sans-serif typography and system monospace for tokens, IDs, probabilities, and parameters
- Architectural grids, thin structure, generous negative space, and restrained 6px corners
- No decorative AI-purple glows, generic glass cards, fake terminals, or ornamental dashboards
- Theme-aware semantic CSS variables with complete light and dark palettes

## Motion

- Animate transform and opacity for interface transitions
- Use movement only for data flow, sequence, feedback, or a state change
- Pause continuous rendering when the page or stage is not visible
- Honor `prefers-reduced-motion` and preserve the complete explanation without movement
- Never require autoplay, sound, a custom cursor, or scroll hijacking

## Visualization contract

Each concept lives at `visualizations/<slug>/index.html` and must:

- Work from disk and from a GitHub Pages project subpath
- Contain all runtime CSS, JavaScript, SVG, and Canvas code
- Make no runtime network requests
- Use semantic controls and support keyboard navigation
- Provide accessible names or descriptions for every visual stage
- Provide named URL hashes for shareable chapters
- End with sources, simplifications, and a statement that implementations vary
- Stay below 1 MB uncompressed unless a documented exception is approved

## Content review

Before publication, verify the main claims against primary research or authoritative technical documentation. Avoid presenting one organization's training recipe as universal. Distinguish pretraining, supervised post-training, preference optimization, evaluation, and inference.
