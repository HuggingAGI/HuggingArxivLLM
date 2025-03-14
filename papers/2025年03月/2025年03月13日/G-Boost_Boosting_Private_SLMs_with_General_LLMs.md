# G-Boost：用通用大语言模型增强私有语言模型

发布时间：2025年03月13日

`LLM应用` `人工智能`

> G-Boost: Boosting Private SLMs with General LLMs

# 摘要

> 由于计算资源的限制，大多数大型语言模型（LLMs）的开发者只能在自己的数据上微调小型语言模型（SLMs）。然而，这些私有模型的性能通常较为有限。为了提升这些私有模型的表现，本研究提出了一种创新方法，即借助通用的大型语言模型（LLMs）的力量。这些通用模型可以是API服务，也可以是开发者能够承担推理成本的更大规模的模型。具体而言，我们提出了G-Boost框架，该框架通过过程奖励机制，使私有SLM能够与通用LLM进行自适应的协作推理。实验结果表明，G-Boost框架能够显著提升私有SLMs的性能。

> Due to the limited computational resources, most Large Language Models (LLMs) developers can only fine-tune Small Language Models (SLMs) on their own data. These private SLMs typically have limited effectiveness. To boost the performance of private SLMs, this paper proposes to ask general LLMs for help. The general LLMs can be APIs or larger LLMs whose inference cost the developers can afford. Specifically, we propose the G-Boost framework where a private SLM adaptively performs collaborative inference with a general LLM under the guide of process reward. Experiments demonstrate that our framework can significantly boost the performance of private SLMs.

[Arxiv](https://arxiv.org/abs/2503.10367)