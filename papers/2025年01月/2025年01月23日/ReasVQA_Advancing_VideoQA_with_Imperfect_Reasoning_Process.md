# ReasVQA: 利用不完美推理提升视频问答能力

发布时间：2025年01月23日

`LLM应用

**理由**：这篇论文主要讨论了如何利用多模态大语言模型（MLLMs）生成的推理过程来提升视频问答（VideoQA）模型的性能。该方法涉及推理生成、推理精炼和推理学习，最终通过多任务学习指导模型如何基于视频内容解释和回答问题。论文的核心在于应用大语言模型（LLM）来增强视频问答系统的性能，因此属于“LLM应用”类别。` `视频分析` `问答系统`

> ReasVQA: Advancing VideoQA with Imperfect Reasoning Process

# 摘要

> # 摘要
视频问答（VideoQA）是一项极具挑战的任务，要求模型深入理解视频中的复杂视觉与时间关系，以精准回答问题。本文提出	extbf{ReasVQA}（推理增强的视频问答），通过多模态大语言模型（MLLMs）生成的推理过程，显著提升VideoQA模型的性能。该方法分为三步：推理生成、推理精炼与推理学习。首先，借助额外的MLLMs生成详细推理过程，随后通过过滤步骤精炼推理，确保数据质量。最后，利用可能不完美的推理数据，通过多任务学习指导VideoQA模型如何基于视频内容解释与回答问题。我们在三大基准测试中评估ReasVQA，结果显示其在NExT-QA上提升+2.9，STAR上提升+7.3，IntentQA上提升+5.9，刷新了当前最佳性能。研究表明，将推理过程融入VideoQA具有显著的监督优势。进一步实验验证了方法的各个组件，包括不同骨干网络与MLLMs，再次凸显了这一简洁高效方法的优势。我们通过引入先进推理技术，为提升VideoQA性能提供了新思路，为该领域设定了新标杆。

> Video Question Answering (VideoQA) is a challenging task that requires understanding complex visual and temporal relationships within videos to answer questions accurately. In this work, we introduce \textbf{ReasVQA} (Reasoning-enhanced Video Question Answering), a novel approach that leverages reasoning processes generated by Multimodal Large Language Models (MLLMs) to improve the performance of VideoQA models. Our approach consists of three phases: reasoning generation, reasoning refinement, and learning from reasoning. First, we generate detailed reasoning processes using additional MLLMs, and second refine them via a filtering step to ensure data quality. Finally, we use the reasoning data, which might be in an imperfect form, to guide the VideoQA model via multi-task learning, on how to interpret and answer questions based on a given video. We evaluate ReasVQA on three popular benchmarks, and our results establish new state-of-the-art performance with significant improvements of +2.9 on NExT-QA, +7.3 on STAR, and +5.9 on IntentQA. Our findings demonstrate the supervising benefits of integrating reasoning processes into VideoQA. Further studies validate each component of our method, also with different backbones and MLLMs, and again highlight the advantages of this simple but effective method. We offer a new perspective on enhancing VideoQA performance by utilizing advanced reasoning techniques, setting a new benchmark in this research field.

[Arxiv](https://arxiv.org/abs/2501.13536)