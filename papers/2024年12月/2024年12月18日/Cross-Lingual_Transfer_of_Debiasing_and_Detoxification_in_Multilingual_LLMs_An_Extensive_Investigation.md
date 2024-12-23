# 多语言大型语言模型中去偏和解毒的跨语言转移：一次广泛的调研

发布时间：2024年12月18日

`LLM应用` `语言模型`

> Cross-Lingual Transfer of Debiasing and Detoxification in Multilingual LLMs: An Extensive Investigation

# 摘要

> 近期的生成式大型语言模型（LLMs）在非英语语言方面表现出色，然而用这些语言提示时，它们往往会呈现出更严重的有害社会偏见和更高的毒性水平。此前的研究表明，在专门的数据集中进行微调能够缓解这种状况，而且在英语中进行微调能够迁移到其他语言。在本研究中，我们探究了不同微调方式对模型的偏见和毒性的影响，还有对其生成流畅且多样文本的能力的影响。我们的成果显示，在精心策划的无害文本上微调更有助于减轻偏见，在直接偏好优化（DPO）数据集上微调更利于降低毒性。在英语中运用这些方法所带来的缓解效果也能迁移到非英语语言中。我们发现有证据表明，迁移的程度可以通过模型预训练数据中给定语言的数据量来预测。不过，这种偏见和毒性缓解的迁移常常以非英语语言的语言生成能力降低为代价，凸显了开发特定语言的偏见和毒性缓解方法的重要性。

> Recent generative large language models (LLMs) show remarkable performance in non-English languages, but when prompted in those languages they tend to express higher harmful social biases and toxicity levels. Prior work has shown that finetuning on specialized datasets can mitigate this behavior, and doing so in English can transfer to other languages. In this work, we investigate the impact of different finetuning methods on the model's bias and toxicity, but also on its ability to produce fluent and diverse text. Our results show that finetuning on curated non-harmful text is more effective for mitigating bias, and finetuning on direct preference optimization (DPO) datasets is more effective for mitigating toxicity. The mitigation caused by applying these methods in English also transfers to non-English languages. We find evidence that the extent to which transfer takes place can be predicted by the amount of data in a given language present in the model's pretraining data. However, this transfer of bias and toxicity mitigation often comes at the expense of decreased language generation ability in non-English languages, highlighting the importance of developing language-specific bias and toxicity mitigation methods.

[Arxiv](https://arxiv.org/abs/2412.14050)