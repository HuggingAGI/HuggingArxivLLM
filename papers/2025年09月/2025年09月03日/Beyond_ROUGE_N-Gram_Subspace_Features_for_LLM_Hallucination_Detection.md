# 超越ROUGE：LLM幻觉检测的N元语法子空间特征

发布时间：2025年09月03日

`LLM应用` `基础理论`

> Beyond ROUGE: N-Gram Subspace Features for LLM Hallucination Detection

# 摘要

> 大型语言模型（LLMs）虽已在各类自然语言任务中展现出强大效能，但幻觉这一核心问题仍困扰着它们，导致其生成一致、真实信息的可信度大打折扣。幻觉检测因此迅速成为研究热点，不确定性估计、LLM 评判器、检索增强生成（RAG）及一致性检查等方法均显示出应用前景。然而，这些方法多依赖 ROUGE、BERTScore、Perplexity 等基础指标，而这些指标往往缺乏有效检测幻觉所需的语义深度。为此，本研究受 ROUGE 启发，提出一种新方法：从 LLM 生成文本中构建 N-Gram 频率张量。该张量通过编码共现模式捕捉更丰富的语义结构，从而能更好地区分事实性内容与幻觉内容。具体而言，我们采用张量分解方法从各模态提取奇异值，并将其作为输入特征训练多层感知器（MLP）二分类器以检测幻觉。在 HaluEval 数据集上的实验表明，我们的方法不仅显著优于传统基线，且与最先进的 LLM 评判器相比也具有竞争力。

> Large Language Models (LLMs) have demonstrated effectiveness across a wide variety of tasks involving natural language, however, a fundamental problem of hallucinations still plagues these models, limiting their trustworthiness in generating consistent, truthful information. Detecting hallucinations has quickly become an important topic, with various methods such as uncertainty estimation, LLM Judges, retrieval augmented generation (RAG), and consistency checks showing promise. Many of these methods build upon foundational metrics, such as ROUGE, BERTScore, or Perplexity, which often lack the semantic depth necessary to detect hallucinations effectively. In this work, we propose a novel approach inspired by ROUGE that constructs an N-Gram frequency tensor from LLM-generated text. This tensor captures richer semantic structure by encoding co-occurrence patterns, enabling better differentiation between factual and hallucinated content. We demonstrate this by applying tensor decomposition methods to extract singular values from each mode and use these as input features to train a multi-layer perceptron (MLP) binary classifier for hallucinations. Our method is evaluated on the HaluEval dataset and demonstrates significant improvements over traditional baselines, as well as competitive performance against state-of-the-art LLM judges.

[Arxiv](https://arxiv.org/abs/2509.05360)