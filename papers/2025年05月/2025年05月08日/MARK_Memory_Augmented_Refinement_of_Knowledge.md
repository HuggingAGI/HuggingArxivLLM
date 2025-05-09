# MARK：增强记忆的知识精炼

发布时间：2025年05月08日

`LLM应用`

> MARK: Memory Augmented Refinement of Knowledge

# 摘要

> 大型语言模型 (LLMs) 在专业任务中表现出色，但若不进行昂贵的微调，往往难以跟上领域知识的更新步伐。领域知识由两部分组成：一是不可变的事实（如“石头是固体”）和被广泛认可的原则（如道德标准）；二是由业务需求和现实变化塑造的动态精炼记忆。然而，领域专家的深入见解与系统中的知识储备之间常存在差距，这可能影响信息的准确检索和应用。我们的 MARK（记忆增强知识精炼）框架通过结构化的精炼记忆，使 LLMs 能够持续学习，无需重新训练。这一设计灵感来源于心智社会理论。MARK 通过三个专门代理协同工作：残差精炼记忆代理负责存储和检索特定领域的见解，维持长期上下文；用户问题精炼记忆代理捕获用户提供的事实、术语和缩写，提升理解能力；LLM 响应精炼记忆代理从响应中提取关键要素，用于精炼和个性化处理。这些代理通过分析存储的精炼记忆，识别模式，解决矛盾，从而提升响应的准确性。时间因素如近期性和频率优先级确保相关信息得到重视，同时淘汰过时的见解。MARK 为 LLMs 带来多方面的提升：基于事实的策略减少幻觉现象；领域特定适应尤其适用于医疗、法律和制造等依赖专有知识的领域；个性化 AI 助手通过记住用户偏好，确保随时间一致的连贯响应，显著提升用户体验。

> Large Language Models (LLMs) assist in specialized tasks but struggle to align with evolving domain knowledge without costly fine-tuning. Domain knowledge consists of: Knowledge: Immutable facts (e.g., 'A stone is solid') and generally accepted principles (e.g., ethical standards); Refined Memory: Evolving insights shaped by business needs and real-world changes. However, a significant gap often exists between a domain expert's deep, nuanced understanding and the system's domain knowledge, which can hinder accurate information retrieval and application. Our Memory-Augmented Refinement of Knowledge (MARK) framework enables LLMs to continuously learn without retraining by leveraging structured refined memory, inspired by the Society of Mind. MARK operates through specialized agents, each serving a distinct role: Residual Refined Memory Agent: Stores and retrieves domain-specific insights to maintain context over time; User Question Refined Memory Agent: Captures user-provided facts, abbreviations, and terminology for better comprehension; LLM Response Refined Memory Agent: Extracts key elements from responses for refinement and personalization. These agents analyse stored refined memory, detect patterns, resolve contradictions, and improve response accuracy. Temporal factors like recency and frequency prioritize relevant information while discarding outdated insights. MARK enhances LLMs in multiple ways: Ground Truth Strategy: Reduces hallucinations by establishing a structured reference; Domain-Specific Adaptation: Essential for fields like healthcare, law, and manufacturing, where proprietary insights are absent from public datasets; Personalized AI Assistants: Improves virtual assistants by remembering user preferences, ensuring coherent responses over time.

[Arxiv](https://arxiv.org/abs/2505.05177)