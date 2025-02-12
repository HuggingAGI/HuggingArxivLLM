# LLMs：轻松掌握推理学习，结构才是关键！

发布时间：2025年02月11日

`LLM应用` `人工智能` `机器学习`

> LLMs Can Easily Learn to Reason from Demonstrations Structure, not content, is what matters!

# 摘要

> 大型推理模型（LRMs）通过长链式思考（Long CoT），包含反思、回溯和自我验证，来解决复杂推理问题。然而，如何有效激发长链式思考的能力，仍是一个未解之谜。本研究发现，大型语言模型（LLM）可通过数据高效的监督微调（SFT）和参数高效低秩适配（LoRA）学习长链式思考推理。仅需17k长链式思考训练样本，Qwen2.5-32B-Instruct模型在数学和编程基准测试中表现优异，AIME 2024达56.7%（+40.0%），LiveCodeBench达57.0%（+8.1%），媲美专有o1-preview模型的44.6%和59.1%。更重要的是，长链式思考的结构对学习至关重要，而单个推理步骤的内容影响甚微。内容上的扰动，如使用错误样本或移除关键词，对性能影响微乎其微。然而，打乱或删除推理步骤等破坏逻辑结构的修改，会显著降低准确性。例如，训练在错误答案样本上的模型，准确率仅下降3.2%。这些发现深化了我们对LLMs推理能力激发的理解，并为训练下一代推理模型提供了关键指导。这是我们在GitHub上开源的Sky-T1-32B-Preview模型的学术论文。代码可在https://github.com/NovaSky-AI/SkyThought获取。

> Large reasoning models (LRMs) tackle complex reasoning problems by following long chain-of-thoughts (Long CoT) that incorporate reflection, backtracking, and self-validation. However, the training techniques and data requirements to elicit Long CoT remain poorly understood. In this work, we find that a Large Language model (LLM) can effectively learn Long CoT reasoning through data-efficient supervised fine-tuning (SFT) and parameter-efficient low-rank adaptation (LoRA). With just 17k long CoT training samples, the Qwen2.5-32B-Instruct model achieves significant improvements on a wide range of math and coding benchmarks, including 56.7% (+40.0%) on AIME 2024 and 57.0% (+8.1%) on LiveCodeBench, competitive to the proprietary o1-preview model's score of 44.6% and 59.1%. More importantly, we find that the structure of Long CoT is critical to the learning process, whereas the content of individual reasoning steps has minimal impact. Perturbations affecting content, such as training on incorrect samples or removing reasoning keywords, have little impact on performance. In contrast, structural modifications that disrupt logical consistency in the Long CoT, such as shuffling or deleting reasoning steps, significantly degrade accuracy. For example, a model trained on Long CoT samples with incorrect answers still achieves only 3.2% lower accuracy compared to training with fully correct samples. These insights deepen our understanding of how to elicit reasoning capabilities in LLMs and highlight key considerations for efficiently training the next generation of reasoning models. This is the academic paper of our previous released Sky-T1-32B-Preview model. Codes are available at https://github.com/NovaSky-AI/SkyThought.

[Arxiv](https://arxiv.org/abs/2502.07374)