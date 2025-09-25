# RAG的安全与隐私：形式化威胁模型与攻击面

发布时间：2025年09月24日

`RAG` `基础理论`

> RAG Security and Privacy: Formalizing the Threat Model and Attack Surface

# 摘要

> 检索增强生成（RAG）是自然语言处理领域的新兴技术，它巧妙融合大型语言模型（LLMs）与外部文档检索，旨在生成更精准、更具事实依据的回答。尽管RAG在减少模型幻觉、提升事实准确性上潜力十足，却也带来了传统LLMs未曾面临的新型隐私与安全难题。现有研究已证实，LLMs可能通过记忆训练数据或对抗性提示泄露敏感信息，而RAG系统也承袭了这些隐患。不仅如此，RAG对外部知识库的依赖还暴露了新的攻击路径，例如可能泄露检索文档的存在或内容，或是被注入恶意内容以操控模型行为。尽管风险重重，目前却尚无规范RAG系统威胁图景的正式框架。为此，本文填补了这一研究空白——据我们所知，首次提出了RAG系统的正式威胁模型。我们根据攻击者对模型组件与数据的访问权限，构建了攻击者类型的结构化分类体系，并明确界定了文档级成员推理、数据投毒等核心威胁向量，这些在实际应用中会引发严重的隐私与完整性风险。通过构建规范的定义与攻击模型，我们的研究为更深入、系统地剖析RAG系统的隐私安全机制奠定了坚实基础。

> Retrieval-Augmented Generation (RAG) is an emerging approach in natural language processing that combines large language models (LLMs) with external document retrieval to produce more accurate and grounded responses. While RAG has shown strong potential in reducing hallucinations and improving factual consistency, it also introduces new privacy and security challenges that differ from those faced by traditional LLMs. Existing research has demonstrated that LLMs can leak sensitive information through training data memorization or adversarial prompts, and RAG systems inherit many of these vulnerabilities. At the same time, reliance of RAG on an external knowledge base opens new attack surfaces, including the potential for leaking information about the presence or content of retrieved documents, or for injecting malicious content to manipulate model behavior. Despite these risks, there is currently no formal framework that defines the threat landscape for RAG systems. In this paper, we address a critical gap in the literature by proposing, to the best of our knowledge, the first formal threat model for retrieval-RAG systems. We introduce a structured taxonomy of adversary types based on their access to model components and data, and we formally define key threat vectors such as document-level membership inference and data poisoning, which pose serious privacy and integrity risks in real-world deployments. By establishing formal definitions and attack models, our work lays the foundation for a more rigorous and principled understanding of privacy and security in RAG systems.

[Arxiv](https://arxiv.org/abs/2509.20324)