# 合成视觉：训练视觉语言模型来理解物理学

发布时间：2024年12月11日

`LLM应用` `视觉语言模型`

> Synthetic Vision: Training Vision-Language Models to Understand Physics

# 摘要

> 物理推理，即对动态环境中物体行为的阐释、理解与预测，对于当下的视觉语言模型（VLMs）而言，依旧是一项重大挑战。在本研究中，我们提出了两种借助模拟数据增强 VLMs 物理推理能力的方法。其一，利用与物理推理任务相关的模拟生成的问答（QA）对，对预训练的 VLM 进行微调。其二，引入物理上下文构建器（PCBs），这是专门经过微调的 VLMs，用于生成富含物理属性和过程的场景描述。在物理推理任务中，这些 PCBs 可用作上下文，辅助大型语言模型（LLM）提升性能。我们通过多个基准来评估这两种方法，其中包括一个新的名为“倒塌塔”的稳定性检测 QA 数据集，它涵盖了模拟和真实世界的场景，还有 CLEVRER。我们证明，经过微调的小型 QA VLM 能显著优于更大的先进基础模型。同时，我们也表明整合 PCBs 能提高基础 LLM 在物理推理任务上的表现。利用“倒塌塔”数据集中的真实世界场景，我们还验证了这两种方法在 Sim2Real 迁移中的稳健性。我们的研究结果凸显了模拟数据在创建具备高级物理推理能力的学习系统中的作用。

> Physical reasoning, which involves the interpretation, understanding, and prediction of object behavior in dynamic environments, remains a significant challenge for current Vision-Language Models (VLMs). In this work, we propose two methods to enhance VLMs' physical reasoning capabilities using simulated data. First, we fine-tune a pre-trained VLM using question-answer (QA) pairs generated from simulations relevant to physical reasoning tasks. Second, we introduce Physics Context Builders (PCBs), specialized VLMs fine-tuned to create scene descriptions enriched with physical properties and processes. During physical reasoning tasks, these PCBs can be leveraged as context to assist a Large Language Model (LLM) to improve its performance. We evaluate both of our approaches using multiple benchmarks, including a new stability detection QA dataset called Falling Tower, which includes both simulated and real-world scenes, and CLEVRER. We demonstrate that a small QA fine-tuned VLM can significantly outperform larger state-of-the-art foundational models. We also show that integrating PCBs boosts the performance of foundational LLMs on physical reasoning tasks. Using the real-world scenes from the Falling Tower dataset, we also validate the robustness of both approaches in Sim2Real transfer. Our results highlight the utility that simulated data can have in the creation of learning systems capable of advanced physical reasoning.

[Arxiv](https://arxiv.org/abs/2412.08619)