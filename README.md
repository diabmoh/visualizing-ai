# Visualizing AI

Interactive, single-file visual stories that make machine learning and AI concepts easy to see.

## Explore

### [How an LLM learns](visualizations/llm-training/)

Follow a common LLM training lifecycle from raw text and tokens through prediction, loss, parameter updates, post-training, and evaluation.

## Why this project exists

AI is often explained with either vague metaphors or dense mathematics. Visualizing AI aims for a useful middle: scientifically grounded explanations that people can understand by watching a system change.

Every visualization is:

- A self-contained `index.html`
- Usable offline with no build step or runtime dependencies
- Responsive, keyboard-accessible, and reduced-motion friendly
- Based on cited primary sources
- Explicit about simplifications and illustrative values

## Run locally

Open a visualization's `index.html` directly in a browser, or serve the repository with any static file server:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Repository structure

```text
visualizations/<concept-slug>/index.html
```

The public catalog lives at the repository root. See [DESIGN.md](DESIGN.md) for the shared experience contract and [CONTRIBUTING.md](CONTRIBUTING.md) before proposing a new concept.

## License

Code is released under the [MIT License](LICENSE). Educational text and diagrams may be reused under the same terms with attribution.
