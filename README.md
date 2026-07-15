# Visualizing AI

Interactive, single-file visual stories that make machine learning and AI concepts easy to see.

## Explore

### [How an LLM learns](https://diabmoh.github.io/visualizing-ai/visualizations/llm-training/)

Follow a common LLM training lifecycle from raw text and tokens through prediction, loss, parameter updates, post-training, and evaluation.

[Open the interactive story →](https://diabmoh.github.io/visualizing-ai/visualizations/llm-training/)

### [How RAG finds the right context](https://diabmoh.github.io/visualizing-ai/visualizations/rag/)

Follow a question through semantic retrieval, context assembly, cited generation, failure modes, and evaluation inside a fictional observatory archive.

[Open the interactive story →](https://diabmoh.github.io/visualizing-ai/visualizations/rag/)

### [How embeddings map meaning](https://diabmoh.github.io/visualizing-ai/visualizations/embeddings/)

Watch text become coordinates, explore semantic neighborhoods, and learn why vector similarity is useful without being a test of truth.

[Open the interactive story →](https://diabmoh.github.io/visualizing-ai/visualizations/embeddings/)

### [How ELIZA made a machine seem to listen](https://diabmoh.github.io/visualizing-ai/visualizations/eliza/)

Trace a guided DOCTOR-style conversation through keyword ranking, pattern matching, reflected wording, scripted replies, and remembered fragments.

[Open the interactive story →](https://diabmoh.github.io/visualizing-ai/visualizations/eliza/)

### [How AI agents turn goals into actions](https://diabmoh.github.io/visualizing-ai/visualizations/agents/)

Follow one fictional expedition agent as it chooses tools, adapts to observations, recovers from failure, keeps working state, and pauses before a consequential action.

[Open the interactive story →](https://diabmoh.github.io/visualizing-ai/visualizations/agents/)

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
