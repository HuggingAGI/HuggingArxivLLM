# 意图即你所需：从意图优化你的代码

发布时间：2025年02月12日

`LLM应用` `软件工程` `代码生成`

> Intention is All You Need: Refining Your Code from Your Intention

# 摘要

> 代码精炼致力于提升现有代码的质量，通过修复问题、重构和优化来满足特定需求。然而，随着软件项目规模和复杂性的增长，传统的审阅者与开发者之间的迭代交流变得日益繁琐。尽管深度学习技术被用于加速这一过程，但其表现仍受限于准确理解审阅者意图的挑战。

    本文提出了一种基于意图的代码精炼技术，通过从评论中提取审阅者的意图，提升传统的评论到代码的流程。我们的方法包含两个关键阶段：意图提取和意图引导的修订生成。意图提取阶段利用预定义模板对评论进行分类，而意图引导的修订生成阶段则借助大型语言模型（LLMs）根据这些意图生成修订代码。我们设计了三类八种子类别的评论转换方法，并采用结合规则和LLM分类器的混合方法进行准确分类。实验结果表明，在不同提示设置下，使用五种LLMs（GPT4o、GPT3.5、DeepSeekV2、DeepSeek7B、CodeQwen7B）进行的大量实验中，我们的方法在意图提取方面达到了79%的准确率，在代码精炼生成方面最高可达66%。这凸显了本方法在提升数据质量和提高代码精炼效率方面的潜力。

> Code refinement aims to enhance existing code by addressing issues, refactoring, and optimizing to improve quality and meet specific requirements. As software projects scale in size and complexity, the traditional iterative exchange between reviewers and developers becomes increasingly burdensome. While recent deep learning techniques have been explored to accelerate this process, their performance remains limited, primarily due to challenges in accurately understanding reviewers' intents.
  This paper proposes an intention-based code refinement technique that enhances the conventional comment-to-code process by explicitly extracting reviewer intentions from the comments. Our approach consists of two key phases: Intention Extraction and Intention Guided Revision Generation. Intention Extraction categorizes comments using predefined templates, while Intention Guided Revision Generation employs large language models (LLMs) to generate revised code based on these defined intentions. Three categories with eight subcategories are designed for comment transformation, which is followed by a hybrid approach that combines rule-based and LLM-based classifiers for accurate classification. Extensive experiments with five LLMs (GPT4o, GPT3.5, DeepSeekV2, DeepSeek7B, CodeQwen7B) under different prompting settings demonstrate that our approach achieves 79% accuracy in intention extraction and up to 66% in code refinement generation. Our results highlight the potential of our approach in enhancing data quality and improving the efficiency of code refinement.

[Arxiv](https://arxiv.org/abs/2502.08172)