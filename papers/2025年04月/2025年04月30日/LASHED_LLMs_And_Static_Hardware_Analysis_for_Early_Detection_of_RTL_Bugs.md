# LASHED：LLMs与静态硬件分析助力RTL Bug早期检测

发布时间：2025年04月30日

`LLM应用` `硬件安全` `漏洞检测`

> LASHED: LLMs And Static Hardware Analysis for Early Detection of RTL Bugs

# 摘要

> 尽管静态分析在早期硬件安全漏洞检测中很有用，但其效果受到限制，因为它需要信息来形成检查，并且通常无法解释检测到的漏洞的安全影响。大语言模型通过识别相关资产，移除静态分析工具标记的误报，并解释报告的违规行为，从而很好地弥补了这些不足。LASHED结合了LLMs和静态分析两种方法，克服了彼此的局限性，从而提升了硬件安全漏洞检测的效果。我们针对五个常见的软件弱点枚举（CWEs），在四个开源片上系统（SoCs）上研究了我们的方法，并提出了通过更好的提示工程优化的策略。发现通过我们的推荐方案标记的实例中，87.5%都是合理的CWE。通过在上下文学习中让模型‘重新思考’，进一步提升了LASHED的检测精度。

> While static analysis is useful in detecting early-stage hardware security bugs, its efficacy is limited because it requires information to form checks and is often unable to explain the security impact of a detected vulnerability. Large Language Models can be useful in filling these gaps by identifying relevant assets, removing false violations flagged by static analysis tools, and explaining the reported violations. LASHED combines the two approaches (LLMs and Static Analysis) to overcome each other's limitations for hardware security bug detection. We investigate our approach on four open-source SoCs for five Common Weakness Enumerations (CWEs) and present strategies for improvement with better prompt engineering. We find that 87.5% of instances flagged by our recommended scheme are plausible CWEs. In-context learning and asking the model to 'think again' improves LASHED's precision.

[Arxiv](https://arxiv.org/abs/2504.21770)