# Med-R$^2$: 通过循证医学的检索与推理，构建可信赖的LLM医生

发布时间：2025年01月20日

`RAG

理由：这篇论文提出了一个名为Med-R^2的框架，该框架通过整合检索机制及证据的选择与推理过程，提升了大型语言模型（LLMs）在医疗场景中的问题解决能力。这涉及到检索增强生成（Retrieval-Augmented Generation, RAG）技术，即通过检索外部知识库来增强LLMs的生成能力。因此，这篇论文应被分类为RAG。` `循证医学`

> Med-R$^2$: Crafting Trustworthy LLM Physicians through Retrieval and Reasoning of Evidence-Based Medicine

# 摘要

> 近年来，大型语言模型（LLMs）在临床场景中表现出了卓越的能力。然而，尽管潜力巨大，现有研究在将LLMs应用于医疗环境时仍面临诸多挑战。依赖医疗数据集进行训练的策略不仅成本高昂，还可能因数据过时而失效。利用外部知识库虽是一种可行的替代方案，但存在检索精度不足和答案提取效果不佳等问题。这些问题共同限制了LLMs在医学专业知识掌握上的表现。为此，我们提出了Med-R^2，一个遵循循证医学（EBM）流程的新型LLM医生框架。该框架通过高效整合检索机制及证据的选择与推理过程，显著提升了LLMs在医疗场景中的问题解决能力，并构建了一个可信赖的LLM医生。实验结果表明，Med-R^2在无需额外训练成本的情况下，相比普通RAG方法提升了14.87%，甚至比微调策略高出3.59%。

> In recent years, Large Language Models (LLMs) have exhibited remarkable capabilities in clinical scenarios. However, despite their potential, existing works face challenges when applying LLMs to medical settings. Strategies relying on training with medical datasets are highly cost-intensive and may suffer from outdated training data. Leveraging external knowledge bases is a suitable alternative, yet it faces obstacles such as limited retrieval precision and poor effectiveness in answer extraction. These issues collectively prevent LLMs from demonstrating the expected level of proficiency in mastering medical expertise. To address these challenges, we introduce Med-R^2, a novel LLM physician framework that adheres to the Evidence-Based Medicine (EBM) process, efficiently integrating retrieval mechanisms as well as the selection and reasoning processes of evidence, thereby enhancing the problem-solving capabilities of LLMs in healthcare scenarios and fostering a trustworthy LLM physician. Our comprehensive experiments indicate that Med-R^2 achieves a 14.87\% improvement over vanilla RAG methods and even a 3.59\% enhancement compared to fine-tuning strategies, without incurring additional training costs.

[Arxiv](https://arxiv.org/abs/2501.11885)