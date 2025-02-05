# CoAT: 关联思维链框架，提升大型语言模型推理能力

发布时间：2025年02月04日

`LLM理论

理由：这篇论文提出了一个新的框架Chain-of-Associated-Thoughts（CoAT），结合了蒙特卡洛树搜索（MCTS）算法和关联记忆机制，旨在改进LLM的推理能力。该研究主要关注LLM的理论改进和推理方式的创新，属于对LLM理论的研究和探索，因此分类为LLM理论。` `人工智能`

> CoAT: Chain-of-Associated-Thoughts Framework for Enhancing Large Language Models Reasoning

# 摘要

> # 摘要
LLM技术的研究正蓬勃发展，多数采用“快速思考”推理方式，即仅凭单一查询和LLM的推理能力生成结果。然而，OpenAI-o1的问世让“慢思考”技术备受瞩目，因其更贴近人类思维。受人类思考时不断关联和补充知识的启发，我们提出了Chain-of-Associated-Thoughts（CoAT）框架，巧妙结合了蒙特卡洛树搜索（MCTS）算法与动态整合新信息的“关联记忆”机制。CoAT融合了MCTS的结构化探索与关联记忆的自适应学习，大幅扩展了LLM的搜索空间，使其能够探索多样推理路径并实时更新知识库。这不仅让框架能重新审视和改进早期推理，还能自适应地整合新信息，确保输出既准确又全面。通过一系列生成和推理任务的实验，我们验证了CoAT在准确性、连贯性和多样性上的卓越表现。其迭代扩展搜索空间并保留上下文相关信息的能力，展现了显著优势。

> Research on LLM technologies is rapidly emerging, with most of them employing a 'fast thinking' approach to inference. Most LLMs generate the final result based solely on a single query and LLM's reasoning capabilities. However, with the advent of OpenAI-o1, 'slow thinking' techniques have garnered increasing attention because its process is closer to the human thought process. Inspired by the human ability to constantly associate and replenish knowledge during thinking, we developed the novel Chain-of-Associated-Thoughts (CoAT) framework, which introduces an innovative synergy between the Monte Carlo Tree Search (MCTS) algorithm and a dynamic mechanism for integrating new key information, termed 'associative memory'. By combining the structured exploration capabilities of MCTS with the adaptive learning capacity of associative memory, CoAT significantly expands the LLM search space, enabling our framework to explore diverse reasoning pathways and dynamically update its knowledge base in real-time. This allows the framework to not only revisit and refine earlier inferences but also adaptively incorporate evolving information, ensuring that the final output is both accurate and comprehensive. To validate the effectiveness of our framework, we conducted extensive experiments across a range of generative and reasoning tasks. These experiments demonstrated that our framework outperforms conventional inference processes on accuracy, coherence, and diversity. The framework's ability to iteratively expand its search space while retaining contextually relevant information results.

[Arxiv](https://arxiv.org/abs/2502.02390)