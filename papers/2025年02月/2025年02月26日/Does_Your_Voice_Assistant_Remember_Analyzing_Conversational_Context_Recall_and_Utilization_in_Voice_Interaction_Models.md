# 你的语音助手还记得吗？语音交互模型中的对话上下文记忆与运用分析

发布时间：2025年02月26日

`LLM应用` `语音交互` `对话系统`

> Does Your Voice Assistant Remember? Analyzing Conversational Context Recall and Utilization in Voice Interaction Models

# 摘要

> 近期，多轮语音交互模型的进步显著提升了用户与模型之间的沟通效果。然而，尽管闭源模型能够有效保留并回忆之前的对话内容，开源模型是否具备这种能力仍是一个未解之谜。为了填补这一研究空白，我们系统性地评估了开源交互模型在利用过往对话内容方面的表现，为此我们提出了一个基准测试工具——ContextDialog。研究发现，基于语音的模型相较于基于文本的模型在回忆过往对话内容时面临更大的挑战，尤其是在需要回忆语音传达的信息时，即便采用了检索增强生成技术，模型在回答关于过往对话内容的问题时仍然表现不佳。这些发现揭示了开源模型在记忆和检索能力上的关键局限性，并为提升模型的记忆保留和检索鲁棒性提供了重要的研究方向。

> Recent advancements in multi-turn voice interaction models have improved user-model communication. However, while closed-source models effectively retain and recall past utterances, whether open-source models share this ability remains unexplored. To fill this gap, we systematically evaluate how well open-source interaction models utilize past utterances using ContextDialog, a benchmark we proposed for this purpose. Our findings show that speech-based models have more difficulty than text-based ones, especially when recalling information conveyed in speech, and even with retrieval-augmented generation, models still struggle with questions about past utterances. These insights highlight key limitations in open-source models and suggest ways to improve memory retention and retrieval robustness.

[Arxiv](https://arxiv.org/abs/2502.19759)