# LLM Pipeline Explorer — Level 0

A Backrooms (Level 0) styled interactive explorer for how an LLM pipeline starts:

- **Tokenisation** — type any sentence and see WordPiece-style tokens, `##` subwords, and token IDs
- **Embeddings in 3D** — each token gets a 16-dim embedding vector, plotted in a rotatable 3D liminal corridor space (Three.js, drag / zoom)
- **Plotting** — vector bar chart, 2D PCA scatter, and a clickable cosine-similarity heatmap with nearest-neighbour readout

Click a token and it syncs across the embedding table, 3D plot, and heatmap.

## Run it

Just open `index.html` in a browser — it's a single self-contained page. No build step, no server needed.

Optionally serve it:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Built by

Addysaur (Advait Bodkhe) — B.Tech AI & ML, Newton School of Technology.
