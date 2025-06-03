# 超越语言：从视频对齐对话中学习非语言交流线索的大规模多模态数据集

发布时间：2025年06月01日

`LLM应用` `对话AI` `人机交互`

> Speaking Beyond Language: A Large-Scale Multimodal Dataset for Learning Nonverbal Cues from Video-Grounded Dialogues

# 摘要

> 非语言交流在人际互动中扮演着重要角色，手势、面部表情和肢体语言能够传递意图和情感的关键信息。然而，现有的大型语言模型（LLMs）在整合这些非语言元素方面存在不足，限制了它们生成沉浸式对话体验的能力。为此，我们提出了MARS——一种能够理解和生成非语言线索的多模态语言模型，填补了对话AI领域的这一空白。

我们的核心创新是VENUS，一个包含时间对齐文本、面部表情和肢体语言的标注视频数据集。基于VENUS，我们以下一个令牌预测为目标训练MARS，将文本与向量化表示的非语言元素相结合，在统一框架内实现了多模态理解和生成。通过对VENUS数据集的多方面分析，我们验证了其规模和有效性。实验结果表明，MARS能够成功生成与对话输入相匹配的文本和非语言表达，定量和定性分析均验证了这一结论。

> Nonverbal communication is integral to human interaction, with gestures, facial expressions, and body language conveying critical aspects of intent and emotion. However, existing large language models (LLMs) fail to effectively incorporate these nonverbal elements, limiting their capacity to create fully immersive conversational experiences. We introduce MARS, a multimodal language model designed to understand and generate nonverbal cues alongside text, bridging this gap in conversational AI. Our key innovation is VENUS, a large-scale dataset comprising annotated videos with time-aligned text, facial expressions, and body language. Leveraging VENUS, we train MARS with a next-token prediction objective, combining text with vector-quantized nonverbal representations to achieve multimodal understanding and generation within a unified framework. Based on various analyses of the VENUS datasets, we validate its substantial scale and high effectiveness. Our quantitative and qualitative results demonstrate that MARS successfully generates text and nonverbal languages, corresponding to conversational input.

[Arxiv](https://arxiv.org/abs/2506.00958)