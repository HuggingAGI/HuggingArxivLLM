# 规模与多样性的邂逅：多语言细粒度声明验证中的语言模型评估

发布时间：2025年07月28日

`LLM应用` `信息真实性评估`

> When Scale Meets Diversity: Evaluating Language Models on Fine-Grained Multilingual Claim Verification

# 摘要

> 多语言虚假信息的迅速蔓延促使我们需要更强大的自动化事实核查系统，以应对多种语言下的细微真实度评估。尽管大型语言模型在众多NLP任务中表现卓越，但其在多语言声明核查，特别是精细分类方案下的有效性仍待深入研究。我们对五个顶尖语言模型在涵盖25种语言和7种真实度类别的X-Fact数据集上进行了全面评估。实验对比了小型语言模型（基于编码器的XLM-R和mT5）与近期仅解码器的大型语言模型（Llama 3.1, Qwen 2.5, Mistral Nemo），分别采用提示和微调方法。令人惊讶的是，XLM-R（270M参数）的表现远超所有测试大型语言模型（7-12B参数），在宏F1指标上达到57.7%，而最佳大型语言模型仅为16.9%。这一成果较之前最先进水平提升了15.8%，树立了多语言事实核查的新标杆。分析显示，大型语言模型存在系统性证据利用困难和不平衡数据下类别偏见等问题。这些发现表明，针对精细多语言事实核查，专门的小型模型可能优于通用大型模型，这对事实核查系统的实际应用具有重要意义。

> The rapid spread of multilingual misinformation requires robust automated fact verification systems capable of handling fine-grained veracity assessments across diverse languages. While large language models have shown remarkable capabilities across many NLP tasks, their effectiveness for multilingual claim verification with nuanced classification schemes remains understudied. We conduct a comprehensive evaluation of five state-of-the-art language models on the X-Fact dataset, which spans 25 languages with seven distinct veracity categories. Our experiments compare small language models (encoder-based XLM-R and mT5) with recent decoder-only LLMs (Llama 3.1, Qwen 2.5, Mistral Nemo) using both prompting and fine-tuning approaches. Surprisingly, we find that XLM-R (270M parameters) substantially outperforms all tested LLMs (7-12B parameters), achieving 57.7% macro-F1 compared to the best LLM performance of 16.9%. This represents a 15.8% improvement over the previous state-of-the-art (41.9%), establishing new performance benchmarks for multilingual fact verification. Our analysis reveals problematic patterns in LLM behavior, including systematic difficulties in leveraging evidence and pronounced biases toward frequent categories in imbalanced data settings. These findings suggest that for fine-grained multilingual fact verification, smaller specialized models may be more effective than general-purpose large models, with important implications for practical deployment of fact-checking systems.

[Arxiv](https://arxiv.org/abs/2507.20700)