# # 学会思考：通过图学习引导LLM推理能力
通过图学习引导大型语言模型（LLM）的推理能力，学会思考。

发布时间：2025年05月08日

`LLM应用` `模型优化` `推理框架`

> Learn to Think: Bootstrapping LLM Reasoning Capability Through Graph Learning

# 摘要

> 大型语言模型（LLMs）在多个领域取得了显著成功，但仍然面临训练成本高和复杂推理能力不足的挑战。现有方法通过结构化范式扩展了LLMs的推理能力，但受限于任务特定的提示和预定义推理过程，灵活性和通用性不足。为此，我们提出了一种基于图学习的新框架，使LLMs具备更灵活和自适应的推理能力。具体而言，该方法将问题的推理过程建模为图，并利用基于LLMs的图学习来引导推理步骤的自适应生成。为了进一步提升模型的自适应能力，我们引入了图神经网络（GNN）模块，对推理过程进行表示学习，实现实时调整模型和提示。实验结果表明，该方法显著提升了多个任务的推理性能，无需额外训练或设计任务特定提示。代码可在https://github.com/zch65458525/L2T中找到。

> Large Language Models (LLMs) have achieved remarkable success across various domains. However, they still face significant challenges, including high computational costs for training and limitations in solving complex reasoning problems. Although existing methods have extended the reasoning capabilities of LLMs through structured paradigms, these approaches often rely on task-specific prompts and predefined reasoning processes, which constrain their flexibility and generalizability. To address these limitations, we propose a novel framework that leverages graph learning to enable more flexible and adaptive reasoning capabilities for LLMs. Specifically, this approach models the reasoning process of a problem as a graph and employs LLM-based graph learning to guide the adaptive generation of each reasoning step. To further enhance the adaptability of the model, we introduce a Graph Neural Network (GNN) module to perform representation learning on the generated reasoning process, enabling real-time adjustments to both the model and the prompt. Experimental results demonstrate that this method significantly improves reasoning performance across multiple tasks without requiring additional training or task-specific prompt design. Code can be found in https://github.com/zch65458525/L2T.

[Arxiv](https://arxiv.org/abs/2505.06321)