# 大型语言模型中的思维链早停

发布时间：2025年09月17日

`LLM应用` `基础理论`

> Early Stopping Chain-of-thoughts in Large Language Models

# 摘要

> 推理大型语言模型（LLMs）凭借生成冗长的思维链（CoT）在解决复杂问题时展现出卓越能力，但其过长的CoT会带来高昂的推理成本。为此，我们提出了ES-CoT——一种推理阶段的优化方法，它通过检测答案收敛来缩短CoT生成过程，实现提前停止且性能损失极小。具体而言，在每个推理步骤结束时，我们会提示LLM输出当前的“步骤答案”（即当前的最终答案），并将连续相同步骤答案的“运行长度”作为衡量答案收敛的指标。当运行长度出现显著跃升并超过预设阈值时，便终止CoT生成。我们从理论与实验两方面验证了这一方法的合理性：步骤答案会稳定收敛至最终答案，而运行长度的大幅增加正是收敛的可靠信号。在三个LLM的五个推理数据集上的实验显示，ES-CoT平均能减少约41%的推理token用量，同时准确率与标准CoT不相上下。更重要的是，ES-CoT可与自一致性提示无缝结合，且对超参数选择表现稳健，堪称高效推理的实用利器。

> Reasoning large language models (LLMs) have demonstrated superior capacities in solving complicated problems by generating long chain-of-thoughts (CoT), but such a lengthy CoT incurs high inference costs. In this study, we introduce ES-CoT, an inference-time method that shortens CoT generation by detecting answer convergence and stopping early with minimal performance loss. At the end of each reasoning step, we prompt the LLM to output its current final answer, denoted as a step answer. We then track the run length of consecutive identical step answers as a measure of answer convergence. Once the run length exhibits a sharp increase and exceeds a minimum threshold, the generation is terminated. We provide both empirical and theoretical support for this heuristic: step answers steadily converge to the final answer, and large run-length jumps reliably mark this convergence. Experiments on five reasoning datasets across three LLMs show that ES-CoT reduces the number of inference tokens by about 41\% on average while maintaining accuracy comparable to standard CoT. Further, ES-CoT integrates seamlessly with self-consistency prompting and remains robust across hyperparameter choices, highlighting it as a practical and effective approach for efficient reasoning.

[Arxiv](https://arxiv.org/abs/2509.14004)