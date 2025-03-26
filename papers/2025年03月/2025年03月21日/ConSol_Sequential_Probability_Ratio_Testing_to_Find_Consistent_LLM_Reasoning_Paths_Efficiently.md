# ConSol：高效利用序列概率比检验，寻找一致的LLM推理路径

发布时间：2025年03月21日

`LLM应用` `人工智能` `计算机科学`

> ConSol: Sequential Probability Ratio Testing to Find Consistent LLM Reasoning Paths Efficiently

# 摘要

> 近期，集成显式推理能力的大型语言模型（LLMs）取得了显著进展，例如 OpenAI 的 o3-mini、DeepSeek-R1 和 QWQ-32B。这些模型能够通过生成中间推理步骤，使更小型的模型也能解决复杂任务。然而，这种显式推理方法显著提升了计算成本，无论是经济成本还是环境成本。广受欢迎的自洽性方法进一步加剧了这一问题，因为它通过聚合多条推理路径来提升准确性，通常每项任务需要 40 到 64 个样本。尽管聚合方法有效降低了方差和偏差，但额外的采样在早期样本已具有一致性时往往会导致收益递减。为了解决这些低效问题，我们提出了一种基于序贯概率比检验（SPRT）的方法，能够在达到足够一致性后动态终止采样。我们针对 LLM 应用对 SPRT 参数进行了专门校准，确保其能够灵敏地检测分布模式。实验结果表明，引入 SPRT 能够显著提升 token 使用效率，在保持与自洽性方法相当的准确性的同时，大幅降低了计算成本。为了促进透明度并方便研究复现，我们已将实验中使用的源代码和数据集公开发布在我们的 GitHub 仓库：https://github.com/LiuzLab/consol，或可通过 PyPI 包管理器安装：pip install consol。我们希望这一资源能够支持进一步的研究，并鼓励基于我们工作的新型方法开发。

> Recent advancements in large language models (LLMs) integrating explicit reasoning, such as OpenAI's o3-mini, DeepSeek-R1, and QWQ-32B, enable smaller models to solve complex tasks by generating intermediate reasoning steps prior to providing answers. However, this approach significantly increases computational costs, both monetarily and environmentally. The widely-used self-consistency method further exacerbates these costs by aggregating multiple reasoning paths to improve accuracy, often requiring between 40 to 64 samples per task. Although aggregation effectively reduces variance and bias, additional sampling can lead to diminishing returns when early samples yield consistent results. To address inefficiencies, we propose leveraging Sequential Probability Ratio Testing (SPRT) to dynamically terminate sampling once sufficient consistency is achieved. We calibrate SPRT parameters specifically for LLM applications, accounting for sensitivity to detect the mode of the distribution. Our experiments demonstrate that incorporating SPRT significantly enhances token efficiency, achieving comparable accuracy to self-consistency methods but at a substantially reduced computational cost. To promote transparency and facilitate reproducibility, we have made the source code and datasets used in our experiments publicly available at our GitHub repository: https://github.com/LiuzLab/consol, or available as a PyPI package: pip install consol. We hope that this resource will support further research and encourage the development of new methods building upon our work.

[Arxiv](https://arxiv.org/abs/2503.17587)