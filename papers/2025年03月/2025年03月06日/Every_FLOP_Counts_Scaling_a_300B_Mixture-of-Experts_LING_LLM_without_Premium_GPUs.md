# 每个计算都至关重要：无需高端 GPU，轻松扩展 3000 亿参数专家混合 LING 大语言模型

发布时间：2025年03月06日

`LLM理论

理由：这篇论文主要探讨了大规模专家混合模型（MoE）在训练中的挑战，并提出创新方法优化模型架构和训练流程，属于LLM的理论和技术层面研究。` `人工智能` `知识图谱`

> Every FLOP Counts: Scaling a 300B Mixture-of-Experts LING LLM without Premium GPUs

# 摘要

> 本技术报告聚焦于大规模专家混合模型（MoE）训练中的挑战，致力于突破成本低效与资源限制的瓶颈。我们推出了两种不同规模的MoE大型语言模型（LLMs）：Ling-Lite（168亿参数，27.5亿激活参数）与Ling-Plus（2900亿参数，288亿激活参数），中文名为“百灵”。这两个模型的性能均与行业领先基准相当。报告为资源受限环境下的AI开发提供实用见解，推动技术的可扩展与可持续发展。我们提出了三项创新方法：优化模型架构与训练流程、完善训练异常处理、提升模型评估效率。借助知识图谱生成的高质量数据，我们的模型在工具使用能力上表现更优。实验结果显示，3000亿参数的MoE LLM可在低性能设备上训练，性能与同规模模型相当，且计算成本降低约20%。模型访问地址：https://huggingface.co/inclusionAI。

> In this technical report, we tackle the challenges of training large-scale Mixture of Experts (MoE) models, focusing on overcoming cost inefficiency and resource limitations prevalent in such systems. To address these issues, we present two differently sized MoE large language models (LLMs), namely Ling-Lite and Ling-Plus (referred to as "Bailing" in Chinese, spelled Bǎilíng in Pinyin). Ling-Lite contains 16.8 billion parameters with 2.75 billion activated parameters, while Ling-Plus boasts 290 billion parameters with 28.8 billion activated parameters. Both models exhibit comparable performance to leading industry benchmarks. This report offers actionable insights to improve the efficiency and accessibility of AI development in resource-constrained settings, promoting more scalable and sustainable technologies. Specifically, to reduce training costs for large-scale MoE models, we propose innovative methods for (1) optimization of model architecture and training processes, (2) refinement of training anomaly handling, and (3) enhancement of model evaluation efficiency. Additionally, leveraging high-quality data generated from knowledge graphs, our models demonstrate superior capabilities in tool use compared to other models. Ultimately, our experimental findings demonstrate that a 300B MoE LLM can be effectively trained on lower-performance devices while achieving comparable performance to models of a similar scale, including dense and MoE models. Compared to high-performance devices, utilizing a lower-specification hardware system during the pre-training phase demonstrates significant cost savings, reducing computing costs by approximately 20%. The models can be accessed at https://huggingface.co/inclusionAI.

[Arxiv](https://arxiv.org/abs/2503.05139)