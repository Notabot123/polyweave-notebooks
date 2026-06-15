# polyweave-notebooks

Companion Jupyter notebooks for the [`polyweave`](https://github.com/Notabot123/polyweave)
blog posts and tutorials. Each notebook is **Binder-runnable** — click a launch badge to
run it in your browser with no install.

> This repo is intentionally separate from the `polyweave` library repo: notebooks are
> large, frequently-rewritten binary files and Binder builds the whole repo, so they live
> on their own.

## Notebooks

<!-- notebooks:begin -->
| Notebook | Launch |
|---|---|
| `differentiable-logic` | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Notabot123/polyweave-notebooks/HEAD?labpath=notebooks/differentiable-logic.ipynb) |
| `how-linear-is-a-transformer-ffn` | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Notabot123/polyweave-notebooks/HEAD?labpath=notebooks/how-linear-is-a-transformer-ffn.ipynb) |
| `hypernetworks-on-cifar` | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Notabot123/polyweave-notebooks/HEAD?labpath=notebooks/hypernetworks-on-cifar.ipynb) |
<!-- notebooks:end -->

## Run locally

```bash
pip install -r requirements.txt
jupyter lab
```

## Add a notebook

Use the `companion-notebooks` skill's scaffold script (`add` subcommand), or copy an
existing notebook to `notebooks/<post-slug>.ipynb`. Keep the slug equal to the blog post's
filename so the two stay paired, then paste the Binder badge it prints into the post's
"Try it out yourself" section.
