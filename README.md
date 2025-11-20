# ResponsibleAI_LLM_Alignment

This repository supports the empirical study “Are We Aligned? — Responsible AI Values in Large Language Models”, focusing on how large language models (LLMs) prioritize, rate, and trade‐off key Responsible AI values across multiple tasks and scenarios.

## 📚 Overview

We conduct **four distinct tasks** with multiple LLMs:

1. **Task 1 – Top-5 Value Selection**: Models select their top 5 most important AI ethics values from a list of 12.  
2. **Task 2 – Importance Rating**: Models rate each of 7 values in 4 real-world AI system scenarios on a 5-point Likert scale.  
3. **Task 3 – Value Trade-offs**: Models face 10 paired trade-off questions (e.g., Fairness vs. Performance) in each scenario and give a single choice from a predefined answer set.  
4. **Task 4 – User-Story Prioritization**: Models rank sets of 6 user-stories by importance (no explanation) in domains such as healthcare, streaming, and advertising.

These tasks are designed to reveal how aligned (or misaligned) LLMs are with human-valued ethics, how they prioritize values, and how consistently they trade-off among competing values.

- Use the Numbers file (instead of Excel) to read my raw data better
- The Notebook has the code for the 4 tasks
- You can get the human judgment data from: https://dl.acm.org/doi/10.1145/3531146.3533097


## 📄 Citation

If you use this repository, please cite:

```bibtex
@misc{yamani2025alignedpreliminaryinvestigationalignment,
  title        = {Are We Aligned? A Preliminary Investigation of the Alignment of Responsible AI Values between LLMs and Human Judgment},
  author       = {Asma Yamani and Malak Baslyman and Moataz Ahmed},
  year         = {2025},
  eprint       = {2511.04157},
  archivePrefix = {arXiv},
  primaryClass = {cs.SE},
  url          = {https://arxiv.org/abs/2511.04157},
}
