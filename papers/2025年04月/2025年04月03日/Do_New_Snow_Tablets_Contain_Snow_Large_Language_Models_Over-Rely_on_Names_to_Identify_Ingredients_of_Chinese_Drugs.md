# “新雪片”真含雪？大型语言模型识别中药成分时过于依赖名称

发布时间：2025年04月03日

`LLM应用` `中医药`

> Do "New Snow Tablets" Contain Snow? Large Language Models Over-Rely on Names to Identify Ingredients of Chinese Drugs

# 摘要

> 传统中医（TCM）在医疗领域广泛应用，专门用于临床应用的大型语言模型（LLMs）应运而生。然而，这些模型在识别中药成分时面临诸多挑战。通过系统性分析，我们发现模型往往对药名进行字面解读，过度使用无关草药，并在面对不熟悉配方时表现不稳定。此外，LLMs还无法理解验证任务。这些发现表明，目前的LLMs主要依赖于药名，而非具备系统的药理学知识。针对这些局限性，我们提出了一种基于成分名称的检索增强生成（RAG）方法。在220种中药配方的测试中，该方法将成分验证任务的准确率从约50%显著提升至82%。我们的研究揭示了当前中医专用LLMs的关键弱点，并提供了一种实用的解决方案，以提升其临床可靠性。


> Traditional Chinese Medicine (TCM) has seen increasing adoption in healthcare, with specialized Large Language Models (LLMs) emerging to support clinical applications. A fundamental requirement for these models is accurate identification of TCM drug ingredients. In this paper, we evaluate how general and TCM-specialized LLMs perform when identifying ingredients of Chinese drugs. Our systematic analysis reveals consistent failure patterns: models often interpret drug names literally, overuse common herbs regardless of relevance, and exhibit erratic behaviors when faced with unfamiliar formulations. LLMs also fail to understand the verification task. These findings demonstrate that current LLMs rely primarily on drug names rather than possessing systematic pharmacological knowledge. To address these limitations, we propose a Retrieval Augmented Generation (RAG) approach focused on ingredient names. Experiments across 220 TCM formulations show our method significantly improves accuracy from approximately 50% to 82% in ingredient verification tasks. Our work highlights critical weaknesses in current TCM-specific LLMs and offers a practical solution for enhancing their clinical reliability.

[Arxiv](https://arxiv.org/abs/2504.03786)