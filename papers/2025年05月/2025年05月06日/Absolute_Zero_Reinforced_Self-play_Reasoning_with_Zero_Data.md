# 零数据强化自对弈推理：探索绝对零度的智能边界

发布时间：2025年05月06日

`LLM应用` `人工智能`

> Absolute Zero: Reinforced Self-play Reasoning with Zero Data

# 摘要

> 可验证奖励的强化学习（RLVR）通过直接利用基于结果的奖励，展现出提升大型语言模型推理能力的潜力。然而，当前基于零样本设置的RLVR方法虽然摆脱了对推理过程的人工标注监督，仍依赖于人工整理的问题和答案集合进行训练。高质量人工示例的匮乏，引发了对长期依赖人工监督可行性的担忧，这一问题在语言模型预训练领域已初现端倪。更进一步，在AI超越人类智能的未来设想中，人类提供的任务可能难以满足超智能系统的学习需求。为此，我们提出了一种全新的RLVR范式——Absolute Zero，让单一模型自主提出能最大化自身学习进度的任务，并通过解决这些任务来提升推理能力，完全摆脱对外部数据的依赖。在此基础上，我们开发了Absolute Zero Reasoner（AZR）系统，它通过内置的代码执行器，既可验证提出的代码推理任务，又能验证答案，作为统一的可验证奖励来源，引导开放且有依据的学习过程。值得注意的是，AZR在完全没有外部数据支持的情况下训练，却在编码和数学推理任务上达到了最优性能，超越了依赖数万个人工整理示例的现有零样本模型。此外，AZR展现出良好的通用性，能够有效应用于不同规模和各类模型。

> Reinforcement learning with verifiable rewards (RLVR) has shown promise in enhancing the reasoning capabilities of large language models by learning directly from outcome-based rewards. Recent RLVR works that operate under the zero setting avoid supervision in labeling the reasoning process, but still depend on manually curated collections of questions and answers for training. The scarcity of high-quality, human-produced examples raises concerns about the long-term scalability of relying on human supervision, a challenge already evident in the domain of language model pretraining. Furthermore, in a hypothetical future where AI surpasses human intelligence, tasks provided by humans may offer limited learning potential for a superintelligent system. To address these concerns, we propose a new RLVR paradigm called Absolute Zero, in which a single model learns to propose tasks that maximize its own learning progress and improves reasoning by solving them, without relying on any external data. Under this paradigm, we introduce the Absolute Zero Reasoner (AZR), a system that self-evolves its training curriculum and reasoning ability by using a code executor to both validate proposed code reasoning tasks and verify answers, serving as an unified source of verifiable reward to guide open-ended yet grounded learning. Despite being trained entirely without external data, AZR achieves overall SOTA performance on coding and mathematical reasoning tasks, outperforming existing zero-setting models that rely on tens of thousands of in-domain human-curated examples. Furthermore, we demonstrate that AZR can be effectively applied across different model scales and is compatible with various model classes.

[Arxiv](https://arxiv.org/abs/2505.03335)