# MCTS-RAG：通过蒙特卡洛树搜索提升检索增强生成的能力

发布时间：2025年03月26日

`RAG` `知识密集型任务`

> MCTS-RAG: Enhancing Retrieval-Augmented Generation with Monte Carlo Tree Search

# 摘要

> 我们提出了一种创新方法MCTS-RAG，通过结合检索增强生成（RAG）和蒙特卡洛树搜索（MCTS），显著提升了小型语言模型在知识密集型任务中的推理能力。MCTS-RAG通过迭代决策过程实现了检索与推理的动态整合。与传统RAG方法独立进行检索和推理、导致知识整合效率低下的问题不同，MCTS-RAG将结构化推理与自适应检索相结合，避免了仅依赖模型内部知识的局限性。这种集成方法不仅提升了决策质量，还减少了幻觉现象，确保了更高的事实准确性和响应一致性。在ComplexWebQA、GPQA和FoolMeTwice等多个推理和知识密集型数据集上的实验结果表明，通过有效扩展推理时的计算资源，MCTS-RAG使小型语言模型的性能达到了与前沿大语言模型（如GPT-4o）相当的水平，为小型模型的推理能力树立了新的标杆。

> We introduce MCTS-RAG, a novel approach that enhances the reasoning capabilities of small language models on knowledge-intensive tasks by leveraging retrieval-augmented generation (RAG) to provide relevant context and Monte Carlo Tree Search (MCTS) to refine reasoning paths. MCTS-RAG dynamically integrates retrieval and reasoning through an iterative decision-making process. Unlike standard RAG methods, which typically retrieve information independently from reasoning and thus integrate knowledge suboptimally, or conventional MCTS reasoning, which depends solely on internal model knowledge without external facts, MCTS-RAG combines structured reasoning with adaptive retrieval. This integrated approach enhances decision-making, reduces hallucinations, and ensures improved factual accuracy and response consistency. The experimental results on multiple reasoning and knowledge-intensive datasets datasets (i.e., ComplexWebQA, GPQA, and FoolMeTwice) show that our method enables small-scale LMs to achieve performance comparable to frontier LLMs like GPT-4o by effectively scaling inference-time compute, setting a new standard for reasoning in small-scale models.

[Arxiv](https://arxiv.org/abs/2503.20757)