# COUNTS：目标检测器与多模态大语言模型在分布变化下的基准测试

发布时间：2025年04月14日

`LLM应用` `计算机视觉` `人工智能`

> COUNTS: Benchmarking Object Detectors and Multimodal Large Language Models under Distribution Shifts

# 摘要

> 当前目标检测器在现实应用中常常会因分布偏移而导致性能显著下降，因此目标检测器的域外（OOD）泛化能力逐渐引起了研究者的广泛关注。尽管如此，目前仍缺乏一个大规模、全面且带有细粒度标注的数据集和评估基准，用于评估目标检测和定位等更复杂任务的OOD泛化能力。为了解决这一问题，我们引入了COUNTS，这是一个带有对象级标注的大规模OOD数据集，包含了14种自然分布偏移，超过222,000个样本，以及超过1,196,000个标注边界框。基于COUNTS，我们提出了两个全新的基准测试：O(OD)2和OODG。O(OD)2旨在通过控制训练数据与测试数据之间的分布偏移，全面评估目标检测器的OOD泛化能力。而OODG的目标则是评估多模态大语言模型（MLLMs）在域外环境下的定位能力。我们的研究发现，尽管大型模型和丰富的预训练数据在同分布（IID）场景下显著提升了性能，但对于目标检测器和MLLMs而言，在OOD场景下仍存在显著的局限性，同时也带来了改进的机会。在视觉定位任务中，即使是最先进的GPT-4o和Gemini-1.5也只能分别达到56.7%和28.0%的准确率。我们希望COUNTS能够推动健壮目标检测器和MLLMs的发展与评估，使它们在分布偏移的情况下仍能保持高性能。

> Current object detectors often suffer significant perfor-mance degradation in real-world applications when encountering distributional shifts. Consequently, the out-of-distribution (OOD) generalization capability of object detectors has garnered increasing attention from researchers. Despite this growing interest, there remains a lack of a large-scale, comprehensive dataset and evaluation benchmark with fine-grained annotations tailored to assess the OOD generalization on more intricate tasks like object detection and grounding. To address this gap, we introduce COUNTS, a large-scale OOD dataset with object-level annotations. COUNTS encompasses 14 natural distributional shifts, over 222K samples, and more than 1,196K labeled bounding boxes. Leveraging COUNTS, we introduce two novel benchmarks: O(OD)2 and OODG. O(OD)2 is designed to comprehensively evaluate the OOD generalization capabilities of object detectors by utilizing controlled distribution shifts between training and testing data. OODG, on the other hand, aims to assess the OOD generalization of grounding abilities in multimodal large language models (MLLMs). Our findings reveal that, while large models and extensive pre-training data substantially en hance performance in in-distribution (IID) scenarios, significant limitations and opportunities for improvement persist in OOD contexts for both object detectors and MLLMs. In visual grounding tasks, even the advanced GPT-4o and Gemini-1.5 only achieve 56.7% and 28.0% accuracy, respectively. We hope COUNTS facilitates advancements in the development and assessment of robust object detectors and MLLMs capable of maintaining high performance under distributional shifts.

[Arxiv](https://arxiv.org/abs/2504.10158)