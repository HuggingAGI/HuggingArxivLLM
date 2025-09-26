# BESPOKE：基于诊断反馈的搜索增强型大型语言模型个性化基准

发布时间：2025年09月25日

`其他` `基础理论`

> BESPOKE: Benchmark for Search-Augmented Large Language Model Personalization via Diagnostic Feedback

# 摘要

> 搜索增强型大型语言模型（LLMs）将检索融入生成过程，推动了信息查找任务的进步，相比传统搜索系统，大大减轻了用户的认知负担。然而，它们仍无法完全满足用户的多样化需求——这需要识别同一查询在不同用户中可能体现的不同意图，并以用户偏好的形式呈现信息。尽管ChatGPT、Gemini等最新系统尝试借助用户历史实现个性化，但这类个性化的系统性评估尚未深入开展。为填补这一空白，我们提出了BESPOKE——一个用于评估搜索增强型LLMs个性化能力的真实基准。BESPOKE的设计兼具真实性与诊断性：真实性体现在直接收集人类真实的聊天和搜索历史；诊断性则通过将响应与细粒度偏好分数及反馈关联实现。该基准通过长期深度参与的人类标注构建：标注者贡献个人历史记录，编写包含详细信息需求的查询，并通过分数和诊断性反馈对响应进行评估。借助BESPOKE，我们开展了系统性分析，揭示了信息查找任务中有效个性化的核心要求，为个性化搜索增强型LLMs的细粒度评估奠定了基础。我们的代码和数据已在https://augustinlib.github.io/BESPOKE/公开。

> Search-augmented large language models (LLMs) have advanced information-seeking tasks by integrating retrieval into generation, reducing users' cognitive burden compared to traditional search systems. Yet they remain insufficient for fully addressing diverse user needs, which requires recognizing how the same query can reflect different intents across users and delivering information in preferred forms. While recent systems such as ChatGPT and Gemini attempt personalization by leveraging user histories, systematic evaluation of such personalization is under-explored. To address this gap, we propose BESPOKE, the realistic benchmark for evaluating personalization in search-augmented LLMs. BESPOKE is designed to be both realistic, by collecting authentic chat and search histories directly from humans, and diagnostic, by pairing responses with fine-grained preference scores and feedback. The benchmark is constructed through long-term, deeply engaged human annotation, where human annotators contributed their own histories, authored queries with detailed information needs, and evaluated responses with scores and diagnostic feedback. Leveraging BESPOKE, we conduct systematic analyses that reveal key requirements for effective personalization in information-seeking tasks, providing a foundation for fine-grained evaluation of personalized search-augmented LLMs. Our code and data are available at https://augustinlib.github.io/BESPOKE/.

[Arxiv](https://arxiv.org/abs/2509.21106)