# # 基于大型语言模型反馈的语音识别模型定制

发布时间：2025年06月05日

`LLM应用

摘要讨论了如何利用大型语言模型（LLM）来改进自动语音识别（ASR）系统的转录质量，特别是在处理罕见命名实体和领域不匹配方面。研究提出了一种基于强化学习的无监督领域适应方法，其中LLM被用作奖励模型，对ASR生成的假设进行评分，并通过强化学习微调ASR模型。这种方法在实体词错误率方面取得了显著提升。因此，这篇论文属于LLM应用类别，因为它展示了如何将LLM应用于特定的语音识别任务中。` `语音识别`

> Customizing Speech Recognition Model with Large Language Model Feedback

# 摘要

> 自动语音识别（ASR）系统在通用转录任务中表现强劲，但在识别罕见命名实体和适应领域不匹配方面仍具挑战性。相比之下，大型语言模型（LLM）经过海量互联网数据训练，在广泛领域中表现更为出色。本研究提出了一种基于强化学习的无监督领域适应方法，通过无标签数据和LLM反馈提升转录质量，尤其在领域不匹配影响的命名实体方面。我们的框架利用LLM作为奖励模型，对ASR模型生成的假设进行评分，并通过强化学习微调ASR模型。与传统自训练方法相比，我们的方法在实体词错误率方面提升了21%。

> Automatic speech recognition (ASR) systems have achieved strong performance on general transcription tasks. However, they continue to struggle with recognizing rare named entities and adapting to domain mismatches. In contrast, large language models (LLMs), trained on massive internet-scale datasets, are often more effective across a wide range of domains. In this work, we propose a reinforcement learning based approach for unsupervised domain adaptation, leveraging unlabeled data to enhance transcription quality, particularly the named entities affected by domain mismatch, through feedback from a LLM. Given contextual information, our framework employs a LLM as the reward model to score the hypotheses from the ASR model. These scores serve as reward signals to fine-tune the ASR model via reinforcement learning. Our method achieves a 21\% improvement on entity word error rate over conventional self-training methods.

[Arxiv](https://arxiv.org/abs/2506.11091)