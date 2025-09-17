# 少样本困境：大语言模型的过度提示之困

发布时间：2025年09月16日

`LLM应用` `工业与制造`

> The Few-shot Dilemma: Over-prompting Large Language Models

# 摘要

> 过度提示——指提示中示例过多导致大型语言模型（LLMs）性能下降的现象——对上下文少样本学习的传统认知提出了挑战。为探究这一少样本困境，我们构建了提示框架，采用随机抽样、语义嵌入和TF-IDF向量三种标准少样本选择方法，并在GPT-4o、GPT-3.5-turbo、DeepSeek-V3、Gemma-3、LLaMA-3.1、LLaMA-3.2及Mistral等多个LLM上进行了评估。实验结果显示，在提示中加入过多领域特定示例反而会降低部分LLM的性能，这与此前“更多相关少样本示例普遍对LLMs有益”的实证结论相悖。鉴于LLM辅助软件工程与需求分析的趋势，我们基于两个真实世界的软件需求分类数据集开展实验。通过逐步增加TF-IDF选择与分层抽样的少样本示例数量，我们找到了各LLM的最佳示例规模。这种组合方法以更少示例实现了更优性能，有效规避了过度提示问题，最终在功能与非功能需求分类任务上较现有最佳水平提升了1%。

> Over-prompting, a phenomenon where excessive examples in prompts lead to diminished performance in Large Language Models (LLMs), challenges the conventional wisdom about in-context few-shot learning. To investigate this few-shot dilemma, we outline a prompting framework that leverages three standard few-shot selection methods - random sampling, semantic embedding, and TF-IDF vectors - and evaluate these methods across multiple LLMs, including GPT-4o, GPT-3.5-turbo, DeepSeek-V3, Gemma-3, LLaMA-3.1, LLaMA-3.2, and Mistral. Our experimental results reveal that incorporating excessive domain-specific examples into prompts can paradoxically degrade performance in certain LLMs, which contradicts the prior empirical conclusion that more relevant few-shot examples universally benefit LLMs. Given the trend of LLM-assisted software engineering and requirement analysis, we experiment with two real-world software requirement classification datasets. By gradually increasing the number of TF-IDF-selected and stratified few-shot examples, we identify their optimal quantity for each LLM. This combined approach achieves superior performance with fewer examples, avoiding the over-prompting problem, thus surpassing the state-of-the-art by 1% in classifying functional and non-functional requirements.

[Arxiv](https://arxiv.org/abs/2509.13196)