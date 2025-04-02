# GenPRM：通过生成式推理优化过程奖励模型的测试时间计算

发布时间：2025年04月01日

`LLM理论` `人工智能`

> GenPRM: Scaling Test-Time Compute of Process Reward Models via Generative Reasoning

# 摘要

> 大型语言模型（LLMs）的最新进展表明，将过程奖励模型（PRMs）作为验证器能够显著提升模型性能。然而，当前的PRMs在三个关键方面存在局限：(1)监督过程和泛化能力有限，(2)仅依赖标量值预测，未充分挖掘LLMs的生成潜力，(3)缺乏有效的测试计算扩展能力。针对这些问题，我们提出了生成式过程奖励模型GenPRM，它通过明确的链式思维（CoT）推理并结合代码验证，为每一步推理提供可靠的判断依据。为获取高质量的过程监督数据，我们创新性地提出了相对进度评估（RPE）方法，并构建了一个基于代码验证的推理依据合成框架。实验结果表明，GenPRM仅基于MATH数据集的2.3万训练数据，就在ProcessBench基准测试和多项数学推理任务中显著超越了现有PRMs。通过计算扩展，15亿参数的GenPRM超越了GPT-4o，而70亿参数的GenPRM在ProcessBench上更是超过了Qwen2.5-Math-PRM-72B。此外，GenPRM在作为策略模型精调的批评模型方面也表现出色。这项研究不仅确立了新的过程监督范式，还成功架起了LLMs中PRMs与批评模型之间的桥梁。我们的代码、模型和数据将在https://ryanliu112.github.io/GenPRM上公开发布。

> Recent advancements in Large Language Models (LLMs) have shown that it is promising to utilize Process Reward Models (PRMs) as verifiers to enhance the performance of LLMs. However, current PRMs face three key challenges: (1) limited process supervision and generalization capabilities, (2) dependence on scalar value prediction without leveraging the generative abilities of LLMs, and (3) inability to scale the test-time compute of PRMs. In this work, we introduce GenPRM, a generative process reward model that performs explicit Chain-of-Thought (CoT) reasoning with code verification before providing judgment for each reasoning step. To obtain high-quality process supervision labels and rationale data, we propose Relative Progress Estimation (RPE) and a rationale synthesis framework that incorporates code verification. Experimental results on ProcessBench and several mathematical reasoning tasks show that GenPRM significantly outperforms prior PRMs with only 23K training data from MATH dataset. Through test-time scaling, a 1.5B GenPRM outperforms GPT-4o, and a 7B GenPRM surpasses Qwen2.5-Math-PRM-72B on ProcessBench. Additionally, GenPRM demonstrates strong abilities to serve as a critic model for policy model refinement. This work establishes a new paradigm for process supervision that bridges the gap between PRMs and critic models in LLMs. Our code, model, and data will be available in https://ryanliu112.github.io/GenPRM.

[Arxiv](https://arxiv.org/abs/2504.00891)