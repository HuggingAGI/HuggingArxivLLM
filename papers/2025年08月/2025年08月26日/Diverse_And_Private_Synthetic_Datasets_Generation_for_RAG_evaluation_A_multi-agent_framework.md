# 面向RAG评估的多样化与隐私保护合成数据集生成：一种多智能体框架

发布时间：2025年08月26日

`RAG` `基础理论`

> Diverse And Private Synthetic Datasets Generation for RAG evaluation: A multi-agent framework

# 摘要

> 检索增强生成（RAG）系统借助整合外部知识提升大型语言模型的输出质量，进而生成更具信息量和上下文感知能力的响应。然而，这类系统的有效性与可信度高度依赖评估方法，尤其是评估过程能否涵盖保护敏感信息等现实约束。尽管目前RAG系统的评估研究多聚焦于性能指标的开发，但对底层评估数据集的设计与质量关注不足——尽管这些数据集是实现有效、可靠评估的核心。为此，本研究提出一种新颖的多智能体框架，用于生成RAG评估所需的合成QA数据集，重点关注语义多样性与隐私保护。该方法具体包括：（1）多样性智能体：通过聚类技术实现主题覆盖与语义变异的最大化；（2）隐私智能体：跨多领域检测并掩盖敏感信息；（3）QA整理智能体：合成兼具隐私性与多样性的QA对，作为RAG评估的基准真值。大量实验验证，我们构建的评估数据集在多样性上超越基线方法，并能在特定领域数据集上实现稳健的隐私掩盖。这项研究为更安全、更全面的RAG系统评估提供了实用且符合伦理的解决方案，同时为未来顺应AI法规与合规标准演进的技术优化奠定了基础。

> Retrieval-augmented generation (RAG) systems improve large language model outputs by incorporating external knowledge, enabling more informed and context-aware responses. However, the effectiveness and trustworthiness of these systems critically depends on how they are evaluated, particularly on whether the evaluation process captures real-world constraints like protecting sensitive information. While current evaluation efforts for RAG systems have primarily focused on the development of performance metrics, far less attention has been given to the design and quality of the underlying evaluation datasets, despite their pivotal role in enabling meaningful, reliable assessments. In this work, we introduce a novel multi-agent framework for generating synthetic QA datasets for RAG evaluation that prioritize semantic diversity and privacy preservation. Our approach involves: (1) a Diversity agent leveraging clustering techniques to maximize topical coverage and semantic variability, (2) a Privacy Agent that detects and mask sensitive information across multiple domains and (3) a QA curation agent that synthesizes private and diverse QA pairs suitable as ground truth for RAG evaluation. Extensive experiments demonstrate that our evaluation sets outperform baseline methods in diversity and achieve robust privacy masking on domain-specific datasets. This work offers a practical and ethically aligned pathway toward safer, more comprehensive RAG system evaluation, laying the foundation for future enhancements aligned with evolving AI regulations and compliance standards.

[Arxiv](https://arxiv.org/abs/2508.18929)