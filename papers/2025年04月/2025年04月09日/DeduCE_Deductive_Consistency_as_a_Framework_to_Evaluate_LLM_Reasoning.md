# DeduCE：评估LLM推理能力的演绎一致性框架

发布时间：2025年04月09日

`LLM理论` `人工智能`

> DeduCE: Deductive Consistency as a Framework to Evaluate LLM Reasoning

# 摘要

> 尽管在高难度推理问题上表现出色，前沿大型语言模型在处理全新高中数学问题时仍可能遇到挑战。我们提出了一种演绎一致性指标，深入分析语言模型的链式思维输出，超越简单的准确率评估。演绎推理涉及两个关键环节：理解输入前提与推导结论。我们通过该指标研究模型在这两个环节的表现，旨在揭示其在全新问题上的推理误区：模型在理解输入前提时的表现如何？在多跳推理中推导结论的能力又如何？由于现有基准可能被模型记住，我们开发了一套评估管道，用于测试模型在全新且经过扰动的基准问题上的演绎一致性。在全新小学数学问题 (GSM-8k) 上，我们发现模型对不断增加的输入前提数量表现稳健，但推理跳数增加时，准确率显著下降。有趣的是，这些错误在原始基准中被掩盖，因为所有模型都达到了接近 100% 的准确率。通过合成数据集增加解决方案步骤后，多跳推理仍然是主要错误来源，相比之下，理解输入前提的表现更为稳定。其他因素如语言风格转变或早期错误传播并不能解释这一趋势。我们的分析为理解模型推理提供了一个全新视角——将其视为对输入前提窗口和推理跳数的计算——从而实现跨领域统一评估。

> Despite great performance on Olympiad-level reasoning problems, frontier large language models can still struggle on high school math when presented with novel problems outside standard benchmarks. Going beyond final accuracy, we propose a deductive consistency metric to analyze chain-of-thought output from language models (LMs).Formally, deductive reasoning involves two subtasks: understanding a set of input premises and inferring the conclusions that follow from them. The proposed metric studies LMs' performance on these subtasks, with the goal of explaining LMs' reasoning errors on novel problems: how well do LMs understand input premises with increasing context lengths, and how well can they infer conclusions over multiple reasoning hops? Since existing benchmarks may be memorized, we develop a pipeline to evaluate LMs' deductive consistency on novel, perturbed versions of benchmark problems. On novel grade school math problems (GSM-8k), we find that LMs are fairly robust to increasing number of input premises, but suffer significant accuracy decay as the number of reasoning hops is increased. Interestingly, these errors are masked in the original benchmark as all models achieve near 100% accuracy. As we increase the number of solution steps using a synthetic dataset, prediction over multiple hops still remains the major source of error compared to understanding input premises. Other factors, such as shifts in language style or natural propagation of early errors do not explain the trends. Our analysis provides a new view to characterize LM reasoning -- as computations over a window of input premises and reasoning hops -- that can provide unified evaluation across problem domains.

[Arxiv](https://arxiv.org/abs/2504.07080)