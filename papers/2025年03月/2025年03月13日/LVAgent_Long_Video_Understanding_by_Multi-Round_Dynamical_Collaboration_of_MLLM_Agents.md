# # LVAgent：多语言模型代理通过多轮动态协作实现长视频理解

发布时间：2025年03月13日

`Agent` `长视频` `视频理解`

> LVAgent: Long Video Understanding by Multi-Round Dynamical Collaboration of MLLM Agents

# 摘要

> 现有的多模态大型语言模型（MLLMs）在处理长视频的时间上下文建模方面面临重大挑战。目前，基于代理的方法通过外部工具（如搜索引擎、记忆库、OCR、检索模型）辅助单一MLLM回答长视频问题，但单一MLLM对长视频的理解仍然不全面，性能有限。为更好地应对长视频任务，我们推出首个支持多轮动态协作的MLLM代理框架——LVAgent，专注于长视频理解。我们的方法包含四个关键步骤：1. 选择：从模型库中预选合适代理，根据不同任务组成最优团队。2. 感知：设计高效的长视频检索方案，提升关键时间片段覆盖，同时保持计算效率。3. 行动：代理回答长视频问题并交换理由。4. 反思：评估每轮讨论中各代理表现，优化团队协作。通过MLLM代理的多轮动态协作，代理逐步完善答案。LVAgent是首个在长视频理解任务中超越所有闭源模型（包括GPT-4o）和开源模型（包括InternVL-2.5和Qwen2-VL）的代理系统方法。在四个主流长视频理解任务中，LVAgent准确率达到80%。特别地，在LongVideoBench数据集上，与SOTA相比，LVAgent准确率提升14.3%。

> Existing Multimodal Large Language Models (MLLMs) encounter significant challenges in modeling the temporal context within long videos. Currently, mainstream Agent-based methods use external tools (e.g., search engine, memory banks, OCR, retrieval models) to assist a single MLLM in answering long video questions. Despite such tool-based support, a solitary MLLM still offers only a partial understanding of long videos, resulting in limited performance. In order to better address long video tasks, we introduce LVAgent, the first framework enabling multi-round dynamic collaboration of MLLM agents in long video understanding. Our methodology consists of four key steps: 1. Selection: We pre-select appropriate agents from the model library to form optimal agent teams based on different tasks. 2. Perception: We design an effective retrieval scheme for long videos, improving the coverage of critical temporal segments while maintaining computational efficiency. 3. Action: Agents answer long video-related questions and exchange reasons. 4. Reflection: We evaluate the performance of each agent in each round of discussion and optimize the agent team for dynamic collaboration. The agents iteratively refine their answers by multi-round dynamical collaboration of MLLM agents. LVAgent is the first agent system method that outperforms all closed-source models (including GPT-4o) and open-source models (including InternVL-2.5 and Qwen2-VL) in the long video understanding tasks. Our LVAgent achieves an accuracy of 80% on four mainstream long video understanding tasks. Notably, on the LongVideoBench dataset, LVAgent improves accuracy by up to 14.3% compared with SOTA.

[Arxiv](https://arxiv.org/abs/2503.10200)