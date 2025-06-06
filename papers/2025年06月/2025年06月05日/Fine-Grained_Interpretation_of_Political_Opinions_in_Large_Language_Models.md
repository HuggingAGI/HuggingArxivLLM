# 大型语言模型中的政治观点细粒度解读

发布时间：2025年06月05日

`LLM理论` `政治学` `人工智能`

> Fine-Grained Interpretation of Political Opinions in Large Language Models

# 摘要

> 关于 LLMs 的政治观点研究主要依赖于对其开放性回答的评估。近期研究表明，LLMs 的回答与其内部意图之间存在不一致。这促使我们深入探究 LLMs 的内部机制，以揭示其内部政治状态。此外，我们发现对 LLMs 政治观点的分析往往依赖于单轴概念，这可能引发概念混淆。在本研究中，我们将单轴扩展为多维度，并引入可解释的表示工程方法，以实现更透明的 LLM 政治概念学习。具体而言，我们设计了一个四维政治学习框架，并构建了相应的数据集，用于细粒度的政治概念向量学习。这些向量能够用于检测和干预 LLM 的内部状态。我们在八种开源 LLM 上应用了三种表示工程方法进行了实验。实验结果表明，这些向量能够有效分解政治概念混淆。检测任务验证了向量的语义含义，并在 OOD 场景下展现了良好的泛化性和鲁棒性。干预实验进一步证明，这些向量可以干预 LLMs，使其生成具有不同政治倾向的回答。

> Studies of LLMs' political opinions mainly rely on evaluations of their open-ended responses. Recent work indicates that there is a misalignment between LLMs' responses and their internal intentions. This motivates us to probe LLMs' internal mechanisms and help uncover their internal political states. Additionally, we found that the analysis of LLMs' political opinions often relies on single-axis concepts, which can lead to concept confounds. In this work, we extend the single-axis to multi-dimensions and apply interpretable representation engineering techniques for more transparent LLM political concept learning. Specifically, we designed a four-dimensional political learning framework and constructed a corresponding dataset for fine-grained political concept vector learning. These vectors can be used to detect and intervene in LLM internals. Experiments are conducted on eight open-source LLMs with three representation engineering techniques. Results show these vectors can disentangle political concept confounds. Detection tasks validate the semantic meaning of the vectors and show good generalization and robustness in OOD settings. Intervention Experiments show these vectors can intervene in LLMs to generate responses with different political leanings.

[Arxiv](https://arxiv.org/abs/2506.04774)