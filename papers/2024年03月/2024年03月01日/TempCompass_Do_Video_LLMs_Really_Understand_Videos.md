# TempCompass——探究视频 LLM 是否真正具备理解视频内容的能力。

发布时间：2024年03月01日

`LLM应用`

> TempCompass: Do Video LLMs Really Understand Videos?

# 摘要

> 随着 Video LLMs 的研究热度高涨，近期发现现有基准对于此类模型的时间感知能力评价并不全面。一方面，多数基准未能区分速度、方向等不同时间维度，导致模型在具体时间层面的微妙表现难以准确衡量；另一方面，由于任务形式单一（如仅限多选问答），阻碍了深入探究模型在不同任务类型中的时间感知性能差异。为此，我们推出了名为 \textbf{TempCompass} 的新基准，囊括多样化的时序维度与任务格式。为确保评测数据质量，我们创新采用了两个策略：(1) 收集视频时，构造具有相同静态内容但在某一特定时间属性上相冲突的视频，从而消除 Video LLMs 对单帧画面或语言预设的依赖；(2) 创新任务指令生成方式，先由人类为视频标注元信息，再通过 LLM 自动生成指令。此外，我们设计了一种基于 LLM 的自动化精准评估方案，用于评判 Video LLMs 的输出结果。基于 TempCompass，我们对 8 款前沿 Video LLMs 及 3 款 Image LLMs 进行了全面评估，揭示出一个令人惊讶的现象——这些模型普遍存在时间感知能力较弱的问题。相关数据资源可访问网址 \url{https://github.com/llyx97/TempCompass} 获取。

> Recently, there is a surge in interest surrounding video large language models (Video LLMs). However, existing benchmarks fail to provide a comprehensive feedback on the temporal perception ability of Video LLMs. On the one hand, most of them are unable to distinguish between different temporal aspects (e.g., speed, direction) and thus cannot reflect the nuanced performance on these specific aspects. On the other hand, they are limited in the diversity of task formats (e.g., only multi-choice QA), which hinders the understanding of how temporal perception performance may vary across different types of tasks. Motivated by these two problems, we propose the \textbf{TempCompass} benchmark, which introduces a diversity of temporal aspects and task formats. To collect high-quality test data, we devise two novel strategies: (1) In video collection, we construct conflicting videos that share the same static content but differ in a specific temporal aspect, which prevents Video LLMs from leveraging single-frame bias or language priors. (2) To collect the task instructions, we propose a paradigm where humans first annotate meta-information for a video and then an LLM generates the instruction. We also design an LLM-based approach to automatically and accurately evaluate the responses from Video LLMs. Based on TempCompass, we comprehensively evaluate 8 state-of-the-art (SOTA) Video LLMs and 3 Image LLMs, and reveal the discerning fact that these models exhibit notably poor temporal perception ability. Our data will be available at \url{https://github.com/llyx97/TempCompass}.

[Arxiv](https://arxiv.org/abs/2403.00476)