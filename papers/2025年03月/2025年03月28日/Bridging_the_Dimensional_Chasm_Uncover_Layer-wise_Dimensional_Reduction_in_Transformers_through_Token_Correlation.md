# 跨越维度鸿沟：探索Transformer中的分层维度约减机制

发布时间：2025年03月28日

`LLM理论

摘要中讨论了大型语言模型（LLMs）的几何结构和内部工作机制，分析了令牌表示的几何演变和内在规律，提出了新的理论框架，并探讨了模型压缩与性能的关系。这些内容属于对LLM理论的深入研究，因此归类为LLM理论。` `理论计算机科学`

> Bridging the Dimensional Chasm: Uncover Layer-wise Dimensional Reduction in Transformers through Token Correlation

# 摘要

> 大型语言模型 (LLMs) 中令牌表示的几何演变揭示了一个有趣的现象：人类语言的语义信息天然组织在低维空间（约【数学公式】维度），而现代 LLMs 却采用高维嵌入（约【数学公式】维度）并通过 Transformer 架构处理信息。为解决这一矛盾，本研究提出了一种几何框架，通过追踪 Transformers 层中的令牌动态，揭示了其中的内在规律。通过对多个架构中各层的内在维度进行逐层分析，我们发现了一个独特的扩张-收缩模式：令牌首先扩散到一个“工作空间”，随后逐步投影到低维子流形上。研究发现表明，工作空间维度与 LLMs 的参数敏感性能之间存在负相关关系，同时发现有效的模型倾向于将令牌压缩到约 10 维的子流形中，这与人类语义空间高度相似。这项研究不仅通过重新定义 Transformers 层为介于高维计算和低维语义之间的投影器，从而深化了对 LLM 的理解，还为模型诊断提供了实用工具，这些工具无需依赖特定任务的评估。

> The geometric evolution of token representations in large language models (LLMs) presents a fundamental paradox: while human language inherently organizes semantic information in low-dimensional spaces ($\sim 10^1$ dimensions), modern LLMs employ high-dimensional embeddings ($\sim 10^3$ dimensions) processed through Transformer architectures. To resolve this paradox, this work bridges this conceptual gap by developing a geometric framework that tracks token dynamics across Transformers layers. Through layer-wise analysis of intrinsic dimensions across multiple architectures, we reveal an expansion-contraction pattern where tokens diffuse to a "working space" and then progressively project onto lower-dimensional submanifolds. Our finding implies a negative correlation between the working space dimension and parameter-sensitive performance of the LLMs, and indicates that effective models tend to compress tokens into approximately 10-dimensional submanifolds, closely resembling human semantic spaces. This work not only advances LLM interpretability by reframing Transformers layers as projectors that mediate between high-dimensional computation and low-dimensional semantics, but also provides practical tools for model diagnostics that do not rely on task-specific evaluations.

[Arxiv](https://arxiv.org/abs/2503.22547)