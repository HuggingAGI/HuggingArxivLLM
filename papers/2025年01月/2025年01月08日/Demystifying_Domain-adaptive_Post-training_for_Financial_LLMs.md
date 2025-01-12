# 解密金融LLM的领域自适应后训练

发布时间：2025年01月08日

`LLM应用

理由：这篇论文主要讨论了在金融领域中对大型语言模型（LLMs）进行领域自适应后训练的方法和策略。具体来说，它提出了一个名为FINDAP的系统性研究，旨在优化LLMs在金融领域的表现。论文涉及了持续预训练、指令微调和偏好对齐等关键后训练阶段，并开发了一个名为Llama-Fin的模型。这些内容都属于LLM在实际应用中的优化和调整，因此应归类为“LLM应用”。` `语言模型`

> Demystifying Domain-adaptive Post-training for Financial LLMs

# 摘要

> # 摘要
领域自适应后训练（Domain-adaptive post-training）已成为医学和金融等专业领域大型语言模型（LLMs）的有力工具。然而，如何在不同数据和模型配置下找到最佳适应标准和训练策略仍是一大挑战。为此，我们推出了FINDAP，这是一个针对金融领域LLMs领域自适应后训练的系统性研究。我们首先识别目标领域的核心能力，并设计了一套全面的评估体系。接着，我们分析了持续预训练、指令微调和偏好对齐等关键后训练阶段的效果。基于这些发现，我们提出了一种以新颖的偏好数据蒸馏方法为核心的有效训练方案，该方法利用了生成奖励模型的过程信号。最终，我们开发的Llama-Fin模型在多种金融任务中表现卓越。我们的研究还揭示了每个后训练阶段如何提升不同能力，并提供了应对具体挑战的有效解决方案，为LLMs的领域适应提供了宝贵经验。项目页面：https://github.com/SalesforceAIResearch/FinDap

> Domain-adaptive post-training of large language models (LLMs) has emerged as a promising approach for specialized domains such as medicine and finance. However, significant challenges remain in identifying optimal adaptation criteria and training strategies across varying data and model configurations. To address these challenges, we introduce FINDAP, a systematic and fine-grained investigation into domain-adaptive post-training of LLMs for the finance domain. Our approach begins by identifying the core capabilities required for the target domain and designing a comprehensive evaluation suite aligned with these needs. We then analyze the effectiveness of key post-training stages, including continual pretraining, instruction tuning, and preference alignment. Building on these insights, we propose an effective training recipe centered on a novel preference data distillation method, which leverages process signals from a generative reward model. The resulting model, Llama-Fin, achieves state-of-the-art performance across a wide range of financial tasks. Our analysis also highlights how each post-training stage contributes to distinct capabilities, uncovering specific challenges and effective solutions, providing valuable insights for domain adaptation of LLMs. Project page: https://github.com/SalesforceAIResearch/FinDap

[Arxiv](https://arxiv.org/abs/2501.04961)