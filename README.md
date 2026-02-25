# Adaptive Arc Length

**ID:** `core-adaptive-arc-length`  
**Tier:** core  
**Score:** 50  
**Units:** WARN  
**Theory:** PASS-WITH-ASSUMPTIONS  

## Equation

$$
L_g(\gamma)=\int_0^1 \Omega(\gamma(t),t)\,|\dot\gamma(t)|\,dt
$$

## Description

Distances and penalties are measured in the adaptive geometry: path lengths scale with the local πₐ field.

## Repository Structure

```
images/       # Visualizations, plots, diagrams
derivations/  # Step-by-step derivations and proofs
simulations/  # Computational models and code
data/         # Numerical data, experimental results
notes/        # Research notes and references
```

## Links

- [TopEquations Leaderboard](https://rdm3dc.github.io/TopEquations/leaderboard.html)
- [TopEquations Main Repo](https://github.com/RDM3DC/TopEquations)
- [Certificates](https://rdm3dc.github.io/TopEquations/certificates.html)

---
*Part of the [TopEquations](https://github.com/RDM3DC/TopEquations) project.*

## Contributing

You can add images, derivations, simulations, data, or notes to this repo:

| Folder | What goes here |
|--------|---------------|
| `images/` | Plots, diagrams, phase portraits, animations (.png, .jpg, .mp4, ...) |
| `derivations/` | Step-by-step derivations and proofs (.tex, .md, .pdf) |
| `simulations/` | Computational models and code (.py, .ipynb, .jl, .m) |
| `data/` | Numerical results, experimental measurements (.csv, .hdf5, .npy) |
| `notes/` | Research notes, lit reviews, references (.md, .bib, .txt) |
| `docs/` | Formal documents, validation plans (.md, .pdf) |

**Three ways to contribute:**
1. **GitHub Issue** — click [New Issue](../../issues/new?template=artifact_submission.yml) and attach your file
2. **Pull Request** — fork, add files, open a PR
3. **CLI** — `python tools/push_to_equation_repo.py --equation-id core-adaptive-arc-length --file <path> --folder <folder>`

All submissions are content-moderated. See the [full contributing guide](https://github.com/RDM3DC/TopEquations/blob/main/CONTRIBUTING.md).
