# # 综述
全面综述合成表格数据生成

发布时间：2025年04月23日

`其他

理由：这篇论文主要探讨合成表格数据生成的方法，包括多种生成模型如GANs、扩散模型和LLMs，属于综述性质，未专注于特定领域如Agent、RAG或LLM的具体应用或理论。` `机器学习` `数据科学`

> A Comprehensive Survey of Synthetic Tabular Data Generation

# 摘要

> 表格数据仍是现实世界应用中最为普遍和关键的数据格式之一。然而，数据稀缺性、隐私顾虑及类别不平衡等问题常制约其在机器学习中的有效应用。合成数据生成作为解决方案应运而生，通过生成模型学习真实数据分布并生成高保真隐私保护样本。我们探索了多种生成范式，包括能量模型（EBMs）、变分自编码器（VAEs）、生成对抗网络（GANs）、大语言模型（LLMs）及扩散模型。尽管已有综述探讨了合成表格数据生成，但多聚焦于特定领域或方法，如GANs、扩散模型或隐私保护技术，导致见解零散，缺乏全面整合。尤其是，LLMs与扩散模型的最新进展尚未得到充分探索。为弥补这一空白，本综述提供统一系统的回顾，贡献包括：（1）提出全面分类法，将现有方法归类为传统方法、扩散模型与LLM模型，并进行深入比较；（2）详细阐述合成表格数据生成完整流程，涵盖数据合成、后处理与评估；（3）识别主要挑战，探索实际应用，并概述开放问题及未来方向，以指导这一快速发展领域的未来研究。

> Tabular data remains one of the most prevalent and critical data formats across diverse real-world applications. However, its effective use in machine learning (ML) is often constrained by challenges such as data scarcity, privacy concerns, and class imbalance. Synthetic data generation has emerged as a promising solution, leveraging generative models to learn the distribution of real datasets and produce high-fidelity, privacy-preserving samples. Various generative paradigms have been explored, including energy-based models (EBMs), variational autoencoders (VAEs), generative adversarial networks (GANs), large language models (LLMs), and diffusion models. While several surveys have investigated synthetic tabular data generation, most focus on narrow subdomains or specific generative methods, such as GANs, diffusion models, or privacy-preserving techniques. This limited scope often results in fragmented insights, lacking a comprehensive synthesis that bridges diverse approaches. In particular, recent advances driven by LLMs and diffusion-based models remain underexplored. This gap hinders a holistic understanding of the field`s evolution, methodological interplay, and open challenges. To address this, our survey provides a unified and systematic review of synthetic tabular data generation. Our contributions are threefold: (1) we propose a comprehensive taxonomy that organizes existing methods into traditional approaches, diffusion-based methods, and LLM-based models, and provide an in-depth comparative analysis; (2) we detail the complete pipeline for synthetic tabular data generation, including data synthesis, post-processing, and evaluation; (3) we identify major challenges, explore real-world applications, and outline open research questions and future directions to guide future work in this rapidly evolving area.

[Arxiv](https://arxiv.org/abs/2504.16506)