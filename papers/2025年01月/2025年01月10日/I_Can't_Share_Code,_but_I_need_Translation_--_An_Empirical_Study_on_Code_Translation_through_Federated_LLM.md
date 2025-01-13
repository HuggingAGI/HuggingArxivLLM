# 无法分享代码，但需翻译——基于联邦LLM的代码翻译实证研究

发布时间：2025年01月10日

`LLM应用

**解释**：这篇论文讨论了使用预训练的大型语言模型（LLMs）进行代码翻译的问题，并提出了一种基于联邦学习的LLM方法，使客户端能够在本地微调模型而不共享敏感数据。这属于LLM在实际应用中的使用，因此分类为LLM应用。` `软件工程` `编程语言`

> I Can't Share Code, but I need Translation -- An Empirical Study on Code Translation through Federated LLM

# 摘要

> 随着技术和项目需求的快速演变，组织需要将软件项目中的代码库升级到新版本的编程语言，甚至完全转换为全新的语言。然而，代码翻译不仅资源密集，还需要精通源语言和目标语言。尽管研究人员在自动化翻译旧语言和现代语言之间取得了进展，但最近的工作越来越多地转向使用预训练的大型语言模型（LLMs）来高效地进行翻译。
    鉴于代码的专有性质，组织更倾向于在本地微调LLMs，而不是依赖外部API。本研究首次提出了一种基于联邦LLM的代码翻译方法，使客户端能够在不共享敏感数据的情况下联合训练代码翻译器。研究表明，参与者可以协作开发一个FedLLM，用于高效的代码翻译（特别是C#到Java及其反向），与单个客户端模型相比，结果更优（CodeLLaMA的CodeBLEU分数提高了40%以上）。我们的研究结果表明，FedLLM提供了一种协作的代码翻译方法，并可能成为该领域未来研究的一个有前景的方向。

> Owing to the rapid evolution of technologies and project requirements, organizations need to upgrade the code base in their software projects to a new version of the programming language or even translating to an entirely new one. However, code translation is resource-intensive and requires expertise in both the source and target languages. While researchers have made progress in automating translations between legacy and modern languages, recent work has increasingly turned to pre-trained Large Language Models (LLMs) to translate efficiently.
  Given the proprietary nature of code, organizations prefer fine-tuning LLMs locally rather than relying on external APIs. This is one of the first empirical studies that proposes a Federated LLM-based approach for code translation. The proposed approach enables clients to jointly train a code translator without sharing sensitive data. This study demonstrates that participants can collaboratively develop a FedLLM for efficient code translation (particularly C\# to Java and vice-versa) with superior results (more than 40\% improvement in CodeLLaMA's CodeBLEU score) compared to individual client models. Our findings indicate that FedLLM offers a collaborative approach to code translation and could serve as a promising direction for future research in this field.

[Arxiv](https://arxiv.org/abs/2501.05724)