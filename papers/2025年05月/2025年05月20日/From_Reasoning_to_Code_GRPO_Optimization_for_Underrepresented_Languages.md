# 从推理到代码：GRPO 优化助力小语种

发布时间：2025年05月20日

`LLM应用` `代码生成`

> From Reasoning to Code: GRPO Optimization for Underrepresented Languages

# 摘要

> 大型语言模型 (LLMs) 在为训练数据有限的语言生成准确且可执行的代码方面更具挑战性，相较于 Python 等流行语言。本文提出了一种通用方法，结合 Qwen 2.5 模型的小规模代码版本与组相对策略优化 (GRPO)，通过显式推理步骤实现有效的代码生成，尤其适用于源代码数据库较小的语言。以 Prolog 为例——鉴于其在线资源有限——初始模型在生成可执行代码方面面临困难。经过一些训练步骤后，模型通过将推理驱动的反馈直接整合到强化学习循环中，成功生成了逻辑一致且语法准确的代码。通过数学逻辑问题基准进行的实验评估表明，在推理质量、代码准确性和逻辑正确性方面均有显著提升，突显了该方法为缺乏大量训练资源的多种编程语言带来潜在益处。


> Generating accurate and executable code using large language models (LLMs) is challenging for languages with limited public training data compared to popular languages such as Python. This paper introduces a generalizable approach that uses small-scale code versions of the Qwen 2.5 model combined with Group Relative Policy Optimization (GRPO) to enable effective code generation through explicit reasoning steps, which is particularly beneficial for languages with smaller source code databases. Using Prolog as a representative use case -- given its limited online presence -- the initial model faced challenges in generating executable code. After some training steps, the model successfully produces logically consistent and syntactically accurate code by directly integrating reasoning-driven feedback into the reinforcement learning loop. Experimental evaluations using mathematical logic problem benchmarks illustrate significant improvements in reasoning quality, code accuracy, and logical correctness, underscoring the potential of this approach to benefit a wide range of programming languages lacking extensive training resources.

[Arxiv](https://arxiv.org/abs/2506.11027)