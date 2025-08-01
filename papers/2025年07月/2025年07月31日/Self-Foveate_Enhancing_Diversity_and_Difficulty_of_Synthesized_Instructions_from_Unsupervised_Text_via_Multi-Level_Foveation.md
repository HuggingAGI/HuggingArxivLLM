# 自我注视：通过多级注视机制增强无监督文本中合成指令的多样性和难度

发布时间：2025年07月31日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）在生成指令数据方面的应用，提出了一种新的方法来提升合成指令的多样性和难度。这种方法属于LLM的应用层面，因为它展示了如何利用LLM来解决实际问题，即生成高质量的指令数据。`

> Self-Foveate: Enhancing Diversity and Difficulty of Synthesized Instructions from Unsupervised Text via Multi-Level Foveation

# 摘要

> 具有指令遵循能力的大型语言模型（LLMs）展现出了令人惊叹的问题解决能力。虽然从无监督文本中合成指令数据已成为训练此类模型的常见方法，但传统方法高度依赖人工标注。尽管现有自动化合成范式在一定程度上缓解了这一问题，但它们在确保合成指令的多样性和难度方面仍存在明显局限。为了解决这些挑战，我们提出了Self-Foveate，一种创新的LLM驱动指令合成方法。该方法通过'微观散射-宏观'多级注视方法，有效引导LLM深入挖掘无监督文本中的细粒度信息，从而显著提升合成指令的多样性和难度。我们的方法在多个无监督语料库和多种模型架构上的全面实验结果，充分验证了其有效性与优越性。我们已公开发布了相关数据和代码：https://github.com/Mubuky/Self-Foveate

> Large language models (LLMs) with instruction following capabilities have demonstrated impressive problem-solving abilities. While synthesizing instructional data from unsupervised text has become a common approach for training such models, conventional methods rely heavily on human effort for data annotation. Although existing automated synthesis paradigms have alleviated this constraint, they still exhibit significant limitations in ensuring adequate diversity and difficulty of synthesized instructions. To address these challenges, we propose Self-Foveate, an innovative LLM-driven method for instruction synthesis. This approach introduces a "Micro-Scatter-Macro" multi-level foveation methodology that effectively guides the LLM to deeply excavate fine-grained information embedded in unsupervised text, thereby enhancing both the diversity and difficulty of synthesized instructions. Comprehensive experiments across multiple unsupervised corpora and diverse model architectures validate the effectiveness and superiority of our proposed method. We publicly release our data and codes: https://github.com/Mubuky/Self-Foveate

[Arxiv](https://arxiv.org/abs/2507.23440)