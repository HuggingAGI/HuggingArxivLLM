# 一调永逸：大型语言模型的多示例上下文微调

发布时间：2025年06月06日

`LLM理论` `人工智能`

> You Only Fine-tune Once: Many-Shot In-Context Fine-Tuning for Large Language Model

# 摘要

> 大型语言模型（LLMs）拥有令人惊叹的上下文学习（ICL）能力，使其无需针对特定任务进行微调即可同时处理多个下游任务。近期研究发现，像Mistral 7B、Gemma 7B和Llama-3 8B这样的中型LLMs，甚至可以通过一次性对所有任务进行少样本上下文微调来实现ICL。然而，这种方法的表现仍逊色于针对每个任务单独训练的专用微调。

    本文提出了一种全新方法——多样本上下文微调（ManyICL）。通过将ICL的原则扩展到多样本场景，我们显著缩小了与专用微调的性能差距。为充分发挥ManyICL的潜力并解决处理包含大量上下文示例的长序列时的低效问题，我们引入了一种创新的训练目标。我们的方法不再局限于预测最终答案，而是将上下文中每一个答案都作为监督训练的目标。这巧妙地将多样本示例的角色从提示转换为自回归学习的目标。

    通过在分类、摘要、问答、自然语言推理和数学等多样化下游任务上的广泛实验，我们证明ManyICL不仅在性能上远超零/少样本微调，更接近专用微调的表现。此外，它还显著缓解了零/少样本微调中常见的灾难性遗忘问题。代码将在论文发表后公开发布。

> Large language models (LLMs) possess a remarkable ability to perform in-context learning (ICL), which enables them to handle multiple downstream tasks simultaneously without requiring task-specific fine-tuning. Recent studies have shown that even moderately sized LLMs, such as Mistral 7B, Gemma 7B and Llama-3 8B, can achieve ICL through few-shot in-context fine-tuning of all tasks at once. However, this approach still lags behind dedicated fine-tuning, where a separate model is trained for each individual task.
  In this paper, we propose a novel approach, Many-Shot In-Context Fine-tuning (ManyICL), which significantly narrows this performance gap by extending the principles of ICL to a many-shot setting. To unlock the full potential of ManyICL and address the inherent inefficiency of processing long sequences with numerous in-context examples, we propose a novel training objective. Instead of solely predicting the final answer, our approach treats every answer within the context as a supervised training target. This effectively shifts the role of many-shot examples from prompts to targets for autoregressive learning. Through extensive experiments on diverse downstream tasks, including classification, summarization, question answering, natural language inference, and math, we demonstrate that ManyICL substantially outperforms zero/few-shot fine-tuning and approaches the performance of dedicated fine-tuning. Furthermore, ManyICL significantly mitigates catastrophic forgetting issues observed in zero/few-shot fine-tuning. The code will be made publicly available upon publication.

[Arxiv](https://arxiv.org/abs/2506.11103)