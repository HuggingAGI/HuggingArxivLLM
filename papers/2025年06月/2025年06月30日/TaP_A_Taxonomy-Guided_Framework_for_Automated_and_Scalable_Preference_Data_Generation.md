# # TaP：基于分类学的自动化偏好数据生成框架

发布时间：2025年06月30日

`LLM应用` `数据科学`

> TaP: A Taxonomy-Guided Framework for Automated and Scalable Preference Data Generation

# 摘要

> 在大型语言模型（LLMs）上进行监督微调和偏好微调，需要高质量的数据集来提升模型遵循指令和与人类偏好及价值观保持一致的能力。然而，构建这样的数据集资源消耗巨大，且大多数现有的监督和偏好微调数据集都是英文的。为了解决这些问题，我们提出了基于分类学的TaP框架，用于自动化和规模化地构建多语言偏好数据集。TaP框架基于结构化的分类学，能够精细控制数据集的组成，从而确保多样性和全面覆盖。我们使用TaP生成的数据集对多个LLM进行监督和偏好微调。实验结果表明，使用TaP生成的数据集训练的LLM优于使用现有开源数据集训练的模型。值得注意的是，即使在数据量大得多的开源数据集上，使用TaP生成的数据集训练的LLM也表现更优。

> Conducting supervised fine-tuning and preference fine-tuning on large language models (LLMs) requires high-quality datasets to improve their ability to follow instructions and align with human preferences and values. However, constructing such datasets is resource-intensive, and most available datasets for supervised and preference fine-tuning are in English. To address these challenges, we propose the \underline{\textbf{Ta}}xonomy-Guided \underline{\textbf{P}}reference Data Generation (TaP) framework, which facilitates automated and scalable construction of preference datasets across various languages. TaP is grounded in a structured taxonomy that allows fine-grained control over dataset composition, thereby ensuring both diversity and comprehensive coverage. We employ TaP-generated datasets to perform supervised and preference fine-tuning on various LLMs. Experimental results demonstrate that LLMs trained on TaP-generated datasets outperform those trained on existing open-source datasets. Remarkably, LLMs trained on TaP-generated datasets surpass the performance of those trained on an open-source dataset that is 180 times larger.

[Arxiv](https://arxiv.org/abs/2506.23979)