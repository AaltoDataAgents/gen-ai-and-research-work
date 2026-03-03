# Generative AI in Research Work

> **Work in progress.** This book is actively being developed. Content may be incomplete, inaccurate, or subject to significant revision. Feedback and contributions are welcome.

A open course book for researchers on using generative AI tools responsibly, critically, and effectively across the research lifecycle. The material is tailored for researchers who may have little prior experience with these technologies — it prioritises intuitive explanations and practical guidance over computer science theory.

**Read the book →** https://aaltodataagents.github.io/gen-ai-and-research-work/

[![CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![Render and Publish](https://github.com/AaltoDataAgents/gen-ai-and-research-work/actions/workflows/publish.yml/badge.svg)](https://github.com/AaltoDataAgents/gen-ai-and-research-work/actions/workflows/publish.yml)

---

## Contents

| Chapter | Title |
|---------|-------|
| Preface | Introduction to the course |
| 0 | Introduction: What is Generative AI? |
| 1 | Research Ethics & Responsible AI |
| 2 | Research Integrity, Authorship & Policies |
| 3 | Legal, Data Protection & Compliance |
| 4 | How Generative AI Works |
| 5 | Prompting Techniques |
| 6 | Evaluating AI Outputs |
| 7 | Multimodal AI for Research |

Each chapter includes **learning outcomes**, **discussion activities**, **practical exercises** using free privacy-respecting tools ([duck.ai](https://duck.ai), [lumo.proton.me](https://lumo.proton.me), [arena.ai](https://arena.ai)), and a **reference list**.

---

## Authors

**Dr. Enrico Glerean** — Staff Scientist and Data Agent at the School of Science (SCI), Aalto University. Background in neuroimaging; works on personal data handling, research ethics, research integrity, and open science. Member of the CodeRefinery network, Finnish Reproducibility Network, and Support Pool of Experts at the European Data Protection Board.

**Dr. Pedro Silva** — Postdoctoral Researcher and Data Agent at the School of Chemical Engineering (CHEM), Aalto University. Works on research data management, open science, and researcher training.

This book builds on lecture slides previously developed by the authors:
> Glerean, E., & Silva, P. (2025). *AI in Research Work: Prompt engineering and advanced uses of generative AI for researchers*. Aalto University. CC BY. DOI: [10.5281/zenodo.14032261](https://doi.org/10.5281/zenodo.14032261)

---

## Building Locally

Requires [Quarto](https://quarto.org) ≥ 1.5.

```bash
# Clone the repository
git clone https://github.com/AaltoDataAgents/gen-ai-and-research-work.git
cd gen-ai-and-research-work

# Preview with live reload
quarto preview book/

# Render to HTML
quarto render book/
# Output: book/_book/index.html
```

---

## Automated Publishing

On every push to `main`, a GitHub Actions workflow renders the book using the official `ghcr.io/quarto-dev/quarto` Docker image and deploys the output to GitHub Pages. Pull requests trigger a render check without publishing.

Workflow: [`.github/workflows/publish.yml`](.github/workflows/publish.yml)

---

## License

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).

You are free to:
- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material for any purpose, even commercially

Under the following terms:
- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made.
- **ShareAlike** — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

See [`LICENSE`](LICENSE) for the full legal text.

---

## Contributing

This book is in active development. If you find errors, have suggestions, or want to contribute content, please [open an issue](https://github.com/AaltoDataAgents/gen-ai-and-research-work/issues) or submit a pull request.
