# # 医学视觉-语言模型发展现状：全面基准测试研究

发布时间：2025年07月15日

`LLM应用` `计算机视觉`

> How Far Have Medical Vision-Language Models Come? A Comprehensive Benchmarking Study

# 摘要

> 视觉-语言模型（VLMs）在自然图像任务中表现出色，并逐渐被应用于医疗领域。然而，它们在医学任务中的能力仍有待深入研究。我们对开源的通用型和医疗专业型VLMs进行了全面评估，覆盖了从3B到72B参数规模的模型，并在MedXpert、OmniMedVQA、PMC-VQA、PathVQA、MMMU、SLAKE 和 VQA-RAD等多个基准测试中进行对比。为了全面观察模型性能，我们将评估分解为理解和推理两个部分。研究发现：首先，大型通用型模型已经在多个基准测试中与医疗专业型模型相匹配或超越，展现出从自然图像到医学图像的强零样本迁移能力。其次，推理性能普遍低于理解性能，突显了安全决策支持的关键障碍。第三，不同基准测试中的性能差异显著，反映了任务设计、标注质量和知识需求的差异。目前还没有模型达到临床部署所需的可靠性阈值，这强调了需要更强大的多模态对齐以及更严格、更细致的评估协议。

> Vision-Language Models (VLMs) trained on web-scale corpora excel at natural image tasks and are increasingly repurposed for healthcare; however, their competence in medical tasks remains underexplored. We present a comprehensive evaluation of open-source general-purpose and medically specialised VLMs, ranging from 3B to 72B parameters, across eight benchmarks: MedXpert, OmniMedVQA, PMC-VQA, PathVQA, MMMU, SLAKE, and VQA-RAD. To observe model performance across different aspects, we first separate it into understanding and reasoning components. Three salient findings emerge. First, large general-purpose models already match or surpass medical-specific counterparts on several benchmarks, demonstrating strong zero-shot transfer from natural to medical images. Second, reasoning performance is consistently lower than understanding, highlighting a critical barrier to safe decision support. Third, performance varies widely across benchmarks, reflecting differences in task design, annotation quality, and knowledge demands. No model yet reaches the reliability threshold for clinical deployment, underscoring the need for stronger multimodal alignment and more rigorous, fine-grained evaluation protocols.

[Arxiv](https://arxiv.org/abs/2507.11200)