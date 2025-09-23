# 句法之音：面向言语病理学的语言模型微调与综合评测

发布时间：2025年09月20日

`LLM应用` `医疗健康`

> The Sound of Syntax: Finetuning and Comprehensive Evaluation of Language Models for Speech Pathology

# 摘要

> 据美国国立卫生研究院统计，超340万儿童存在需要临床干预的言语障碍。而言语语言病理学家（SLPs）的数量仅为患病儿童的1/20，这凸显了儿童康复护理的巨大缺口，亟需借助技术手段提升SLP的工作效率。尽管最先进的多模态语言模型（MLMs）为支持SLP提供了潜力，但由于对其在高风险临床场景中的表现缺乏深入了解，其实际应用仍处于探索阶段。为填补这一空白，我们与领域专家合作，构建了多模态语言模型在言语语言病理学中的实际应用场景分类体系。基于该分类体系，我们首次提出了一个全面的基准，用于评估多模态语言模型在五个核心应用场景中的表现，每个场景均包含1000个人工标注的数据样本。该基准还包含不同场景下的鲁棒性和敏感性测试，如背景噪音、说话人性别及口音等变量。我们对15个最先进的多模态语言模型进行评估后发现，没有任何一个模型能在所有任务中持续领先。值得注意的是，我们发现模型存在系统性表现差异——对男性说话人的识别效果更佳；同时观察到，在标签空间大且决策边界狭窄的分类任务中，思维链提示反而会降低模型性能。此外，我们通过在特定领域数据上微调多模态语言模型，使其性能较基础模型提升了30%以上。这些发现既展现了当前多模态语言模型在言语语言病理学应用中的潜力，也揭示了其局限性，强调了进一步研究和针对性开发的重要性。

> According to the U.S. National Institutes of Health, more than 3.4 million children experience speech disorders that require clinical intervention. The number of speech-language pathologists (SLPs) is roughly 20 times fewer than the number of affected children, highlighting a significant gap in children's care and a pressing need for technological support that improves the productivity of SLPs. State-of-the-art multimodal language models (MLMs) show promise for supporting SLPs, but their use remains underexplored largely due to a limited understanding of their performance in high-stakes clinical settings. To address this gap, we collaborate with domain experts to develop a taxonomy of real-world use cases of MLMs in speech-language pathologies. Building on this taxonomy, we introduce the first comprehensive benchmark for evaluating MLM across five core use cases, each containing 1,000 manually annotated data points. This benchmark includes robustness and sensitivity tests under various settings, including background noise, speaker gender, and accent. Our evaluation of 15 state-of-the-art MLMs reveals that no single model consistently outperforms others across all tasks. Notably, we find systematic disparities, with models performing better on male speakers, and observe that chain-of-thought prompting can degrade performance on classification tasks with large label spaces and narrow decision boundaries. Furthermore, we study fine-tuning MLMs on domain-specific data, achieving improvements of over 30% compared to base models. These findings highlight both the potential and limitations of current MLMs for speech-language pathology applications, underscoring the need for further research and targeted development.

[Arxiv](https://arxiv.org/abs/2509.16765)