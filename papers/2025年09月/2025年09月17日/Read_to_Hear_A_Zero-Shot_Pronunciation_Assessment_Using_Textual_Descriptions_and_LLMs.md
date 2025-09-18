# 以读助听：基于文本描述与大型语言模型（LLMs）的零样本发音评估

发布时间：2025年09月17日

`LLM应用` `教育科技`

> Read to Hear: A Zero-Shot Pronunciation Assessment Using Textual Descriptions and LLMs

# 摘要

> 自动发音评估通常由基于音频-分数对训练的声学模型完成。尽管这类系统效果不错，却只给出数值分数，无法提供帮助学习者理解自身错误的必要信息。与此同时，大型语言模型（LLMs）在辅助语言学习上已展现出成效，但其在发音评估领域的潜力尚未得到挖掘。本研究提出了TextPA——一种零样本、基于文本描述的发音评估方法。TextPA会对语音信号进行人类可读的表示处理，再将其输入LLM，以此评估发音的准确性与流利度，同时解释评分依据。最后，通过音素序列匹配评分法进一步优化准确性得分。这项研究指出了发音评估中一个此前被忽略的全新方向：我们没有采用基于音频-分数样本的监督训练，而是充分挖掘书面文本中蕴含的丰富发音知识。实验结果显示，该方法不仅成本效益高，性能也颇具竞争力。此外，TextPA还能通过提供互补视角，大幅提升传统音频-分数训练模型在域外数据上的表现。

> Automatic pronunciation assessment is typically performed by acoustic models trained on audio-score pairs. Although effective, these systems provide only numerical scores, without the information needed to help learners understand their errors. Meanwhile, large language models (LLMs) have proven effective in supporting language learning, but their potential for assessing pronunciation remains unexplored. In this work, we introduce TextPA, a zero-shot, Textual description-based Pronunciation Assessment approach. TextPA utilizes human-readable representations of speech signals, which are fed into an LLM to assess pronunciation accuracy and fluency, while also providing reasoning behind the assigned scores. Finally, a phoneme sequence match scoring method is used to refine the accuracy scores. Our work highlights a previously overlooked direction for pronunciation assessment. Instead of relying on supervised training with audio-score examples, we exploit the rich pronunciation knowledge embedded in written text. Experimental results show that our approach is both cost-efficient and competitive in performance. Furthermore, TextPA significantly improves the performance of conventional audio-score-trained models on out-of-domain data by offering a complementary perspective.

[Arxiv](https://arxiv.org/abs/2509.14187)