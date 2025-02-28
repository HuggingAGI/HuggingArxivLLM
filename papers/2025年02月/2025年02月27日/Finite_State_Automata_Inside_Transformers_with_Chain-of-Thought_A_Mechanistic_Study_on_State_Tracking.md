# 探索Transformer中的有限状态自动机：链式思维视角下的状态跟踪机制研究

发布时间：2025年02月27日

`LLM理论` `模型机制`

> Finite State Automata Inside Transformers with Chain-of-Thought: A Mechanistic Study on State Tracking

# 摘要

> Chain-of-Thought (CoT) 在提升大型语言模型 (LLMs) 的广泛任务性能方面表现出显著效果，理论研究表明 CoT 能够增强模型的表达能力。然而，对于 Transformer+CoT 学习到的算法机制，我们仍缺乏深入理解。本研究 (1) 评估了 Transformer+CoT 及其变体的状态追踪能力，证实了 CoT 的有效性。 (2) 接下来，我们识别出负责追踪世界状态的模型组件子集——电路，发现晚期层的 MLP 神经元扮演了关键角色。我们提出了两个指标：压缩和区分，并展示了每个状态的神经元集合实现了近 100% 的准确率，这为模型中隐含的有限状态自动机 (FSA) 提供了证据。 (3) 此外，我们探索了三个现实场景：跳过中间步骤、引入数据噪声和测试长度泛化。结果表明，Transformer+CoT 学习到的算法 (FSA) 具备强大的鲁棒性，突显了其在挑战性场景中的适应能力。

> Chain-of-Thought (CoT) significantly enhances the performance of large language models (LLMs) across a wide range of tasks, and prior research shows that CoT can theoretically increase expressiveness. However, there is limited mechanistic understanding of the algorithms that Transformer+CoT can learn. In this work, we (1) evaluate the state tracking capabilities of Transformer+CoT and its variants, confirming the effectiveness of CoT. (2) Next, we identify the circuit, a subset of model components, responsible for tracking the world state, finding that late-layer MLP neurons play a key role. We propose two metrics, compression and distinction, and show that the neuron sets for each state achieve nearly 100% accuracy, providing evidence of an implicit finite state automaton (FSA) embedded within the model. (3) Additionally, we explore three realistic settings: skipping intermediate steps, introducing data noise, and testing length generalization. Our results demonstrate that Transformer+CoT learns robust algorithms (FSA), highlighting its resilience in challenging scenarios.

[Arxiv](https://arxiv.org/abs/2502.20129)