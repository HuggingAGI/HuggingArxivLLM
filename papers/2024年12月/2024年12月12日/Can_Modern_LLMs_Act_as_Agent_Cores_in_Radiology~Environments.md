# 现代 LLMs 能否成为放射学环境中的代理核心？

发布时间：2024年12月12日

`Agent` `放射学`

> Can Modern LLMs Act as Agent Cores in Radiology~Environments?

# 摘要

> 大型语言模型（LLMs）的发展为基于 LLM 的代理系统开辟了道路，此类系统在众多领域实现了更高的准确性和可解释性。放射学因其复杂的分析需求，成为这些代理应用的理想领域。本文旨在探究构建具体放射学代理的先决问题——“现代 LLMs 能否在放射学环境中充当代理核心？”为进行研究，我们引入了 RadABench，其有三方面贡献：其一，我们展示了 RadABench-Data，这是一个针对基于 LLM 代理的综合合成评估数据集，由涵盖 6 个解剖结构、5 种成像方式、10 个工具类别和 11 个放射学任务的广泛分类法生成。其二，我们提出了 RadABench-EvalPlat，这是一个新颖的代理评估平台，具备提示驱动的工作流程和模拟各类放射学工具集的能力。其三，我们从 5 个角度通过多个指标评估了 7 个领先的 LLMs 在我们的基准测试中的性能。我们的发现表明，尽管当前的 LLMs 在许多方面展现出强大能力，但在完全运行的放射学代理系统中，它们仍不够先进，无法充当核心代理。此外，我们还确定了影响基于 LLM 代理核心性能的关键因素，为临床医生提供了如何在现实放射学实践中有效应用代理系统的见解。我们所有的代码和数据均在 https://github.com/MAGIC-AI4Med/RadABench 开源。

> Advancements in large language models (LLMs) have paved the way for LLM-based agent systems that offer enhanced accuracy and interpretability across various domains. Radiology, with its complex analytical requirements, is an ideal field for the application of these agents. This paper aims to investigate the pre-requisite question for building concrete radiology agents which is, `Can modern LLMs act as agent cores in radiology environments?' To investigate it, we introduce RadABench with three-fold contributions: First, we present RadABench-Data, a comprehensive synthetic evaluation dataset for LLM-based agents, generated from an extensive taxonomy encompassing 6 anatomies, 5 imaging modalities, 10 tool categories, and 11 radiology tasks. Second, we propose RadABench-EvalPlat, a novel evaluation platform for agents featuring a prompt-driven workflow and the capability to simulate a wide range of radiology toolsets. Third, we assess the performance of 7 leading LLMs on our benchmark from 5 perspectives with multiple metrics. Our findings indicate that while current LLMs demonstrate strong capabilities in many areas, they are still not sufficiently advanced to serve as the central agent core in a fully operational radiology agent system. Additionally, we identify key factors influencing the performance of LLM-based agent cores, offering insights for clinicians on how to apply agent systems in real-world radiology practices effectively. All of our code and data are open-sourced in https://github.com/MAGIC-AI4Med/RadABench.

[Arxiv](https://arxiv.org/abs/2412.09529)