# NexusSum：面向长篇叙事摘要生成的分层大语言模型智能体

发布时间：2025年05月30日

`LLM应用` `叙事总结`

> NexusSum: Hierarchical LLM Agents for Long-Form Narrative Summarization

# 摘要

> 总结长篇叙事（如书籍、电影和电视剧本）需要精准把握复杂情节、角色互动和主题连贯性，这一直是现有LLMs难以攻克的难题。我们推出NexusSum，一个无需微调的多智能体LLM框架，通过结构化、顺序化的处理管道高效处理长篇文本。我们的方法创新性地引入了两大核心技术：(1) 对话转描述预处理方法：将角色对话与描述性文本统一格式，显著提升文本连贯性。 (2) 分层多LLM总结管道：通过优化块处理和输出长度控制，生成精准且高质量的摘要。NexusSum在叙事总结领域树立了新的标杆，实现了书籍、电影和电视剧本上高达30.0%的BERTScore (F1)提升。这一突破性成果不仅证明了多智能体LLMs在长篇内容处理上的强大能力，更为多样化叙事领域的结构化总结提供了一种可扩展的解决方案。

> Summarizing long-form narratives--such as books, movies, and TV scripts--requires capturing intricate plotlines, character interactions, and thematic coherence, a task that remains challenging for existing LLMs. We introduce NexusSum, a multi-agent LLM framework for narrative summarization that processes long-form text through a structured, sequential pipeline--without requiring fine-tuning. Our approach introduces two key innovations: (1) Dialogue-to-Description Transformation: A narrative-specific preprocessing method that standardizes character dialogue and descriptive text into a unified format, improving coherence. (2) Hierarchical Multi-LLM Summarization: A structured summarization pipeline that optimizes chunk processing and controls output length for accurate, high-quality summaries. Our method establishes a new state-of-the-art in narrative summarization, achieving up to a 30.0% improvement in BERTScore (F1) across books, movies, and TV scripts. These results demonstrate the effectiveness of multi-agent LLMs in handling long-form content, offering a scalable approach for structured summarization in diverse storytelling domains.

[Arxiv](https://arxiv.org/abs/2505.24575)