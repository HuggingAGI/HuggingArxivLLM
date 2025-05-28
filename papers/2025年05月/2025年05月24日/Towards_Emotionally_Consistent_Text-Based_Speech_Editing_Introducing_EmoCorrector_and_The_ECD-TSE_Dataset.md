# 探索基于文本的情感一致语音编辑：介绍EmoCorrector与ECD-TSE数据集

发布时间：2025年05月24日

`RAG` `语音编辑` `语音处理`

> Towards Emotionally Consistent Text-Based Speech Editing: Introducing EmoCorrector and The ECD-TSE Dataset

# 摘要

> 文本驱动的语音编辑（TSE）通过纯文本修改语音，避免了重复录音的麻烦。然而，现有的TSE方法虽然在合成语音片段的内容准确性和语音一致性上表现突出，却常常忽视了文本修改带来的情感变化或不一致问题。为了解决这一难题，我们推出了EmoCorrector——一款创新的TSE后校正工具。EmoCorrector采用检索增强生成（RAG）技术，从编辑后的文本中提取情感特征，匹配相应情感的语音样本，并生成与目标情感相符的语音，同时保持说话人声音的原真性。为了评估和训练TSE中的情感一致性模型，我们首次推出了专门用于TSE的情感校正数据集（ECD-TSE）。该数据集的独特之处在于包含了丰富的文本变体和多样的情感表达的<text, speech>配对数据。通过在ECD-TSE上进行的主观和客观实验以及深入分析，我们证实EmoCorrector不仅显著提升了预期情感的表达效果，还有效克服了现有TSE方法中情感不一致的局限性。更多代码和音频示例请访问https://github.com/AI-S2-Lab/EmoCorrector。


> Text-based speech editing (TSE) modifies speech using only text, eliminating re-recording. However, existing TSE methods, mainly focus on the content accuracy and acoustic consistency of synthetic speech segments, and often overlook the emotional shifts or inconsistency issues introduced by text changes. To address this issue, we propose EmoCorrector, a novel post-correction scheme for TSE. EmoCorrector leverages Retrieval-Augmented Generation (RAG) by extracting the edited text's emotional features, retrieving speech samples with matching emotions, and synthesizing speech that aligns with the desired emotion while preserving the speaker's identity and quality. To support the training and evaluation of emotional consistency modeling in TSE, we pioneer the benchmarking Emotion Correction Dataset for TSE (ECD-TSE). The prominent aspect of ECD-TSE is its inclusion of $<$text, speech$>$ paired data featuring diverse text variations and a range of emotional expressions. Subjective and objective experiments and comprehensive analysis on ECD-TSE confirm that EmoCorrector significantly enhances the expression of intended emotion while addressing emotion inconsistency limitations in current TSE methods. Code and audio examples are available at https://github.com/AI-S2-Lab/EmoCorrector.

[Arxiv](https://arxiv.org/abs/2505.20341)