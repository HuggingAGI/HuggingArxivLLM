# 借助思维链技术，实现无需问答数据支持的共情口语对话

发布时间：2025年01月18日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）来改进共情对话系统，特别是在多模态（语音和文本）场景下的应用。论文提出了一种新的方法（LPE），通过两阶段训练来增强LLM在语音情感感知和共情回应生成方面的能力。这属于LLM在实际应用中的改进和优化，因此归类为LLM应用。` `人机交互` `情感计算`

> Leveraging Chain of Thought towards Empathetic Spoken Dialogue without Corresponding Question-Answering Data

# 摘要

> # 摘要
共情对话在人机交互中至关重要，它让对话系统能够以更个性化和情感感知的方式回应，提升用户满意度和参与感。大型语言模型（LLMs）的出现彻底革新了对话生成，并在多模态领域展现了巨大潜力。许多研究将语音与基于文本的LLMs结合，以语音问题为输入并输出文本响应。然而，缺乏包含语音风格信息的口语问答数据集用于监督微调（SFT），限制了这些系统的表现。因此，尽管这些系统在理解语音内容上表现出色，却难以生成共情回应。为此，我们提出了一种名为“倾听、感知和表达”（LPE）的新方法，绕过了对问答数据的需求。该方法采用两阶段训练：首先引导LLM倾听内容并感知语音情感，随后通过思维链（CoT）提示，解锁模型基于倾听内容和感知情感生成共情回应的能力。实验证明了该方法的有效性。据我们所知，这是首次将CoT应用于基于语音的对话。

> Empathetic dialogue is crucial for natural human-computer interaction, allowing the dialogue system to respond in a more personalized and emotionally aware manner, improving user satisfaction and engagement. The emergence of large language models (LLMs) has revolutionized dialogue generation by harnessing their powerful capabilities and shown its potential in multimodal domains. Many studies have integrated speech with text-based LLMs to take speech question as input and output text response. However, the lack of spoken question-answering datasets that include speech style information to supervised fine-tuning (SFT) limits the performance of these systems. As a result, while these systems excel at understanding speech content, they often struggle to generate empathetic responses. In response, we propose a novel approach that circumvents the need for question-answering data, called Listen, Perceive, and Express (LPE). Our method employs a two-stage training process, initially guiding the LLM to listen the content and perceive the emotional aspects of speech. Subsequently, we utilize Chain-of-Thought (CoT) prompting to unlock the model's potential for expressing empathetic responses based on listened spoken content and perceived emotional cues. We employ experiments to prove the effectiveness of proposed method. To our knowledge, this is the first attempt to leverage CoT for speech-based dialogue.

[Arxiv](https://arxiv.org/abs/2501.10937)