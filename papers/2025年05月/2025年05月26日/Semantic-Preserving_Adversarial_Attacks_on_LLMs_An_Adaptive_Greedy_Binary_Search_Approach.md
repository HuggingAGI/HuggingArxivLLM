# 针对大型语言模型（LLMs）的语义保持对抗攻击：一种自适应贪婪二分搜索方法

发布时间：2025年05月26日

`LLM应用

论文摘要讨论了大型语言模型（LLMs）在图形用户界面（GUI）中的应用，特别是通过自动提示工程来优化用户输入和提升响应准确性。尽管用户需求的多样性可能导致误解读，但论文提出了一种名为自适应贪婪二分搜索（AGBS）的方法，旨在优化提示工程，以提高LLM的性能和鲁棒性。该研究属于应用层面，专注于如何在实际应用中改进和优化LLMs的表现，因此归类为LLM应用。` `人工智能` `人机交互`

> Semantic-Preserving Adversarial Attacks on LLMs: An Adaptive Greedy Binary Search Approach

# 摘要

> 大型语言模型（LLMs）在图形用户界面（GUI）中越来越多地借助自动提示工程来优化用户输入并提升响应的准确性。然而，用户需求的多样性常常导致意外的误解读，自动优化有时会扭曲原始意图并产生错误的输出。为解决这一问题，我们提出了一种名为自适应贪婪二分搜索（AGBS）的方法，该方法在保持语义稳定的同时，模拟了常见的提示优化机制。我们的方法动态评估了这些策略对LLM性能的影响，从而实现了鲁棒的对抗样本生成。通过对开源和闭源的LLMs进行广泛的实验，我们展示了AGBS在平衡语义一致性和攻击效果方面的有效性。我们的研究结果为设计更可靠的提示优化系统提供了可操作的见解。代码可在以下链接获取：https://github.com/franz-chang/DOBS

> Large Language Models (LLMs) increasingly rely on automatic prompt engineering in graphical user interfaces (GUIs) to refine user inputs and enhance response accuracy. However, the diversity of user requirements often leads to unintended misinterpretations, where automated optimizations distort original intentions and produce erroneous outputs. To address this challenge, we propose the Adaptive Greedy Binary Search (AGBS) method, which simulates common prompt optimization mechanisms while preserving semantic stability. Our approach dynamically evaluates the impact of such strategies on LLM performance, enabling robust adversarial sample generation. Through extensive experiments on open and closed-source LLMs, we demonstrate AGBS's effectiveness in balancing semantic consistency and attack efficacy. Our findings offer actionable insights for designing more reliable prompt optimization systems. Code is available at: https://github.com/franz-chang/DOBS

[Arxiv](https://arxiv.org/abs/2506.18756)