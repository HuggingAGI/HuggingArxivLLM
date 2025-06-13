# 基于上下文LLM的命名实体转录优化

发布时间：2025年06月12日

`LLM应用` `语音处理`

> Improving Named Entity Transcription with Contextual LLM-based Revision

# 摘要

> 得益于建模技术的最新突破和监督式训练数据的日益丰富，自动语音识别（ASR）系统在普通语音识别方面表现优异。然而，即使是最先进的ASR系统，面对命名实体时的词错误率（WER）仍然居高不下。由于命名实体往往是信息中最关键的关键词，识别错误不仅影响单一应用，更会波及整个下游系统，尤其当ASR作为复杂系统前端时。为此，本文提出了一种基于大语言模型（LLM）的修正机制，巧妙结合LLM的推理能力与包含正确命名实体的局部上下文（如讲座笔记），有效修正ASR预测中的错误命名实体。最后，我们推出了NER-MIT-OpenCourseWare数据集，汇集了麻省理工学院课程的45小时数据，专为开发和测试之用。实验结果表明，我们的技术在该数据集上，成功将命名实体的相对WER降低了高达30%。

> With recent advances in modeling and the increasing amount of supervised training data, automatic speech recognition (ASR) systems have achieved remarkable performance on general speech. However, the word error rate (WER) of state-of-the-art ASR remains high for named entities. Since named entities are often the most critical keywords, misrecognizing them can affect all downstream applications, especially when the ASR system functions as the front end of a complex system. In this paper, we introduce a large language model (LLM) revision mechanism to revise incorrect named entities in ASR predictions by leveraging the LLM's reasoning ability as well as local context (e.g., lecture notes) containing a set of correct named entities. Finally, we introduce the NER-MIT-OpenCourseWare dataset, containing 45 hours of data from MIT courses for development and testing. On this dataset, our proposed technique achieves up to 30\% relative WER reduction for named entities.

[Arxiv](https://arxiv.org/abs/2506.10779)