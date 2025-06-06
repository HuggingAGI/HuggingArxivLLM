# 推理还是过度思考？评估大型语言模型在金融情感分析中的表现

发布时间：2025年06月04日

`LLM应用` `情感分析`

> Reasoning or Overthinking: Evaluating Large Language Models on Financial Sentiment Analysis

# 摘要

> 我们研究了包括基于推理和非推理模型在内的大型语言模型（LLMs），在零样本金融情感分析中的有效性。通过使用由领域专家标注的金融语料库数据集，我们评估了各种LLMs和提示策略在金融语境下与人工标注情感的对齐程度。我们比较了三个专有LLMs（GPT-4o、GPT-4.1、o3-mini）在不同提示范式下的表现，这些范式模拟了System 1（快速且直觉的）或System 2（缓慢且深思熟虑的）思维方式，并将其与两个较小模型（FinBERT-Prosus、FinBERT-Tone）进行了基准测试，这些模型专门针对金融情感分析进行了微调。研究发现，无论是通过提示还是模型设计的推理，并未提升在此任务上的性能。令人惊讶的是，最准确且与人类判断高度一致的模型与方法组合是未使用任何链式思维（CoT）提示的GPT-4o。我们进一步探讨了语言复杂性和标注一致性水平对性能的影响，发现推理可能会导致过度思考，从而产生次优预测。这表明，在金融情感分类中，快速、直觉的“System 1”式思考与人类判断的契合度更高，而“System 2”式缓慢、深思熟虑的推理（由推理模型或CoT提示模拟）则不然。我们的研究结果挑战了默认假设，即更多的推理总是能带来更好的LLM决策，尤其是在高风险的金融应用中。

> We investigate the effectiveness of large language models (LLMs), including reasoning-based and non-reasoning models, in performing zero-shot financial sentiment analysis. Using the Financial PhraseBank dataset annotated by domain experts, we evaluate how various LLMs and prompting strategies align with human-labeled sentiment in a financial context. We compare three proprietary LLMs (GPT-4o, GPT-4.1, o3-mini) under different prompting paradigms that simulate System 1 (fast and intuitive) or System 2 (slow and deliberate) thinking and benchmark them against two smaller models (FinBERT-Prosus, FinBERT-Tone) fine-tuned on financial sentiment analysis. Our findings suggest that reasoning, either through prompting or inherent model design, does not improve performance on this task. Surprisingly, the most accurate and human-aligned combination of model and method was GPT-4o without any Chain-of-Thought (CoT) prompting. We further explore how performance is impacted by linguistic complexity and annotation agreement levels, uncovering that reasoning may introduce overthinking, leading to suboptimal predictions. This suggests that for financial sentiment classification, fast, intuitive "System 1"-like thinking aligns more closely with human judgment compared to "System 2"-style slower, deliberative reasoning simulated by reasoning models or CoT prompting. Our results challenge the default assumption that more reasoning always leads to better LLM decisions, particularly in high-stakes financial applications.

[Arxiv](https://arxiv.org/abs/2506.04574)