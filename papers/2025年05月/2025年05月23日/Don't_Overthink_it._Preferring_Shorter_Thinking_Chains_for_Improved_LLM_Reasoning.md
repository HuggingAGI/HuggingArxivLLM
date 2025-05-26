# 不要想太多！简短的思维链让LLM推理更出色。

发布时间：2025年05月23日

`LLM应用

这篇论文探讨了如何优化大型语言模型（LLMs）的推理过程，提出了一种新的方法short-m@k，以提高推理效率和准确性。该研究属于LLM应用领域，因为它专注于优化LLMs在推理任务中的实际应用。` `人工智能`

> Don't Overthink it. Preferring Shorter Thinking Chains for Improved LLM Reasoning

# 摘要

> 推理型大型语言模型（LLMs）通过生成冗长的“思考链”来完成复杂推理任务，这种方法虽然展现了引人注目的结果，但计算成本和推理时间居高不下。本研究颠覆性地提出：更长的思考链未必带来更强的推理能力。我们发现，在单一问题中采用较短的推理链，正确回答的可能性显著提高，与同一问题中最长的思考链相比，准确率提升了34.5%。基于这一发现，我们提出了short-m@k这一创新性推理方法：通过并行生成k个独立的推理过程，并在前m个思考完成时立即终止计算，最终答案则通过这m个链中的多数投票法决定。基础版short-1@k在低计算资源环境下表现与标准多数投票法相当，甚至更优，同时减少了高达40%的思考链长度。short-3@k虽然在效率上略逊于short-1@k，但在所有计算资源预算下均超越了多数投票法，且速度显著提升（最多减少33%的运行时间）。受此启发，我们使用短、长及随机选择的推理链对LLM进行微调。结果表明，采用较短的推理链进行训练能带来更好的模型性能。我们的研究发现促使我们重新思考当前推理型LLM在推理阶段的计算方式，强调了“更长的思考”并不必然带来更好的性能，甚至可能在反直觉的情况下导致结果下降。

> Reasoning large language models (LLMs) heavily rely on scaling test-time compute to perform complex reasoning tasks by generating extensive "thinking" chains. While demonstrating impressive results, this approach incurs significant computational costs and inference time. In this work, we challenge the assumption that long thinking chains results in better reasoning capabilities. We first demonstrate that shorter reasoning chains within individual questions are significantly more likely to yield correct answers - up to 34.5% more accurate than the longest chain sampled for the same question. Based on these results, we suggest short-m@k, a novel reasoning LLM inference method. Our method executes k independent generations in parallel and halts computation once the first m thinking processes are done. The final answer is chosen using majority voting among these m chains. Basic short-1@k demonstrates similar or even superior performance over standard majority voting in low-compute settings - using up to 40% fewer thinking tokens. short-3@k, while slightly less efficient than short-1@k, consistently surpasses majority voting across all compute budgets, while still being substantially faster (up to 33% wall time reduction). Inspired by our results, we finetune an LLM using short, long, and randomly selected reasoning chains. We then observe that training on the shorter ones leads to better performance. Our findings suggest rethinking current methods of test-time compute in reasoning LLMs, emphasizing that longer "thinking" does not necessarily translate to improved performance and can, counter-intuitively, lead to degraded results.

[Arxiv](https://arxiv.org/abs/2505.17813)