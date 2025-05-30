# 从Token到动作：通过状态机推理缓解信息检索中的过度思考

发布时间：2025年05月29日

`LLM应用

摘要中讨论了链式思维提示在大型语言模型中的应用，特别是在信息检索领域的优化，提出了一种新的推理框架来提升性能和效率，属于应用层面的改进。` `信息检索`

> From Token to Action: State Machine Reasoning to Mitigate Overthinking in Information Retrieval

# 摘要

> 链式思维提示助力大型语言模型复杂推理，尤其在信息检索领域展现潜力。然而，该方法常导致过犹不及，生成冗长且语义重复的推理轨迹，却无明显收益。针对信息检索中的两大挑战——重复访问相似状态的冗余轨迹和偏离用户意图的错误推理，我们提出基于状态机的推理（SMR）。该框架通过离散动作（细化、重排序、停止）实现早期终止和精细控制。实验结果显示，SMR在BEIR和BRIGHT基准测试中将检索性能（nDCG@10）提升3.4%，同时将token使用量减少74.4%。其优势在于通用性强，无需特定任务调优，为传统链式推理提供实用替代方案。更多详情请访问https://github.com/ldilab/SMR。

> Chain-of-Thought (CoT) prompting enables complex reasoning in large language models (LLMs), including applications in information retrieval (IR). However, it often leads to overthinking, where models produce excessively long and semantically redundant traces with little or no benefit. We identify two key challenges in IR: redundant trajectories that revisit similar states and misguided reasoning that diverges from user intent. To address these, we propose State Machine Reasoning (SMR), a transition-based reasoning framework composed of discrete actions (Refine, Rerank, Stop) that support early stopping and fine-grained control. Experiments on the BEIR and BRIGHT benchmarks show that SMR improves retrieval performance (nDCG@10) by 3.4% while reducing token usage by 74.4%. It generalizes across LLMs and retrievers without requiring task-specific tuning, offering a practical alternative to conventional CoT reasoning. The code and details are available at https://github.com/ldilab/SMR.

[Arxiv](https://arxiv.org/abs/2505.23059)