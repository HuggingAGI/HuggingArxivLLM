# 谁灌输了谎言？检索增强生成中被污染知识的责任归因

发布时间：2025年09月17日

`RAG` `基础理论`

> Who Taught the Lie? Responsibility Attribution for Poisoned Knowledge in Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）通过整合外部知识提升大型语言模型的响应质量，但近期研究发现其极易遭受投毒攻击——恶意文本一旦潜入知识库，便会干扰模型输出。尽管已有防御手段，却常被更狡猾的自适应攻击或复杂攻击绕过。
  本文提出黑盒责任归因框架RAGOrigin，专门用于定位知识库中导致生成内容误导或错误的文本源头。该方法为每个错误生成事件构建聚焦归因范围，通过评估候选文本的检索排名、语义相关性及对生成响应的影响，为其分配责任分数；随后采用无监督聚类方法隔离投毒文本。我们在七个数据集和十五种投毒攻击场景下对RAGOrigin进行了评估，涵盖新开发的自适应投毒策略与多攻击者场景。结果显示，该方法在识别投毒内容上优于现有基线，并在动态、嘈杂环境中保持稳健性。这表明RAGOrigin为追踪RAG系统中受损知识的来源提供了实用且有效的解决方案。

> Retrieval-Augmented Generation (RAG) integrates external knowledge into large language models to improve response quality. However, recent work has shown that RAG systems are highly vulnerable to poisoning attacks, where malicious texts are inserted into the knowledge database to influence model outputs. While several defenses have been proposed, they are often circumvented by more adaptive or sophisticated attacks.
  This paper presents RAGOrigin, a black-box responsibility attribution framework designed to identify which texts in the knowledge database are responsible for misleading or incorrect generations. Our method constructs a focused attribution scope tailored to each misgeneration event and assigns a responsibility score to each candidate text by evaluating its retrieval ranking, semantic relevance, and influence on the generated response. The system then isolates poisoned texts using an unsupervised clustering method. We evaluate RAGOrigin across seven datasets and fifteen poisoning attacks, including newly developed adaptive poisoning strategies and multi-attacker scenarios. Our approach outperforms existing baselines in identifying poisoned content and remains robust under dynamic and noisy conditions. These results suggest that RAGOrigin provides a practical and effective solution for tracing the origins of corrupted knowledge in RAG systems.

[Arxiv](https://arxiv.org/abs/2509.13772)