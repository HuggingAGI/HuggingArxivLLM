# EvolveNav: 基于LLM的视觉语言导航中的自我提升具身推理

发布时间：2025年06月02日

`LLM应用` `视觉语言导航` `计算机视觉`

> EvolveNav: Self-Improving Embodied Reasoning for LLM-Based Vision-Language Navigation

# 摘要

> 构建能够根据自然语言指令进行导航的视觉语言导航（VLN）代理一直是人机交互应用中的长期目标。近期研究表明，通过训练开源大型语言模型（LLMs）可以释放其推理能力以改善导航效果，同时缩小LLMs训练语料与VLN任务之间的领域差距。然而，这些方法主要采用直接的输入输出映射范式，导致映射学习困难且导航决策难以解释。链式思维（CoT）训练是一种有望同时提升导航决策准确性和可解释性的方法，但导航任务的复杂性使得完美的CoT标签难以获得，并可能通过纯CoT监督微调导致过拟合。本文中，我们提出了一种名为EvolveNav的新型自我改进式具身推理框架，用于提升基于LLM的视觉语言导航性能。我们的EvolveNav框架包含两个阶段：（1）形式化CoT监督微调，其中我们使用形式化的CoT标签训练模型，以激活模型的导航推理能力并提高推理速度；（2）自我反思式后训练，其中模型通过自身推理输出作为自我增强的CoT标签进行迭代训练，以增强监督的多样性。此外，我们还引入了一种自我反思式辅助任务，通过对比错误的推理模式来鼓励学习正确的推理模式。在流行的VLN基准测试中的实验结果表明，EvolveNav优于之前的基于LLM的VLN方法。代码可在https://github.com/expectorlin/EvolveNav获取。

> Building Vision-Language Navigation (VLN) agents which can navigate following natural language instructions is a long-standing goal in human-robot interaction applications. Recent studies have revealed the potential of training open-source Large Language Models (LLMs) to unleash LLMs' reasoning ability for improving navigation, and simultaneously mitigate the domain gap between LLMs' training corpus and the VLN task. However, these approaches primarily adopt direct input-output mapping paradigms, causing the mapping learning difficult and the navigational decisions unexplainable. Chain-of-Thought (CoT) training is a promising way to improve both navigational decision accuracy and interpretability, while the complexity of the navigation task makes the perfect CoT labels unavailable and may lead to overfitting through pure CoT supervised fine-tuning. In this paper, we propose a novel sElf-improving embodied reasoning framework for boosting LLM-based vision-language Navigation, dubbed EvolveNav. Our EvolveNav consists of two stages: (1) Formalized CoT Supervised Fine-Tuning, where we train the model with formalized CoT labels to both activate the model's navigational reasoning capabilities and increase the reasoning speed; (2) Self-Reflective Post-Training, where the model is iteratively trained with its own reasoning outputs as self-enriched CoT labels to enhance the supervision diversity. A self-reflective auxiliary task is also introduced to encourage learning correct reasoning patterns by contrasting with wrong ones. Experimental results on the popular VLN benchmarks demonstrate the superiority of EvolveNav over previous LLM-based VLN approaches. Code is available at https://github.com/expectorlin/EvolveNav.

[Arxiv](https://arxiv.org/abs/2506.01551)