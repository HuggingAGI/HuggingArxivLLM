# 从输入到输出的完整视觉分词器微调流程

发布时间：2025年05月15日

`LLM应用` `计算机视觉`

> End-to-End Vision Tokenizer Tuning

# 摘要

> 现有的视觉分词方法孤立地优化视觉分词器，与下游训练过程脱节，假设视觉分词能够很好地泛化到图像生成和视觉问答等任务。然而，针对低级别重建优化的视觉分词器对多样化表征和语义需求的下游任务缺乏感知。这种解耦范式导致关键不匹配问题：视觉分词的损失可能成为目标任务的瓶颈。例如，图像文本分词错误会导致识别或生成结果不佳。为解决此问题，我们提出ETT，一种端到端视觉分词器调优方法，实现视觉分词与目标自回归任务的联合优化。与仅使用冻结视觉分词器离散索引的自回归模型不同，ETT利用分词器代码本的视觉嵌入，通过重建和描述目标对视觉分词器进行端到端优化。ETT可无缝集成到现有训练流程中，仅需极小架构修改。我们的ETT易于实现和集成，无需调整大型语言模型的原始代码本或架构。大量实验表明，端到端视觉分词器调优方法显著提升了性能，即在多模态理解和视觉生成任务上相比冻结分词器基线提升了2-6%，同时保留了原始重建能力。我们希望这一简单而强大的方法不仅能赋能图像生成和理解，还能增强多模态基础模型的能力。


> Existing vision tokenization isolates the optimization of vision tokenizers from downstream training, implicitly assuming the visual tokens can generalize well across various tasks, e.g., image generation and visual question answering. The vision tokenizer optimized for low-level reconstruction is agnostic to downstream tasks requiring varied representations and semantics. This decoupled paradigm introduces a critical misalignment: The loss of the vision tokenization can be the representation bottleneck for target tasks. For example, errors in tokenizing text in a given image lead to poor results when recognizing or generating them. To address this, we propose ETT, an end-to-end vision tokenizer tuning approach that enables joint optimization between vision tokenization and target autoregressive tasks. Unlike prior autoregressive models that use only discrete indices from a frozen vision tokenizer, ETT leverages the visual embeddings of the tokenizer codebook, and optimizes the vision tokenizers end-to-end with both reconstruction and caption objectives. ETT can be seamlessly integrated into existing training pipelines with minimal architecture modifications. Our ETT is simple to implement and integrate, without the need to adjust the original codebooks or architectures of the employed large language models. Extensive experiments demonstrate that our proposed end-to-end vision tokenizer tuning unlocks significant performance gains, i.e., 2-6% for multimodal understanding and visual generation tasks compared to frozen tokenizer baselines, while preserving the original reconstruction capability. We hope this very simple and strong method can empower multimodal foundation models besides image generation and understanding.

[Arxiv](https://arxiv.org/abs/2505.10562)