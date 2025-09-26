# 元记忆：检索并整合语义-空间记忆助力机器人空间推理

发布时间：2025年09月25日

`Agent` `工业与制造`

> Meta-Memory: Retrieving and Integrating Semantic-Spatial Memories for Robot Spatial Reasoning

# 摘要

> 机器人在复杂环境中导航时，需将观测信息高效存储为记忆，并利用这些记忆回答人类的空间位置查询——这是一项至关重要却尚未深入探索的研究难题。尽管已有研究在构建机器人记忆方面取得进展，但高效记忆检索与整合所需的系统性机制仍缺乏深入探讨。为此，我们提出Meta-Memory——一种由大型语言模型（LLM）驱动的智能体，可构建环境的高密度记忆表征。其核心创新在于：针对自然语言位置查询，通过语义与空间模态的联合推理检索并整合相关记忆，进而赋予机器人稳健且精准的空间推理能力。为评估性能，我们构建了SpaceLocQA——一个涵盖多种真实世界空间问答场景的大规模数据集。实验结果显示，Meta-Memory在SpaceLocQA和公开的NaVQA基准测试中均显著优于现有最优方法。此外，我们已将其成功部署于真实机器人平台，验证了其在复杂环境中的实际应用价值。Project page: https://itsbaymax.github.io/meta-memory.github.io/ .

> Navigating complex environments requires robots to effectively store observations as memories and leverage them to answer human queries about spatial locations, which is a critical yet underexplored research challenge. While prior work has made progress in constructing robotic memory, few have addressed the principled mechanisms needed for efficient memory retrieval and integration. To bridge this gap, we propose Meta-Memory, a large language model (LLM)-driven agent that constructs a high-density memory representation of the environment. The key innovation of Meta-Memory lies in its capacity to retrieve and integrate relevant memories through joint reasoning over semantic and spatial modalities in response to natural language location queries, thereby empowering robots with robust and accurate spatial reasoning capabilities. To evaluate its performance, we introduce SpaceLocQA, a large-scale dataset encompassing diverse real-world spatial question-answering scenarios. Experimental results show that Meta-Memory significantly outperforms state-of-the-art methods on both the SpaceLocQA and the public NaVQA benchmarks. Furthermore, we successfully deployed Meta-Memory on real-world robotic platforms, demonstrating its practical utility in complex environments. Project page: https://itsbaymax.github.io/meta-memory.github.io/ .

[Arxiv](https://arxiv.org/abs/2509.20754)