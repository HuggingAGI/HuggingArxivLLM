# 大型语言模型中的符号回归：上下文学习与推理

发布时间：2024年10月22日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在符号回归中的应用，具体描述了如何使用GPT-4从数据中生成表达式，并通过外部工具进行优化和评估。论文还讨论了如何通过提示和自然语言界面来提升模型性能，并展示了LLMs在科学方程发现中的潜力。这些内容主要涉及LLMs在实际任务中的应用，因此归类为“LLM应用”。` `机器学习` `符号回归`

> In Context Learning and Reasoning for Symbolic Regression with Large Language Models

# 摘要

> 大型语言模型（LLMs）是基于Transformer的机器学习模型，在未明确训练的任务中表现出色。本文探讨了LLMs在符号回归中的潜力——一种从数据中寻找简洁准确方程的机器学习方法。我们通过提示GPT-4从数据中生成表达式，并使用外部Python工具进行优化和评估。结果反馈给GPT-4，GPT-4在优化复杂性和损失的同时提出改进的表达式。通过思维链提示，我们指导GPT-4在生成新表达式前分析数据、历史表达式及科学背景（以自然语言描述）。我们在重新发现五个著名科学方程的实验数据上评估了该工作流程，并在一个无已知方程的额外数据集上进行了测试。GPT-4成功重新发现了所有五个方程，且在使用草稿本并考虑科学背景时表现更佳。我们还展示了战略提示如何提升模型性能，以及自然语言界面如何简化理论与数据的融合。尽管在目标方程更复杂的情况下，该方法不及传统符号回归程序，但LLMs仍能在遵循指令并融入自然语言科学背景的情况下迭代优化解决方案。

> Large Language Models (LLMs) are transformer-based machine learning models that have shown remarkable performance in tasks for which they were not explicitly trained. Here, we explore the potential of LLMs to perform symbolic regression -- a machine-learning method for finding simple and accurate equations from datasets. We prompt GPT-4 to suggest expressions from data, which are then optimized and evaluated using external Python tools. These results are fed back to GPT-4, which proposes improved expressions while optimizing for complexity and loss. Using chain-of-thought prompting, we instruct GPT-4 to analyze the data, prior expressions, and the scientific context (expressed in natural language) for each problem before generating new expressions. We evaluated the workflow in rediscovery of five well-known scientific equations from experimental data, and on an additional dataset without a known equation. GPT-4 successfully rediscovered all five equations, and in general, performed better when prompted to use a scratchpad and consider scientific context. We also demonstrate how strategic prompting improves the model's performance and how the natural language interface simplifies integrating theory with data. Although this approach does not outperform established SR programs where target equations are more complex, LLMs can nonetheless iterate toward improved solutions while following instructions and incorporating scientific context in natural language.

[Arxiv](https://arxiv.org/abs/2410.17448)