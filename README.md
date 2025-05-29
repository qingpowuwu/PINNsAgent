# PINNsAgent: Automated PDE Surrogation with Large Language Models

[**Project Page**](https://qingpowuwu.github.io/PINNsAgent/) | [**arXiv Paper**](https://arxiv.org/abs/2501.12053)

![PINNsAgent Pipeline](./static/images/2_PINNsAgent.png)

Solving partial differential equations (PDEs) using neural methods has been a long-standing scientific and engineering research pursuit. Physics-Informed Neural Networks (PINNs) have emerged as a promising alternative to traditional numerical methods for solving PDEs. However, the gap between domain-specific knowledge and deep learning expertise often limits the practical application of PINNs. Previous works typically involve manually conducting extensive PINNs experiments and summarizing heuristic rules for hyperparameter tuning. In this work, we introduce PINNsAgent, a novel surrogation framework that leverages large language models (LLMs) and utilizes PINNs as a foundation to bridge the gap between domain-specific knowledge and deep learning. Specifically, PINNsAgent integrates (1) Physics-Guided Knowledge Replay (PGKR), which encodes the essential characteristics of PDEs and their associated best-performing PINNs configurations into a structured format, enabling efficient knowledge transfer from solved PDEs to similar problems and (2) Memory Tree Reasoning, a strategy that effectively explores the search space for optimal PINNs architectures. By leveraging LLMs and exploration strategies, PINNsAgent enhances the automation and efficiency of PINNs-based solutions. We evaluate PINNsAgent on 14 benchmark PDEs, demonstrating its effectiveness in automating the surrogation process and significantly improving the accuracy of PINNs-based solutions.

---

## Citation

```bibtex
@article{wuwu2025pinnsagent,
  title={PINNsAgent: Automated PDE Surrogation with Large Language Models},
  author={Wuwu, Qingpo and Gao, Chonghan and Chen, Tianyu and Huang, Yihang and Zhang, Yuekai and Wang, Jianing and Li, Jianxin and Zhou, Haoyi and Zhang, Shanghang},
  journal={arXiv:2501.12053},
  year={2025}
}