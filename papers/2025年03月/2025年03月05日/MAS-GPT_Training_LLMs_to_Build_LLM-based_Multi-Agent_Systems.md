# MAS-GPT：利用 LLMs 打造基于 LLM 的多智能体系统

发布时间：2025年03月05日

`Agent` `智能系统` `自动化`

> MAS-GPT: Training LLMs to Build LLM-based Multi-Agent Systems

# 摘要

> 基于LLM的多智能体系统（MAS）在处理各种任务方面展现出巨大潜力，但现有方法在设计MAS时依赖手动配置或多次调用LLM，导致适应性差和成本高昂。本文通过将MAS构建重新定义为生成语言任务，输入为用户查询，输出为对应MAS，简化了这一过程。为了解决这一任务，我们统一MAS表示为可执行代码，并提出了一种以一致性为导向的数据构建管道，创建高质量的连贯查询-MAS对数据集。基于此，我们训练了开源中型LLM——MAS-GPT，能够在一个推理过程中生成与查询自适应的MAS。生成的MAS可无缝处理用户查询并提供高质量响应。在9个基准和5个LLM上的实验表明，MAS-GPT在多种设置下优于10多种基线方法，展现了其高效性、效能和泛化能力。代码将在https://github.com/rui-ye/MAS-GPT上提供。

> LLM-based multi-agent systems (MAS) have shown significant potential in tackling diverse tasks. However, to design effective MAS, existing approaches heavily rely on manual configurations or multiple calls of advanced LLMs, resulting in inadaptability and high inference costs. In this paper, we simplify the process of building an MAS by reframing it as a generative language task, where the input is a user query and the output is a corresponding MAS. To address this novel task, we unify the representation of MAS as executable code and propose a consistency-oriented data construction pipeline to create a high-quality dataset comprising coherent and consistent query-MAS pairs. Using this dataset, we train MAS-GPT, an open-source medium-sized LLM that is capable of generating query-adaptive MAS within a single LLM inference. The generated MAS can be seamlessly applied to process user queries and deliver high-quality responses. Extensive experiments on 9 benchmarks and 5 LLMs show that the proposed MAS-GPT consistently outperforms 10+ baseline MAS methods on diverse settings, indicating MAS-GPT's high effectiveness, efficiency and strong generalization ability. Code will be available at https://github.com/rui-ye/MAS-GPT.

[Arxiv](https://arxiv.org/abs/2503.03686)