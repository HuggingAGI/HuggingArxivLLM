# 基于检索增强的对话知识聚合技术，实现富有表现力的对话语音合成

发布时间：2025年01月11日

`RAG

理由：这篇论文提出了一种名为RADKA-CSS的检索增强对话知识聚合方案，用于对话语音合成（CSS）。该方案通过从存储对话（SD）中检索与当前对话（CD）在语义和风格上相似的对话，并利用这些检索到的对话来增强语音合成的表现力。这种方法明显属于检索增强生成（RAG）的范畴，因为它结合了检索和生成技术来提升任务性能。因此，将其分类为RAG是合适的。` `语音合成` `人机交互`

> Retrieval-Augmented Dialogue Knowledge Aggregation for Expressive Conversational Speech Synthesis

# 摘要

> # 摘要
对话语音合成（CSS）旨在利用当前对话（CD）历史，生成符合对话风格的富有表现力的语音。与CD不同，存储对话（SD）包含了用户与智能体交互早期阶段的对话片段，这些片段蕴含了与CD类似场景相关的风格表达知识。这些知识对于智能体生成富有表现力的对话语音和共情反馈至关重要，但先前的研究却忽视了这一点。为此，我们提出了一种新颖的检索增强对话知识聚合方案——RADKA-CSS，它包含三个核心模块：1）从SD中高效检索出与CD在语义和风格上相似的对话。我们首先构建了一个存储对话语义-风格数据库（SDSSD），包含文本和音频样本，然后设计了一种多属性检索方案，将CD的对话语义和风格向量与SDSSD中的存储对话进行匹配，检索出最相似的对话。2）为了充分利用CD和SD中的风格知识，我们采用多粒度图结构编码对话，并引入多源风格知识聚合机制。3）最后，聚合的风格知识被输入语音合成器，帮助智能体生成符合对话风格的富有表现力的语音。我们在CSS任务的基准数据集DailyTalk上进行了全面实验，客观和主观评估均表明，RADKA-CSS在表现力渲染上优于基线模型。代码和音频样本可在以下链接获取：https://github.com/Coder-jzq/RADKA-CSS。

> Conversational speech synthesis (CSS) aims to take the current dialogue (CD) history as a reference to synthesize expressive speech that aligns with the conversational style. Unlike CD, stored dialogue (SD) contains preserved dialogue fragments from earlier stages of user-agent interaction, which include style expression knowledge relevant to scenarios similar to those in CD. Note that this knowledge plays a significant role in enabling the agent to synthesize expressive conversational speech that generates empathetic feedback. However, prior research has overlooked this aspect. To address this issue, we propose a novel Retrieval-Augmented Dialogue Knowledge Aggregation scheme for expressive CSS, termed RADKA-CSS, which includes three main components: 1) To effectively retrieve dialogues from SD that are similar to CD in terms of both semantic and style. First, we build a stored dialogue semantic-style database (SDSSD) which includes the text and audio samples. Then, we design a multi-attribute retrieval scheme to match the dialogue semantic and style vectors of the CD with the stored dialogue semantic and style vectors in the SDSSD, retrieving the most similar dialogues. 2) To effectively utilize the style knowledge from CD and SD, we propose adopting the multi-granularity graph structure to encode the dialogue and introducing a multi-source style knowledge aggregation mechanism. 3) Finally, the aggregated style knowledge are fed into the speech synthesizer to help the agent synthesize expressive speech that aligns with the conversational style. We conducted a comprehensive and in-depth experiment based on the DailyTalk dataset, which is a benchmarking dataset for the CSS task.
  Both objective and subjective evaluations demonstrate that RADKA-CSS outperforms baseline models in expressiveness rendering. Code and audio samples can be found at: https://github.com/Coder-jzq/RADKA-CSS.

[Arxiv](https://arxiv.org/abs/2501.06467)