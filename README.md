# ⭐ Tokenized Semantic Communication Paper Collection

A curated and actively updated list of representative works on **token-level / tokenization-driven semantic communication** (e.g., **Token Communications / TokCom / TokenCom**), covering **token as communication unit**, **semantic token selection**, **token-domain transmission**, and **LLM- or foundation-model-guided reconstruction**.

This repository focuses on research at the intersection of:
- **Semantic Communication**
- **Large Language Models (LLMs) / Foundation Models**
- **Token-level representation and transmission**
- **Cross-modal semantic encoding and reconstruction**

---

## 📘 Overview

Traditional communication systems aim to transmit **bits** reliably.  
By contrast, **semantic communication** aims to transmit the **meaning** required for a downstream task.

A recent research trend pushes this idea further by treating **tokens** as the basic communication units. In these frameworks, source content (text, image patches, visual codes, or multimodal symbols) is mapped into tokens, which are then selectively transmitted, aggregated, decoded, or regenerated with the help of **Transformers**, **LLMs**, and **foundation models**.

This paradigm is promising because it can improve:
- **semantic efficiency** (send only what matters),
- **compression** (fewer transmitted symbols),
- **task-awareness** (adapt to downstream inference goals), and
- **interpretability** (tokens are easier to inspect than latent vectors).

---

## 🧩 Papers

| Year | Title | Authors | Venue / Status | Link |
|------|-------|---------|----------------|------|
| **2026 (Sep)** | **Thinking in Tokens, Talking in Bits: A Practical Interface for Token Communication** | Chanho Park, Bumsu Park, Soonhee Kwon, Sangrim Lee, Namyoon Lee | arXiv | [arXiv:2609.15256](https://arxiv.org/abs/2609.15256) |
| **2026 (Sep)** | **Agentic TokenCom: A Chain-of-Agents Framework for Multimodal Token Communications** | Feibo Jiang, Lei Mao, Li Dong, Kezhi Wang, Cunhua Pan, Abbas Jamalipour | IEEE Transactions on Cognitive Communications and Networking | [DOI:10.1109/TCCN.2026.3732515](https://doi.org/10.1109/TCCN.2026.3732515) |
| **2026 (Sep)** | **From Semantic to Token Communication: The Next Paradigm for Large-Model-Driven 6G Intelligent Connectivity** | Yu Ma, Zhen Gao, Li Qiao, Xiaoyuan Zhang, Mahdi Boloursaz Mashhadi, Yin Xu, Wenjun Xu, Xiaodong Xu, Kaibin Huang, Jiangzhou Wang, Rahim Tafazolli, Sheng Chen, Tony Q. S. Quek, Ping Zhang | arXiv / survey | [arXiv:2609.10714](https://arxiv.org/abs/2609.10714) |
| **2026 (Sep)** | **TokenComSR: Task-Sensitivity-Guided Token Communication for Wireless Image Super-Resolution** | Ye Wang, Li Qiao, Zhen Gao, Hua Wang | arXiv | [arXiv:2609.03735](https://arxiv.org/abs/2609.03735) |
| **2026 (Aug)** | **Ada-TokenCom: Rate-Adaptive Token Communications via Large-Model-Driven Token Compression and Generation** | Zijun Zhang, Li Qiao, Mahdi Boloursaz Mashhadi, Zhen Gao, Mehdi Bennis, Kaibin Huang | arXiv | [arXiv:2608.28086](https://arxiv.org/abs/2608.28086) |
| **2026 (Jul)** | **ATS-ToDMA: Adaptive Token Selection and Token-Domain Multiple Access for Cross-Modal Semantic Communications** | Sachin Kadam, Dong In Kim | arXiv | [arXiv:2607.03520](https://arxiv.org/abs/2607.03520) |
| **2026 (May)** | **Context-Aware Wireless Token Communication via Joint Token Masking and Detection** | Junyong Shin, Joohyuk Park, Yongjeong Oh, Jihong Park, Jinho Choi, Yo-Seb Jeon | arXiv | [arXiv:2605.02123](https://arxiv.org/abs/2605.02123) |
| **2026 (May)** | **Evolving Token Communication with Parametric Memory Network** | Weixuan Chen, Qianqian Yang | arXiv | [arXiv:2605.01869](https://arxiv.org/abs/2605.01869) |
| **2026 (Mar)** | **Video TokenCom: Textual Intent-Guided Multi-Rate Video Token Communications with UEP-Based Adaptive Source-Channel Coding** | Jingxuan Men, Mahdi Boloursaz Mashhadi, Ning Wang, Yi Ma, Mike Nilsson, Rahim Tafazolli | arXiv | [arXiv:2603.02470](https://arxiv.org/abs/2603.02470) |
| **2026 (Feb)** | **Wireless TokenCom: RL-Based Tokenizer Agreement for Semantic-Aware Wireless Resource Allocation** | Fatemeh Zeinali, Mahdi Boloursaz Mashhadi, Michail Matthaiou, H. Vincent Poor, Mehdi Bennis | arXiv | [arXiv:2602.12338](https://arxiv.org/abs/2602.12338) |
| **2025 (Sep)** | **Adaptive Token Merging for Efficient Transformer Semantic Communication at the Edge** | Omar Erak, Omar Alhussein, Hatem Abou-Zeid, Mehdi Bennis, Sami Muhaidat | arXiv | [arXiv:2509.09955](https://arxiv.org/abs/2509.09955) |
| **2025 (Sep)** | **Adaptive Pareto-Optimal Token Merging for Edge Transformer Models in Semantic Communication** | Omar Erak, Omar Alhussein, Hatem Abou-Zeid, Mehdi Bennis | arXiv | [arXiv:2509.09168](https://arxiv.org/abs/2509.09168) |
| **2025 (Aug)** | **SemToken: Semantic-Aware Tokenization for Efficient Long-Context Language Modeling** | Dong Liu, Yanxuan Yu | arXiv | [arXiv:2508.15190](https://arxiv.org/abs/2508.15190) |
| **2025 (Jul)** | **Text-Guided Token Communication for Wireless Image Transmission** | Bole Liu, Li Qiao, Ye Wang, Zhen Gao, Yu Ma, Keke Ying, Tong Qin | arXiv / IEEE ICCC 2025 | [arXiv:2507.05781](https://arxiv.org/abs/2507.05781) |
| **2025 (May)** | **Adaptive Semantic Token Communication for Transformer-based Edge Inference** | Alessio Devoto, Jary Pomponi, Mattia Merluzzi, Paolo Di Lorenzo, Simone Scardapane | arXiv | [arXiv:2505.17604](https://arxiv.org/abs/2505.17604) |
| **2025 (May)** | **ToDMA: Large Model-Driven Token-Domain Multiple Access for Semantic Communications** | Li Qiao, Mahdi Boloursaz Mashhadi, Zhen Gao, Robert Schober, Deniz Gündüz | arXiv | [arXiv:2505.10946](https://arxiv.org/abs/2505.10946) |
| **2025 (Apr)** | **Semantic Packet Aggregation for Token Communication via Genetic Beam Search** | Seunghun Lee, Jihong Park, Jinho Choi, Hyuncheol Park | arXiv | [arXiv:2504.19591](https://arxiv.org/abs/2504.19591) |
| **2025 (Mar)** | **Multi-Task Semantic Communications via Large Models** | Wanli Ni, Zhijin Qin, Haofeng Sun, Xiaoming Tao, Zhu Han | arXiv | [arXiv:2503.22064](https://arxiv.org/abs/2503.22064) |
| **2025 (Feb)** | **A Contemporary Survey on Semantic Communications: Theory of Mind, Generative AI, and Deep Joint Source-Channel Coding** | Loc X. Nguyen, Avi Deb Raha, Pyae Sone Aung, Dusit Niyato, Zhu Han, Choong Seon Hong | arXiv / later IEEE Communications Surveys & Tutorials | [arXiv:2502.16468](https://arxiv.org/abs/2502.16468) |
| **2025 (Feb)** | **Token Communications: A Large Model-Driven Framework for Cross-modal Context-aware Semantic Communications** | Li Qiao, Mahdi Boloursaz Mashhadi, Zhen Gao, Rahim Tafazolli, Mehdi Bennis, Dusit Niyato | arXiv | [arXiv:2502.12096](https://arxiv.org/abs/2502.12096) |
| **2025 (Feb)** | **Token-Domain Multiple Access: Exploiting Semantic Orthogonality for Collision Mitigation** | Li Qiao, Mahdi Boloursaz Mashhadi, Zhen Gao, Deniz Gündüz | arXiv / INFOCOM Workshops 2025 | [arXiv:2502.06118](https://arxiv.org/abs/2502.06118) |
| **2025 (Jan)** | **Large Model Empowered Multi-Modal Semantic Communication With Selective Tokens for Training** | Jincheng Peng, Huanlai Xing, Fuhui Zhou, Dusit Niyato, Xianfu Lei | IEEE Signal Processing Letters | [Semantic Scholar entry](https://www.semanticscholar.org/paper/Large-Model-Empowered-Multi-Modal-Semantic-With-for-Peng-Xing/eb4b18696ad562809129a45acfa02f420c930ec6) |
| **2024 / 2025** | **Generative Semantic Communication: Architectures and Technologies** | Xiang Chen, Hao Du, Dusit Niyato, et al. | arXiv / survey-style overview | [arXiv:2412.08642](https://arxiv.org/abs/2412.08642) |
| **2024** | **A Survey on Semantic Communications: Technologies, Solutions, Applications and Challenges** | Guan Gui, Zhe Yang, Hsiao-Hwa Chen, Ming Xiao | Digital Communications and Networks | [ScienceDirect](https://www.sciencedirect.com/science/article/pii/S2352864823000925) |
| **2024 (Aug)** | **Rethinking Generative Semantic Communication for Multi-User Systems with Multi-Modal LLM** | Wanting Yang, Zehui Xiong, Shiwen Mao, Tony Q. S. Quek, Ping Zhang, Merouane Debbah, Rahim Tafazolli | arXiv | [arXiv:2408.08765](https://arxiv.org/abs/2408.08765) |
| **2024 (Jun)** | **Towards Semantic Equivalence of Tokenization in Multimodal LLMs (SeTok)** | Shengqiong Wu, Hao Fei, Xiangtai Li, Jiayi Ji, Hanwang Zhang, Tat-Seng Chua, Shuicheng Yan | arXiv / ICLR 2025 | [arXiv:2406.05127](https://arxiv.org/abs/2406.05127) |
| **2024 (May)** | **Semantic Importance-Aware Communications with Semantic Correction Using Large Language Models** | Shuaishuai Guo, Yanhu Wang, Jia Ye, Anbang Zhang, Kun Xu | arXiv | [arXiv:2405.16011](https://arxiv.org/abs/2405.16011) |
| **2024 (May)** | **Adaptive Semantic Token Selection for AI-native Goal-oriented Communications** | Alessio Devoto, Simone Petruzzi, Jary Pomponi, Paolo Di Lorenzo, Simone Scardapane | arXiv / IEEE Globecom Workshops 2024 | [arXiv:2405.02330](https://arxiv.org/abs/2405.02330) |

---

## 📝 Notes

- This list includes **core TokenCom papers**, **closely related neighboring works**, and **survey/background papers**.
- The papers are listed in **chronological order** only.
- Most recent items are currently available as **arXiv preprints**; some also have workshop, conference, or journal versions.

---

## 🤝 Contribution

Pull requests are welcome for:
- newly published TokCom / TokenCom papers,
- related semantic communication papers,
- benchmark datasets,
- tutorial or survey papers.

---

## ⭐ Citation

If this repository helps your work, please consider starring it and citing the relevant original papers.
