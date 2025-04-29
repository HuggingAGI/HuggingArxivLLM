# m-KAILIN：知识驱动的智能科学语料蒸馏框架，专为生物医学大型语言模型训练而设计

发布时间：2025年04月28日

`Agent` `生物医学` `人工智能`

> m-KAILIN: Knowledge-Driven Agentic Scientific Corpus Distillation Framework for Biomedical Large Language Models Training

# 摘要

> 大型语言模型 (LLMs) 在生物医学研究中的快速发展凸显了现有开源标注科学语料库的局限性，这些语料库通常在数量和质量上都难以满足需求。针对生物医学知识复杂层级带来的挑战，我们提出了一种知识驱动的多智能体框架，专门用于 LLM 生物医学领域训练的科学语料蒸馏。我们的方法核心是一个协作式多智能体架构，其中每个智能体都遵循医学主题词 (MeSH) 分类体系，协同工作以从海量科学文献中自主提取、合成和自我评估高质量文本数据。这些智能体共同生成并优化领域特定的问题-答案对，确保全面覆盖并符合生物医学本体，同时大幅减少人工干预。大量实验结果表明，基于我们多智能体蒸馏数据集训练的语言模型在生物医学问答任务中取得了显著提升，超越了强大的生命科学 LLM 基线模型和先进的专有模型。值得注意的是，我们的 AI-Ready 数据集使 Llama3-70B 在 MedPrompt 和 Med-PaLM-2 的对比下表现更优，尽管其规模较小。详细的消融研究和案例分析进一步验证了框架内每个智能体的有效性和协同作用，凸显了多智能体协作在生物医学 LLM 训练中的潜力。

> The rapid progress of large language models (LLMs) in biomedical research has underscored the limitations of existing open-source annotated scientific corpora, which are often insufficient in quantity and quality. Addressing the challenge posed by the complex hierarchy of biomedical knowledge, we propose a knowledge-driven, multi-agent framework for scientific corpus distillation tailored for LLM training in the biomedical domain. Central to our approach is a collaborative multi-agent architecture, where specialized agents, each guided by the Medical Subject Headings (MeSH) hierarchy, work in concert to autonomously extract, synthesize, and self-evaluate high-quality textual data from vast scientific literature. These agents collectively generate and refine domain-specific question-answer pairs, ensuring comprehensive coverage and consistency with biomedical ontologies while minimizing manual involvement. Extensive experimental results show that language models trained on our multi-agent distilled datasets achieve notable improvements in biomedical question-answering tasks, outperforming both strong life sciences LLM baselines and advanced proprietary models. Notably, our AI-Ready dataset enables Llama3-70B to surpass GPT-4 with MedPrompt and Med-PaLM-2, despite their larger scale. Detailed ablation studies and case analyses further validate the effectiveness and synergy of each agent within the framework, highlighting the potential of multi-agent collaboration in biomedical LLM training.

[Arxiv](https://arxiv.org/abs/2504.19565)