# 推理之旅的起点迷航

发布时间：2025年06月27日

`LLM理论

摘要主要探讨了大型语言模型在复杂推理过程中的自我纠正能力，分析了初始推理步骤对最终结果的影响，并提出了优化策略。这属于对LLM内部机制的理论研究，因此归类为LLM理论。` `人工智能` `机器学习`

> Lost at the Beginning of Reasoning

# 摘要

> 大型语言模型（LLMs）的最新进展显著提升了复杂推理能力，尤其通过引入回溯、自我反思和自我纠正等机制的扩展型思维链（CoT）推理。然而，LLMs在长CoT推理过程中的自我纠正能力仍未得到充分探索。近期研究发现，这类模型常常陷入不必要的冗余推理。在本研究中，我们实证发现：初始推理步骤对最终预测结果具有显著且不成比例的影响——该阶段产生的错误会严重影响后续推理质量。这一现象在DeepSeek-R1 和 Qwen3两个先进的开源推理模型家族中得到了一致验证。为解决这一问题，我们提出了一种高效的采样策略，借助奖励模型识别并保留高质量的初始推理步骤，同时淘汰次优选项，从而实现高达70%的推理成本降低，且不影响准确性。最后，我们引入了一个全新的基准测试，特意设计了有缺陷的初始推理步骤，以系统性评估模型的自我纠正能力，为未来在LLMs中实现稳健推理的研究奠定了基础。

> Recent advancements in large language models (LLMs) have significantly advanced complex reasoning capabilities, particularly through extended chain-of-thought (CoT) reasoning that incorporates mechanisms such as backtracking, self-reflection and self-correction. Despite these developments, the self-correction abilities of LLMs during long CoT reasoning remain underexplored. And recent findings on overthinking suggest that such models often engage in unnecessarily redundant reasoning. In this work, we empirically show that the first reasoning step exerts a disproportionately large influence on the final prediction - errors introduced at this stage can substantially degrade subsequent reasoning quality. This phenomenon is consistently observed across two state-of-the-art open-source reasoning model families: DeepSeek-R1 and Qwen3. To address this, we propose an efficient sampling strategy that leverages a reward model to identify and retain high-quality first reasoning steps while discarding suboptimal ones, achieving up to a 70% reduction in inference cost without sacrificing accuracy. Finally, we introduce a new benchmark specifically constructed with deliberately flawed first reasoning steps to systematically evaluate model self-correction capabilities, offering a foundation for future research on robust reasoning in LLMs.

[Arxiv](https://arxiv.org/abs/2506.22058)