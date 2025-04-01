# ORAL: 通过条件循环扩散机制，轻松驾驭大规模LoRAs的提示技巧

发布时间：2025年03月31日

`LLM应用` `参数生成` `大型语言模型`

> ORAL: Prompting Your Large-Scale LoRAs via Conditional Recurrent Diffusion

# 摘要

> 参数生成作为一种新兴的神经网络开发范式，通过直接合成高质量模型权重，为传统训练提供了新思路。在针对不断更新的大型语言模型（LLMs）进行低秩适应（LoRA）时，这一方法无需高昂的重新训练成本，即可实现高效适应。然而，现有方法在可扩展性和可控性方面存在局限。本文提出了名为$	exttt{ORAL}$的全新$	extbf{条件递归扩散}$框架，该框架通过创新的条件机制，将模型架构与文本任务规范相结合，成功生成特定任务的LoRA参数，并可无缝迁移至不断演进的基础模型。我们的方法不仅扩展至数十亿参数规模的大型语言模型，还保持了可控性。通过在七项语言任务、四项视觉任务及三项多模态任务上的广泛实验，使用五种预训练大型语言模型，我们证明$	exttt{ORAL}$生成的LoRA参数可达到甚至超越传统训练方法的性能表现。

> Parameter generation has emerged as a novel paradigm for neural network development, offering an alternative to traditional neural network training by synthesizing high-quality model weights directly. In the context of Low-Rank Adaptation (LoRA) for evolving ($\textit{i.e.}$, constantly updated) large language models (LLMs), this approach promises efficient adaptation without costly retraining. However, existing methods face critical limitations in simultaneously achieving scalability and controllability. In this paper, we introduce $\texttt{ORAL}$, a novel $\textbf{conditional recurrent diffusion}$ framework that addresses these challenges. $\texttt{ORAL}$ incorporates a novel conditioning mechanism that integrates model architecture and textual task specifications, enabling the generation of task-specific LoRA parameters that can seamlessly transfer across evolving foundation models. Our approach successfully scales to billions-of-parameter LLMs and maintains controllability. Through extensive experiments across seven language tasks, four vision tasks, and three multimodal tasks using five pre-trained LLMs, we demonstrate that $\texttt{ORAL}$ generates high-quality LoRA parameters that achieve comparable or superior performance to vanilla trained counterparts.

[Arxiv](https://arxiv.org/abs/2503.24354)