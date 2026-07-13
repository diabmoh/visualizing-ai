# Contributing

Thanks for helping make difficult AI ideas easier to see.

## Propose a concept first

Open a concept proposal describing:

- The learner question the visualization will answer
- The intended audience
- The central visual metaphor
- The main interaction
- Primary sources that ground the explanation
- Important simplifications or disputed details

Do not begin with a framework choice. Begin with the learning outcome.

## Build contract

Create `visualizations/<lowercase-hyphenated-slug>/index.html`. The file must be self-contained, work offline, and follow [DESIGN.md](DESIGN.md).

Update both the root catalog and README only after the visualization is complete. Do not add roadmap cards or empty concept folders.

## Definition of done

- Every chapter works with pointer and keyboard input
- Named chapter hashes support direct linking and browser history
- Text and controls meet WCAG AA contrast
- Reduced-motion mode preserves meaning
- Layout works at 320, 390, 768, 1024, and 1440 pixel widths
- Current Chrome, Firefox, Safari, and Edge show no console errors
- The file works with networking disabled
- Illustrative data is labeled
- Scientific claims have primary sources
- Copy has been reviewed for clarity and unnecessary jargon

## Pull requests

Keep a pull request focused on one concept or one coherent improvement. Include screenshots of the opening, the main interaction, and the narrow mobile layout.
