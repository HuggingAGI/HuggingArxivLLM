# 推理模型中的动态早期退出机制

发布时间：2025年04月22日

`LLM应用

理由：这篇论文讨论了如何优化大型推理语言模型（LRLMs）的推理过程，提出了一种通过早期退出实现推理链自我截断的方法。这种方法属于对大语言模型的应用优化，旨在提高模型在特定推理任务中的效率和准确率，因此归类为LLM应用。` `问题解决`

> Dynamic Early Exit in Reasoning Models

# 摘要

> 近期，大型推理语言模型（LRLMs）的进步依赖于测试时扩展，将长推理链生成扩展到解决复杂任务。然而，长推理链中的过度思考不仅降低了问题解决的效率，还可能因推理步骤过于冗长或重复而导致准确率下降。我们提出了一种简单而有效的方法，使大语言模型能够在生成过程中通过早期退出实现推理链的自我截断。与依赖固定启发式方法不同，我们的方法会在潜在的推理过渡点（例如，“Wait”标记）监控模型行为，并在模型对某个候选答案表现出高度信心时，动态终止后续推理链的生成。该方法无需额外训练，可无缝集成到现有的o1-like推理大语言模型中。在MATH-500、AMC 2023、GPQA Diamond和AIME 2024等多个推理基准测试中的实验表明，该方法在深度求索系列推理大语言模型上表现一致有效，平均将推理链长度缩短31%至43%，同时将准确率提升1.7%至5.7%。

> Recent advances in large reasoning language models (LRLMs) rely on test-time scaling, which extends long chain-of-thought (CoT) generation to solve complex tasks. However, overthinking in long CoT not only slows down the efficiency of problem solving, but also risks accuracy loss due to the extremely detailed or redundant reasoning steps. We propose a simple yet effective method that allows LLMs to self-truncate CoT sequences by early exit during generation. Instead of relying on fixed heuristics, the proposed method monitors model behavior at potential reasoning transition points (e.g.,"Wait" tokens) and dynamically terminates the next reasoning chain's generation when the model exhibits high confidence in a trial answer. Our method requires no additional training and can be seamlessly integrated into existing o1-like reasoning LLMs. Experiments on multiple reasoning benchmarks MATH-500, AMC 2023, GPQA Diamond and AIME 2024 show that the proposed method is consistently effective on deepseek-series reasoning LLMs, reducing the length of CoT sequences by an average of 31% to 43% while improving accuracy by 1.7% to 5.7%.

[Arxiv](https://arxiv.org/abs/2504.15895)