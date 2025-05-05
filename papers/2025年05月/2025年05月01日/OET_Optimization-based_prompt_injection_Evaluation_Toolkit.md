# OET: 优化驱动的提示注入评估工具包

发布时间：2025年05月01日

`LLM应用

摘要中提到的OET工具包是一个应用于评估和防御提示注入攻击的工具，属于LLM的实际应用和工具开发，因此归类为LLM应用。` `人工智能`

> OET: Optimization-based prompt injection Evaluation Toolkit

# 摘要

> 大型语言模型（LLMs）凭借其卓越的自然语言理解和生成能力，在多个领域得到了广泛应用。然而，这些模型容易受到提示注入攻击，带来严重的安全风险，因为恶意输入可以操纵模型行为并覆盖预期指令。尽管已有多种防御策略，但缺乏一个标准化的框架来严格评估这些策略的有效性，尤其是在适应性对抗场景下。为了解决这一问题，我们引入了OET，一个基于优化的评估工具包。它通过适应性测试框架，在多样化的数据集上系统地基准测试提示注入攻击和防御。我们的工具包具备模块化工作流，支持对抗字符串生成、动态攻击执行和全面结果分析，提供了一个统一的平台来评估对抗鲁棒性。适应性测试框架利用优化方法，结合白盒和黑盒访问，生成最坏情况下的对抗样本，从而实现严格的红队评估。大量实验表明了当前防御机制的局限性，即使在实施安全增强后，某些模型仍可能受到攻击。

> Large Language Models (LLMs) have demonstrated remarkable capabilities in natural language understanding and generation, enabling their widespread adoption across various domains. However, their susceptibility to prompt injection attacks poses significant security risks, as adversarial inputs can manipulate model behavior and override intended instructions. Despite numerous defense strategies, a standardized framework to rigorously evaluate their effectiveness, especially under adaptive adversarial scenarios, is lacking. To address this gap, we introduce OET, an optimization-based evaluation toolkit that systematically benchmarks prompt injection attacks and defenses across diverse datasets using an adaptive testing framework. Our toolkit features a modular workflow that facilitates adversarial string generation, dynamic attack execution, and comprehensive result analysis, offering a unified platform for assessing adversarial robustness. Crucially, the adaptive testing framework leverages optimization methods with both white-box and black-box access to generate worst-case adversarial examples, thereby enabling strict red-teaming evaluations. Extensive experiments underscore the limitations of current defense mechanisms, with some models remaining susceptible even after implementing security enhancements.

[Arxiv](https://arxiv.org/abs/2505.00843)