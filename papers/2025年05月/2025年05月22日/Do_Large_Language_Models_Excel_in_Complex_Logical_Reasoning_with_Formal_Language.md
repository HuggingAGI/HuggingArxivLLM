# 大型语言模型能否在复杂逻辑推理中运用形式语言？

发布时间：2025年05月22日

`LLM应用` `逻辑推理` `形式语言`

> Do Large Language Models Excel in Complex Logical Reasoning with Formal Language?

# 摘要

> 大型语言模型（LLMs）在复杂逻辑推理任务中表现卓越，但现有研究多集中于利用形式语言引导其推理，系统性评估仍显不足。本文通过形式语言对LLMs在逻辑推理问题上的能力进行全面评估，从模型谱系、任务分类和轨迹格式三个维度，我们发现：1）思考型模型在形式语言引导下显著优于指令型模型；2）所有LLMs在归纳推理能力上均有局限；3）采用PoT格式的数据在跨语言泛化上表现最佳。此外，我们整理了形式语言相关的训练数据以提升小型模型能力，实验表明简单拒绝微调方法能有效提升LLMs在形式语言上的泛化能力并实现最优性能。代码和报告可在https://github.com/jiangjin1999/FormalEval获取。

> Large Language Models (LLMs) have been shown to achieve breakthrough performance on complex logical reasoning tasks. Nevertheless, most existing research focuses on employing formal language to guide LLMs to derive reliable reasoning paths, while systematic evaluations of these capabilities are still limited. In this paper, we aim to conduct a comprehensive evaluation of LLMs across various logical reasoning problems utilizing formal languages. From the perspective of three dimensions, i.e., spectrum of LLMs, taxonomy of tasks, and format of trajectories, our key findings are: 1) Thinking models significantly outperform Instruct models, especially when formal language is employed; 2) All LLMs exhibit limitations in inductive reasoning capability, irrespective of whether they use a formal language; 3) Data with PoT format achieves the best generalization performance across other languages. Additionally, we also curate the formal-relative training data to further enhance the small language models, and the experimental results indicate that a simple rejected fine-tuning method can better enable LLMs to generalize across formal languages and achieve the best overall performance. Our codes and reports are available at https://github.com/jiangjin1999/FormalEval.

[Arxiv](https://arxiv.org/abs/2505.16998)