# 结构熵引导智能体，检测与修复大语言模型的知识漏洞

发布时间：2025年05月11日

`LLM应用` `科学研究`

> Structural Entropy Guided Agent for Detecting and Repairing Knowledge Deficiencies in LLMs

# 摘要

> 大型语言模型（LLMs）借助庞大的预训练语料库取得了前所未有的性能突破，但在医学和科学研究等知识密集型领域，其表现仍不尽如人意，尤其是在需要高度事实精确性的场景中。尽管合成数据为增强领域知识提供了一条有前景的途径，但现有方法常生成与模型真实知识缺口不匹配的冗余样本。为解决这一问题，我们提出了一种新颖的基于结构熵的知识导航框架——SENATOR，旨在弥补LLMs的知识缺陷。该框架通过结构熵（SE）指标量化知识图谱路径上的不确定性，并借助蒙特卡洛树搜索（MCTS）选择性地探索模型缺乏特定领域知识的区域。基于这些洞见，框架生成针对监督微调的合成数据，从而实现持续的自我改进。实验结果表明，在LLaMA-3和Qwen2上，SENATOR能够有效检测和修复知识缺口，在多个领域特定基准测试中取得了显著的性能提升。我们的方法和实验的代码及数据可在https://github.com/weiyifan1023/senator获取。

> Large language models (LLMs) have achieved unprecedented performance by leveraging vast pretraining corpora, yet their performance remains suboptimal in knowledge-intensive domains such as medicine and scientific research, where high factual precision is required. While synthetic data provides a promising avenue for augmenting domain knowledge, existing methods frequently generate redundant samples that do not align with the model's true knowledge gaps. To overcome this limitation, we propose a novel Structural Entropy-guided Knowledge Navigator (SENATOR) framework that addresses the intrinsic knowledge deficiencies of LLMs. Our approach employs the Structure Entropy (SE) metric to quantify uncertainty along knowledge graph paths and leverages Monte Carlo Tree Search (MCTS) to selectively explore regions where the model lacks domain-specific knowledge. Guided by these insights, the framework generates targeted synthetic data for supervised fine-tuning, enabling continuous self-improvement. Experimental results on LLaMA-3 and Qwen2 across multiple domain-specific benchmarks show that SENATOR effectively detects and repairs knowledge deficiencies, achieving notable performance improvements. The code and data for our methods and experiments are available at https://github.com/weiyifan1023/senator.

[Arxiv](https://arxiv.org/abs/2505.07184)