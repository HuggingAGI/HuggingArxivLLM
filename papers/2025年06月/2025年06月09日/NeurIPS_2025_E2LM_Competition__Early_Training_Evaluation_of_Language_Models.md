# 2025 NeurIPS E2LM竞赛：语言模型早期训练评估

发布时间：2025年06月09日

`LLM应用

理由：这篇论文主要探讨了在评估小型语言模型的早期训练阶段时，现有基准测试的不足，并提出设计专门的科学知识评估任务来更精准地衡量模型的性能。这属于大型语言模型的应用领域，因为它关注如何有效评估和优化模型的训练过程，而不是理论层面的探讨或其他应用领域。` `人工智能`

> NeurIPS 2025 E2LM Competition : Early Training Evaluation of Language Models

# 摘要

> 现有基准测试在评估大型语言模型性能方面表现优异，但在小型模型的早期训练阶段，这些基准往往无法提供有效的区分信号。为了探究这一现象背后的原因，本次竞赛聚焦于设计专门的科学知识评估任务，旨在精准衡量语言模型的早期训练进展。我们诚邀研究者开发创新的评估方法或优化现有基准，以更敏锐地捕捉不同模型间的性能差异。为支持这一研究，我们提供了三个预训练小模型（0.5B、1B、3B参数量）及训练过程中生成的200B令牌的中间检查点。所有实验均可在免费的云GPU平台上运行，为资源有限的研究者敞开大门。参赛作品将从三个维度接受评估：性能信号的质量、模型排名的一致性，以及与科学知识领域的契合度。本次竞赛旨在激发跨学科的创新思维，吸引更多非机器学习专家参与，推动基础LLM研究从早期阶段就走上系统化、基准化的科学发展道路。


> Existing benchmarks have proven effective for assessing the performance of fully trained large language models. However, we find striking differences in the early training stages of small models, where benchmarks often fail to provide meaningful or discriminative signals. To explore how these differences arise, this competition tackles the challenge of designing scientific knowledge evaluation tasks specifically tailored for measuring early training progress of language models. Participants are invited to develop novel evaluation methodologies or adapt existing benchmarks to better capture performance differences among language models. To support this effort, we provide three pre-trained small models (0.5B, 1B, and 3B parameters), along with intermediate checkpoints sampled during training up to 200B tokens. All experiments and development work can be run on widely available free cloud-based GPU platforms, making participation accessible to researchers with limited computational resources. Submissions will be evaluated based on three criteria: the quality of the performance signal they produce, the consistency of model rankings at 1 trillion tokens of training, and their relevance to the scientific knowledge domain. By promoting the design of tailored evaluation strategies for early training, this competition aims to attract a broad range of participants from various disciplines, including those who may not be machine learning experts or have access to dedicated GPU resources. Ultimately, this initiative seeks to make foundational LLM research more systematic and benchmark-informed from the earliest phases of model development.

[Arxiv](https://arxiv.org/abs/2506.07731)