# # 生成基于事实的回应以对抗虚假信息：通过学习高效细致的批评方法
本研究提出了一种通过学习高效细致的批评方法来生成基于事实的回应，从而有效对抗虚假信息的新方法。

发布时间：2025年06月06日

`LLM应用` `事实核查`

> Generating Grounded Responses to Counter Misinformation via Learning Efficient Fine-Grained Critiques

# 摘要

> # 摘要  
虚假新闻和错误信息对社会危害巨大，亟需有效的应对措施。然而，传统的人工事实核查不仅成本高昂，还难以大规模应用。大型语言模型（LLMs）在自动化生成反制回应以应对错误信息方面展现出巨大潜力，但其生成非事实信息的倾向却是一个亟待解决的难题。现有解决方案主要依赖LLM自身的反馈机制来减少幻觉现象，但这种方法计算成本过高。  
本文提出MisMitiFact，即基于事实的错误信息缓解框架，这是一个高效生成事实依据的反制回应的框架。MisMitiFact通过生成简洁的批判反馈来优化LLM输出，确保回应有据可依。我们开发了轻量级、细致的批判模型，这些模型基于从现成的事实核查网站获取的数据进行训练，能够识别并纠正LLM生成中的关键错误，如数字、实体和主题等。  
实验结果表明，与LLM自身的反馈机制相比，MisMitiFact生成的反制回应质量相当，但使用的批判模型规模显著更小。更重要的是，它将反馈生成吞吐量提高了约5倍，使其非常适合成本效益高、大规模的错误信息缓解工作。代码和LLM提示模板可在https://github.com/xxfwin/MisMitiFact获取。

> Fake news and misinformation poses a significant threat to society, making efficient mitigation essential. However, manual fact-checking is costly and lacks scalability. Large Language Models (LLMs) offer promise in automating counter-response generation to mitigate misinformation, but a critical challenge lies in their tendency to hallucinate non-factual information. Existing models mainly rely on LLM self-feedback to reduce hallucination, but this approach is computationally expensive. In this paper, we propose MisMitiFact, Misinformation Mitigation grounded in Facts, an efficient framework for generating fact-grounded counter-responses at scale. MisMitiFact generates simple critique feedback to refine LLM outputs, ensuring responses are grounded in evidence. We develop lightweight, fine-grained critique models trained on data sourced from readily available fact-checking sites to identify and correct errors in key elements such as numerals, entities, and topics in LLM generations. Experiments show that MisMitiFact generates counter-responses of comparable quality to LLMs' self-feedback while using significantly smaller critique models. Importantly, it achieves ~5x increase in feedback generation throughput, making it highly suitable for cost-effective, large-scale misinformation mitigation. Code and LLM prompt templates are at https://github.com/xxfwin/MisMitiFact.

[Arxiv](https://arxiv.org/abs/2506.05924)