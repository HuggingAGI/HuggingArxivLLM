# Qwen3 技术报告

发布时间：2025年05月14日

`LLM理论` `语言技术` `人工智能`

> Qwen3 Technical Report

# 摘要

> # Qwen3：性能与效率兼备的多语言大模型新突破

我们很高兴推出 Qwen 模型家族的最新成员——Qwen3。这一系列大型语言模型（LLMs）在性能、效率和多语言能力方面均有显著提升。Qwen3 系列包含密集架构和专家混合（MoE）架构的模型，参数规模从 0.6 亿到 2350 亿不等。

Qwen3 的一大创新亮点是将思考模式（用于复杂推理）和非思考模式（用于快速响应）整合到一个统一框架中。这一突破性设计让用户无需在不同模型间切换——无论是优化聊天的模型（如 GPT-4o），还是专用推理模型（如 QwQ-32B）。系统可根据用户查询或聊天模板，智能切换模式。

我们还引入了创新的思考预算机制，让用户在推理过程中灵活调配计算资源。这一机制可根据任务复杂性，自动平衡响应速度与性能表现。此外，通过知识迁移技术，我们大幅降低了小规模模型的训练成本，同时保持了其强劲的性能表现。

实验结果表明，Qwen3 在代码生成、数学推理、代理任务等多个领域均达到当前最优水平，与更大规模的 MoE 模型和专有模型相比毫不逊色。与上一代 Qwen2.5 相比，Qwen3 的多语言支持从 29 种语言和方言扩展到 119 种，跨语言理解和生成能力的提升让全球用户都能更轻松地使用。

为了推动开放研究和社区协作，所有 Qwen3 模型均已开源，采用 Apache 2.0 许可证。我们期待与全球研究者和开发者共同探索，推动自然语言处理技术的持续进步。

> In this work, we present Qwen3, the latest version of the Qwen model family. Qwen3 comprises a series of large language models (LLMs) designed to advance performance, efficiency, and multilingual capabilities. The Qwen3 series includes models of both dense and Mixture-of-Expert (MoE) architectures, with parameter scales ranging from 0.6 to 235 billion. A key innovation in Qwen3 is the integration of thinking mode (for complex, multi-step reasoning) and non-thinking mode (for rapid, context-driven responses) into a unified framework. This eliminates the need to switch between different models--such as chat-optimized models (e.g., GPT-4o) and dedicated reasoning models (e.g., QwQ-32B)--and enables dynamic mode switching based on user queries or chat templates. Meanwhile, Qwen3 introduces a thinking budget mechanism, allowing users to allocate computational resources adaptively during inference, thereby balancing latency and performance based on task complexity. Moreover, by leveraging the knowledge from the flagship models, we significantly reduce the computational resources required to build smaller-scale models, while ensuring their highly competitive performance. Empirical evaluations demonstrate that Qwen3 achieves state-of-the-art results across diverse benchmarks, including tasks in code generation, mathematical reasoning, agent tasks, etc., competitive against larger MoE models and proprietary models. Compared to its predecessor Qwen2.5, Qwen3 expands multilingual support from 29 to 119 languages and dialects, enhancing global accessibility through improved cross-lingual understanding and generation capabilities. To facilitate reproducibility and community-driven research and development, all Qwen3 models are publicly accessible under Apache 2.0.

[Arxiv](https://arxiv.org/abs/2505.09388)