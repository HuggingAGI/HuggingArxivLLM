# 「借助于调整表示，提升多语言模型性能」

发布时间：2025年05月18日

`LLM理论` `多语言处理`

> Improving Multilingual Language Models by Aligning Representations through Steering

# 摘要

> 在这篇论文中，我们探讨了大型语言模型（LLMS）如何在其层表示中处理非英语词汇，尽管该领域取得了显著进展，但这一问题仍未得到充分解答。通过向单个模型层的激活添加一个学习向量，我们展示了调整单个模型层能够显著提升性能。我们的分析表明，这种方法可以达到与翻译基线相当的结果，并超越现有的最优提示优化方法。此外，我们还强调了监督微调（	extsc{sft}）和人类反馈强化学习（	extsc{rlhf}）等高级技术如何通过改变表示空间来提升多语言能力。我们进一步展示了这些方法如何与我们的方法相结合，以重塑LLMS的层表示。

> In this paper, we investigate how large language models (LLMS) process non-English tokens within their layer representations, an open question despite significant advancements in the field. Using representation steering, specifically by adding a learned vector to a single model layer's activations, we demonstrate that steering a single model layer can notably enhance performance. Our analysis shows that this approach achieves results comparable to translation baselines and surpasses state of the art prompt optimization methods. Additionally, we highlight how advanced techniques like supervised fine tuning (\textsc{sft}) and reinforcement learning from human feedback (\textsc{rlhf}) improve multilingual capabilities by altering representation spaces. We further illustrate how these methods align with our approach to reshaping LLMS layer representations.

[Arxiv](https://arxiv.org/abs/2505.12584)