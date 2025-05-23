# 大型语言模型擅长使用形式语言进行复杂逻辑推理吗？

发布时间：2025年05月22日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在逻辑推理任务中的系统性评估，分析了不同模型类型、任务分类及推理轨迹格式的影响，并提出了改进方法。研究属于理论层面，旨在理解模型的能力和局限性，因此归类为LLM理论。` `人工智能`

> Do Large Language Models Excel in Complex Logical Reasoning with Formal Language?

# 摘要

> 大型语言模型（LLMs）在复杂逻辑推理任务中表现卓越，但现有研究多侧重于利用形式语言引导模型推导可靠推理路径，而对其能力的系统性评估仍显不足。本文通过形式语言对LLMs在各类逻辑推理问题上的表现进行全面评估。从模型谱系、任务分类及推理轨迹格式三个维度，我们的主要发现包括：1）思考型模型在使用形式语言时显著优于指令型模型；2）所有LLMs在归纳推理能力上均存在局限性，无论是否采用形式语言；3）采用PoT格式的数据在跨语言泛化性能上表现最佳。此外，我们还整理了与形式语言相关的训练数据，进一步提升小型语言模型的性能。实验结果表明，简单的拒绝微调方法能更好地帮助LLMs在形式语言间实现泛化，达到整体最优性能。我们的代码和报告已发布在https://github.com/jiangjin1999/FormalEval。

> Large Language Models (LLMs) have been shown to achieve breakthrough performance on complex logical reasoning tasks. Nevertheless, most existing research focuses on employing formal language to guide LLMs to derive reliable reasoning paths, while systematic evaluations of these capabilities are still limited. In this paper, we aim to conduct a comprehensive evaluation of LLMs across various logical reasoning problems utilizing formal languages. From the perspective of three dimensions, i.e., spectrum of LLMs, taxonomy of tasks, and format of trajectories, our key findings are: 1) Thinking models significantly outperform Instruct models, especially when formal language is employed; 2) All LLMs exhibit limitations in inductive reasoning capability, irrespective of whether they use a formal language; 3) Data with PoT format achieves the best generalization performance across other languages. Additionally, we also curate the formal-relative training data to further enhance the small language models, and the experimental results indicate that a simple rejected fine-tuning method can better enable LLMs to generalize across formal languages and achieve the best overall performance. Our codes and reports are available at https://github.com/jiangjin1999/FormalEval.

[Arxiv](https://arxiv.org/abs/2505.16998)