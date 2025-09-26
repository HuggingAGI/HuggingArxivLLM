# 合成数据在多语言多文化人工智能系统中的作用：印度语言的经验启示

发布时间：2025年09月25日

`LLM应用` `基础理论`

> The role of synthetic data in Multilingual, Multi-cultural AI systems: Lessons from Indic Languages

# 摘要

> 开发既能跨语言高效运行又兼具文化适应性的AI系统，一直是个长期难题，在低资源场景下尤为突出。合成数据为此提供了潜在解决方案，但它在多语言、多元文化场景中的实际效果尚未得到充分研究。为此，我们针对印度语言，研究了合成文化语境化数据集的构建方法及其影响。我们采用自下而上的生成策略，通过提示大型开源LLM（参数≥2350亿）以特定语言的维基百科内容为基础生成数据。这一方法与主流的“自上而下”范式形成互补——后者通常是将英语等资源丰富语言的合成数据集翻译而来。我们发布了Updesh——一个高质量、大规模的合成指令遵循数据集，涵盖13种印度语言，包含950万个数据点。该数据集覆盖多样化的推理与生成任务，重点关注长上下文、多轮对话能力，以及与印度文化背景的贴合度。我们通过结合自动化指标与1万次人工标注的综合评估发现，生成数据质量优异，但人工评估也揭示了一些有待改进的方向。此外，我们还通过在该数据集上微调模型，并在15个多样化的多语言数据集上进行评估，开展了下游任务测试。结果显示，在Updesh上训练的模型在生成任务中持续取得显著提升，在选择题式NLU任务中也保持竞争力。值得注意的是，低资源和中资源语言的相对提升最为显著，缩小了它们与高资源语言的差距。这些发现为“构建高效多语言AI需采用多维度的数据构建与生成策略，并融入情境感知、文化根植的方法”提供了实证支持。

> Developing AI systems that operate effectively across languages while remaining culturally grounded is a long-standing challenge, particularly in low-resource settings. Synthetic data provides a promising avenue, yet its effectiveness in multilingual and multicultural contexts remains underexplored. We investigate the creation and impact of synthetic, culturally contextualized datasets for Indian languages through a bottom-up generation strategy that prompts large open-source LLMs (>= 235B parameters) to ground data generation in language-specific Wikipedia content. This approach complements the dominant top-down paradigm of translating synthetic datasets from high-resource languages such as English. We introduce Updesh, a high-quality large-scale synthetic instruction-following dataset comprising 9.5M data points across 13 Indian languages, encompassing diverse reasoning and generative tasks with an emphasis on long-context, multi-turn capabilities, and alignment with Indian cultural contexts. A comprehensive evaluation incorporating both automated metrics and human annotation across 10k assessments indicates that generated data is high quality; though, human evaluation highlights areas for further improvement. Additionally, we perform downstream evaluations by fine-tuning models on our dataset and assessing the performance across 15 diverse multilingual datasets. Models trained on Updesh consistently achieve significant gains on generative tasks and remain competitive on multiple-choice style NLU tasks. Notably, relative improvements are most pronounced in low and medium-resource languages, narrowing their gap with high-resource languages. These findings provide empirical evidence that effective multilingual AI requires multi-faceted data curation and generation strategies that incorporate context-aware, culturally grounded methodologies.

[Arxiv](https://arxiv.org/abs/2509.21294)