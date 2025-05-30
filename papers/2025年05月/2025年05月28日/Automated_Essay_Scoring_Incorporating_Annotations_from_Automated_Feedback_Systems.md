# # 结合自动反馈系统标注的自动作文评分

发布时间：2025年05月28日

`LLM应用`

> Automated Essay Scoring Incorporating Annotations from Automated Feedback Systems

# 摘要

> 本研究展示了如何将反馈导向的标注整合到评分流程中，以提升自动作文评分（AES）的准确性。我们以PERSUADE语料库为研究对象，集成了两类反馈驱动的标注：一类用于识别拼写和语法错误，另一类用于突出论辩成分。为了展示这一方法在实际场景中的应用，我们采用了两种大型语言模型（LLMs）来生成标注——一种用于拼写纠正的生成式语言模型，以及一种基于编码器的标记分类器，经过训练可识别并标注论辩元素。通过将标注整合到评分流程中，我们展示了基于编码器的大型语言模型作为分类器进行微调后在性能上的提升。

> This study illustrates how incorporating feedback-oriented annotations into the scoring pipeline can enhance the accuracy of automated essay scoring (AES). This approach is demonstrated with the Persuasive Essays for Rating, Selecting, and Understanding Argumentative and Discourse Elements (PERSUADE) corpus. We integrate two types of feedback-driven annotations: those that identify spelling and grammatical errors, and those that highlight argumentative components. To illustrate how this method could be applied in real-world scenarios, we employ two LLMs to generate annotations -- a generative language model used for spell-correction and an encoder-based token classifier trained to identify and mark argumentative elements. By incorporating annotations into the scoring process, we demonstrate improvements in performance using encoder-based large language models fine-tuned as classifiers.

[Arxiv](https://arxiv.org/abs/2505.22771)