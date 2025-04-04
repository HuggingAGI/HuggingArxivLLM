# 大型（视觉）语言模型：天生的上下文学习者

发布时间：2025年04月03日

`LLM应用` `人工智能`

> Large (Vision) Language Models are Unsupervised In-Context Learners

# 摘要

> 大型语言和视觉语言模型的最新进展使零样本推理成为可能，无需针对特定任务进行训练即可解决新问题。除了零样本推理，还可以通过提示工程、In-Context Learning (ICL) 和监督微调等方法进一步提升模型性能，但这些方法需要耗费大量人工 effort 来构建有效提示或标注示例。本研究提出了一种全新的联合推理框架，实现完全无监督的适应，无需手动提示工程和标注示例。与独立预测的零样本推理不同，联合推理在给定任务中对所有输入同时进行预测。由于直接联合推理涉及计算代价高昂的优化，我们开发了高效的近似技术，从而提出了两种无监督适应方法：无监督微调和无监督 ICL。我们在多种任务和模型上验证了方法的有效性，包括仅限语言的 Llama-3.1 在自然语言处理任务上的表现、面向推理的 Qwen2.5-Math 在小学数学问题上的表现、视觉语言模型 OpenFlamingo 在视觉任务上的表现，以及仅限 API 访问的 GPT-4o 模型在大规模跨学科任务上的表现。实验结果表明，与标准零样本方法相比，我们的方法在具有挑战性的 GSM8K 数学推理数据集上实现了 39% 的绝对提升。值得注意的是，尽管我们的框架完全无监督，但在许多情况下，其性能可与依赖真实标签的监督方法相媲美。

> Recent advances in large language and vision-language models have enabled zero-shot inference, allowing models to solve new tasks without task-specific training. Various adaptation techniques such as prompt engineering, In-Context Learning (ICL), and supervised fine-tuning can further enhance the model's performance on a downstream task, but they require substantial manual effort to construct effective prompts or labeled examples. In this work, we introduce a joint inference framework for fully unsupervised adaptation, eliminating the need for manual prompt engineering and labeled examples. Unlike zero-shot inference, which makes independent predictions, the joint inference makes predictions simultaneously for all inputs in a given task. Since direct joint inference involves computationally expensive optimization, we develop efficient approximation techniques, leading to two unsupervised adaptation methods: unsupervised fine-tuning and unsupervised ICL. We demonstrate the effectiveness of our methods across diverse tasks and models, including language-only Llama-3.1 on natural language processing tasks, reasoning-oriented Qwen2.5-Math on grade school math problems, vision-language OpenFlamingo on vision tasks, and the API-only access GPT-4o model on massive multi-discipline tasks. Our experiments demonstrate substantial improvements over the standard zero-shot approach, including 39% absolute improvement on the challenging GSM8K math reasoning dataset. Remarkably, despite being fully unsupervised, our framework often performs on par with supervised approaches that rely on ground truth labels.

[Arxiv](https://arxiv.org/abs/2504.02349)