# 模仿才能成名：多智能体对话解决会议记录稀缺问题

发布时间：2025年02月18日

`LLM应用` `对话系统`

> You need to MIMIC to get FAME: Solving Meeting Transcript Scarcity with a Multi-Agent Conversations

# 摘要

> 会议摘要任务面临高质量数据稀缺的问题，主要源于隐私限制和数据收集成本高昂。我们通过FAME数据集解决了这一问题，该数据集包含500个英文会议和300个德文会议，由我们的新型多智能体会议合成框架MIMIC生成。MIMIC基于给定的知识源，通过定义具有心理依据的参与者档案、规划对话流程，并协调大型语言模型（LLM）的辩论来生成会议记录。随后，一个模块化的后处理步骤对输出进行优化，有效缓解了重复和过于正式的语调，确保生成连贯且可信的大规模对话。我们还提出了一个基于心理学的评估框架，用于评估对话的自然性、社交行为的真实性和记录的难度。人类评估结果显示，FAME在自然性方面达到了4.5/5的评分，保持了以发言者为中心的挑战（口语表达方面3/5），并引入了更丰富信息导向的难度（难度方面4/5）。这些发现表明，FAME不仅是真实会议环境的良好替代方案，还具备良好的可扩展性。它为会议摘要研究及其他以对话为中心的应用开辟了新的测试场景，尤其在需要对话数据或在行为约束下模拟社交场景的任务中。

> Meeting summarization suffers from limited high-quality data, mainly due to privacy restrictions and expensive collection processes. We address this gap with FAME, a dataset of 500 meetings in English and 300 in German produced by MIMIC, our new multi-agent meeting synthesis framework that generates meeting transcripts on a given knowledge source by defining psychologically grounded participant profiles, outlining the conversation, and orchestrating a large language model (LLM) debate. A modular post-processing step refines these outputs, mitigating potential repetitiveness and overly formal tones, ensuring coherent, credible dialogues at scale. We also propose a psychologically grounded evaluation framework assessing naturalness, social behavior authenticity, and transcript difficulties. Human assessments show that FAME approximates real-meeting spontaneity (4.5/5 in naturalness), preserves speaker-centric challenges (3/5 in spoken language), and introduces richer information-oriented difficulty (4/5 in difficulty). These findings highlight that FAME is a good and scalable proxy for real-world meeting conditions. It enables new test scenarios for meeting summarization research and other conversation-centric applications in tasks requiring conversation data or simulating social scenarios under behavioral constraints.

[Arxiv](https://arxiv.org/abs/2502.13001)