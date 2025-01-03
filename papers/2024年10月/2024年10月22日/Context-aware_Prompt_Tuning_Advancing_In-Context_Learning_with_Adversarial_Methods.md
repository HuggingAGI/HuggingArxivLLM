# 上下文感知提示调优：利用对抗方法提升上下文学习

发布时间：2024年10月22日

`LLM理论

理由：这篇论文主要讨论了如何通过上下文感知提示调优（Context-aware Prompt Tuning, CPT）方法来改进大型语言模型（LLMs）的少样本学习能力。论文的核心内容涉及对LLMs的优化和调优策略的理论探讨，特别是如何结合上下文学习（ICL）和提示调优（PT）来提高模型的性能。因此，这篇论文更适合归类为“LLM理论”，因为它主要关注的是LLMs的理论改进和优化方法，而不是具体的应用场景或代理（Agent）技术。` `机器学习`

> Context-aware Prompt Tuning: Advancing In-Context Learning with Adversarial Methods

# 摘要

> # 摘要
微调大型语言模型（LLMs）通常需要更新数十亿个参数，而提示调优（Prompt Tuning, PT）则更为高效，仅更新少量可学习的标记。相比之下，上下文学习（In-Context Learning, ICL）通过在输入中加入示例来适应新任务，无需训练。基于优化的方法（如微调和PT）在少样本学习中会专门适应小规模训练集，而ICL则保持模型不变，这使得传统方法更容易过拟合，而ICL对少样本场景更为稳健。然而，ICL并未充分利用训练示例中的信息。本文提出了一种受ICL、PT和对抗攻击启发的上下文感知提示调优（Context-aware Prompt Tuning, CPT）方法。我们在ICL的基础上，通过类似PT的学习扩展了上下文嵌入的优化过程，以从训练示例中提取更深层次的见解。我们根据输入输出格式的独特结构，精心调整特定上下文标记，并借鉴对抗攻击的思路，基于上下文标签调整输入，专注于最小化损失。此外，我们采用投影梯度下降算法，确保标记嵌入接近原始值，假设用户提供的数据本身具有价值。实验表明，CPT在多种LLM模型的分类任务中表现出色。

> Fine-tuning Large Language Models (LLMs) typically involves updating at least a few billions of parameters. A more parameter-efficient approach is Prompt Tuning (PT), which updates only a few learnable tokens, and differently, In-Context Learning (ICL) adapts the model to a new task by simply including examples in the input without any training. When applying optimization-based methods, such as fine-tuning and PT for few-shot learning, the model is specifically adapted to the small set of training examples, whereas ICL leaves the model unchanged. This distinction makes traditional learning methods more prone to overfitting; in contrast, ICL is less sensitive to the few-shot scenario. While ICL is not prone to overfitting, it does not fully extract the information that exists in the training examples. This work introduces Context-aware Prompt Tuning (CPT), a method inspired by ICL, PT, and adversarial attacks. We build on the ICL strategy of concatenating examples before the input, but we extend this by PT-like learning, refining the context embedding through iterative optimization to extract deeper insights from the training examples. We carefully modify specific context tokens, considering the unique structure of input and output formats. Inspired by adversarial attacks, we adjust the input based on the labels present in the context, focusing on minimizing, rather than maximizing, the loss. Moreover, we apply a projected gradient descent algorithm to keep token embeddings close to their original values, under the assumption that the user-provided data is inherently valuable. Our method has been shown to achieve superior accuracy across multiple classification tasks using various LLM models.

[Arxiv](https://arxiv.org/abs/2410.17222)