# MARS-Bench：对话评估的多轮竞技现实场景基准

发布时间：2025年05月27日

`LLM应用

论文摘要：大型语言模型（LLMs）在对话应用中的表现评估，特别是多轮复杂对话场景，属于LLM应用的范畴。` `对话系统` `基准测试`

> MARS-Bench: A Multi-turn Athletic Real-world Scenario Benchmark for Dialogue Evaluation

# 摘要

> 大型语言模型（	extbf{LLMs}），如 ChatGPT，已在实际对话应用中得到广泛应用。然而，LLMs 在处理包含频繁动机转移和复杂跨轮依赖的长复杂对话会话时的稳健性长期受到批评。尽管如此，现有的基准测试无法完全反映这些弱点。为此，我们提出了 	extbf{MARS-Bench}，一个专为评估多轮对话设计的基准测试，包含三个关键方面：超多轮对话、交互式多轮对话和跨轮任务。通过 MARS-Bench 的广泛实验发现，闭源 LLMs 显著优于开源替代品，显式推理显著提升了 LLMs 处理长复杂对话会话的稳健性，而 LLMs 在处理动机转移和复杂跨轮依赖时确实面临重大挑战。此外，我们通过基于 Qwen2.5-7B-Instruction 的注意力可视化实验，揭示了特殊令牌导致注意力池化从而引发 LLMs 在处理长复杂对话会话时性能下降的机制。

> Large Language Models (\textbf{LLMs}), e.g. ChatGPT, have been widely adopted in real-world dialogue applications. However, LLMs' robustness, especially in handling long complex dialogue sessions, including frequent motivation transfer, sophisticated cross-turn dependency, is criticized all along. Nevertheless, no existing benchmarks can fully reflect these weaknesses. We present \textbf{MARS-Bench}, a \textbf{M}ulti-turn \textbf{A}thletic \textbf{R}eal-world \textbf{S}cenario Dialogue \textbf{Bench}mark, designed to remedy the gap. MARS-Bench is constructed from play-by-play text commentary so to feature realistic dialogues specifically designed to evaluate three critical aspects of multi-turn conversations: Ultra Multi-turn, Interactive Multi-turn, and Cross-turn Tasks. Extensive experiments on MARS-Bench also reveal that closed-source LLMs significantly outperform open-source alternatives, explicit reasoning significantly boosts LLMs' robustness on handling long complex dialogue sessions, and LLMs indeed face significant challenges when handling motivation transfer and sophisticated cross-turn dependency. Moreover, we provide mechanistic interpretability on how attention sinks due to special tokens lead to LLMs' performance degradation when handling long complex dialogue sessions based on attention visualization experiment in Qwen2.5-7B-Instruction.

[Arxiv](https://arxiv.org/abs/2505.23810)