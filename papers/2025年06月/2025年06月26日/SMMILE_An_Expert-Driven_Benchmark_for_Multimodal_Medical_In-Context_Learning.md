# SMMILE：一个由专家主导的多模态医学上下文学习基准评估

发布时间：2025年06月26日

`LLM应用` `多模态学习`

> SMMILE: An Expert-Driven Benchmark for Multimodal Medical In-Context Learning

# 摘要

> 尽管多模态上下文学习（ICL）在医学等领域具有巨大潜力，但目前仍处于探索不足的状态。临床医生在日常工作中经常遇到需要根据有限示例进行适应的多样化、专业性任务，例如从少量相关既往案例中汲取见解，或者在有限的鉴别诊断集中进行考量。尽管多模态大型语言模型（MLLMs）在医学视觉问答（VQA）方面已显示出进展，但它们从上下文中学习多模态任务的能力仍 largely unknown。我们引入了SMMILE，首个基于专家驱动的医学任务多模态ICL基准测试。11位医学专家整理了问题，每个问题包括一个多模态查询和作为任务演示的多模态上下文示例。SMMILE涵盖了111个问题（517个问题-图像-答案三元组），覆盖了6个医学专业和13种成像模态。我们进一步引入了SMMILE++，一个增强的变体，包含1038个排列问题。对15个MLLMs的全面评估表明，大多数模型在医学任务中的多模态ICL能力表现一般到较差。在开放式的评估中，与零-shot相比，ICL在SMMILE上平均仅带来8%的改进，在SMMILE++上为9.4%。我们观察到对无关上下文示例的易感性：即使一个噪声或无关的示例也可能导致性能下降高达9.5%。此外，示例顺序存在近期偏差，即将最相关的示例放在最后可以带来显著的性能提升，最高可达71%。我们的研究结果突显了当前MLLMs在从上下文学习多模态医学任务时所面临的关键限制和偏见。

> Multimodal in-context learning (ICL) remains underexplored despite significant potential for domains such as medicine. Clinicians routinely encounter diverse, specialized tasks requiring adaptation from limited examples, such as drawing insights from a few relevant prior cases or considering a constrained set of differential diagnoses. While multimodal large language models (MLLMs) have shown advances in medical visual question answering (VQA), their ability to learn multimodal tasks from context is largely unknown. We introduce SMMILE, the first expert-driven multimodal ICL benchmark for medical tasks. Eleven medical experts curated problems, each including a multimodal query and multimodal in-context examples as task demonstrations. SMMILE encompasses 111 problems (517 question-image-answer triplets) covering 6 medical specialties and 13 imaging modalities. We further introduce SMMILE++, an augmented variant with 1038 permuted problems. A comprehensive evaluation of 15 MLLMs demonstrates that most models exhibit moderate to poor multimodal ICL ability in medical tasks. In open-ended evaluations, ICL contributes only 8% average improvement over zero-shot on SMMILE and 9.4% on SMMILE++. We observe a susceptibility for irrelevant in-context examples: even a single noisy or irrelevant example can degrade performance by up to 9.5%. Moreover, example ordering exhibits a recency bias, i.e., placing the most relevant example last can lead to substantial performance improvements by up to 71%. Our findings highlight critical limitations and biases in current MLLMs when learning multimodal medical tasks from context.

[Arxiv](https://arxiv.org/abs/2506.21355)