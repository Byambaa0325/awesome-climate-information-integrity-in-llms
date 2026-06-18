# Contributing

Thanks for helping improve **Awesome Climate Information Integrity in LLMs**. This list curates research on detecting, mitigating, and correcting climate and scientific misinformation, hallucination, and factual inaccuracy in large language models.

## Scope

A paper is in scope if it:

- concerns **LLMs** (or directly comparable foundation models), and
- proposes or rigorously evaluates an **intervention** against misinformation, hallucination, or factual inaccuracy (RAG, fine-tuning / domain adaptation, machine unlearning, fact-checking pipelines, hallucination/misinformation detection, or mechanistic interpretability), and
- targets **climate, sustainability, or an adjacent scientific-accuracy domain** (general scientific factuality work is welcome where it transfers).

Out of scope: pure emission/impact estimation with no factuality angle, image-only misinformation with no language model, and work with no LLM component.

Benchmarks, surveys, and evaluation-only studies live in their own section — they don't propose a mitigation but provide context.

## How to add a paper

1. Fork the repo and create a branch.
2. Add your entry to the most appropriate section, keeping entries ordered by quality/relevance within a section.
3. Use the entry format below.
4. Open a pull request with a one-line justification of scope and placement.

## Entry format

```markdown
- **[Paper Title](https://link-to-paper)** — First Author et al. — *Venue* (Year)
  One-line description of the contribution. `QA x.x`
```

- **Link:** prefer a DOI (`https://doi.org/...`) or arXiv (`https://arxiv.org/abs/...`) URL. Open-access links preferred over paywalled ones.
- **Authors:** `Surname et al.` for multi-author works, or the single surname otherwise.
- **Description:** one neutral sentence on what the paper does — what intervention, on what task/domain.
- **`QA x.x` badge:** optional. Only original-corpus entries carry a quality-assessment score from the underlying review; new community additions may omit it or propose one in the PR for discussion.

## Quality bar

- Peer-reviewed venues and well-cited preprints preferred.
- No duplicate entries (search the list first).
- Keep descriptions factual and non-promotional.

## License

By contributing, you agree that your contributions are released under [CC0 1.0](LICENSE) (public domain dedication). Linked papers remain under their own rights.
