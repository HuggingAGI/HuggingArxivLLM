# 超越文字：多模态 LLM 懂得何时开口

发布时间：2025年05月20日

`LLM应用` `多模态` `对话式AI`

> Beyond Words: Multimodal LLM Knows When to Speak

# 摘要

> 基于大型语言模型（LLM）的聊天机器人在生成连贯且上下文相关的回复方面表现出色，但在何时开口这一问题上常常表现欠佳，尤其是在需要快速做出简短回应的持续对话中。这一局限性主要源于它们对文本输入的依赖，缺乏现实世界人类对话中丰富的上下文线索。在此工作中，我们专注于实时预测回复类型，特别关注那些依赖于视觉、音频和文本中细微的多模态信号的简短、反应性 utterances。为此，我们引入了一个新的多模态数据集，该数据集由真实世界的对话视频构建而成，包含时间对齐的视觉、听觉和文本流。该数据集支持在一对一互动中对回复时机进行细粒度建模。基于此数据集，我们提出了MM-When2Speak，这是一个多模态LLM模型，能够自适应地整合视觉、听觉和文本上下文，以预测何时应做出回应，以及何种类型的回复最为合适。实验表明，MM-When2Speak显著超越了现有的单模态和基于LLM的基线模型，在回复时机准确性方面比领先的商业LLMs提升了高达4倍。这些结果凸显了多模态输入对于生成及时、自然且引人入胜的对话式AI的重要性。


> While large language model (LLM)-based chatbots have demonstrated strong capabilities in generating coherent and contextually relevant responses, they often struggle with understanding when to speak, particularly in delivering brief, timely reactions during ongoing conversations. This limitation arises largely from their reliance on text input, lacking the rich contextual cues in real-world human dialogue. In this work, we focus on real-time prediction of response types, with an emphasis on short, reactive utterances that depend on subtle, multimodal signals across vision, audio, and text. To support this, we introduce a new multimodal dataset constructed from real-world conversational videos, containing temporally aligned visual, auditory, and textual streams. This dataset enables fine-grained modeling of response timing in dyadic interactions. Building on this dataset, we propose MM-When2Speak, a multimodal LLM-based model that adaptively integrates visual, auditory, and textual context to predict when a response should occur, and what type of response is appropriate. Experiments show that MM-When2Speak significantly outperforms state-of-the-art unimodal and LLM-based baselines, achieving up to a 4x improvement in response timing accuracy over leading commercial LLMs. These results underscore the importance of multimodal inputs for producing timely, natural, and engaging conversational AI.

[Arxiv](https://arxiv.org/abs/2505.14654)