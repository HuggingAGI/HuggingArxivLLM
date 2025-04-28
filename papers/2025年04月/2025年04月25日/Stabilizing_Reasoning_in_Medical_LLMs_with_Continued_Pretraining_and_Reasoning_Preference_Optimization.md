# 通过持续预训练和推理偏好优化策略，增强医疗LLMs的推理稳定性

发布时间：2025年04月25日

`LLM应用

理由：这篇论文主要讨论了大型语言模型在医学领域的应用，特别是针对日语医学领域的优化和改进。论文中提到了模型的微调过程、在特定基准测试中的表现以及模型的发布，这些都是关于LLM在具体领域中的应用和优化，因此归类为LLM应用。`

> Stabilizing Reasoning in Medical LLMs with Continued Pretraining and Reasoning Preference Optimization

# 摘要

> 大型语言模型 (LLMs) 在医学领域展现出潜力，但临床应用受到事实准确性、语言特定限制（如日语）以及在需要生成推理解释时可靠性的担忧所阻碍——这是建立信任的前提。本文介绍了Preferred-MedLLM-Qwen-72B，这是一个针对日语医学领域的720亿参数模型，旨在实现高准确性和稳定的推理能力。我们对Qwen2.5-72B基础模型采用了两阶段微调过程：首先，在一个全面的日语医学语料库上进行持续预训练 (CPT)，以灌输深厚的领域知识。其次，推理偏好优化 (RPO)，一种基于偏好的方法，增强了可靠推理路径的生成，同时保持高答案准确性。在日语医学考试基准测试 (IgakuQA) 上的评估显示，Preferred-MedLLM-Qwen-72B实现了最先进的性能（0.868准确率），超过了GPT-4o等强大的专有模型（0.866）。至关重要的是，与基线模型或仅使用CPT的模型在需要解释时表现出显著的准确性下降（在IgakuQA上分别下降11.5%和3.8%）不同，我们的模型在这些条件下保持了高准确性（0.868）。这凸显了RPO在稳定推理生成方面的有效性。这项工作强调了在优化准确性和可靠解释方面的双重重要性。我们发布了Preferred-MedLLM-Qwen-72B模型权重，以促进对高信任度LLMs在专业、高风险应用中的研究。

> Large Language Models (LLMs) show potential in medicine, yet clinical adoption is hindered by concerns over factual accuracy, language-specific limitations (e.g., Japanese), and critically, their reliability when required to generate reasoning explanations -- a prerequisite for trust. This paper introduces Preferred-MedLLM-Qwen-72B, a 72B-parameter model optimized for the Japanese medical domain to achieve both high accuracy and stable reasoning. We employ a two-stage fine-tuning process on the Qwen2.5-72B base model: first, Continued Pretraining (CPT) on a comprehensive Japanese medical corpus instills deep domain knowledge. Second, Reasoning Preference Optimization (RPO), a preference-based method, enhances the generation of reliable reasoning pathways while preserving high answer accuracy. Evaluations on the Japanese Medical Licensing Exam benchmark (IgakuQA) show Preferred-MedLLM-Qwen-72B achieves state-of-the-art performance (0.868 accuracy), surpassing strong proprietary models like GPT-4o (0.866). Crucially, unlike baseline or CPT-only models which exhibit significant accuracy degradation (up to 11.5\% and 3.8\% respectively on IgakuQA) when prompted for explanations, our model maintains its high accuracy (0.868) under such conditions. This highlights RPO's effectiveness in stabilizing reasoning generation. This work underscores the importance of optimizing for reliable explanations alongside accuracy. We release the Preferred-MedLLM-Qwen-72B model weights to foster research into trustworthy LLMs for specialized, high-stakes applications.

[Arxiv](https://arxiv.org/abs/2504.18080)