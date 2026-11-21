---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<p><a href="{{ base_path }}/files/cv.pdf"><i class="fas fa-fw fa-file-pdf" aria-hidden="true"></i> Download PDF</a></p>

Education
======
* **Ph.D. in Computer Science and Engineering**, The Ohio State University, Aug. 2023 – present
  * Advisor: [Andrew Perrault](https://cse.engineering.osu.edu/people/perrault.17)
  * GPA: 3.85/4.0
* **B.Sc. in Electrical Engineering**, University of Tehran, Sep. 2018 – June 2023
  * Best Undergraduate Project Award, School of Electrical and Computer Engineering
  * GPA: 3.77/4.0

Research Experience
======
* **Graduate Research: LLM Alignment and RL Post-Training**, The Ohio State University, Aug. 2023 – present
  * Studying how safety training affects the strategic behavior of LLMs in game-theoretic settings (Kuhn Poker, Prisoner's Dilemma, Ultimatum), comparing base and post-trained models across multiple model families.
  * Evaluating the behavioral effects of safety training on LLM agents in autonomous, multi-agent environments.
  * Developing constrained optimization methods for multi-objective RLHF that enforce per-objective performance thresholds instead of fixed reward weights.
  * Training LLMs with self-play RL on stochastic games, studying transfer to general reasoning and credit assignment under chance.

Publications
======
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Technical Skills
======
* **RL & Alignment:** RL post-training (GRPO, PPO, RLVR), constrained and multi-objective RLHF, self-play RL, credit assignment, reward modeling, behavioral evaluation of LLMs, interpretability
* **Frameworks:** PyTorch, Hugging Face (Transformers, TRL, Datasets), veRL, DeepSpeed, Weights & Biases
* **Programming:** Python, C/C++, Bash, LaTeX
* **Infrastructure:** Slurm HPC, multi-GPU distributed training, large-scale experiment management

Service & Teaching
======
* **Reviewer:** NeurIPS 2026, ICML 2026, ICLR 2025
* **Teaching Assistant**, Ohio State CSE: Artificial Intelligence (Spring 2024), Computer Networking (Fall 2023)
