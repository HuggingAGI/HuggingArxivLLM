# 面向监管文件的自适应信息提取智能体工具包

发布时间：2025年09月15日

`Agent` `工业与制造`

> An Agentic Toolkit for Adaptive Information Extraction from Regulatory Documents

# 摘要

> 性能声明（DoP）文件是欧盟法规强制要求的建筑产品性能证明文件。尽管部分内容已标准化，但DoP在布局、语言、结构和格式上差异显著，为自动化键值对提取（KVP）和问答（QA）带来了难题。现有的静态或纯大型语言模型（LLM）信息提取（IE）管道常出现幻觉现象，且难以适应这种结构多样性。我们针对特定领域设计的有状态智能体系统，采用规划器-执行器-响应器架构，成功应对了这些挑战。该系统能够推断用户意图、检测文档模态，并动态编排工具，实现稳健且可追溯的推理，同时避免工具误用或执行循环。在精心构建的DoP数据集上的评估显示，该系统在不同格式和语言下的稳健性显著提升，为受监管工作流中的结构化数据提取提供了可扩展方案。

> Declaration of Performance (DoP) documents, mandated by EU regulation, certify the performance of construction products. While some of their content is standardized, DoPs vary widely in layout, language, schema, and format, posing challenges for automated key-value pair extraction (KVP) and question answering (QA). Existing static or LLM-only IE pipelines often hallucinate and fail to adapt to this structural diversity. Our domain-specific, stateful agentic system addresses these challenges through a planner-executor-responder architecture. The system infers user intent, detects document modality, and orchestrates tools dynamically for robust, traceable reasoning while avoiding tool misuse or execution loops. Evaluation on a curated DoP dataset demonstrates improved robustness across formats and languages, offering a scalable solution for structured data extraction in regulated workflows.

[Arxiv](https://arxiv.org/abs/2509.11773)