# 推理模型更易出现幻觉生成吗？

发布时间：2025年05月29日

`LLM理论` `事实核查`

> Are Reasoning Models More Prone to Hallucination?

# 摘要

> 最近发展的大型推理模型（LRMs）在解决复杂任务时展现出强大的能力，尤其在长链式推理方面表现突出。然而，这些模型在事实核查任务中是否能通过推理能力减少幻觉现象仍存在争议。例如，DeepSeek-R1在SimpleQA基准上的表现有所提升，但OpenAI-o3却出现了更严重的幻觉。这一现象引出了一个重要问题：推理模型是否更容易产生幻觉？本文从三个角度进行探讨。

首先，我们对LRMs中的幻觉进行了全面评估。分析发现，经过冷启动监督微调（SFT）和可验证奖励强化学习（RL）的完整后训练流程通常能有效减轻幻觉。然而，仅进行知识蒸馏或不进行冷启动微调的强化学习训练会引入更复杂的幻觉。

其次，我们通过行为分析探讨了不同后训练流程对幻觉影响的原因。研究发现，两种关键认知行为直接影响了LRMs的事实性：错误重复，即推理过程反复遵循相同的错误逻辑；以及思考-答案不匹配，即最终答案与之前的推理过程不符。

最后，我们从模型不确定性角度深入探讨了幻觉的机制。研究发现，幻觉的增加通常与模型不确定性与事实准确性之间的不一致有关。本研究为理解LRMs中的幻觉现象提供了重要的初步认识。


> Recently evolved large reasoning models (LRMs) show powerful performance in solving complex tasks with long chain-of-thought (CoT) reasoning capability. As these LRMs are mostly developed by post-training on formal reasoning tasks, whether they generalize the reasoning capability to help reduce hallucination in fact-seeking tasks remains unclear and debated. For instance, DeepSeek-R1 reports increased performance on SimpleQA, a fact-seeking benchmark, while OpenAI-o3 observes even severer hallucination. This discrepancy naturally raises the following research question: Are reasoning models more prone to hallucination? This paper addresses the question from three perspectives. (1) We first conduct a holistic evaluation for the hallucination in LRMs. Our analysis reveals that LRMs undergo a full post-training pipeline with cold start supervised fine-tuning (SFT) and verifiable reward RL generally alleviate their hallucination. In contrast, both distillation alone and RL training without cold start fine-tuning introduce more nuanced hallucinations. (2) To explore why different post-training pipelines alters the impact on hallucination in LRMs, we conduct behavior analysis. We characterize two critical cognitive behaviors that directly affect the factuality of a LRM: Flaw Repetition, where the surface-level reasoning attempts repeatedly follow the same underlying flawed logic, and Think-Answer Mismatch, where the final answer fails to faithfully match the previous CoT process. (3) Further, we investigate the mechanism behind the hallucination of LRMs from the perspective of model uncertainty. We find that increased hallucination of LRMs is usually associated with the misalignment between model uncertainty and factual accuracy. Our work provides an initial understanding of the hallucination in LRMs.

[Arxiv](https://arxiv.org/abs/2505.23646)