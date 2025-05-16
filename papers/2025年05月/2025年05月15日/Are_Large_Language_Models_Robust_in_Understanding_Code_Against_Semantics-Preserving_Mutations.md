# 大型语言模型在理解代码方面是否稳健？——对抗语义保留变异的测试

发布时间：2025年05月15日

`LLM应用` `软件工程`

> Are Large Language Models Robust in Understanding Code Against Semantics-Preserving Mutations?

# 摘要

> 理解大型语言模型（LLMs）的推理能力和鲁棒性对于其在编程任务中的可靠应用至关重要。尽管 recent studies 已经评估了 LLMs 预测程序输出的能力，但大多数研究仅关注预测的准确性，而没有评估其背后的推理过程。此外，在数学推理任务中发现，LLMs 可能通过有缺陷的逻辑得出正确的答案，这引发了人们对代码理解中类似问题的担忧。

在本研究中，我们评估了参数量高达80亿的先进 LLMs 是否能够真正理解 Python 程序，或者只是在随机猜测。我们采用了五种保留语义的代码变异方法：重命名变量、镜像比较表达式、交换 if-else 分支、将 for 循环转换为 while 循环，以及展开循环。这些变异方法保持了程序的语义，但改变了其语法结构。我们对六种 LLMs 进行了评估，并使用 LiveCodeBench 进行了专家分析，以判断正确的预测是否基于合理的推理。同时，我们在 LiveCodeBench 和 CruxEval 上评估了不同代码变异下预测结果的稳定性。研究发现，某些 LLMs，如 Llama3.2，在高达 61% 的情况下基于有缺陷的推理得出正确预测。此外，LLMs 经常因我们的代码变异而改变预测结果，表明其对语义理解的鲁棒性有限。

> Understanding the reasoning and robustness of Large Language Models (LLMs) is critical for their reliable use in programming tasks. While recent studies have assessed LLMs' ability to predict program outputs, most focus solely on the accuracy of those predictions, without evaluating the reasoning behind them. Moreover, it has been observed on mathematical reasoning tasks that LLMs can arrive at correct answers through flawed logic, raising concerns about similar issues in code understanding.
  In this work, we evaluate whether state-of-the-art LLMs with up to 8B parameters can reason about Python programs or are simply guessing. We apply five semantics-preserving code mutations: renaming variables, mirroring comparison expressions, swapping if-else branches, converting for loops to while, and loop unrolling. These mutations maintain program semantics while altering its syntax. We evaluated six LLMs and performed a human expert analysis using LiveCodeBench to assess whether the correct predictions are based on sound reasoning. We also evaluated prediction stability across different code mutations on LiveCodeBench and CruxEval. Our findings show that some LLMs, such as Llama3.2, produce correct predictions based on flawed reasoning in up to 61% of cases. Furthermore, LLMs often change predictions in response to our code mutations, indicating limited robustness in their semantic understanding.

[Arxiv](https://arxiv.org/abs/2505.10443)