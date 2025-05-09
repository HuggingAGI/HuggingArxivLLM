# 大型语言模型的社交能力如何？多用户多轮社交任务基准测试

发布时间：2025年04月04日

`LLM应用` `社交代理` `社交互动`

> How Social is It? A Benchmark for LLMs' Capabilities in Multi-user Multi-turn Social Agent Tasks

# 摘要

> 将大型语言模型（LLMs）的应用从单纯的个人辅助工具扩展到复杂社会场景中的多用户、多轮社交代理任务，需要 LLMs 具备独立承担此类任务的能力。然而，目前尚缺乏系统性的基准测试来衡量这一能力。为此，我们首先引入了一个基于社会学原理的代理任务分级框架，并提出了一种新型基准测试——“它有多社交”（简称 HSII）。HSII 旨在全面评估 LLM 在复杂社交任务中的表现，并对代表性模型进行基准测试。

HSII 包含四个核心阶段：格式解析、目标选择、目标切换对话和稳定对话，这些阶段共同构成了一个完整的评估体系，用于测试 LLMs 在基于现实社会互动场景数据集（HSII-Dataset）中的沟通与任务完成能力。该数据集是逐步从新闻数据集中推导而来，我们通过对数据集进行聚类分析，开展了一项深入的消融研究。

此外，我们还深入探究了思维链（COT）方法对提升 LLMs 社交性能的影响。由于 COT 方法需要额外的计算资源，我们引入了一个新的统计指标——COT-复杂度，用于量化特定 LLMs 在使用 COT 时的效率，从而在正确性和效率之间找到更好的平衡点。实验结果表明，我们的基准测试体系能够很好地评估 LLMs 的社交能力，为相关研究提供了有力支持。

> Expanding the application of large language models (LLMs) to societal life, instead of primary function only as auxiliary assistants to communicate with only one person at a time, necessitates LLMs' capabilities to independently play roles in multi-user, multi-turn social agent tasks within complex social settings. However, currently the capability has not been systematically measured with available benchmarks. To address this gap, we first introduce an agent task leveling framework grounded in sociological principles. Concurrently, we propose a novel benchmark, How Social Is It (we call it HSII below), designed to assess LLM's social capabilities in comprehensive social agents tasks and benchmark representative models. HSII comprises four stages: format parsing, target selection, target switching conversation, and stable conversation, which collectively evaluate the communication and task completion capabilities of LLMs within realistic social interaction scenarios dataset, HSII-Dataset. The dataset is derived step by step from news dataset. We perform an ablation study by doing clustering to the dataset. Additionally, we investigate the impact of chain of thought (COT) method on enhancing LLMs' social performance. Since COT cost more computation, we further introduce a new statistical metric, COT-complexity, to quantify the efficiency of certain LLMs with COTs for specific social tasks and strike a better trade-off between measurement of correctness and efficiency. Various results of our experiments demonstrate that our benchmark is well-suited for evaluating social skills in LLMs.

[Arxiv](https://arxiv.org/abs/2505.04628)