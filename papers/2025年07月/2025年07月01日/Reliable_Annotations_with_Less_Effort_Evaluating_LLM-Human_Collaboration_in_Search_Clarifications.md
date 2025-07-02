# 可靠标注，事半功倍：探索 LLM 与人类协作在搜索澄清中的表现

发布时间：2025年07月01日

`LLM应用` `数据标注` `自动标注`

> Reliable Annotations with Less Effort: Evaluating LLM-Human Collaboration in Search Clarifications

# 摘要

> 尽管大型语言模型（LLMs）在自动标注领域的热度持续升温，但其在复杂、细致且多维度的标注任务中的表现仍有待深入探索。本研究专注于搜索澄清任务的标注工作，借助一个高质量且多维度的数据集，该数据集涵盖了五个独特的细粒度标注子任务。尽管LLMs在通用场景下展现出了令人瞩目的能力，但我们的研究发现，即使是当前最先进的模型，在面对主观或细粒度评估任务时，也难以达到人类水平的表现。通过系统性评估，我们发现LLM的预测结果往往存在不一致、校准不佳以及对提示变化高度敏感等问题。为了解决这些局限性，我们提出了一种简单而有效的“人机协作”（HITL）工作流，通过设置置信度阈值和利用模型间分歧，有选择性地引入人工审核环节。研究结果表明，这一轻量级干预措施不仅显著提升了标注可靠性，还将人工 effort 减少高达45%，为在实际评估场景中部署LLMs提供了一条相对可扩展、经济高效且准确的路径。

> Despite growing interest in using large language models (LLMs) to automate annotation, their effectiveness in complex, nuanced, and multi-dimensional labelling tasks remains relatively underexplored. This study focuses on annotation for the search clarification task, leveraging a high-quality, multi-dimensional dataset that includes five distinct fine-grained annotation subtasks. Although LLMs have shown impressive capabilities in general settings, our study reveals that even state-of-the-art models struggle to replicate human-level performance in subjective or fine-grained evaluation tasks. Through a systematic assessment, we demonstrate that LLM predictions are often inconsistent, poorly calibrated, and highly sensitive to prompt variations. To address these limitations, we propose a simple yet effective human-in-the-loop (HITL) workflow that uses confidence thresholds and inter-model disagreement to selectively involve human review. Our findings show that this lightweight intervention significantly improves annotation reliability while reducing human effort by up to 45%, offering a relatively scalable and cost-effective yet accurate path forward for deploying LLMs in real-world evaluation settings.

[Arxiv](https://arxiv.org/abs/2507.00543)