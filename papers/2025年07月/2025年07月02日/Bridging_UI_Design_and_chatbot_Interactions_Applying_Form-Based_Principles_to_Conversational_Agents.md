# 连接UI设计与聊天机器人互动：将表单设计原则应用于对话式代理

发布时间：2025年07月02日

`LLM应用` `聊天机器人` `客户管理`

> Bridging UI Design and chatbot Interactions: Applying Form-Based Principles to Conversational Agents

# 摘要

> 特定领域的聊天机器人应用往往涉及多步骤交互，如调整搜索筛选、选择多个项目或进行比较。传统的图形用户界面（GUI）通过明确的“提交”和“重置”操作处理这些流程，确保后端系统能清晰跟踪用户意图。然而，对话式代理依赖语言线索，容易导致混淆和上下文管理问题。本文提出将GUI启发的确认（提交类）和上下文切换（重置类）建模为LLM提示中的显式任务。通过捕捉用户确认、重置操作及推理链作为结构化会话数据，我们提升了清晰度，减少了用户困惑，并使特定领域聊天机器人与后端逻辑保持一致。我们在酒店预订和客户管理场景中展示了该方法，结果表明多轮任务连贯性、用户满意度和效率均有所提升。

> Domain specific chatbot applications often involve multi step interactions, such as refining search filters, selecting multiple items, or performing comparisons. Traditional graphical user interfaces (GUIs) handle these workflows by providing explicit "Submit" (commit data) and "Reset" (discard data) actions, allowing back-end systems to track user intent unambiguously. In contrast, conversational agents rely on subtle language cues, which can lead to confusion and incomplete context management. This paper proposes modeling these GUI inspired metaphors acknowledgment (submit like) and context switching (reset-like) as explicit tasks within large language model (LLM) prompts. By capturing user acknowledgment, reset actions, and chain of thought (CoT) reasoning as structured session data, we preserve clarity, reduce user confusion, and align domain-specific chatbot interactions with back-end logic. We demonstrate our approach in hotel booking and customer management scenarios, highlighting improvements in multi-turn task coherence, user satisfaction, and efficiency.

[Arxiv](https://arxiv.org/abs/2507.01862)