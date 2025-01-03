# 一种基于本体的方法，助力用户中心化与知识驱动的AI系统解释

发布时间：2024年10月22日

`LLM应用

理由：这篇论文主要讨论了如何通过知识增强的问答管道和解释本体来提升大型语言模型在临床环境中的性能，并支持上下文解释。这涉及到将大型语言模型应用于特定领域（临床环境）的实际问题解决，因此属于LLM应用的范畴。` `人工智能`

> An Ontology-Enabled Approach For User-Centered and Knowledge-Enabled Explanations of AI Systems

# 摘要

> # 摘要
可解释人工智能（AI）致力于帮助人类理解AI系统或其决策的工作原理，几十年来一直是AI的核心。最近的研究聚焦于AI模型的工作原理或模型可解释性。尽管有几份立场声明和综述论文详细阐述了终端用户对以用户为中心的可解释性的需求，但实际实现较少。因此，本论文旨在弥合模型可解释性和以用户为中心的可解释性之间的差距。我们创建了一个解释本体（EO），通过其支持组件来表示文献中的解释类型。我们实现了一个知识增强的问答（QA）管道，以支持临床环境中的上下文解释。此外，我们正在开发一个系统，用于结合来自不同AI方法和数据模态的解释。在EO中，我们能够表示十五种不同的解释类型，并在六个示例用例中进行了测试。我们发现，知识增强显著提升了基础大型语言模型在上下文QA中的性能，且性能在不同疾病组中表现不一。在同一环境中，临床医生更倾向于将可操作性作为解释的主要焦点之一。在我们的解释组合方法中，我们计划使用相似性度量来确定慢性疾病检测环境中解释的相似性。总体而言，本论文设计了一系列方法，支持跨不同用例的知识增强解释，结合了当今AI时代生成解释支持组件的方法和增强解释的领域知识来源。

> Explainable Artificial Intelligence (AI) focuses on helping humans understand the working of AI systems or their decisions and has been a cornerstone of AI for decades. Recent research in explainability has focused on explaining the workings of AI models or model explainability. There have also been several position statements and review papers detailing the needs of end-users for user-centered explainability but fewer implementations. Hence, this thesis seeks to bridge some gaps between model and user-centered explainability. We create an explanation ontology (EO) to represent literature-derived explanation types via their supporting components. We implement a knowledge-augmented question-answering (QA) pipeline to support contextual explanations in a clinical setting. Finally, we are implementing a system to combine explanations from different AI methods and data modalities. Within the EO, we can represent fifteen different explanation types, and we have tested these representations in six exemplar use cases. We find that knowledge augmentations improve the performance of base large language models in the contextualized QA, and the performance is variable across disease groups. In the same setting, clinicians also indicated that they prefer to see actionability as one of the main foci in explanations. In our explanations combination method, we plan to use similarity metrics to determine the similarity of explanations in a chronic disease detection setting. Overall, through this thesis, we design methods that can support knowledge-enabled explanations across different use cases, accounting for the methods in today's AI era that can generate the supporting components of these explanations and domain knowledge sources that can enhance them.

[Arxiv](https://arxiv.org/abs/2410.17504)