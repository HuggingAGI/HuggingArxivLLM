# SemViQA：一个用于越南语信息核查的语义问答系统。

发布时间：2025年03月02日

`LLM应用

理由：这篇论文讨论了大型语言模型在事实核查中的应用，特别是在越南语这种资源较少的语言中的应用。它提出了一种新的事实核查框架，并展示了其在实际数据集中的性能。因此，它属于LLM应用类别。` `信息科学`

> SemViQA: A Semantic Question Answering System for Vietnamese Information Fact-Checking

# 摘要

> 虚假信息的泛滥问题因 GPT 和 Gemini 等大型语言模型 (LLMs) 的兴起而日益严重，尤其是在越南语等资源较少的语言中，亟需强大的事实核查解决方案。现有方法在面对语义模糊、同义词和复杂语言结构时往往以牺牲准确性换取效率。我们推出了一款全新的越南语事实核查框架 SemViQA，该框架融合了基于语义的证据检索 (SER) 和两步判决分类 (TVC)。我们的方法在精度和速度之间找到了完美平衡，在 ISE-DSC01 数据集上达到了 78.97\% 的严格准确率，在 ViWikiFC 数据集上达到了 80.82\% 的准确率，斩获 UIT 数据科学挑战赛第一名。此外，SemViQA Faster 版本在保持竞争力的同时，将推理速度提升了 7 倍。SemViQA 为越南语事实核查树立了新的基准，为打击虚假信息的斗争增添了重要力量。源代码可在以下链接获取：https://github.com/DAVID-NGUYEN-S16/SemViQA。
    

> The rise of misinformation, exacerbated by Large Language Models (LLMs) like GPT and Gemini, demands robust fact-checking solutions, especially for low-resource languages like Vietnamese. Existing methods struggle with semantic ambiguity, homonyms, and complex linguistic structures, often trading accuracy for efficiency. We introduce SemViQA, a novel Vietnamese fact-checking framework integrating Semantic-based Evidence Retrieval (SER) and Two-step Verdict Classification (TVC). Our approach balances precision and speed, achieving state-of-the-art results with 78.97\% strict accuracy on ISE-DSC01 and 80.82\% on ViWikiFC, securing 1st place in the UIT Data Science Challenge. Additionally, SemViQA Faster improves inference speed 7x while maintaining competitive accuracy. SemViQA sets a new benchmark for Vietnamese fact verification, advancing the fight against misinformation. The source code is available at: https://github.com/DAVID-NGUYEN-S16/SemViQA.

[Arxiv](https://arxiv.org/abs/2503.00955)