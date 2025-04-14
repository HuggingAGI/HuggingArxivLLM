# DocAgent：一个多智能体系统，专注于自动生成代码文档。

发布时间：2025年04月11日

`Agent

摘要中提到DocAgent是一个基于多智能体协作的系统，专门的智能体如阅读器、搜索器、写手、验证器和编排器协作生成文档。这表明论文的重点在于智能体的设计和协作机制，而不是大型语言模型（LLM）的应用或理论。因此，这篇论文应归类为Agent。` `软件工程`

> DocAgent: A Multi-Agent System for Automated Code Documentation Generation

# 摘要

> 在AI时代，高质量的代码文档对于软件开发至关重要。然而，使用大型语言模型（LLMs）自动生成高质量文档仍然面临挑战，现有方法往往生成不完整、无用或事实错误的内容。我们提出了DocAgent，这是一个基于拓扑代码处理的增量上下文构建技术的新型多智能体协作系统。专门的智能体（阅读器、搜索器、写手、验证器、编排器）协作生成文档。我们还提出了一种多维度评估框架，从完整性、有用性和真实性三个方面进行评估。全面的实验表明，DocAgent在各种基准测试中表现显著优于现有方法。我们的消融实验进一步证实了拓扑处理顺序的重要性。DocAgent为复杂且私有的代码仓库提供了一种可靠生成高质量代码文档的强健方法。


> High-quality code documentation is crucial for software development especially in the era of AI. However, generating it automatically using Large Language Models (LLMs) remains challenging, as existing approaches often produce incomplete, unhelpful, or factually incorrect outputs. We introduce DocAgent, a novel multi-agent collaborative system using topological code processing for incremental context building. Specialized agents (Reader, Searcher, Writer, Verifier, Orchestrator) then collaboratively generate documentation. We also propose a multi-faceted evaluation framework assessing Completeness, Helpfulness, and Truthfulness. Comprehensive experiments show DocAgent significantly outperforms baselines consistently. Our ablation study confirms the vital role of the topological processing order. DocAgent offers a robust approach for reliable code documentation generation in complex and proprietary repositories.

[Arxiv](https://arxiv.org/abs/2504.08725)